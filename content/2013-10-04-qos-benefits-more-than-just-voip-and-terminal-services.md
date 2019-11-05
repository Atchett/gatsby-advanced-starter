---
title: QoS benefits more than just VoIP and Terminal Services
author: Evolving Networks
type: post
date: 2013-10-04T14:37:43+00:00
url: /qos-benefits-more-than-just-voip-and-terminal-services/
categories:
  - Blog
tags:
  - QoS

---
We have already talked about how great QoS (Quality of Service) is for time sensitive applications like VoIP and RDP. Ensuring that packets that need to get there first do, overriding less important traffic (like an email attachment or a big upload) that will still get there, but nobody is going to notice if it takes a few more seconds.

Here is where we have gone further.

What if there were ways of making the internet connection _feel_ faster, just by being clever about how the packets are delivered?

Could we actually make web browsing faster?

Could we make downloads more efficient and therefore take less time?

Well we’ve developed our Quality of Service option to do exactly that.  By prioritising packets you may never even have heard of, we are making everything feel slicker.

## DNS Requests

We prioritise DNS lookups, which are only tiny amounts of data, but may happen several times during the loading of a web page on your screen.  By pushing these to the front of the queue, we make sure that web pages load as quickly as they can.

## TCP Acknowledgements

By prioritising the little messages that get sent between computers and servers managing the flow of any given stream of data, we can make sure that none get lost and that they always get there first, ahead of the actual traffic itself.

What this means is that it’s much rarer to have to resend data during a transfer, meaning it all happens right first time and finishes quicker.

In other words, you click on a download, and it goes as fast as it can, using every scrap of bandwidth it can, not missing a beat.

## Everything feels generally better

So even if you don’t have VoIP yet, or don’t have anything specific that is time sensitive that would suffer when your connection is saturated, QoS can really make an improvement to your everyday experience.

Web browsing will feel faster, because in the background we’re being clever with your packets.

We’ve done our homework and a lot of testing and tweaking to come up with something that will even improve normal every day usage of the internet without any effort from you.  Surely this is how all internet connections should be?