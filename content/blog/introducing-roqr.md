+++
title = "Mic check: Introducing RoQR"
description = "Introducing RoQR, a modern, open, privacy-respecting and affordable platform for dynamic QR codes."
date = 2022-11-01T09:19:42+00:00
updated = 2022-11-01T09:19:42+00:00
draft = true
template = "blog/page.html"

[taxonomies]
authors = ["Sebastian Rollén"]

[extra]
lead = "RoQR is a modern, open, privacy-respecting and affordable platform for dynamic QR codes."
+++

## Why QR codes?

QR codes are having a moment. Originally invented in 1994 as a solution for tracking components in automotive manufacturing, adoption of QR codes for all sorts of industries has exploded over the past couple of years. It's no wonder either - QR codes are a modern technological marvel in terms of convenience and durability. We believe that QR codes have officially won the war for how we connect the physical and digital worlds. Scanning a QR code is significantly more convenient for your customers than manually entering a URL, and displaying a QR code is almost costless compared to other physical-to-digital links such as NFC badges.

QR codes are also chock full of helpful functionality that you might not even be aware of. Because of it's two-dimensional nature and thoughtful design, QR codes can be scanned from any orientation. They also have a built-in self-correction algorithm, meaning that even a code that has been damaged from inclement weather or wear-and-tear can be scanned. QR codes can also link to a wide range of data beyond URLs, including phone numbers, emails, SMS, apps and much more. 

## Why dynamic QR codes?

As fantastic as QR codes are, they can be made even more powerful when combined with a management platform to create what's known as a "dynamic" QR code.

When you create a traditional QR code, the data you want the code to link to is encoded directly into the code, meaning that there's no way to update where the code links to. For example, if you add a QR code to your business card as a way to make it easier for your clients to store your contact details, you have no way of updating those details if you change your phone number or email; you will have to create a new code, re-print your cards and make sure that your clients scan your new card to update the information.

A dynamic QR code doesn't link to your data directly, but instead links to our servers and then redirect the client to your stored data. This means that if you want to update any of your information, you can do so directly on our platform and your code remains the same. No need to print updated QR codes or marketing materials.

Since all scans of your QR codes now go through our servers, it also means that you can view analytics about how often your codes have been scanned. This data can serve as a crucial component in determining the effectiveness of your marketing campaigns. Dynamic codes also allow for dynamic interactions with your customers. Do you want to share a resource with a limited subset of your customers before the official launch? We allow you to password-protect your links, so that only your customers with the password can view it; when you're ready for launch, just remove the password from the code. Do you want to offer a special perk for the first 1,000 customers who scan your code? Create a conditional code[^1], redirecting the first 1,000 customers to a rewards page and the customers after that to another resource.

## Why RoQR?

### No arbitrary limits

One of our largest competitors only allows two QR codes and one user at the lowest pricing tier, and at their highest non-enterprise tier they have a restriction of max 5 users. Another allows for 3 codes at their intro tier and only allows for a single user until you upgrade to the "plus" tier which costs 20x as much as the starter tier.

At RoQR, we believe strongly that the best way to do pricing is to align our prices with our costs. The variable costs from our business is driven almost exclusively by the amount of scans on our platform, which is why that's the only vector we use to determine our pricing. A QR code platform that charges you based on users or number of codes is not doing that because it costs them significantly more to support those users or codes, but because they know they can then encourage some users to upgrade to more costly plans prematurely.

Use the workflow that works for you, invite any teammate you want, and experiment with many different types of codes - at RoQR we empower you to do it your way. And if you find that your QR codes are being scanned at a rate much higher than you originally anticipated[^2] we will help you find the plan with scan limits that best fits your need - with no other arbitrary limits, of course.

[See our pricing](https://roqr.app/marketing#Pricing)

### Privacy respecting

We believe that respecting ones customers' privacy is not just the right thing to do, it makes a lot of financial sense, too. Digital analytics tools are a necessary and crucial tool in the modern company's toolbox, but too many of these tools have strayed from their mandate of providing insights into becoming pseudo-spyware. Tracking pixels follow our movements across vast swathes of the web, and long-lasting cookies allow for tracking of individual web users far more closely than most consumers realize. 

But change is happening all around us. Privacy-respecting analytics tools are getting more popular by the day, and trailblazers such as [Plausible Analytics](https://plausible.io/) are drawing a line in the sand while showing that it's possible to build profitable, privacy-respecting and delightful tools. With many of the privacy-impinging old-guard finding their [business-practices scrutinized more closely](https://techcrunch.com/2022/06/23/google-analytics-italy-eu-data-transfers/) by regulators and empowered consumers, we know exactly which side of that line we want to be on.

Unlike some of our competitors, RoQR uses no tracking pixels, doesn't place any cookies on the devices of your customers, and stores no personally identifiable information (such as IP addresses) about them in our databases. We also respect the wishes of customers who directly indicate to us that they [do not want to be tracked at all](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/DNT). This means more peace of mind for your customers, easier data-compliance for you, and a nicer web for all of us.

### Open code, open data

RoQR is built on the shoulders of contemporary giants, those of open-source developers. We benefit immensely from the often-thankless work that other developers have put in to their projects, and for that we are ever grateful. As a way of paying this debt forward, we decided to also make RoQR into an open-source project: all of [the code](https://github.com/RoQR/RoQR) behind our platform is freely available for anyone to look at, contribute to and use. You can even self-host RoQR if you so choose.

The data that you gather through our platform is also freely yours to use. You can always export your data and use it as you see fit, and we will soon launch webhook access so you can react to events on the platform in real-time. If at any point you want to cancel your account and delete your data, we give you an option to do so with no question asked on the settings page.

## Ready to rock?

[Sign up now](https://roqr.app/users/sign_up) for a risk-free 30 day trial - no credit card needed.

---
[^1]: Conditional QR codes are not available yet, but are on our short-term roadmap. [See the current roadmap](../../docs/roadmap.md).

[^2]: That, my friend, is what we like to call a champagne problem
