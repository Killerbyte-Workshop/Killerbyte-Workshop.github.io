---
layout: post
title: Home Assistant Part 2 - Smart Plugs
date: 2024-05-07 19:00:00 +1000
author: Killerbyte
---

Now that Home Assistant is setup and the cameras are installed, the smart plugs are next. The Temperature/Humidity sensor needs it's own post for how strange it was to setup.

Now, the Smart Plugs are actually easy. The Smart Plugs I have are the TP-Link Tapo P110 with WiFi and Energy Monitoring which are the main reasons I have these plugs. I don't want to turn stuff on and off, I want to measure the energy consumption of my various appliances...in this case, the two Raspberry Pis that are running as servers. I have another two that I'm still deciding where to put them. 

Back to installing the smart plugs, all I needed was the Tapo app and the app ran through installing them and connecting them to my WiFi. Now, this time around for connecting to Home Assistant, you need the TP-Link Smart Home integration which is already installed on Home Assistant. Once you get the IP addresses from the Tapo app, Home Assistant does the rest and viola, your smart plugs are now on Home Assistant.

Next will be the MQTT broker and the Temperature/Humidity Sensor.

Until next time,
Killerbyte