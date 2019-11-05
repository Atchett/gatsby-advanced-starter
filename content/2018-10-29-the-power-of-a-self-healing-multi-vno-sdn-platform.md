---
title: The Power of a self-healing, multi-VNO SDN Platform
author: admin
type: post
date: 2018-10-29T14:51:14+00:00
url: /the-power-of-a-self-healing-multi-vno-sdn-platform/
featured_image: /wp-content/uploads/2018/10/blog-image-890-410.jpg
categories:
  - Blog

---
Today we had an issue with one of our carrier partners. Nothing too major, just a period of about an hour when all their tails (ADSL 2+, FTTC and leased lines) experienced increased latency of about 100ms.

Certainly they didn’t consider it to be a very big deal, they diagnosed the issue (a problem with a peering partner) and fixed after about an hour, and anyway, no one actually went offline.

Which is all well and good, but if you are a business customer and you are reliant on that ISP for your WAN (as many hundreds of businesses are) you experienced an hour of pretty much useless connectivity – very slow web browsing, VoIP calls not working, cloud apps unworkable. So there is little comfort in “at least you weren’t offline”. When user experience is so severely impacted, you may as well be.

It’s during events such as these that our multi-VNO SDN platform really comes into its own. No customers of ours have connectivity delivered via just one platform. So, whilst some of our customers did have component links within their multipath ethernet solutions routed via the affected network, we had the Get Out of Jail card ready to play.

Our monitoring alerted us to the issue within 30 seconds of it happening, our AI suite had crunched the numbers and come up with a network wide re-routing policy within a further 30 seconds, and suggested a fix. A quick thumbs up from our Head of Infrastructure and network traffic was routed away from the affected carriers’ links, on the fly, with customers experiencing no downtime.

We had one incoming support call from a customer, who happened to be on a VoIP call when the initial latency issue hit, but their user experience returned to normal as soon as the network traffic was rerouted. No other customers noticed the issue and got in touch. We have since rebalanced the network, again without impacting customers at all.

It was hard work setting up the multi-VNO network, and the investment of time and resources in the monitoring was very considerable. However, the network has proved its worth time and time again, this morning being just the latest example.