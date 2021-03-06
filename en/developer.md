---
layout: default
title: Developer
lang: en
main_visual:
  main_copy: Shape your ideas into reality.
  sub_copy: With SDKs supporting multiple platforms, lots of tutorials and sample code, ECLWebRTC can help you materialize your ideas.
  links: 
  copy_position: ["after"]
  image_file_name: 
  font_color: "#fff"
  background_color: "#004386"
breadcrumb: [en/index.md]
---

## Get Started

ECLWebRTC enables customers to start developing applications easily.

### STEP1

Enter the following command to start a videochat application.

```sh
$ git clone git@github.com:skyway/skyway-js-skeleton.git
$ cd skyway-js-skeleton
$ npm install & npm start
```

### STEP2

Once you've given it a try, sign up for the free [Community Edition](https://console-webrtc-free.ecl.ntt.com/users/registration) and get an API Key.

### STEP3

Replace the API key in the sample code with the one you got in STEP2.
Start a developing a fully functioning app by reading the tutorials and API reference.

```sh
$ echo "window.__SKYWAY_KEY__ = '<YOUR_KEY_HERE>';" > ./key.js
```

## Basic Concept

This article describes basic concept of ECLWebRTC. Recommended for developers interested in knowing about the communication model of ECLWebRTC.

[Communication Model](./communication-model.html){: .btn .btn-primary }

## SDK

There are SDKs for Web browsers, iOS, Android and IoT devices.

<div id="sdk-div" class="row row-for-slim-card">
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="./js-sdk.html" class="list-group-item active list-head">
                <i class="fa fa-television fa-fw" aria-hidden="true"></i>
                <span>JavaScript SDK</span>
            </a>
            <a href="./js-tutorial.html" class="list-group-item list-group-item-action">Tutorial</a>
            <a href="./js-sdk.html#sdkdownload" class="list-group-item list-group-item-action">SDK Download</a>
            <a href="./js-reference/" class="list-group-item list-group-item-action">API Reference</a>
            <a href="https://github.com/skyway/skyway-js-sdk/tree/master/examples/" class="list-group-item list-group-item-action" target="_blank">Sample Code</a>
        </div>
    </div>
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="./ios-sdk.html" class="list-group-item active list-head">
                <i class="fa fa-apple fa-fw fa-3x" aria-hidden="true"></i>
                <span>iOS SDK</span>
            </a>
            <a href="./ios-tutorial.html" class="list-group-item list-group-item-action">Tutorial</a>
            <a href="./ios-sdk.html#sdkdownload" class="list-group-item list-group-item-action">SDK Download</a>
            <a href="./ios-reference/" class="list-group-item list-group-item-action">API Reference</a>
            <a href="https://github.com/skyway/skyway-ios-sdk/tree/master/examples/" class="list-group-item list-group-item-action" target="_blank">Sample Code</a>
        </div>
    </div>
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="./android-sdk.html" class="list-group-item active list-head">
                <i class="fa fa-android fa-fw fa-3x" aria-hidden="true"></i>
                <span>Android SDK</span>
            </a>
            <a href="./android-tutorial.html" class="list-group-item list-group-item-action">Tutorial</a>
            <a href="./android-sdk.html#sdkdownload" class="list-group-item list-group-item-action">SDK Download</a>
            <a href="./android-reference/" class="list-group-item list-group-item-action">API Reference</a>
            <a href="https://github.com/skyway/skyway-android-sdk/tree/master/examples/" class="list-group-item list-group-item-action" target="_blank">Sample Code</a>
        </div>
    </div>
    <div class="col-6 col-md-3">
        <div class="list-group">
            <a href="https://github.com/nttcom/skyway-iot-sdk" target="_blank" class="list-group-item active list-head">
                <i class="fa fa-microchip fa-fw fa-3x" aria-hidden="true"></i>
                <span>IoT SDK</span>
                <small>β version</small>
            </a>
            <a href="https://github.com/nttcom/skyway-iot-sdk/blob/master/docs/how_to_install.md" target="_blank" class="list-group-item list-group-item-action">Install</a>
            <a href="https://github.com/nttcom/skyway-iot-sdk/blob/master/docs/how_to_use_sample_app.md" target="_blank" class="list-group-item list-group-item-action">Use Procedure</a>
            <a href="https://github.com/nttcom/skyway-iot-sdk/tree/master/docs/apiref" target="_blank" class="list-group-item list-group-item-action">API Reference</a>
            <a href="https://github.com/nttcom/skyway-siru-sample" target="_blank" class="list-group-item list-group-item-action">Sample Code</a>
        </div>
    </div>
</div>



## All Features

<div id="feature-div" class="row row-for-slim-card">
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Media & Data</h3>
                <p class="card-text">With the provided SDK, media channels and data channels can be used.</p>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Signaling</h3>
                <p class="card-text">Exchanges information needed to start a WebRTC session, such as IP addresses and codec with the partner. Also includes Room management functionality useful for communicating with many people.</p>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">STUN</h3>
                <p class="card-text">Servers used to get your public IP address and port number to traverse your NAT can be used for free.<br></p>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Authorization</h3>
                <p class="card-text">Authentication is provided to prevent illegal use of API keys.</p>
                <a href="https://github.com/skyway/skyway-peer-authentication-samples" target="_blank" class="btn btn-outline-primary">How to use(Github)</a>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">TURN</h3>
                <p class="card-text">Servers to relay media in environments where Peer to Peer communication cannot be established.</p>
                <a href="./pricing.html#turnsfu-communication-charge" class="btn btn-outline-primary">Pricing</a>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">SFU</h3>
                <p class="card-text">Media servers that relay voice and video data to make conferences with many people possible.</p>
                <a href="./pricing.html#turnsfu-communication-charge" class="btn btn-outline-primary">Pricing</a>
                <a href="./sfu.html" class="btn btn-outline-primary">Details of SFU</a>
            </div>
        </div>
    </div>
    <div class="col-6 col-sm-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Screen Sharing</h3>
                <p class="card-text">A library and sample code to help implement a browser extension that allows screen sharing.</p>
                <a href="https://github.com/skyway/skyway-screenshare" target="_blank" class="btn btn-outline-primary">How to use(Github)</a>
            </div>
        </div>
    </div>
</div>

## Document

Documents useful for development.

<div id="docs-div" class="row row-for-slim-card">
    <div class="col-12 col-md-6 col-lg-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">Communication Model of ECLWebRTC</h3>
                <p class="card-text">This article describes basic concept of ECLWebRTC. Recommended for developers interested in knowing about the communication model of ECLWebRTC.</p>
                <small class="text-muted">Dec 8th, 2017</small>
                <a href="./communication-model.html" class="btn btn-outline-primary">Communication Model</a>
            </div>
        </div>
    </div>
    <div class="col-12 col-md-6 col-lg-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">How to migrate to ECLWebRTC</h3>
                <p class="card-text">SkyWay will be terminated as of March, 2018. Please migrate from SkyWay to ECLWebRTC using this document.</p>
                <small class="text-muted">Sep 7th, 2017</small>
                <a href="./migration.html" class="btn btn-outline-primary">Migration</a>
            </div>
        </div>
    </div>
    <div class="col-12 col-md-6 col-lg-4">
        <div class="card">
            <div class="card-body">
                <h3 class="card-title">WebRTC Security report</h3>
                <p class="card-text">An open-source document on the considerations on WebRTC security. Recommended for customers interested in knowing about the security concerns of WebRTC.</p>
                <small class="text-muted">Jul 28th, 2017</small>
                <a href="http://webrtc-security.github.io/index.html" target="_blank" class="btn btn-outline-primary">Security Report</a>
            </div>
        </div>
    </div>
</div>

## Support

Provides developer community and support ticket useful for development.

{% include support-cards.html %}

## Maintenance and Failure Information

Maintenance and Failure Information.
If you want to receive RSS notifications, please see [Announcement and Notification of Maintenance and Failure Information](https://support.skyway.io/hc/en-us/articles/236195548){:target="_blank"}.



<div class="card">
  <div class="card-header">
    <ul class="nav nav-tabs card-header-tabs">
      <li class="nav-item">
        <a class="nav-link active" data-toggle="tab" href="#maintenance" role="tab">Maintenance Information</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" data-toggle="tab" href="#failure" role="tab">Failure Information</a>
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
      .text('See all')
      .appendTo('<div class="allnewslink">')
      .parent();
    $('#' + id).append($rows).append($link);
  }
});
</script>
