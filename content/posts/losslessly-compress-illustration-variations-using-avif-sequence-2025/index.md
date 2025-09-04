---
title: "avif sequence でイラスト差分をロスレス圧縮する"
slug: "losslessly-compress-illustration-variations-using-avif-sequence-2025"
categories: [ quiku-review ]
tags: [ avif, avis ]
date: 2025-09-04T19:00:00+09:00
draft: false
description: 'avif sequence で複数のイラスト差分をほぼ1枚分の容量に無劣化で圧縮します。'
summary: "avif sequence で複数のイラスト差分をほぼ1枚分の容量に無劣化で圧縮します。"
---
### 背景 {#background}
イラストなどの画像は、表情や服装、セリフだけを変えた別バージョン (いわゆる差分イラスト) も公開されることがあります。これらは大部分が共通しているため、各ファイルの容量は元の画像とほとんど変わらず、ファイル数が増えるほど全体の容量も増加します。
例えば 1 枚 2MiB の画像が差分イラストと合わせて 10 枚あれば 20MiB の容量になります。  

こういった複数の画像ファイルを ZIP などで圧縮してもほとんど小さくなりません。 これは ZIP の圧縮アルゴリズムがファイルごとに個別に処理を行う仕組みであり、さらに PNG や JPG はすでに圧縮済みの形式であるためです。  

これに対し avif sequence (avis) はフレーム間圧縮が行われ、他の画像と違う部分だけを保存できるためイラスト差分の保存に適していると思われます。

### 実験 {#experiment}
今回は 1 枚の画像と 1 枚の差分画像、そしてそれぞれに 4 言語分のセリフ画像を追加して合計 10 枚の PNG 画像 (19.9MiB) を 1 枚の avif sequence 画像 (1.9MiB) に無劣化で変換しファイル容量を 90% 削減しました。
以下に手順を示します。

```
# 10枚のPNGを 1 枚の avif sequence に lossless で変換
avifenc --lossless --fps 1 --speed 0 -o sequence.avif original/*

# avif sequence から 1 枚目だけを PNG に変換
avifdec --index 0 sequence.avif sequence-frame-1.png

# 元の PNG と変換した PNG を比較し劣化がないことを確認
magick compare -metric AE original/01*.png sequence-frame-1.png null: 2>&1

```

### 結果 {#results}
{{< figure src="group1-sequence.avif" title="group1-sequence.avif (1.9MiB)" width="422" height="678"  
    caption="[ruf150124a04](https://www.flickr.com/photos/webdiver/16398369412/) and [ruf150124a07](https://www.flickr.com/photos/webdiver/16221689489/) by [Yama Q](https://www.flickr.com/photos/webdiver/), used under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja) / Added text from original" >}}
各画像の類似度によりますが好条件の画像では avif sequence を使うと、画像 1 枚分のファイル容量とほぼ同等の容量で多くの差分ファイルを保存できることがわかりました。

今回用いた画像群のように画像間で異なる部分が少ない複数の画像をまとめて圧縮する場合に大きなフレーム間圧縮の効果を得られ、また画像の枚数が多いほどその恩恵をより多く得られると思われます。

ただし、見かけ上類似している画像群でも実際には同じ色のピクセルではないような画像では圧縮効果が得られないか逆に増えてしまうこともありました。  
以下の例では合計 4 枚の PNG 画像 (7.1MiB) を 1 枚の avif sequence 画像 (9.6MiB) に無劣化で変換したところファイル容量が 35% 増加しました。

単純に色味の異なる画像を保存したい場合は画像作成時に heif multi-image を使うと良いと思われますが今回は試していません。

{{< figure src="group2-sequence.avif" title="group2-sequence.avif (9.6MiB)" width="406" height="558"  
    caption="[ruf180809a01](https://www.flickr.com/photos/webdiver/42259368980/), [ruf180809a02](https://www.flickr.com/photos/webdiver/29131711307/), [ruf180809a03](https://www.flickr.com/photos/webdiver/29131711737/) and [ruf180809a04](https://www.flickr.com/photos/webdiver/43162148685/) by [Yama Q](https://www.flickr.com/photos/webdiver/), used under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja)" >}}


また、avif sequence はパラパラ漫画のように連続表示され、1 枚ずつ表示する方法はまだ一般的ではありません (FPS は設定できます)。そのため、1 枚ずつ表示したい場合は PNG などに変換する必要があります。

### Outro
avif sequence は大抵はアニメーション GIF のような動画を圧縮する目的で使われていますが、フレーム間圧縮をイラスト差分の圧縮に適用した事例を見たことがなかったので今回記事にしてみました。

実験に使った画像データとその出力を [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja) の下で以下のリンクで再配布しておくので、ぜひ試してみてください。

[test-data.zip](https://github.com/Coro365/blog.coro3.net/raw/refs/heads/main/content/posts/losslessly-compress-illustration-variations-using-avif-sequence-2025/test-data.zip) (43.2MiB)


### LICENSE NOTICE {#license-notice}
今回使用した画像は以下のように [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja) の下で許諾された [Yama Q](https://x.com/ycums)さん の 2 枚のイラスト画像と、それらに私が 4 言語分のセリフをそれぞれ追加したもの、さらに追加で 4 枚のイラスト画像を使用しました。  
ありがとうございます。

- "[ruf150124a04](https://www.flickr.com/photos/webdiver/16398369412/)" and "group1-sequence-frame-1.png" by [Yama Q](https://www.flickr.com/photos/webdiver/) is licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja).
- "[ruf150124a07](https://www.flickr.com/photos/webdiver/16221689489/)" by [Yama Q](https://www.flickr.com/photos/webdiver/) is licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja).
- These material, "ruf150124a07_ara", "ruf150124a07_eng", "ruf150124a07_jpn", "ruf150124a07_kor" and "group1-sequence.avif" is adapted from "[ruf150124a07](https://www.flickr.com/photos/webdiver/16221689489/)" by [Yama Q](https://www.flickr.com/photos/webdiver/), used under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja). "ruf150124a07_ara", "ruf150124a07_eng", "ruf150124a07_jpn", "ruf150124a07_kor" and "sequence.avif" is licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja) by [Coro365](https://coro3.net).
- These material, "ruf150124a04_ara", "ruf150124a04_eng", "ruf150124a04_jpn", "ruf150124a04_kor" and "group1-sequence.avif" is adapted from "[ruf150124a04](https://www.flickr.com/photos/webdiver/16398369412/)" by [Yama Q](https://www.flickr.com/photos/webdiver/), used under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja). "ruf150124a04_ara", "ruf150124a04_eng", "ruf150124a04_jpn", "ruf150124a04_kor" and "sequence.avif" is licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja) by [Coro365](https://coro3.net).

- "[ruf180809a01](https://www.flickr.com/photos/webdiver/42259368980/)", "[ruf180809a02](https://www.flickr.com/photos/webdiver/29131711307/)", "[ruf180809a03](https://www.flickr.com/photos/webdiver/29131711737/)", "[ruf180809a04](https://www.flickr.com/photos/webdiver/43162148685/)" and "group2-sequence-frame-1.png" by [Yama Q](https://www.flickr.com/photos/webdiver/) is licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja).
- This material, "group2-sequence.avif" is adapted from "[ruf180809a01](https://www.flickr.com/photos/webdiver/42259368980/)", "[ruf180809a02](https://www.flickr.com/photos/webdiver/29131711307/)", "[ruf180809a03](https://www.flickr.com/photos/webdiver/29131711737/)" and "[ruf180809a04](https://www.flickr.com/photos/webdiver/43162148685/)" by [Yama Q](https://www.flickr.com/photos/webdiver/), used under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja). "group2-sequence.avif" is licensed under [CC BY-NC 2.0](https://creativecommons.org/licenses/by-nc/2.0/deed.ja) by [Coro365](https://coro3.net).

### Ref
- https://github.com/AOMediaCodec/libavif
- https://github.com/ImageMagick/ImageMagick
- https://github.com/strukturag/libheif
- https://nokiatech.github.io/heif
- https://wiki.creativecommons.org/wiki/Recommended_practices_for_attribution#Attributing_an_image
- https://www.gimp.org


**TEXT LICENSE: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed)**
