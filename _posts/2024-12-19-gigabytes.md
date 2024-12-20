---
layout: post
title: Gigabytes
---

Today, we tackled an invisible but critical challenge: how to handle the sheer weight of Pyria's digital assets. When you're dealing with 20+ gigabytes of content—everything from textures to models to sound effects—even simple tasks like sharing files between developers can become  a bottleneck.

We’re GitHub based, so while Git LFS is a natural choice it costs $5/50GB/mo for both storage and transfer. Multiple downloads of a 20 GB repo would eat that up in a day. We need something faster, more resilient, and built for the way modern game development actually works—iterating on lots of big files.

Enter our custom solution: instead of pulling massive files from a remote server every time, we can now directly sync our Git LFS object directory between development machines. When there's a copy on the local network, a new environment downloads in minutes and doesn't cost us any bandwidth from GitHub.

It's not just about speed—though cutting setup time by 95% is nothing to sneeze at. It's about removing friction. Every minute saved in setup and synchronization is a minute we can spend actually building Pyria. Today's proof? We set up a completely new development PC from scratch this afternoon, just in time to shoot our daily TikTok update.

These are the kinds of solutions that make an ambitious 90-day development cycle possible. Every optimization matters. Every minute counts.

85 days to March 14th
