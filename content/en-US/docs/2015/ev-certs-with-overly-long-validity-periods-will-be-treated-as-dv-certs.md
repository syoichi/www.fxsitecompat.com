---
title: "EV certs with overly long validity periods will be treated as DV certs"
date: "2015-08-05T00:48:18-04:00"
categories: ["privacy-security"]
tags: []
versions: ["42"]
cclicense: "BY-SA 3.0"
references:
    "https://bugzilla.mozilla.org/show_bug.cgi?id=1145679": "Bug 1145679 - Reject EV status for end-entity EV certs with overly long validity periods"
---
According to the current version of the EV SSL Certificate Guidelines, EV certificates should not be valid for longer than 27 months. Firefox has set the limit to 39 months for the backward compatibility and potential limit increase in the near future. Therefore, EV certificates with validity periods longer than 39 months will be rejected the EV status and rather treated as normal DV certificates.
