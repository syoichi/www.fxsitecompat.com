---
title: "HTTP/2 ヘッダ内の改行は許容されなくなりました"
date: "2015-10-30T17:06:00-07:00"
categories: ["networking"]
tags: []
versions: ["44"]
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1197847": "Bug 1197847 - dont allow line folding in h2 headers"
---
従来の HTTP と異なり、HTTP/2 レスポンスヘッダ内では改行文字 (`\n`) は許可されていません。Firefox 44 は実装を更新してこの制約を遵守させるようになったため、今後そうしたヘッダは不正なものと見なされます。
