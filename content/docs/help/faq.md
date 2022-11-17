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

## Will I lose access to the platform or have my plan updated automatically if my codes receive more scans than my current plan allows?
No. If you exceed the allowed scans for more than one month in a row, we'll reach out to you to upgrade your plan. At that point you'll have the choice to upgrade to a new plan or cancel your account.

If the number of scans you receive per month is much higher than what your plan allows, we may reach out sooner.

In any case, we will not cancel or pause your account without giving you notice and the time to make a decision about upgrading.

## Why do some rows on the Insights page appear blank?
RoQR completely hides the scan data for any scanner of a QR code who asks not to be tracked using the [Do Not Track ("DNT")](https://www.eff.org/issues/do-not-track) setting on their web browser. You will still see that the code has been scanned and at what time, but not any further information about that particular scan.

## Why does my QR code not keep its transparent background when downloading as a JPEG?
The JPEG format uses RGB color space and [does not support transparent backgrounds](https://stackoverflow.com/questions/16906144/transparent-background-in-jpeg-image). To retain the transparent background, you can download your code in the PNG, SVG or WebP formats.
