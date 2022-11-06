+++
title = "FAQ"
description = "Answers to frequently asked questions."
date = 2021-05-01T19:30:00+00:00
updated = 2021-05-01T19:30:00+00:00
draft = false
weight = 30
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Answers to frequently asked questions."
toc = true
top = false
+++

## What's the difference between static and dynamic QR codes?
A code can be either static or dynamic. A static code encodes data directly into the QR code, meaning that users who scan your code will be served the data without going through RoQR's servers. This means that no statistics regarding the scans of the code can be seen on the platform. Since a static code encodes the data into the QR code directly, any changes to the code's data will mean that the QR code also changes.

Conversely, a dynamic code can be updated without changing the QR code, and scans of the code will route the users through the RoQR platform before redirecting them to the code target, meaning that statistics about the scans are accessible through RoQR. A dynamic code can also be protected behind a password, prompting users to enter the password before being redirected to the code's data.

## Why do some rows on the Insights page appear blank?
RoQR 
