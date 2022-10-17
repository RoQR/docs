+++
title = "Link"
description = "Links specify what should happen when a user scans one of your QR codes."
date = 2021-05-01T08:00:00+00:00
updated = 2021-05-01T08:00:00+00:00
draft = false
weight = 10
sort_by = "weight"
template = "docs/page.html"

[extra]
toc = true
top = false
+++

Links specify what should happen when a user scans one of your QR codes:
- Where should the user be redirected to?
- Should the redirection be password protected?
- Should statistics regarding the scan be recorded?

All of these behaviors are defined within the link settings.

## Link types

### URL Link

Links to any website (URL) on the internet.

#### Attributes

<dl>
    <dt>URL</dt>
    <dd>The <a href="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL">URL</a> that the user should be redirected to after scanning the QR code. </dd>
</dl>

### Email Link

Links to a prepoulated email with a recipient email address, subject and body text. When scanned, the users default email app will open, and the user will be presented with a draft email containing the data specified in the link.

#### Attributes

<dl>
    <dt>Email address (optional)</dt>
    <dd>The email address to which the email should be addressed.</dd>
    <dt>Subject (optional)</dt>
    <dd>The subject line of the email.</dd>
    <dt>Body (optional)</dt>
    <dd>The body text of the email.</dd>
</dl>

### WiFi Link

Links to the settings for a WiFi network, allowing the scanner to connect to the network by scanning the QR code.

{% important() %}
	WiFi links cannot be made dynamic.
{% end %}

#### Attributes

<dl>
    <dt>Network name</dt>
    <dd>The name of the network.</dd>
    <dt>Password (optional)</dt>
    <dd>The password that is used to connect to the WiFi network.</dd>
    <dt>Security protocol</dt>
    <dd>
        Specifies the type of security protocol used to secure the WiFi network.
        One of :
	    <ul>
            <li>None</li>
            <li>WEP</li>
            <li>WPA</li>
        </ul>
        <a href="https://www.avast.com/c-wep-vs-wpa-or-wpa2">More information on various WiFi security protocols</a>.
    </dd>
</dl>
