---
title: Fasthosts and the Importance of Testing Redundancy
author: admin
type: post
date: 2014-01-08T16:27:02+00:00
url: /fasthosts-and-the-importance-of-testing-redundancy/
categories:
  - Blog
tags:
  - Failover

---
This weekend saw probably the most serious outage Fasthosts have experienced, certainly in the 10 years I have worked with them.

Serious in that it was widespread, covering email of all types, shared hosting, dedicated and virtual servers all at the same time.

Serious also, because they have prided themselves on the robustness of their datacentre.  Their website boasts all the things you would expect, including flood defences, backup generators, high security etc.

The bad weather was clearly the trigger of this problem, but what failed to work was the failover itself.  It’s no good having redundant anything without testing it – the whole point of redundancy is for the times when you need it most, so don’t wait until the worst happens to find out if it works!

We love failover and resilience here at Evolving Networks.  Nobody is perfect, and we continue to invest in systems and processes to avoid problems and provide as seamless a failover as possible.

Bonding multiple internet connections together is inherently resilient, and bonding them through a virtual cluster of servers with High Availability VMware helps that much more.  Add complete datacentre redundancy (something Fasthosts don’t seem to have) and multiple connections to each carrier, and there isn’t much left for us to add to our network in terms of making it more reliable.

Most problems we see customers face are local issues – lines going down in a large local area.  Generally speaking this is where having a line included in the bonded connection that is of a different carrier can be helpful.  It’s not fool proof though.  Cross carrier resilience is always something we recommend, but in the case of an exchange fire or something like that, sometimes all carriers suffer problems, and even mobile telecoms can fail as well, leaving you without many options.

We encourage new customers to test the failover inherent to their bonded connections.  Our latest generation of hardware detects line changes in less than half a second.  This means if you were to pull a cable out of a modem, the bonder would react quicker than your IT systems and users would detect.

**Nic Elliott &#8211; Technical Director **