---
title: "A Preference to disable HTTP Keep-Alive has been removed"
date: "2012-12-03T03:50:54-05:00"
categories: ["networking"]
tags: []
versions: ["17"]
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=770331": "Bug 770331 – Remove HTTP Keep-Alive disable pref"
---
In Firefox, the HTTP Keep-Alive (persistent connection) feature has been enabled, and it can be disabled with a hidden preference `network.http.keep-alive` if any issues found. The pref has been removed from Firefox 17 and Keep-Alive will always be enabled.
