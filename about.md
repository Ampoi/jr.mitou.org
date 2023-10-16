---
layout: post
title: 未踏ジュニアとは
description: 本ページでは初めての方を対象としたコンテンツをまとめています。
---

<p style='margin: 50px auto;'><b>未踏ジュニアへようこそ!</b> 本ページでは初めての方を対象としたコンテンツをまとめています <i class="fas fa-tv green" aria-hidden="true"></i> ✨</p>

<div class="youtube" itemprop="video" itemscope itemtype="http://schema.org/VideoObject">
  <meta itemprop="isFamilyFriendly"     content="True">
  <meta itemprop="requiresSubscription" content="False">
  <meta itemprop="width"                content="1280">
  <meta itemprop="height"               content="720">
  <meta itemprop="thumbnailUrl"         content="https://i.gyazo.com/c9279aac3f89da401e0d3d14f570fa37.jpg">
  <meta itemprop="uploadDate"           content="2022-10-05">
  <meta itemprop="contentUrl"           content="https://youtube.googleapis.com/v/Eu42E-FXBME">
  <meta itemprop="embedUrl"             content="https://www.youtube.com/embed/Eu42E-FXBME?rel=0">
  <meta itemprop="name"                 content="未踏ジュニアとは？">
  <meta itemprop="description"          content="未踏ジュニアとは何か、IPA が実施する未踏事業とは何が違うのか、どういう関係なのか？といったことを３分で説明する動画です。「未踏」について知るキッカケになれば嬉しいです。">
  <iframe width="100%" src="https://www.youtube.com/embed/Eu42E-FXBME?list=PLNObH2jlC6lc3c-gRpILyQrMhlqBIRjKr" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<a href="https://www.youtube.com/playlist?list=PLNObH2jlC6lc3c-gRpILyQrMhlqBIRjKr" class="button">YouTubeで視聴する</a>

<br>

## 未踏ジュニアとは？ {#mitoujr}
独創的なアイデア、卓越した技術を持つ17歳以下の小中高生や[高専生](https://ja.wikipedia.org/wiki/高等専門学校)などを支援するプログラムです。

[未踏事業](https://www.ipa.go.jp/jinzai/mitou/about.html)という、経産省所管の独立行政法人情報処理推進機構（[IPA](https://www.ipa.go.jp/about/index.html)）が主催している、優秀な25歳以下の若者を支援するプログラムがあります。この未踏事業の修了生を中心に設立・運営されているのが、**未踏ジュニア**です。

{% assign total_applications = 0 %}
{% assign total_creators     = 0 %}
{% for stat in site.data.stats %}
  {% assign total_applications = total_applications | plus: stat.applications %}
  {% assign total_creators     = total_creators     | plus: stat.creators     %}
{% endfor %}

2016年から未踏ジュニアが始まり、これまでに **{{ total_applications }} 件の応募、{{ total_creators }} 名のクリエータを支援・採択**してきました。

<div class='flex'>
  <a href='/final'    class='button'>最新の採択例を見る</a>
  <a href='/projects' class='button'>過去の採択例を見る</a>
</div>

<br>

## 採択者への支援 {#supports}
未踏ジュニアに応募し、採択されると、採択者（クリエータ）は以下の支援を得られます。

### メンタリングの提供 {#mentoring-support}
担当の[メンター](/mentors)をはじめ、未踏事業の修了生らを中心とする各界で活躍するエンジニア・専門家の指導が受けられます。

<div class="tips">期間中は、毎週１時間ほど、オンラインでメンターと話せる機会があります。プログラミングの質問やプロジェクトの方針など、なんでも相談できます。</div>
<a href="/mentors" class="button">メンター紹介を見る</a>

### 開発資金の援助 {#financial-support}
採択された各グループへ、50万円を上限として開発資金の援助を行います。

例えばハードウェア開発で機材・資材を使いたい場面や、ソフトウェア開発で有料のAPI・サーバーを使いたい場面などで、50万円まで使える仕組みになっています。

### 開発場所の援助 {#development-support}
必要に応じて、開発場所及び工作機材の援助を行います。

### 未踏ジュニアスーパークリエータの認定 {#award-outstanding-performance}
特に顕著な成果を残したクリエータを、未踏ジュニアスーパークリエータとして認定します。[慶應義塾大学SFC](https://www.sfc.keio.ac.jp/news/012903.html)や[東京都立大学](https://cs.sd.tmu.ac.jp/admission_office.html)、[近畿大学](https://newscast.jp/news/1055602)に推薦枠で出願できます。

<!--(追記: 東京都立大学の推薦枠は<a href='https://twitter.com/mamoruk/status/1318484847317315584'>採択者全員に緩和</a>されました)-->

<!--<img src="/assets/img/press_by_universities.webp" data-src="/assets/img/press_by_universities.webp" alt="各大学の発表資料の例" class="top-img lazyload" loading="lazy" style='margin-top: 30px;'>-->

<br>

## 運営団体について {#organizer}
[一般社団法人未踏](https://www.mitou.org/)という、[未踏事業](https://www.ipa.go.jp/jinzai/mitou/about.html)の卒業生を中心とした団体が運営をしています。未踏ジュニアは、その中のプログラミング教育研究会というグループで取り組んでいる事業となっています。

### 未踏関係者インタビュー {#interviews}
未踏関係者に『**なんで未踏?**』という質問をしてみました。未踏について一歩深く知るキッカケになれば嬉しいです <i class="far fa-laugh-squint" aria-hidden="true" /> <i class="far fa-thumbs-up" aria-hidden="true" />

<div class="youtube" itemprop="video" itemscope itemtype="http://schema.org/VideoObject">
  <meta itemprop="isFamilyFriendly"     content="True">
  <meta itemprop="requiresSubscription" content="False">
  <meta itemprop="width"                content="1280">
  <meta itemprop="height"               content="720">
  <meta itemprop="thumbnailUrl"         content="https://i.gyazo.com/67c56597574a341d2d686a51ad8238ed.jpg">
  <meta itemprop="uploadDate"           content="2019-02-20">
  <meta itemprop="contentUrl"           content="https://youtube.googleapis.com/v/1KNkEAh9AK4">
  <meta itemprop="embedUrl"             content="https://www.youtube.com/embed/1KNkEAh9AK4?rel=0">
  <meta itemprop="name"                 content="未踏ジュニアとは？">
  <meta itemprop="description"          content="未踏関係者に『なんで未踏?』という質問をしてみました。未踏について一歩深く知るキッカケになれば嬉しいです。">
  <iframe width="100%" src="https://www.youtube.com/embed/playlist?list=PLNObH2jlC6leiUTypiJYO2zUcwBg7M0Bg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
</div>

<a href="https://www.youtube.com/playlist?list=PLNObH2jlC6leiUTypiJYO2zUcwBg7M0Bg&disable_polymer=true" class="button">YouTubeで視聴する</a>

<br>

### 応募〜採択までの流れ {#guideline}
未踏ジュニアでは応募から採択までの流れや、応募書類（提案書）を書くコツ、採択者の体験談なども公開しています。もし興味があればぜひチェックしてみてください。

<div class='flex'>
  <a href="/guideline" class="button">採択までの流れを見る</a>
  <a href="/download"  class="button">提案書・体験談を見る</a>
</div>


### 他の支援プログラム {#opportunities}
<a href='https://www.mitou.org/'>未踏社団</a>が運営する未踏ジュニア以外にも、あなたの作りたいもの（<a href='/download'>提案書</a>）を支援してくれるプログラムがあります。こちらもぜひ！

<a href="/opportunities" class="button">他の支援プログラムを見る</a>
