---
title: "`@-moz-document` support has been dropped"
date: "2015-10-13T13:17:00-04:00"
categories: ["css", "privacy-security"]
tags: []
versions: ["44"]
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1035091": "Bug 1035091 - limit @-moz-document to user and UA sheets (Makes it useless for exfiltration in CSS-injection attacks)"
---
The [`@-moz-document`](https://developer.mozilla.org/en-US/docs/Web/CSS/@document) rule is no longer available from Web content since it could be used by attackers for CSS injection to steal private data in the URL of third-party sites. Firefox users are still able to use this rule in their user stylesheet to personalize the browsing experience.
