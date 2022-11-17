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

## Link attributes

<dl>
    <dt>Name</dt>
    <dd>A unique name to identify the link. This name is used within the app and in exported statistics to show which link has been scanned.</dd>
    <dt>Dynamic</dt>
    <dd>A link can be either static or dynamic. A static link encodes data directly into the QR code, meaning that users who scan your code will be served the data without going through RoQR's servers. This means that no statistics regarding the scans of the link can be seen on the platform. Since a static link encodes the data into the QR code directly, any changes to the link's data will mean that the QR code also changes. Conversely, a dynamic code can be updated without changing the QR code, and scans of the code will route the users through the RoQR platform before redirecting them to the link target, meaning that statistics about the scans are accessible through RoQR.</dd>
    <dt>Password (optional)</dt>
    <dd>Dynamic links can be password-protected. If a user scans a password-protected link, they will be prompted to enter the password before being redirected to the link data.</dd>
    <dt>Style (optional)</dt>
    <dd>The predifined style to use in styling the QR code. If no style is selected, the code will be generated using a standard black-and-white format.</dd>
</dl>

## Link types

### URL link

Links to any website (URL) on the internet.

#### Attributes

<dl>
    <dt>URL</dt>
    <dd>The <a href="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL">URL</a> that the user should be redirected to after scanning the QR code. </dd>
</dl>

### Email link

Links to a pre-populated email with a recipient email address, subject and body text. When scanned, the users default email app will open, and the user will be presented with a draft email containing the data specified in the link.

#### Attributes

<dl>
    <dt>Email address (optional)</dt>
    <dd>The email address to which the email should be addressed.</dd>
    <dt>Subject (optional)</dt>
    <dd>The subject line of the email.</dd>
    <dt>Body (optional)</dt>
    <dd>The body text of the email.</dd>
</dl>

### WiFi link

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

### Telephone link

Links to a phone number. When scanned, the users default phone app will be opened with the phone number filled in.

#### Attributes

<dl>
    <dt>Phone number</dt>
    <dd>The phone number in the link.</dd>
</dl>

### SMS link

Links to a pre-populated SMS with a recipient phone number and body text. When scanned, the user's default SMS app will open, and the user will be presented with a draft SMS containing the data specified in the link.

#### Attributes

<dl>
    <dt>Telephone number (optional)</dt>
    <dd>The telephone number to which the SMS should be addressed.</dd>
    <dt>Body (optional)</dt>
    <dd>The body text of the SMS.</dd>
</dl>

### Contact link

Links to a contact that can be imported into an address book. When scanned, the user will be presented with the contact and the option to edit and save the details.

#### Attributes

<dl>
    <dt>First name (optional)</dt>
    <dd>The first name of the contact</dd>
    <dt>Last name (optional)</dt>
    <dd>The last name of the contact.</dd>
    <dt>Email (optional)</dt>
    <dd>The email address of the contact.</dd>
    <dt>Phone (optional)</dt>
    <dd>The telephone number of the contact.</dd>
    <dt>Birthday (optional)</dt>
    <dd>The contact's birthday.</dd>
    <dt>Website (optional)</dt>
    <dd>A website associated with the contact.</dd>
    <dt>Address (optional)</dt>
    <dd>The contact's street address.</dd>
    <dt>Company (optional)</dt>
    <dd>The contact's employer / company.</dd>
    <dt>Title (optional)</dt>
    <dd>The contact's title / role at their company.</dd>
    <dt>Note (optional)</dt>
    <dd>A free-form note to associate with the contact.</dd>
</dl>
