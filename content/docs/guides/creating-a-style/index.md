+++
title = "Creating a reusable style"
description = "Styles let you re-use the visual design of your QR codes."
date = 2021-05-01T08:00:00+00:00
updated = 2021-05-01T08:00:00+00:00
draft = false
weight = 10
sort_by = "weight"
template = "docs/page.html"

[extra]
toc = false
top = false
+++

Styles let you define and re-use the visual design of your QR codes across the RoQR platform.

## Creating a style

To create a new style, navigate to the ["Styles" page](https://roqr.app/styles) and click the `New style` button. Give the style a new name, customize the color and shape of the QR code components, and optionally add a logo. For a full reference of what the various settings do, see the [style reference](../../reference/style).

{% info() %}
	By default, any change to the `dots` settings will also apply to the `corner squares` and `corner dots` settings. To override the styling for the corners, just update the relevant fields directly.
{% end %}

### Example: Facebook QR code

As an example, lets create a style that you can use to link to a Facebook page.

In the `name` field of the new style form, enter `Facebook`. In the background settings, set the background color to Facebook Blue (`#1877F2`) and the dots color to white (`#ffffff`).

Change the dots shape field to extra-rounded to reflect Facebook's rounded design.

Finally, fill the image URL field with the URL `https://upload.wikimedia.org/wikipedia/en/thumb/0/04/Facebook_f_logo_%282021%29.svg/1920px-Facebook_f_logo_%282021%29.svg.png` to add the Facebook logo to the center of the QR code.

{{ resize_image(path="docs/guides/creating-a-style/facebook_style.png", height=0, width=695, op="fit_width") }}
