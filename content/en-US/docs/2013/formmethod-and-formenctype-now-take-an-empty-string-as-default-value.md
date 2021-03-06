---
title: "`formMethod` and `formEnctype` now take an empty string as default value"
date: "2013-02-06T08:44:10-05:00"
categories: ["dom"]
tags: []
versions: ["21"]
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=787095": "Bug 787095 – Update formMethod reflection to have the empty string as default value (and \'get\' as invalid value)"
    "https://bugzilla.mozilla.org/show_bug.cgi?id=839171": "Bug 839171 – Update formMethod reflection to have the empty string as default value (and \'get\' as invalid value)"
---
The HTML5 spec of the [`formMethod`](https://developer.mozilla.org/en-US/docs/HTML/Element/Input#attr-formmethod) and [`formEnctype`](https://developer.mozilla.org/en-US/docs/HTML/Element/Input#attr-formenctype) properties has been updated to have the empty string as default value. Firefox followed the change.
