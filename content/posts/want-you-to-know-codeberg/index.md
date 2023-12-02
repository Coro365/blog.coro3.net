---
title: "Codeberg を知ってほしい"
slug: "want-you-to-know-codeberg"
categories: [ free-software ]
tags: [ free-software, libre-software ]
date: 2023-12-03T04:50:00+09:00
draft: false
description: 'ドイツの NPO が運営している Git サーバ Codeberg を紹介します'
summary: "Codeberg.org は GitHub.com や GitLab.com のような Git リポジトリのホスティングサイトです。"
---

この記事は、[知ってほしい技術 Advent Calendar 2023](https://adventar.org/calendars/9017) の 3 日目の記事です。  

[Codeberg.org](https://codeberg.org/) は [GitHub.com](https://github.com/) や [GitLab.com](https://about.gitlab.com/) のような [Git](https://git-scm.com/) リポジトリのホストサイトです。  
[GitLab.com](https://about.gitlab.com/) が [GitLab (アプリケーション)](https://gitlab.com/gitlab-org/gitlab-foss) で動いているように、 [Codeberg.org](https://codeberg.org/) は [Forgejo](https://forgejo.org/) で動いています。  

codeberg.org の珍しい点は、オープンソースソフトウェア (自由ソフトウェア) のリポジトリだけがホストを許されるという点です。  
- [Can I host software and resources without a free and open-source software license?](https://docs.codeberg.org/getting-started/faq/#can-i-host-software-and-resources-without-a-free-and-open-source-software-license%3F)

他にも以下のような特徴を持っています。  

- 運営者はドイツのベルリンを[拠点](https://www.google.com/maps/place/Codeberg+e.V./@52.5278085,13.3379916,19z/data=!3m1!5s0x47a8510cbf604bbf:0x13f86c88be3c7dd4!4m6!3m5!1s0x47a8512a95d7bb01:0x1bc3db33f28f589c!8m2!3d52.5277375!4d13.3387882!16s%2Fg%2F11vdx0nf7z?entry=ttu)にしている非営利団体です。
    - [org/Imprint.md at main - org - Codeberg.org](https://codeberg.org/Codeberg/org/src/branch/main/Imprint.md#impressum-nach-5-tmg-imprint-according-to-german-law)
- サーバーはベルリンのレンタル施設の専用のサーバーでホストされているそうです。
    - [Where is Codeberg hosted?](https://docs.codeberg.org/getting-started/faq/#where-is-codeberg-hosted%3F)
- そのため恐らく準拠法はドイツ法です。
- 運営費用は寄付によって賄っているそうです。
    - [Improving Codeberg | Codeberg Documentation](https://docs.codeberg.org/improving-codeberg/#donate-to-codeberg)
- 非営利団体のメンバーになり資金を提供したりもできるそうです。
- code**berg** の berg はドイツ語で山を意味します ([発音](https://ja.bab.la/%E7%99%BA%E9%9F%B3/%E3%83%89%E3%82%A4%E3%83%84%E8%AA%9E/berg))
    - [Codeberg is moving ... and what this means to you — Codeberg News](https://blog.codeberg.org/codeberg-is-moving-and-what-this-means-to-you.html)
- [Forgejo](https://forgejo.org/) 自体は MIT License で許諾されてます。
- Forgejo は [Gitea](https://about.gitea.com/) の fork で Gitea は [Gogs](https://gogs.io/) の fork です。
- 私がアカウントを作成した 2023-10 時点ではスパム対策を理由に gmail.com ドメインのメールアドレスではアカウントを作成できませんでした。そのため proton.me ドメインのメールアドレスで作成しました。

### Codebreg でホストされている代表的なリポジトリ
- [forgejo/forgejo](https://codeberg.org/forgejo/forgejo)
    - codebreg.org でも実行されている Git サーバ
- [Freeyourgadget/Gadgetbridge](https://codeberg.org/Freeyourgadget/Gadgetbridge)
    - Pebble や PineTime などのスマートガジェットと接続するための Android アプリ
- [dnkl/foot](https://codeberg.org/dnkl/foot)
    - 端末エミュレーター
- [gitnex/GitNex](https://codeberg.org/gitnex/GitNex)
    - Git サーバの Android クライアントアプリ
- [Kbin/kbin-core](https://codeberg.org/Kbin/kbin-core)
    - reddit に似たオープンソースのサーバーアプリケーション
- [tenacityteam/tenacity](https://codeberg.org/tenacityteam/tenacity)
    - 音声編集ソフト Audacity の fork
- [keyoxide/keyoxide-web](https://codeberg.org/keyoxide/keyoxide-web)
    - 公開鍵によるアイデンティティの検証を行えるサイト [Keyoxide](https://keyoxide.org/) のソースコード
- [Liblast/Liblast](https://codeberg.org/Liblast/Liblast)
    - Gotdot などオープンソースのツールのみで作られたオープンソースの FPS ゲーム

[ここ](https://codeberg.org/explore/repos?tab=&sort=moststars&q=&language=) で他のリポジトリをもっと探すことができます。  


もし OSS リポジトリのホスト先として GitHub.com 以外をお探しなら [Codeberg.org](https://codeberg.org/) を試してみてください。  


**TEXT LICENSE: CC BY 4.0**