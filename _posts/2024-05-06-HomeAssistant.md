---
layout: post
title: Home Assistant
date: 2024-05-06 19:45:00 +1000
author: Killerbyte
---

I recently installed Home Assistant on my homelab using use with a few security cameras but I've also expanded it with some smart plugs and I'm looking into more stuff. 

The weird thing with the security cameras though is they are TP-Link Tapo C110s and getting them to work with Home Assistant is really tricky to pull off.

To do this, you need [HACS](https://hacs.xyz/docs/setup/download/), thankfully there are instructions for installing on a container. Then, you can install [Tapo Camera Control](https://github.com/JurajNyiri/HomeAssistant-Tapo-Control) from the HACS store. 

Next is to do the initial setup for the cameras. You will need the Tapo App ( [Android](https://play.google.com/store/apps/details?id=com.tplink.iot) [iOS](https://apps.apple.com/au/app/tp-link-tapo/id1472718009) ) and then select C110 for the camera type. After the initial setup is done, you will need to create the cloud account that way we can pull everything from TP-Link. You will also want to pull the IP address from the Tapo app as Home Assistant will need it for connection.

That should do it for installing the cameras. Next will be the smart plugs and then the MQTT broker for use with a Raspberry Pi Pico for a temperature/humdity sensor combo.

Until next time

Killerbyte