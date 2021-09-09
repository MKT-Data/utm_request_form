# UTM Builder Library  <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->
- [Medium Definition & Usage Scenario](#medium-definition--usage-scenario)
  - [Paid Search](#paid-search)
  - [Paid Social](#paid-social)
  - [Social](#social)
  - [Display](#display)
  - [Text](#text)
  - [Email](#email)
  - [Video](#video)
  - [QRCode](#qrcode)
- [FAQ](#faq)
  - [I got two links that have same medium and same source. How to divide the traffic in this case?](#i-got-two-links-that-have-same-medium-and-same-source-how-to-divide-the-traffic-in-this-case)
  - [I use hyperlink on banner and text in the email. What kind of utm_medium should I choose?](#i-use-hyperlink-on-banner-and-text-in-the-email-what-kind-of-utm_medium-should-i-choose)

## Medium Definition & Usage Scenario

### Paid Search
- The link is paid to display as search result in a search engine.

### Paid Social
- The link is displayed as any type of AD in social media platforms.

### Social
- The link is posted in the organic social post.
- The link is posted by channel partner in their social media. 

### Display
- The link is displayed as banner or image format.

### Text
- The link is displayed as text format.

### Email
- The link is displayed as any type of content format (ex: text, image...) in an email.

### Video
- The link is posted in description of video platforms.

### QRCode
- The link is displayed as QR Code in physical material.

## FAQ

### I got two links that have same medium and same source. How to divide the traffic in this case?

Please use "utm_content" to add additional information to divide the traffic.

Ex: Multiple AD type in the LinkedIn's paid social.

| utm_medium  | utm_source | utm_content |
| ----------- | ---------- | ----------- |
| paid-social | LinkedIn   | ad-im       |
| paid-social | LinkedIn   | ad-image    |

Multiple email material from the same channel partner.

| utm_medium | utm_source     | utm_content  |
| ---------- | -------------- | ------------ |
| email      | ChannelPartner | newsletter_1 |
| email      | ChannelPartner | newsletter_2 |

### I use hyperlink on banner and text in the email. What kind of utm_medium should I choose?

If the user will see the link in an email.
- Choose "Email" as utm_medium no matter what kind of content format with a hyperlink in an email.

If the user will see the link in a common website.
- The link is displayed as banner/image, then choose "Display" as utm_medium.
- The link is displayed as text, then choose "Text" as utm_medium.
