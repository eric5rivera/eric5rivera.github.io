---
layout: project
type: project
image: images/uhmm-landing.png
title: Ku Ka'awale - Visualizing Campus Occupancy during COVID-19
permalink: projects/ku-kaawale
# All dates must be YYYY-MM-DD format!
date: 2020-12-10
labels:
  - Mobile Application
  - Software Development
  - React Native
summary: Bowfolios reimplimented as a cross-platform native mobile app.
---

# Ku Ka'awale - Visualizing Campus Occupancy during COVID-19

## What the hecc is the HACC?
#### Think hackathon, but longer
While most hackathons usually give participants just a day or just a weekend, the HACC provides participants several weeks to dream up a solution, come up with a plan, learn, and develop to bring their ideas to a proof of concept reality.
#### Built for and built by the Aloha State
Another facet of the the HACC that makes it unique amoungst other hackathons is its location and its intent. The HACC offers challenges that are reverse-pitched by various departments of the state, and also various institutions in the state of Hawaii.

This is my second time participating in the HACC.
## UH Manoa campus is in use, even during the pandemic
The data comes from the hundreds of wireless access points (AP) throughout the Manoa campus. We can assume that nearly every person on campus has a wireless device that is connected to the campus wifi. As the people roam about the campus, their wireless device will connect to the strongest broadcast (usually the closest access point). 

## Our Solution

## Expectation: Our game plan
To date, my favorite course I've taken in my college career was ICS 314 - Software Engineering I. In this course, I made it through an entire tech stack, learning many tools to help me during each stage of development. Many of my team mates have also already taken ICS314 and were thus already familiar with the tech stack, techniques, and processess taught in that course. 

The challenge specifications fit the description of a dashboard. Instead of trying to reinvent the wheel, our team decided on looking for a dashboard framework. As a longtime lurker of the r/homelab subreddit,, I often see other homelab enthusiests using Grafana to power their homelab analytics dashboard. I pitched this idea to my team as a potential framwork. Much of week one and two were spend learning about Grafana and determining if it had the right features and modules for our HACC challenge. While much of the analytics and interface were already squared away, we knew that we would still have to solve the big problem of generating a heat map over our geographic map.

I stood up an instance of Grafana using Amazon Web Services Light Sail. This part came easy because of my work experience in IT.


## Reality: What really happened
With only a week remaining, we decided to go back to basics - back to using the template we used in ICS314. It was familiar to each of us, and we already knew what it could do. It was just a matter of implementing what we had already worked out into that template.

#### We were missing a lot of information
While the data given to us only included only the name of the access point and its corresponding building, and the max and unique number of clients, we were still missing the actual geographic location of each access point. We were expecting to have the coordinates of each AP in the latitude and longitude format. Without this coordinate information, we were left guessing where each AP actually was. Some of the buildins are multi-story and very large in area - so deteriming where the AP actually was turned out to be an impossible task.
To work around this issue, we decided to work on a small subset of the data that we were given. Not only did this solve our lack of given information, but it also helped us with our lack of remaining time.


## The dust has settled... Now what?
While initially it felt like we had failed, I realized that I had to learn a lot throughout those three weeks. 

HACC 2020 has been my second hackathon I've ever participated in. I'm discouraged to take on my third hackathon. Considering that we are all living during the pandemic, I'm more open to trying national hackathons that are not local to the state of Hawaii. 
