---
title: 'Smartthings and Shinobi'
subtitle: 'Making dumb cameras smarter'
summary: Using IFTTT with Webhooks, Shinobi, and Smartthings
authors:
- bfrost
tags:
- Smartthings
- Shinobi
- Groovy
- Webhooks
- IFTT
categories:
- HomeAutomation
date: "2020-09-11T00:00:00Z"
lastmod: "2020-09-11T00:00:00Z"
featured: true
draft: true

image:
  placement: 2
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

---
**It took me two hours to do this but I bet you can get it done in 15 minutes.**


{{< figure src="https://briandfrost.com/assets/images/askaninja.jpg" title="Classic Ask-a-Ninja Ninja" >}}

**Key Technologies and Products**
- [Shinobi](https://shinobi.io)
- [Smartthings IDE](https://graph-na02-useast1.api.smartthings.com/)
- [IFTTT](https://ifttt.com/)
- [Groovy](https://groovy-lang.org/)
- [ActionTiles](https://www.actiontiles.com/)
- [Webhooks](https://en.wikipedia.org/wiki/Webhook)

There are quite a few cameras available but most of them require roll to the cloud prior to displaying locally and that doesn't really provide what I want for home security. I want to process it as quickly as possible to determine if motion has been detected.

I have a set of Arlo cameras (which are really cool) but the batteries are a real issue for me. They drain quickly and their recharable replacements drain even quicker.

There is a common issue noted on the web that some camera
