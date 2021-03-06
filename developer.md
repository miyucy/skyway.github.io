---
layout: default
title: 開発者
lang: ja
main_visual:
  main_copy: <span>あなたの</span><wbr><span>アイデアを</span><wbr><span>形にしよう</span>
  sub_copy: <span>マルチ</span><wbr><span>プラット</span><wbr><span>フォームに</span><wbr><span>対応する</span><wbr><span>SDKや</span><wbr><span>実践的な</span><wbr><span>チュートリアル、</span><wbr><span>豊富な</span><wbr><span>サンプルコードを</span><wbr><span>用意、</span><wbr><span>あなたの</span><wbr><span>アイデアを</span><wbr><span>すぐに</span><wbr><span>形に</span><wbr><span>できます</span>
  links: 
  copy_position: ["after"]
  image_file_name: 
  font_color: "#fff"
  background_color: "#004386"
breadcrumb: [index.md]
---

## Get Started

SkyWayを利用すればアプリケーションの開発を簡単に始めることができます。 

### STEP1

次のコマンドを入力して、ビデオ通話アプリを動かしてみましょう。

```sh
$ git clone git@github.com:skyway/skyway-js-skeleton.git
$ cd skyway-js-skeleton
$ npm install & npm start
```

### STEP2

うまく動いたら、[Community Edition](https://console-webrtc-free.ecl.ntt.com/users/registration)に登録し、APIキーを発行しましょう。　　

### STEP3

次のコマンドを入力して、STEP1のビデオ通話アプリのAPIキーをあなたのものに変更しましょう。  
チュートリアルやAPIリファレンスを参考に、本格的な開発を始めましょう。

```sh
$ echo "window.__SKYWAY_KEY__ = '<YOUR_KEY_HERE>';" > ./key.js
```

## SDKを利用する前に

各SDKを利用する際に役立つ、共通の概念や通信モデルについて、ドキュメントを公開しています。  
はじめにお読みください。

[SkyWayの通信モデル](./communication-model.html){: .btn .btn-primary }

## SDK

Webブラウザ、iOS、Android、IoTデバイスをカバーできる4つのSDKを用意しています。

<div id="sdk-div" class="row row-for-slim-card">
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="./js-sdk.html" class="list-group-item active list-head">
                <i class="fa fa-television fa-fw" aria-hidden="true"></i>
                <span>JavaScript SDK</span>
            </a>
            <a href="./js-tutorial.html" class="list-group-item list-group-item-action">チュートリアル</a>
            <a href="./js-sdk.html#sdkdownload" class="list-group-item list-group-item-action">SDKダウンロード</a>
            <a href="./js-reference/" class="list-group-item list-group-item-action">APIリファレンス</a>
            <a href="https://github.com/skyway/skyway-js-sdk/tree/master/examples" class="list-group-item list-group-item-action" target="_blank">サンプルコード</a>
        </div>
    </div>
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="./ios-sdk.html" class="list-group-item active list-head">
                <i class="fa fa-apple fa-fw fa-3x" aria-hidden="true"></i>
                <span>iOS SDK</span>
            </a>
            <a href="./ios-tutorial.html" class="list-group-item list-group-item-action">チュートリアル</a>
            <a href="./ios-sdk.html#sdkdownload" class="list-group-item list-group-item-action">SDKダウンロード</a>
            <a href="./ios-reference/" class="list-group-item list-group-item-action">APIリファレンス</a>
            <a href="https://github.com/skyway/skyway-ios-sdk/tree/master/examples" class="list-group-item list-group-item-action" target="_blank">サンプルコード</a>
        </div>
    </div>
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="./android-sdk.html" class="list-group-item active list-head">
                <i class="fa fa-android fa-fw fa-3x" aria-hidden="true"></i>
                <span>Android SDK</span>
            </a>
            <a href="./android-tutorial.html" class="list-group-item list-group-item-action">チュートリアル</a>
            <a href="./android-sdk.html#sdkdownload" class="list-group-item list-group-item-action">SDKダウンロード</a>
            <a href="./android-reference/" class="list-group-item list-group-item-action">APIリファレンス</a>
            <a href="https://github.com/skyway/skyway-android-sdk/tree/master/examples" class="list-group-item list-group-item-action" target="_blank">サンプルコード</a>
        </div>
    </div>
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="https://github.com/nttcom/skyway-iot-sdk" target="_blank" class="list-group-item active list-head">
                <i class="fa fa-microchip fa-fw fa-3x" aria-hidden="true"></i>
                <span>IoT SDK</span>
                <small>β version</small>
            </a>
            <a href="https://github.com/nttcom/skyway-iot-sdk/blob/master/docs/how_to_install.md" target="_blank" class="list-group-item list-group-item-action">インストール</a>
            <a href="https://github.com/nttcom/skyway-iot-sdk/blob/master/docs/how_to_use_sample_app.md" target="_blank" class="list-group-item list-group-item-action">利用手順</a>
            <a href="https://github.com/nttcom/skyway-iot-sdk/tree/master/docs/apiref" target="_blank" class="list-group-item list-group-item-action">APIリファレンス</a>
            <a href="https://github.com/nttcom/skyway-siru-sample" target="_blank" class="list-group-item list-group-item-action">サンプルコード</a>
        </div>
    </div>
</div>



## すべての機能 

<div id="feature-div" class="row row-for-slim-card">
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Media & Data</h3>
                <p class="card-text">提供するSDKではメディアチャンネル・データチャンネルを利用可能</p>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">シグナリング</h3>
                <p class="card-text">IPアドレスやコーデック等の情報を相手と交換するためのサーバ、多人数通話に便利なRoom管理機能を備える</p>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">STUN</h3>
                <p class="card-text">NAT越えに必要な、自身のグローバルIPアドレスとポート番号を確認するサーバを無料で提供<br></p>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">認証</h3>
                <p class="card-text">APIキーの不正利用を防止するための認証機能を提供</p>
                <a href="https://github.com/skyway/skyway-peer-authentication-samples" target="_blank" class="btn btn-outline-primary">利用方法(GitHub)</a>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">TURN</h3>
                <p class="card-text">P2Pで通信が確立できない環境にメディアを中継するサーバを提供</p>
                <a href="./pricing.html#サーバ通信料" class="btn btn-outline-primary">料金</a>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">SFU</h3>
                <p class="card-text">多人数通話や配信を実現する、映像・音声送信を代行するメディアサーバを提供</p>
                <a href="./pricing.html#サーバ通信料" class="btn btn-outline-primary">料金</a>
                <a href="./sfu.html" class="btn btn-outline-primary">SFUの説明</a>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">画面共有</h3>
                <p class="card-text">画面共有用ブラウザ拡張を簡単に実装するためのライブラリ、サンプルコードを提供</p>
                <a href="https://github.com/skyway/skyway-screenshare" target="_blank" class="btn btn-outline-primary">利用方法(GitHub)</a>
            </div>
        </div>
    </div>
</div>

## ドキュメント

開発に役立つドキュメントを公開しています。

<div id="docs-div" class="row row-for-slim-card">
    <div class="col-12 col-sm-6 col-lg-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">SkyWayの通信モデル</h3>
                <p class="card-text">各SDKを利用する際に役立つ、共通の概念や通信モデルについて、ドキュメントを公開しています。</p>
                <small class="text-muted">2017年12月4日</small>
                <a href="./communication-model.html" class="btn btn-outline-primary">SkyWayの通信モデル</a>
            </div>
        </div>
    </div>
    <div class="col-12 col-sm-6 col-lg-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">新SDKへの移行方法</h3>
                <p class="card-text">トライアル版のSkyWayは2018年3月をもって提供を終了します。
                  2017年9月7日に提供を開始した新バージョンのSDKへの移行をお願いします。</p>
                <small class="text-muted">2017年9月5日</small>
                <a href="./migration.html#toECLWebRTC" class="btn btn-outline-primary">マイグレーション</a>
            </div>
        </div>
    </div>
    <div class="col-12 col-sm-6 col-lg-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">WebRTCセキュリティレポート</h3>
                <p class="card-text">WebRTCのセキュリティに関する考察をオープンソースで公開しています。WebRTCのセキュリティについて詳しく知りたい方はご覧ください。</p>
                <small class="text-muted">2015年7月28日</small>
                <a href="http://webrtc-security.github.io/index.html" target="_blank" class="btn btn-outline-primary">セキュリティレポート</a>
            </div>
        </div>
    </div>
</div>

## サポート

開発に役立つ開発者コミュニティやチケットサポートを提供しています。

{% include support-cards.html %}

## メンテナンス・障害情報

メンテナンス、障害情報を公開しています。  
各情報の通知をRSSで受け取りたい方は、 [メンテナンスおよび障害情報のお知らせと通知について](https://support.skyway.io/hc/ja/articles/236195548){:target="_blank"} をご覧ください。


<div class="card">
  <div class="card-header">
    <ul class="nav nav-tabs card-header-tabs">
      <li class="nav-item">
        <a class="nav-link active" data-toggle="tab" href="#maintenance" role="tab">メンテナンス情報</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#failure" role="tab">障害情報</a>
      </li>
    </ul>
  </div>
  <div class="card-body">
    <div class="tab-content">
      <div class="tab-pane active" id="maintenance" role="tabpanel"> 
      </div>
      <div class="tab-pane" id="failure" role="tabpanel">
      </div>
    </div>
  </div>
</div>

<script>
$(function() {
  'use strict';

  // AJAXでZendeskのお知らせを取得して表示

  // JSON取得
  $.getJSON(CONST.JSON_URL_MAINTENANCE).done(function(data) {
    updateNews(data, 'maintenance', CONST.ZENDESK_URL_MAINTENANCE);
  }).fail(function(data) {
    console.log('xhr failed');
  });

  $.getJSON(CONST.JSON_URL_FAILURE).done(function(data) {
    updateNews(data, 'failure', CONST.ZENDESK_URL_FAILURE);
  }).fail(function(data) {
    console.log('xhr failed');
  });

  // DOM作成
  function updateNews(obj, id, siteurl){
    var $rows = $('<div>').addClass('rows');;
    for (var i = 0; i < obj.articles.length; i++) {
      var $cardTitle = $('<h4>')
        .text(obj.articles[i].body.substr(4, 10))
        .addClass('card-title h6');
      var $cardText = $('<p>')
        .html(obj.articles[i].body)
        .addClass('mini-headline-text card-text');
      var $col1 = $('<div>')
        .addClass('col-sm-3 col-lg-2')
        .append($cardTitle);
      var $col2 = $('<div>')
        .addClass('col-sm-9 col-lg-10')
        .append($cardText);
      var $row = $('<div>')
        .addClass('row')
        .append($col1)
        .append($col2);
      $rows.append($row);
    }
    var $link = $('<a>')
      .addClass('btn btn-primary')
      .attr({
        href: siteurl,
        target: '_blank'
      })
      .text('すべて見る')
      .appendTo('<div class="allnewslink">')
      .parent();
    $('#' + id).append($rows).append($link);
  }
});
</script>
