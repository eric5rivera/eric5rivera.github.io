---
layout: project
type: project
image: images/raspberries.jpeg
title: Raspberry Pi
permalink: projects/raspberryPi
# All dates must be YYYY-MM-DD format!
date: 2019-06-11
labels:
  - Raspberry Pi
  - Networking
  - Home Lab
summary: Using the Raspberry Pi, I set up DNS add blocking and a controller for networking devices.
---
My introduction to the Raspberry Pi platform was in a college physics class where we had a mini hackathon using the device. Detailed below, are my experiences with the device at home in my home-lab. This affordable device has been the starting ground for my learning of basic networking concepts.

<img class="ui image" src="{{ site.baseurl }}/images/piHole.png">

The first thing I set up on the Pi was [Pi-hole](https://pi-hole.net). I learned about how the DNS works in a networking environment As a result of this endeavor, I no longer get annoying ads when scrolling through blogs, news sites and even while shopping. I’ve learned how to set up a device completely over SSH.

## How does it work?
When a user goes to a website, the address is sent first to the Raspberry Pi for DNS lookup. Pi-hole then returns the domains that serve the web content, but intentionally leaves out any content that comes from a domain that serves ads.

<hr>
<img class="ui image" src="{{ site.baseurl }}/images/cloudKey.png">

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

