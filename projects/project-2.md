---
layout: project
type: project
image: images/winston-square.png
title: Discord Bot (Winston)
permalink: projects/winston
# All dates must be YYYY-MM-DD format!
date: 2017-10-15
labels:
  - Javascript
  - Node.js
  - discord.js
  - Discord
summary: An all-purpose Discord bot in-development for eventual public use in any Discord server.
---

<div class="ui medium rounded images">
  <img class="ui image" src="../images/winston-sample-1.png">
  <img class="ui image" src="../images/winston-sample-2.png">
</div>

Winston is a Discord bot written in JavaScript and utilizing the discord.js library. I started developing this bot as a replacement for another Discord bot that I wrote that utilized the discord.io library. However, I had been wanted to re-write the bot for a while now, and just recently, discord.io has been deprecated until it supports the newest Discord gateway version, v6. As such, the old Discord bot does not function correctly. This change has forced me to start writing this new bot.

This bot is being written in modern JavaScript, making full use of ECMAScript 6 class constructs, Promises, and the let and const keywords. Modularity was the key concept in this bot, so commands have been separated in to separate command "modules" that can be enabled/disabled on a per-server basis.
