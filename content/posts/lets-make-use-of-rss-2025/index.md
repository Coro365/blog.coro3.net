---
title: "RSS を活用しよう"
slug: "lets-make-use-of-rss-2025"
categories: [ ]
tags: [ rss ]
date: 2025-12-07T13:20:00+09:00
author: Coro365
draft: false
description: 'RSS はニュースサイトやブログなどを購読する便利な方法ですが、意外な場所でも使われています。それらを幾つか紹介します。'
summary: "RSS はニュースサイトやブログなどを購読する便利な方法ですが、意外な場所でも使われています。それらを幾つか紹介します。"
---

# RSS とは

RSS (Really Simple Syndication) は記事の URL やタイトルのリストを 機械可読な書式のテキストファイル(XML) にしたものです。
RSS ファイルをインターネット上に公開している物を RSS フィードと言い、このブログの RSS フィードは以下のようなものです。
- https://blog.coro3.net/index.xml

この RSS フィードを RSS リーダーというソフトウェアで解釈させると記事を一覧できます。
RSS リーダーに複数の RSS フィードを読ませれば複数のブログ記事やニュース記事を 1 つの画面で一覧することができます。

{{< figure src="freshrss.avif" title="freshrss screenshot" width="1416" height="1331" >}}

RSS はニュースサイトやブログ、ポッドキャストなどを購読する便利な方法ですが、意外な場所でも使われています。それらをいくつか紹介します。

# SNS
めったに投稿しないが見逃したくないアカウントなどを購読するといいかもしれません。
## Mastodon, Pleroma, Misskey (ActivityPub)  {#activitypub}
`.rss`
- https://mastodon.social/@Mastodon
- https://mastodon.social/@Mastodon.rss
## BlueSky (AT Protocol) {#atprotocol}
`/rss`
- https://bsky.app/profile/bsky.app
- https://bsky.app/profile/bsky.app/rss
# Video
配信後すぐ限定公開 (Unlisted) にしてしまうチャンネルやニュースチャンネルを購読するといいかもしれません。
またニコニコ動画などを常用しないが、購読したいチャンネルがある場合も有用でしょう。

## YouTube
### Channel
- https://www.youtube.com/channel/UCpC6ZVYT8-SxVb9zIcPDOTA
- https://www.youtube.com/feeds/videos.xml?channel_id=UCpC6ZVYT8-SxVb9zIcPDOTA
### Playlist
- https://www.youtube.com/playlist?list=PL8BNGGvgTRPQdJa_faeP6d1vVAJ6zkvKE
- https://www.youtube.com/feeds/videos.xml?playlist_id=PL8BNGGvgTRPQdJa_faeP6d1vVAJ6zkvKE

## niconico {#niconico}
`?rss=2.0`
- https://www.nicovideo.jp/user/5844196/video
- https://www.nicovideo.jp/user/5844196/video?rss=2.0

2025-08 に RSS 発行終了を予定していましたが、無期延期されています。
- https://blog.nicovideo.jp/niconews/255055.html

# Other
### tumblr 
`/rss`
- https://staff.tumblr.com
- https://staff.tumblr.com/rss

他にも以下のようなサイトが対応しているようです。

GitHub, Reddit, Substack, Medium, Pinterest, Flickr, Vimeo, SoundCloud, Steam

# RSS Reader {#rss-reader}

RSSリーダーを紹介しておきます。

- https://www.freshrss.org (Server)
    - https://github.com/FreshRSS/FreshRSS (AGPL-3.0)
    - https://framapiaf.org/@freshrss (Mastodon)

- https://netnewswire.com (iOS)
    - https://github.com/Ranchero-Software/NetNewsWire (AGPL-3.0)
    - https://indieweb.social/@NetNewsWire (Mastodon)

- https://hyliu.me/fluent-reader-lite (Android, iOS)
    - https://github.com/yang991178/fluent-reader-lite (BSD-3-Clause)

- https://hyliu.me/fluent-reader (Linux, Windows, macOS)
    - https://github.com/yang991178/fluent-reader (BSD-3-Clause)

# Ref
- https://ja.wikipedia.org/wiki/RSS
- https://www.kanzaki.com/docs/sw/rss.html

この記事は、Fediverse (2) Advent Calendar 2025 の 5日目の記事です。

最後までお付き合いいただき、ありがとうございました。

{{<license title="RSS を活用しよう" year="2025" \
        author="Coro365" author-url="https://coro3.net" \
        soruce-url="https://blog.coro3.net/lets-make-use-of-rss-2025" \
        license="CC BY 4.0" license-url="https://creativecommons.org/licenses/by/4.0/" \
        remarks="Excluding quoted parts and images.">}}