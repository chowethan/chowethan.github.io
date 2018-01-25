---
layout: project
type: project
image: images/winston-square.png
title: Winston
permalink: projects/winston
# All dates must be YYYY-MM-DD format!
date: 2017-10-15
labels:
  - js
  - Node.js
  - discord.js
  - Discord
summary: An all-purpose Discord bot in-development for eventual public use in any Discord server.
---

<div class="ui medium rounded images">
  <img class="ui image" src="../images/winston-sample-1.png">
  <img class="ui image" src="../images/winston-sample-2.png">
</div>

Winston is a Discord bot written in JavaScript that utilizes the [discord.js](https://discord.js.org/) library. I started developing this bot as a replacement for [Cassandra](https://chowethan.github.io/projects/cassandra), which, for a while, I have wanted to re-write. Just recently, discord.io stopped working because it used an old Discord gateway protocol, which has been deprecated. For now, the discord.io library is not supported, as they update it to support the newest Discord gateway version, v6. As such, Cassandra does not function correctly. This change has forced me to start writing this new bot.

This bot is being written in modern JavaScript, making full use of ECMAScript 6 class constructs, Promises, and the let and const keywords. Modularity was the key concept in this bot, so commands have been separated in to separate command "modules" that can be enabled/disabled on a per-server basis.
