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


## Saving money with the Raspberry Pi
For my home network, I was upgrading my router, switch and access points to those from the [Ubiquiti Unif](https://unifi-network.ui.com) line. These devices require a "Cloud Key" for the devices to work togethor. Did I buy this Cloud Key?

<img class="ui image" src="{{ site.baseurl }}/images/cloudKey.png">

For $96, I decided to find a more economical solution. By implementing the Raspberry Pi alternative, I avoided having to pay $90+ on a device that performs the same functions that my raspberry Pi now does.

Through this experience, I've learned how to be more effective with the limited resources that I have. I now understand that cheaper alternatives can be implemented if one has the right technical background.

## What did I do with the money I saved?
With the money I saved, I did what any smart home-lab-doer would do... buy another Raspberry Pi.
For the future, I plan to dabble in distributed computing by using an array of Raspberry Pi's as nodes in a cluster.

