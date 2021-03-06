---
title: "`window.defaultStatus` が削除されました"
date: "2013-04-06T04:52:59-04:00"
categories: ["dom"]
tags: []
versions: ["23"]
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=862917": "Bug 862917 – Remove window.defaultStatus"
---
[`window.defaultStatus`](https://developer.mozilla.org/ja/docs/Web/API/window.defaultStatus) プロパティが使用できなくなりました。Firefox では、初期設定で Web ページによるステータス文字列の変更が許可されていないため、このプロパティを設定しても効果がありませんでした。最近、Firefox のユーザインタフェースから、この設定を有効にするオプション項目が削除されました。また、このプロパティは HTML5 仕様でも規定されていません。[`window.status`](https://developer.mozilla.org/ja/docs/Web/API/window.status) は引き続き使用可能です。
