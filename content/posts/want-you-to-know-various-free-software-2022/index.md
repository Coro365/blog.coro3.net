---
title: "いろいろな自由ソフトウェアを知ってほしい"
slug: "want-you-to-know-various-free-software-2022"
categories: [ free-software ]
tags: [ free-software, libre-software ]
date: 2022-12-25T07:00:00+09:00
draft: false
description: '41個の自由ソフトウェアを簡単に紹介します。'
summary: "41個の自由ソフトウェアを簡単に紹介します。
          デスクトップアプリケーションが中心です。"
---

41個の自由ソフトウェアを簡単に紹介します。  
この記事は一般的なコンピュータ利用者に向けて書かれました。  
そのため殆どがデスクトップアプリケーションです。  
また、用語の解説も付けました。  
動画はなるべく公式の物を集めましたが非公式の物もあります。  
動画の下段に公式サイト、ソースコード、Wikipedia へのリンクがありますので適宜ご利用ください。  

## 目次 {#index}
- [自由ソフトウェアとは](#what-free-software)
- [画像編集](#image-edit)
- [ゲーム](#game)
- [録画](#record)
- [映像編集](#video-edit)
- [音声](#audio)
- [セルフホストとは](#what-self-host)
- [E2EEとは](#what-e2ee)
- [コミュニケーション](#communication)
- [Markdownとは](#what-markdown)
- [作文](#write)
- [文章 写真 映像の表示](#text-photo-video-display)
- [ユーティリティ](#utility)
- [科学](#science)
- [自由ソフトウェアとオープンソース](#free-software-and-open-source)
- [最後に](#last-section)

# 自由ソフトウェアとは {#what-free-software}
自由ソフトウェア (Free-Software) は大抵は無料 (Free) ではありますがそれだけではありません。  
自由ソフトウェアは誰でもどんな目的でもソフトウェアを使用でき、変更したり再配布したりできます。  
よく耳にするオープンソースソフトウェアは自由ソフトウェアから派生したもので、表面的には殆ど同じですが動機が異なります。  
詳しくは[この記事の末尾](#free-software-and-open-source)に記載しています。  
- [自由ソフトウェアとは? - GNUプロジェクト - フリーソフトウェアファウンデーション](https://www.gnu.org/philosophy/free-sw.ja.html)  

なぜ無料なだけのソフトウェアより自由ソフトウェアが優れているのかを知るには以下の記事を読むことをおすすめします。  
- [開発者による支配から身を守るために自由ソフトウェアを使いましょう](https://www.tojo.tokyo/posts/freedom-for-yourself.html)  

また、ソフトウェアを公開する場合はそのライセンスにも気を配り、ぜひ長期間の検証に耐えてきた既存のライセンスを使ってみてください。  
- [失われた「フリーソフト」の哀愁と、今を生きる開発者への願い。 - Zopfcode](https://www.zopfco.de/entry/2022/12/23/173235)

# 画像編集 {#image-edit}
## Krita 
{{<youtube_lazy fga5f3ixmVo>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://krita.org">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/KDE/krita ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Krita">Wikipedia</a>
</div>

イラストを書くためのソフトウェアです。  
ビットマップ画像を出力できます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | KDE                     |
| 初版                 | 2005                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Photoshop      |
| 主な使用言語           | C++, Qt                       |

## Inkscape
{{<youtube_lazy 1U4hVbvRr_g>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://inkscape.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://gitlab.com/inkscape/inkscape">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Inkscape">Wikipedia</a>
</div>

イラストを書くためのソフトウェアです。  
ベクター画像を出力できます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Raph Levien                     |
| 初版                 | 2003                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Illustrator      |
| 主な使用言語           | C++                       |

## Pixelorama
{{<youtube_lazy sM1v5uaBSrM>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://orama-interactive.itch.io/pixelorama">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/Orama-Interactive/Pixelorama">ソースコード</a>
</div>

ピクセルアートを書くためのソフトウェアです。  
アニメーションも作れます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Emmanouil Papadeas                     |
| 初版                 | 2019                    |
| ライセンス            | MIT                 |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア |       |
| 主な使用言語           | GDScript                      |

## GIMP 
{{<youtube_lazy M6N-3QJc6g8>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.gimp.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://gitlab.gnome.org/GNOME/gimp ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/GIMP">Wikipedia</a>
</div>

画像編集、写真の編集ができるソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Spencer Kimball, Peter Mattis                     |
| 初版                 | 1995                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Photoshop      |
| 主な使用言語           | C                       |

## darktable
{{<youtube_lazy VJbJ0btlui0>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.darktable.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/darktable-org/darktable">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Darktable">Wikipedia</a>
</div>

RAW写真の編集ができるソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Johannes Hanika                     |
| 初版                 | 2009                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Lightroom      |
| 主な使用言語           | C                       |

## Blender 
{{<youtube_lazy QRqY_20ti9A>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.blender.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://git.blender.org ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Blender">Wikipedia</a>
</div>

3Dモデルを作成したり編集したりできるソフトウェアです。  


|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Ton Roosendaal                     |
| 初版                 | 1998                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | CINEMA 4D, 3ds Max      |
| 主な使用言語           | C++                       |

# ゲーム {#game}
## godot
{{<youtube_lazy P6nQ3E-Cyfk>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://godotengine.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/godotengine/godot">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Godot_(%E3%82%B2%E3%83%BC%E3%83%A0%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%B3)">Wikipedia</a>
</div>

ゲームを作るためのソフトウェアです。  
前節で紹介したピクセルアートソフトウェアの [Pixelorama](#pixelorama) も godot を利用して作成されているそうです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Juan Linietsky, Ariel Manzur                     |
| 初版                 | 2014                    |
| ライセンス            | MIT                 |
| 対応環境              | Linux, Windows, macOS, Android   |
| 類似の不自由ソフトウェア | Unity, Unreal Engine      |
| 主な使用言語           | C++                       |

## osu!
{{<youtube_lazy ut_SOreClcc>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://osu.ppy.sh">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/ppy/osu">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Osu!">Wikipedia</a>
</div>

音楽リズムゲームです。  
動画サイトでプレイ動画を見かけた人も多いでしょう。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Dean peppy Herbert                     |
| 初版                 | 2007                    |
| ライセンス            | MIT                 |
| 対応環境              | Linux, Windows, macOS, Android, iOS   |
| 類似の不自由ソフトウェア |       |
| 主な使用言語           | C#                      |

# 録画 {#record}
## Vokoscreen
{{<youtube_lazy Zih0Egei73Y>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://linuxecke.volkoh.de/vokoscreen/vokoscreen.html">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/vkohaupt/vokoscreenNG">ソースコード</a>
</div>

コンピュータの画面を録画するソフトウェアです。   

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Volker Kohaupt                     |
| 初版                 | 2012                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows   |
| 類似の不自由ソフトウェア | Windows Game Bar      |
| 主な使用言語           | C++                       |

## OBS 
{{<youtube_lazy DFWDuq8kCM0>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://obsproject.com">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/obsproject/obs-studio ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/OBS_Studio">Wikipedia</a>
</div>

コンピュータの画面を録画したり動画サイトに生配信したりするソフトウェアです。  
多くの動画配信者が使っており業界標準になっています。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Hugh Jim Bailey                     |
| 初版                 | 2012                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Bandicam      |
| 主な使用言語           | C++                       |

## Inochi2D
{{<youtube_lazy zdZEkDABDXI>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://inochi2d.com/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/Inochi2D/inochi2d">ソースコード</a>
</div>

カメラで撮影した人間の顔の映像から目や鼻の動きを捉えて顔の動きを認識し、アニメ調のキャラクターの動きを同期させることができます。  
VTuberなどがよく利用する Live2D と類似の働きをします。  
しかし、まだベータ版なので実験以外での利用は推奨されていません。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | LunaTheFoxgirl                     |
| 初版                 | 2021                    |
| ライセンス            | BSD-2-Clause                 |
| 対応環境              |    |
| 類似の不自由ソフトウェア | Live2D      |
| 主な使用言語           | D                      |

# 映像編集 {#video-edit}
## kdenlive
{{<youtube_lazy g2Q6sluqc2I>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://kdenlive.org/en/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://invent.kde.org/複数の自由なライセンスmedia/kdenlive">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Kdenlive">Wikipedia</a>
</div>

動画編集ソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | KDE                     |
| 初版                 | 2002                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Premiere Pro      |
| 主な使用言語           | C++                       |

## Shotcut
{{<youtube_lazy NUDCcq6WcJU>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://shotcut.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/mltframework/shotcut">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Shotcut">Wikipedia</a>
</div>

動画編集ソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Charlie Yates                     |
| 初版                 | 2011                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Express      |
| 主な使用言語           | C, C++                      |

## NATRON
{{<youtube_lazy ompQOAeuFR0>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://natrongithub.github.io/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/NatronGitHub/Natron">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Natron">Wikipedia</a>
</div>

動画編集ソフトウェアです。  
特に動画の合成などに優れます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Alexandre Gauthier, Frédéric Devernay                     |
| 初版                 | 2012                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe After Effects      |
| 主な使用言語           | C++                       |

## LosslessCut
{{<youtube_lazy AOS3jFOs0jo>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://mifi.no/losslesscut/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/mifi/lossless-cut">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://en.wikipedia.org/wiki/Losslesscut">Wikipedia</a>
</div>

無劣化で動画を切り取るソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Mikael Finstad                     |
| 初版                 | 2016                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | VideoProc Converter      |
| 主な使用言語           | JavaScript                      |

## HandBrake
{{<youtube_lazy WgZq6Sakcog>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://handbrake.fr/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/HandBrake/HandBrake">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/HandBrake">Wikipedia</a>
</div>

動画のフォーマットを変更するソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Eric titer Petit                     |
| 初版                 | 2003                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Media Encoder      |
| 主な使用言語           | C, C#                      |

# 音声 {#audio}
## Ardour
{{<youtube_lazy YpMP8uGGpzI>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="http://www.ardour.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/Ardour/ardour">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Ardour">Wikipedia</a>
</div>

音声を編集するソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Paul Davis                     |
| 初版                 | 2004                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Audition      |
| 主な使用言語           | C++                       |

## VOICEVOX 
{{<youtube_lazy 4yVpklclxwU>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://voicevox.hiroshiba.jp/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/VOICEVOX/voicevox">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/VOICEVOX">Wikipedia</a>
</div>

音声合成ソフトウェアです。  
ずんだもん、春日部つむぎ といったキャラクタの音声ライブラリを使って、利用者が入力した文字を合成音声として出力できます。  
ただし、音声ライブラリ自体は自由なライセンスの下で利用できないことに注意してください。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Hiho                     |
| 初版                 | 2021                    |
| ライセンス            | LGPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | YAMAHA VOCALOID      |
| 主な使用言語           | TypeScript, Vue                      |

# セルフホストとは {#what-self-host}
今回の文脈では自分で (selfで) データやソフトウェアをホスティング (hosting) することを指します。  
例えばメモサービスである Google Keep は Google のサーバにあなたのメモを送信しそこに保存してもらうことであなたの端末間 (携帯やコンピュータ) でデータを同期し、たとえすべての端末が故障したとしてもパスワードさえわかればデータが失われることはありません。  
こういった形態をクラウドサービスといいます。  

クラウドサービスは便利ではありますが、危険もあります。  
なぜならクラウドサービスの管理者とデータを共有することになるからです。  
書類や写真を Google や Dropbox、Amazon にあずけている人も多いでしょうが、彼らはあなたのデータを盗み見ることができます。  
この問題への対処法の1つとしてセルフホストがあります。  
つまり Google のサーバにデータを預ける代わりに自分のサーバでデータを保管するのです。  
しかし、自宅で常時起動するコンピュータと、多少の専門知識が必要で敷居が少し高いでしょう。  
そのため、もう1つの対処法である [E2EE (end-to-end encryption) を次の節](#what-e2ee)で紹介します。  

# E2EEとは {#what-e2ee}
E2EE (end-to-end 暗号化) とは、終端 (end) からもう一方の終端 (end) までを暗号化する方式のことを言います。  

佐藤さんから鈴木さんにメール送る例を考えてみましょう。  
E2EE が採用されていない Google Gmail の様なサービスの場合、佐藤さんが送信したメールは Google のメールサーバを経由して鈴木さんに届きます。  
この時、佐藤さんと Google の間の経路上と Google と鈴木さんの間の経路上は Google が生成した暗号鍵 (数百から数千文字のパスワード) によって暗号化されます。しかし暗号鍵の生成者である Google は暗号化されたメールを復号してメールの内容を見ることができるのです。  
盗み見たメールの内容は大小様々な悪事に利用できます。  

それに対して E2EE では終端 (佐藤さん) から終端 (鈴木さん) まで暗号化されます。  
この場合、佐藤さんが鈴木さんにメールを送る時、鈴木さんの暗号鍵でメールを暗号化します。そのため鈴木さん以外はメールを読むことができなくなります。(他人が読むにはスーパーコンピュータで数千年掛けて解読する必要があり現実的ではありません。)  
E2EE された状態であればデータをクラウドサービス事業者にあずけても盗み見られることはなくなります。  

つまり E2EE を採用していないサービスを利用する場合、サービス運営者の良識と能力を信頼することが前提になります。  
しかし残念なことに、不正侵入、従業員の買収、意図的なデータ販売によってデータが流出するといったニュースはよく耳にします。  
E2EE はそういった事態に対する1つの解決策なのです。

- [エンドツーエンドの暗号化（E2EE）とは？ | Cloudflare](https://www.cloudflare.com/ja-jp/learning/privacy/what-is-end-to-end-encryption/)  

E2EE を利用できるサービスとして [Proton Mail](https://proton.me/) や Apple iMessage などがあります。  
ただし Apple iMessage は不自由ソフトウェアのため実際に E2EE が正しく実装され機能しているかを確認することはできません。  
一方で自由ソフトウェアである Proton Mail は誰でも E2EE が宣伝通り機能するか検証することができます。  
- [ProtonMail/proton-mail-android: Proton Mail Android app](https://github.com/ProtonMail/proton-mail-android)  

今月(2022-12)、E2EE でのデータ暗号化を謳っていた Anker社の防犯カメラ Eufy が実際には単純な暗号化すら行われていなかったことが発覚しました。  
もしこの監視カメラが自由ソフトウェアで動作していたら、本当に E2EE が行われているか簡単に検査することができたでしょう。  
そうした点でも自由ソフトウェアは有益であり、セルフホスト、E2EE、自由ソフトウェアは密接に関連しているといえるでしょう。  
- [Anker’s Eufy breaks its silence on security cam security - The Verge](https://www.theverge.com/2022/12/20/23519772/anker-eufy-security-camera-statement-december-19-2022)

ちなみに Google や鈴木さんが暗号鍵自体 (大抵は共通鍵) を安全にやり取りする方法として公開鍵暗号 (非対称鍵暗号) という方式が使われます。  
- [公開鍵暗号 - Wikipedia](https://ja.wikipedia.org/wiki/%E5%85%AC%E9%96%8B%E9%8D%B5%E6%9A%97%E5%8F%B7)  

また、以下のサイトで非対称暗号を実際に生成し暗号化と復号を体験することができます。  
- [鍵対の生成 | mitome.in](https://mitome.in/OpenPGP/keyPair.html)

しかし E2EE を採用するサービスでもデータを突然削除されたり、データを人質に自社サービスに利用者を縛り付けたり、データのエクスポートは有料プランのみになっており、自分のデータを取り戻すのに金銭を要求されることさえあります。この問題への対処法として[前の節で紹介したセルフホスト](#what-self-host)という方法があります。 

# コミュニケーション {#communication}
## Firefox
{{<youtube_lazy czEGwcZSYyo>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.mozilla.org/en-US/firefox/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://hg.mozilla.org/mozilla-central/">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Mozilla_Firefox">Wikipedia</a>
</div>

インターネットブラウザです。  

ブラウザにおける自由ソフトウェアの選択肢は少なく主要なものは Firefox と Chromium くらいのものです。    
ただし Chromium の開発は Google が主導しており、彼らは広告ネットワークも運営していますから Chromium において広告を拒否する拡張機能を阻害する傾向が見られます。  
- [Chrome Users Beware: Manifest V3 is Deceitful and Threatening | Electronic Frontier Foundation](https://www.eff.org/deeplinks/2021/12/chrome-users-beware-manifest-v3-deceitful-and-threatening)

また、以下のブラウザは自由ソフトウェアである Chromium を組み込んで作成されていますが、それらのブラウザの開発者は自由ソフトウェアライセンスの下での利用を許していません。  
- Google Chrome
- Microsoft Edge
- Opera
- Vivaldi

Apple iOS/iPad OS においては、Apple が開発した Safari で使われている WebKitエンジン 以外を搭載したブラウザを AppStore に出品することを許可していません。  
そのため、どんな iOS/iPad OS 向けブラウザも内部的には Safari となんら変わりません。  
従って iOS/iPad OS の利用者は実質的には Safari 以外のブラウザを選ぶことができません。  
しかし、2024年にEUで施行されるデジタル市場法によって AppStore の独占が禁止されれば状況が改善する可能性があります。  
- [アップル、EUで代替アプリストアを来年容認へ=BGG | ロイター](https://jp.reuters.com/article/apple-app-store-idJPKBN2SX247)

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Mozilla Foundation                     |
| 初版                 | 2002                    |
| ライセンス            | MPL-2.0                  |
| 対応環境              | Linux, Windows, macOS, Android   |
| 類似の不自由ソフトウェア | Google Chrome, Apple Safari      |
| 主な使用言語           | C++, Rust                      |

## Thunderbird
{{<youtube_lazy MbELg6ii7MQ>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.thunderbird.net/en-US/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://hg.mozilla.org/comm-central">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Mozilla_Thunderbird">Wikipedia</a>
</div>

メールをするためのソフトウェアです。  
RSSの購読、カレンダ管理もできます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Mozilla Foundation                     |
| 初版                 | 2003                    |
| ライセンス            | MPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Microsoft Outlook      |
| 主な使用言語           | C, C++                      |

## ActivityPub
{{<youtube_lazy IPSbNdBmWKE>}}

<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://activitypub.rocks/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://www.w3.org/TR/activitypub/">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/ActivityPub">Wikipedia</a>
</div>

ActivityPub は分散SNSのサーバ同士が通信する際の取り決め (プロトコル) です。  
このプロトコルに対応する自由ソフトウェアとしてTwitterのように使える Mastodon や Pleroma、YouTube のように使える PeerTube などが代表的です。  
例えば以下の3つの分散SNSサーバがそれぞれ投稿(Twitterで言うところのツイート)を見たりDMを送りあったりするときに ActivityPub が利用されています。
- mastodon.sato.org (佐藤さんの自宅サーバで[セルフホスト](#what-self-host)されている Mastodonサーバ)
- pleroma.suzuki.net (鈴木さんの契約したクラウドサーバでホストされている Pleromaサーバ)
- mastodon.matrix.org (Matrix財団が運営する Mastodonサーバ)

上記の例のように個人が1人で使うことも、組織が運営し複数人が使うこともできます。  
そして Mastodon と Pleroma 間といった異なるソフトウェア同士でも ActivityPub を使うことによってコミュニケーションできるのです。  
これは既存のサービスに例えると Twitter から Facebook の友人にDMを送るようなものです。  

ActivityPub のようなプロトコルはネットワーク効果の負の側面である Twitter や YouTube のような企業による寡占状態を改善する可能性があります。  
- [ネットワーク外部性 - Wikipedia](https://ja.wikipedia.org/wiki/%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E5%A4%96%E9%83%A8%E6%80%A7)

Mastodon などについて詳しく知りたい場合は、以下を読むことをおすすめします。
- [Mastodon - 分散型ソーシャルネットワーク](https://joinmastodon.org/ja)
- [御託はいいから fediverse とは何なのか Mastodon とは何なのか、端的に理解する - 何とは言わない天然水飲みたさ](https://blog.cardina1.red/2022/11/08/fediverse-in-a-nutshell/)
- [自分のサーバーを動かすこと - Mastodon documentation](https://docs.joinmastodon.org/ja/user/run-your-own/)

ActivityPub には Mastodon や PeerTube 以外にもたくさんのアプリケーションがあり以下の記事で紹介されています。  
- [The many branches of the Fediverse](https://axbom.com/fediverse/)

以下の動画もおすすめで PeerTubeサーバの1つである framatube.org で配信されています。
- [What is the Fediverse? - Framatube](https://framatube.org/w/4294a720-f263-4ea4-9392-cf9cea4d5277)

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Evan Prodromou, W3C                     |
| 初版                 | 2018                    |
| ライセンス            | W3C Software Notice and License                 |
| 対応環境              |    |
| 類似の不自由ソフトウェア | Twitter, Facebook      |
| 主な使用言語           |                       |

## Matrix
{{<youtube_lazy DffJmQyBkR8>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://matrix.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://spec.matrix.org/latest/">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Matrix_(%E3%83%97%E3%83%AD%E3%83%88%E3%82%B3%E3%83%AB)">Wikipedia</a>
</div>

Matrix はテキストチャットやビデオ、音声チャットのための分散プロトコルです。  
Mastodon が Twitter を代替可能なように Matrix は Apple iMassage や Discord、zoom、IRC を代替できます。  
将来的には VR にも対応する計画があるようで、成功すれば VRChat も代替できるようになります。  
もちろん、[セルフホスト](#what-self-host)可能です。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | The Matrix.org Foundation                     |
| 初版                 | 2014                    |
| ライセンス            | Apache-2.0                 |
| 対応環境              | Linux, Windows, macOS, Android, iOS   |
| 類似の不自由ソフトウェア | Apple iMessage, Discord, LINE      |
| 主な使用言語           |                       |

# Markdownとは {#what-markdown}
Markdownとは文章を簡単に構造化するための取り決めです。  
構造化と言っても、この文は見出し、この文は太い文字、この文は表、といった簡単なものです。  
HTMLも同じ様な機能を提供しますが、Markdown の方が人間が書きやすく読みやすいという利点があります。  
この取り決めに従って文章を書くと Markdown を理解するソフトウェアがそれを認識してきれいに表示してくれます。  
 
以下に Markdown の簡単な法則がまとまっています。  
- [Markdown Cheat Sheet | Markdown Guide](https://www.markdownguide.org/cheat-sheet)  
 
また、この記事も Markdown で書かれました。  
- https://github.com/Coro365/blog.coro3.net/blob/76e956a28903fd9f535378f05aef4491046dd43f/content/posts/want-you-to-know-various-free-software-2022/index.md?plain=1


# 作文 {#write}
## LibreOffice 
{{<youtube_lazy 3KC0ZdcA6s8>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://libreoffice.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://git.libreoffice.org/core ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/LibreOffice">Wikipedia</a>
</div>

オフィス向けソフトウェアです。  
ワープロソフト、表計算ソフト、プレゼンテーションソフト、作図ソフト、データベース管理システム、数式エディタがセットになっています。  
この記事の情報も表計算ソフト LibreOffice Calc で作成されました。 CSV として出力されたものが以下から閲覧できます。  
- https://github.com/Coro365/blog.coro3.net/tree/main/content/posts/want-you-to-know-various-free-software-2022/free-software.csv

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | The Document Foundation                     |
| 初版                 | 2010                    |
| ライセンス            | MPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Microsoft Offece      |
| 主な使用言語           | C++                       |

## Sigil
{{<youtube_lazy BMlY361BA7w>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://sigil-ebook.com/sigil/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/Sigil-Ebook/Sigil">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://en.wikipedia.org/wiki/Sigil_(application)">Wikipedia</a>
</div>

電子書籍を書くためのソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Strahinja Val Marković                     |
| 初版                 | 2009                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Apple Pages      |
| 主な使用言語           | C++                      |

## Joplin
{{<youtube_lazy S3ftmgoZ34o>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://joplinapp.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/laurent22/joplin">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://en.wikipedia.org/wiki/Joplin_(software)">Wikipedia</a>
</div>

メモを書くためのソフトウェアです。  
[E2EE](#what-e2ee) で暗号化され端末間で同期することができます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Laurent Cozic                     |
| 初版                 | 2017                    |
| ライセンス            | MIT                 |
| 対応環境              | Linux, Windows, macOS, Android, iOS   |
| 類似の不自由ソフトウェア | Apple Notes, Google Keep      |
| 主な使用言語           | TypeScript, JavaScript                      |

## Logseq
{{<youtube_lazy Pji6_0pbHFw>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://logseq.com">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/logseq/logseq">ソースコード</a>
</div>

メモを書くためのソフトウェアです。  
[Markdown](#what-markdown) で書くことができます。

|                     |                         |
|---------------------|-------------------------|
| 主な著者              |                      |
| 初版                 | 2020                    |
| ライセンス            | AGPL-3.0                 |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア |       |
| 主な使用言語           | Clojure, TypeScript                      |

## Marp
{{<youtube_lazy EzQ-p41wNEE>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://marp.app/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/marp-team/marp">ソースコード</a>
</div>

[Markdown](#what-markdown) で発表スライドを書くソフトウェアです。  
スライドのデザインと内容を分離することでスライドを効率的に作成、管理できます。  
いくつかのデザイン (CSS) が用意されており、自分で CSS を書くこともできます。  


|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Yuki Hattori                     |
| 初版                 | 2018                    |
| ライセンス            | MIT                 |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Microsoft PowerPoint      |
| 主な使用言語           | TypeScript                      |

## Mermaid
{{<youtube_lazy 6TiIrJf63Xs>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="">ソースコード</a>
</div>

文章で図を書くためのソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Knut Sveidqvist                     |
| 初版                 | 2014                    |
| ライセンス            | MIT                 |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Microsoft Visio      |
| 主な使用言語           | JavaScript                      |

## Hugo
{{<youtube_lazy 0RKpf3rK57I>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://gohugo.io/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/gohugoio/hugo">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Hugo_(%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2)">Wikipedia</a>
</div>

[Markdown](#what-markdown) から Webサイトを生成するソフトウェアです。  
現在 (2022) このブログも Hugo を使って生成されています。  
このページは YouTube の埋め込みが大量にあるので表示が遅いですが、静的サイトなので通常は高速です。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Steve Francia                     |
| 初版                 | 2013                    |
| ライセンス            | Apache-2.0                 |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | note.com, medium.com      |
| 主な使用言語           | Go                      |

# 文章 写真 映像の表示 {#text-photo-video-display}
## digiKam
{{<youtube_lazy p1LMy6bbovE>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.digikam.org">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://invent.kde.org/graphics/digikam">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/DigiKam">Wikipedia</a>
</div>

写真を整理するソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | KDE                     |
| 初版                 | 2006                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Adobe Lightroom      |
| 主な使用言語           | C++                       |

## calibre
{{<youtube_lazy oGzfYEeshl4>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://calibre-ebook.com/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/kovidgoyal/calibre">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Calibre">Wikipedia</a>
</div>

電子書籍を閲覧、管理するソフトウェアです。  
デスクトップアプリケーションですがブラウザから閲覧するためにWebサーバを搭載しています。  
また、サーバ専用のソフトウェアもあり[セルフホスト](#what-self-host)できます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Kovid Goyal                     |
| 初版                 | 2006                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Apple Books Amazon Kindle      |
| 主な使用言語           | Python                      |

## VLC 
{{<youtube_lazy NZwPgpAzNlo>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.videolan.org/vlc/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://code.videolan.org/videolan/vlc/ ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/VLC%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2%E3%83%97%E3%83%AC%E3%83%BC%E3%83%A4%E3%83%BC">Wikipedia</a>
</div>

動画を再生するソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | VideoLAN project                     |
| 初版                 | 2001                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | GOM Player, QuickTime Player      |
| 主な使用言語           | C                       |

## mpv
{{<youtube_lazy w-g04TLp0tg>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://mpv.io">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/mpv-player/mpv/">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Mpv_(%E3%83%A1%E3%83%87%E3%82%A3%E3%82%A2%E3%83%97%E3%83%AC%E3%83%BC%E3%83%A4%E3%83%BC)">Wikipedia</a>
</div>

動画を再生するソフトウェアです。  
プラグインを使うことでリアルタイムでアップコンバートすることもできます。(FHDを4Kにするなど)  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Gergely Árpád                     |
| 初版                 | 2013                    |
| ライセンス            | GPL-2.0,LGPL-2.1                 |
| 対応環境              | Linux, Windows, macOS, Android   |
| 類似の不自由ソフトウェア | GOM Player, QuickTime Player      |
| 主な使用言語           | C                      |

# ユーティリティ {#utility}
## Bitwarden
{{<youtube_lazy lSDs6wXvx3w>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://bitwarden.com/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/bitwarden/clients">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/Bitwarden">Wikipedia</a>
</div>

パスワードを管理するためのソフトウェアです。  
パスワードを管理する方法はいくつかあり、1つはOSに搭載された機能を使う方法、もう1つはブラウザに搭載された機能を使う方法です。  
しかし、これらの方法は OS やブラウザを跨ぐ利用が困難です。また、OSやブラウザの種類を変更する際に小さな障害になりえます。  
そのため、様々な OS やブラウザで使える独立したパスワード管理ソフトウェアを使うことをおすすめします。  
Bitwarden は利用者のデータ (パスワードなど) を同期するために Bitwarden社のサーバを利用しますが [E2EE](#what-e2ee) されるためBitwarden社を信頼する必要がありませんし、自由ソフトウェアのためソフトウェアを検証して実際に [E2EE](#what-e2ee) が行われているか確認することができます。  
また、データ同期のために Bitwarden社のサーバを利用せずに自分のサーバを利用 ([セルフホスト](#what-self-host)) して同期することもできます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Bitwarden                     |
| 初版                 | 2016                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS, Android, iOS   |
| 類似の不自由ソフトウェア | 1Password, LastPass      |
| 主な使用言語           | TypeScript                      |

## KDEConnect
{{<youtube_lazy d4ghirmM1Ys>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://kdeconnect.kde.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://invent.kde.org/network/kdeconnect-kde">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://en.wikipedia.org/wiki/KDE_Connect">Wikipedia</a>
</div>

所有する端末間 (携帯やパソコンなど) で通知やデータ、クリップボードを共有するソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | KDE                     |
| 初版                 | 2013                    |
| ライセンス            | 複数の自由なライセンス                 |
| 対応環境              | Linux, Windows, macOS, Android, iOS   |
| 類似の不自由ソフトウェア | Apple AirDrop, Android Nearby Sharee      |
| 主な使用言語           | C++                       |

## Filelight
{{<youtube_lazy Po0WxJ1BWXo>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://apps.kde.org/filelight/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/KDE/filelight">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://en.wikipedia.org/wiki/Filelight">Wikipedia</a>
</div>

コンピュータ内のデータのサイズを円グラフで可視化するソフトウェアです。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Max Howell                     |
| 初版                 | 2004                    |
| ライセンス            | GPL-3.0, GPL-2.0                 |
| 対応環境              | Linux, Windows   |
| 類似の不自由ソフトウェア | DaisyDisk      |
| 主な使用言語           | C++                       |

# 科学 {#science}
## FreeCAD 
{{<youtube_lazy 85HlYXnaxbw>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.freecadweb.org">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/FreeCAD/FreeCAD ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/FreeCAD">Wikipedia</a>
</div>

工業製品を設計するソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Juergen Riegel, Werner Mayer, Yorik van Havre                     |
| 初版                 | 2002                    |
| ライセンス            | LGPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Autodesk AutoCAD      |
| 主な使用言語           | C++, Python                      |

## PrusaSlicer
{{<youtube_lazy Zbpmnubsblg>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.prusa3d.com/page/prusaslicer_424/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/prusa3d/PrusaSlicer">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://en.wikipedia.org/wiki/Slic3r">Wikipedia</a>
</div>

FreeCAD などで設計した造形物を元に3Dプリンタに印刷させるためのデータを生成するソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Alessandro Ranellucci                     |
| 初版                 | 2018                    |
| ライセンス            | AGPL-3.0                 |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Ultimaker Cura      |
| 主な使用言語           | C++                       |

## KiCad
{{<youtube_lazy uhcMGQ32Xw0>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.kicad.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://gitlab.com/kicad/code/kicad ">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/KiCad">Wikipedia</a>
</div>

回路を設計するソフトウェアです。  
回路図を書きそれを元にパターン図を生成します。  
そのデータを基板製造メーカに送信すると数日で基板が自宅に届きます。  

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Jean Pierre Charras                     |
| 初版                 | 1992                    |
| ライセンス            | GPL-3.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | Autodesk EAGLE      |
| 主な使用言語           | C++                       |

## QGIS
{{<youtube_lazy IEkOhQezQMk>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://qgis.org">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://github.com/qgis/QGIS">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/QGIS">Wikipedia</a>
</div>

地図を書くためのソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | QGIS Development Team                     |
| 初版                 | 2002                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS, Android   |
| 類似の不自由ソフトウェア | ESRI ArcGIS      |
| 主な使用言語           | C++                       |

## R
{{<youtube_lazy ANMuuq502rE>}}
<div style="display: flex; text-align: center; margin: auto;">
    <a style="margin: 0.5em 4em;" href="https://www.r-project.org/">Webサイト</a>
    <a style="margin: 0.5em 4em;"href="https://r-forge.r-project.org/">ソースコード</a>
    <a style="margin: 0.5em 4em;"href="https://ja.wikipedia.org/wiki/R%E8%A8%80%E8%AA%9E">Wikipedia</a>
</div>

統計処理をするためのソフトウェアです。    

|                     |                         |
|---------------------|-------------------------|
| 主な著者              | Ross Ihaka, Robert Gentleman                     |
| 初版                 | 1993                    |
| ライセンス            | GPL-2.0                  |
| 対応環境              | Linux, Windows, macOS   |
| 類似の不自由ソフトウェア | SAS      |
| 主な使用言語           | C, FORTRAN, R                      |

# 自由ソフトウェアとオープンソース {#free-software-and-open-source}
自由ソフトウェアとは自由ソフトウェア財団(Free Software Foundation)が定義した条件を満たすライセンスの下で利用できるソフトウェアを指します 。   
- [自由ソフトウェアとは? - GNUプロジェクト - フリーソフトウェアファウンデーション](https://www.gnu.org/philosophy/free-sw.ja.html)  

対してオープンソースソフトウェアはオープンソース・イニシアティブ (Open Source Initiative) が定義した条件を満たすライセンスの下で利用できるソフトウェアを指します。  
- [The Open Source Definition | Open Source Initiative](https://opensource.org/osd)  

そしてこの2つの団体はそれぞれの定義に基づいてライセンスを承認しており、承認されたライセンスの多くは両方から承認されています。  
- [さまざまなライセンスとそれらについての解説 - GNUプロジェクト - フリーソフトウェアファウンデーション](https://www.gnu.org/licenses/license-list.ja.html)  
- [Licenses by Name | Open Source Initiative](https://opensource.org/licenses/alphabetical)  
 
しかし違いもあり、例えば NASA Open Source Agreement v1.3 (NASA-1.3) は オープンソース・イニシアティブ からは承認されていますが、自由ソフトウェア財団 (FSF) からは承認されていません。  
なぜなら自由ソフトウェアはソフトウェア利用者の自由を擁護するとうい動機に基づくためです。  
このNASAライセンスの下で配布されるソフトウェアを改造する場合、自分でコードを書く必要があり他人が書いた自由ソフトウェアのコードを組み込むことが出来ません。これは利用者の自由を制限することになります。  
詳しくは以下の記事を読むことをおすすめします。  
- [なぜ、オープンソースは自由ソフトウェアの的を外すのか - GNUプロジェクト - フリーソフトウェアファウンデーション](https://www.gnu.org/philosophy/open-source-misses-the-point.ja.html)  

また双方の定義を満たすライセンスの下で使用できるソフトウェアを FLOSS (Free/Libre and Open Source Software) と呼ぶこともありますが、自由ソフトウェアである場合はそれを自由ソフトウェアと呼称するように FSF は推奨しています。  
- [避けるべき言葉 (あるいは注意深く使う)、含みがあるかまぎらわしいので - GNU プロジェクト - フリーソフトウェアファウンデーション](https://www.gnu.org/philosophy/words-to-avoid.ja.html#FLOSS)  

# 最後に {#last-section}
41個中、いくつ知っていましたか? いくつ使いたくなりましたか?  
1つでも興味を持った自由ソフトウェアがあれば幸いです。  
また以下のサイトでもっと自由ソフトウェアを探すことができます。  
- [Open Source Alternatives to Proprietary Software](https://www.opensourcealternative.to/)  
- [KDE Applications](https://apps.kde.org/)  
- [Apps for GNOME – Discover the best Apps for GNOME](https://apps.gnome.org/)  
- [F-Droid - Free and Open Source Android App Repository](https://f-droid.org/)  

この記事は [知ってほしい技術 Advent Calendar 2022](https://adventar.org/calendars/7490) をきっかけに作成されました。  
ありがとうございます。   

界隈で有名なソフトウェアもエンドユーザーには知られていないことも多いと感じており、この記事を書くことによって良いソフトウェアが必要とする人々に届いてほしいなと思っています。  

間違いなどがありまりたらご連絡いただけるとありがたいです。  
最後までお付き合いいただきありがとうございました。  

**TEXT LICENSE CC-BY**