---
layout: post
title:  "Bouncer: First PCBs!"
category: bouncer
image: /assets/bouncer-board-v0-1.jpg
tags: [ESP8266, hc-sr04, iot, fritzing, pcb]
---

A few weeks back I got my first ever PCBs in the mail from [Aisler](https://aisler.net/). They look awesome!

![Bouncer Blank PCB]({{ "/assets/bouncer-board-v0-1.jpg" | absolute_url }})

I immediately soldered everything on and fired it up. I connected the serial console to the ESP8266 and alas, no dice. I've been poking and prodding but still can't figure out why it's not working. The ESP8266 isn't getting the echo response from the hc-sr04 for some reason. I haven't had much time over the holidays to be able to troubleshoot. Hopefully I'll be able to get back to it this week.

![Bouncer PCB with Components]({{ "/assets/bouncer-board-v0-2.jpg" | absolute_url }})

I do have some things I'd like to correct for v0.1 of the board. I need to leave a lot more space for the hc-sr04. My measurements were way off. Also my custom fritzing part for the huzzah ESP8266 needs to have bigger pin holes.
