---
title: "OS X 上で Canvas が絵文字を描画できません"
date: "2015-10-03T22:54:00-04:00"
categories: ["canvas-webgl"]
tags: []
versions: ["41", "42", "43", "44", "45"]
statuses: "regressed"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1209480": "Bug 1209480 - Canvas no longer able to render emojis (caused by switch to Skia)"
---
[Canvas API](https://developer.mozilla.org/ja/docs/Web/API/Canvas_API) が、Skia 2D グラフィックスライブラリへの移行により、OS X プラットフォーム向けの Firefox 41 とそれ以降のバージョンで絵文字を描画できなくなっています。これにより *WordPress* などで使われている *Modernizr* の絵文字判別機能がうまく動作していません。Mozilla 開発者が解決策に取り組んでいます。
