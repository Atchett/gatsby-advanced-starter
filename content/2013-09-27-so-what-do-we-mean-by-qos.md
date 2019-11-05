---
title: So what do we mean by QoS?
author: Evolving Networks
type: post
date: 2013-09-27T14:05:55+00:00
url: /so-what-do-we-mean-by-qos/
categories:
  - Blog
tags:
  - QoS

---
You just have to put QoS into your favourite search engine and read some long and boring articles to know that:

  1. It’s complicated
  2. It means so many different things

Something we have never really shouted about is our ability to prioritise traffic over the upload or download element of a circuit as part of a <a href="/bonded-internet" target="_blank">bonded connection</a>.  So if someone is using VoIP they can dedicate the upload, download or both portions of a line or lines to just their VoIP calls.

This is great as it means no other traffic can touch your voice calls and degrade them.  It also means no changes at all to customer’s equipment or settings.  Now that I write it down like that, that’s pretty great so maybe we should have been shouting about it more!

But what it does lack is a great deal of flexibility in what you can prioritise, and basically wastes a lot of bandwidth in the process.

VoIP calls are tiny in bandwidth terms so you might be wasting 80% or more of an individual circuit when using that method of QoS.  And here’s the important thing, that was still QoS, but as you will find if you research it, QoS means a lot of things.

So what can we offer now?  Well it’s difficult to maybe give it an absolute name other than maybe calling it true QoS.  It’s more advanced than just reserving a single line for VoIP.  Much more.

**No more wasting bandwidth**

What we can now do on any of our internet connections with our hardware on the end is prioritise individual packets of data and make sure they follow the rules we’ve set them.

Time sensitive packets like those used for VoIP calls and Terminal Services (RDP and Citrix) are given a higher priority than normal web browsing traffic, file downloads, FTP uploads and email.

When a phone call or RDP session isn’t in use, those other types of traffic (all others in fact) get free reign over the whole connection, but when you pick up the phone to use VoIP or start using a Citrix session, those new packets push the others out the way just enough for them to work.

It works really, really well and solves so many IT Manager headaches.  No changes are needed by customers other than maybe to remove some rudimentary throttling they may have attempted to use on their own firewall.  <a title="Say hello to our brand new kit!" href="/say-hello-to-our-brand-new-kit" target="_blank">Our kit</a> does all the hard work.

So what kind of QoS is it? Well without going into the detail of what queuing mechanisms are in place and a list of traffic classes, the answer is: the best kind.  No wasted bandwidth, no effort from the customer – it just works.

We’re really excited by this development and if you’re an existing customer you’ll be hearing from us soon about how you could upgrade your internet connection to take full advantage of it.  If you think you need something like this on your own internet connection, then do call us up on 0330 55 55 333 or email us and we’ll gladly talk you through how easy it could be for your business as well.

**Nic Elliott – Technical Director**