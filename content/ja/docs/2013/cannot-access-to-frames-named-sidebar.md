---
title: "`sidebar` という名前のフレームにアクセスできません"
date: "2013-02-24T03:44:31-05:00"
categories: ["dom"]
tags: []
versions: ["22"]
statuses: "regressed"
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=888225": "Bug 888225 – firefox 22 breaks access to frames named \'sidebar\'"
---
Firefox 22 で、`sidebar` という名前の付いた [`<frame>`](https://developer.mozilla.org/ja/docs/Web/HTML/Element/frame) と [`<iframe>`](https://developer.mozilla.org/ja/docs/Web/HTML/Element/iframe) 要素へアクセスできなくなりました。このリグレッションは Firefox 23 で修正されました。
