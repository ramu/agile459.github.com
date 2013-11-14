---
layout: page
title: Home
---
{% include JB/setup %}

## はじめまして

Agile459は、四国地域においてアジャイルな開発、アジャイルなビジネスを実践研究するためのコミュニティです。

[アジャイルプロセス協議会](http://www.agileprocess.jp)四国支部も兼ねています。

詳しい情報は[Agile459とは](about.html)を参照ください。

## 最新の投稿

{% assign posts = site.posts %}
{% assign listing_limit = 5 %}
{% include post-listing.html %}

