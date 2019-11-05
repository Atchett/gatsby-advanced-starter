---
title: We’ve Made Broadband More Reliable Than A Leased Line
author: admin
type: post
date: 2016-07-29T09:46:26+00:00
url: /broadband-more-reliable-than-leased-line/
categories:
  - Blog

---
<a href="https://evolving.net.uk/wp-content/uploads/2016/07/pexels-photo-large.jpg" rel="attachment wp-att-3739"><img class="alignnone size-full wp-image-3739" src="https://evolving.net.uk/wp-content/uploads/2016/07/pexels-photo-large.jpg" alt="pexels-photo-large" width="890" height="593" srcset="http://evolving-networks.local/wp-content/uploads/2016/07/pexels-photo-large.jpg 890w, http://evolving-networks.local/wp-content/uploads/2016/07/pexels-photo-large-300x200.jpg 300w, http://evolving-networks.local/wp-content/uploads/2016/07/pexels-photo-large-768x512.jpg 768w" sizes="(max-width: 709px) 85vw, (max-width: 909px) 67vw, (max-width: 1362px) 62vw, 840px" /></a>

###  {.green}

### A low for the UK communications industry {.green}

<p class="biggerp">
  Last week was a low point for the communications industry in the UK, specifically for providers hosting routers and servers in two of the biggest datacentres in London.
</p>

<p class="biggerp">
  On Wednesday there was an issue at Telecity’s Harbour Exchange (HEX), and on Thursday a problem at Telehouse North (THN). Both of these made the national news and were picked up by <a href="http://www.bbc.co.uk/news/technology-36844712" target="_blank">the BBC</a> and other outlets as well as national newspapers, although their focus was almost entirely on the impact they had on broadband.
</p>

<p class="biggerp">
  Their spin was even more directly targeted at BT broadband, either because as the largest residential ISP, they were affected the most, or because they think that all internet connectivity in the UK is from BT. That second point is a more complicated issue, which I’ll come back to soon, because it comes at the heart of what Evolving Networks does to protect against these issues, but it should also be noted that there was what was arguably a more pressing issue on those two days last week – leased lines went down.
</p>

### Leased lines down {.green}

<p class="biggerp">
  Ethernet circuits terminating through Harbour Exchange went down when it did (a power failure that could have been mitigated), and likewise on Thursday, those leased lines which ran from customer sites to Telehouse North were down for 5 and a half hours.
</p>

<p class="biggerp">
  The problem at THN was also power related, and also should have been mitigated by battery backups and generators that are tested regularly. It wasn’t that many months ago that Sovereign House, another big datacentre in London had a power issue and didn’t just keep on functioning.
</p>

<p class="biggerp">
  It is possible to keep servers and routers running and have power systems fail over, but in these instances, they did not, and clearly had problems getting the power working again even though each of those datacentres is billed as having redundant power systems.
</p>

<p class="biggerp">
  But this is the point. Leased lines can go down. Leased lines do go down. And where is your 4 hour SLA when you are in hour 6 of not being able to run your business? We hear it all the time.
</p>

<p class="biggerp">
  “A leased line is better isn’t it?”<br /> “It’s more reliable – fact.”<br /> “But I get a 4 hour SLA.”
</p>

<p class="biggerp">
  Our answer to all of these things is to say that all circuits can go down, and for a variety of reasons. That we have seen many unreliable leased lines based on fibre ethernet right up to the server room of a customer. Not a copper pair in sight.
</p>

<p class="biggerp">
  Our entire philosophy is different. We are unlike any other ISP in the industry. We assume every circuit is going to go down at some point, and work tirelessly to make sure each and every time they do, they only impact a customer minimally.
</p>

### So how did broadband fare? {.green}

<p class="biggerp">
  So let’s talk about how broadband connections fared last week. During those major datacentre power outages last week, there were many thousands of broadband lines that went down. Some came back within an hour because they ran through well run platforms, and some didn’t and waited until the power issues were fixed before they resumed.
</p>

<p class="biggerp">
  I’ll let you into a secret. I love watching big network events now, because I get to see how the network we’ve built responds to them, and how it protects customer’s connectivity and in turn keeps their business running.
</p>

<p class="biggerp">
  Thursday was a particularly good example, as the overall power outage lasted around 5 and a half hours. Running from just before 8am to about half past 1 in the afternoon. That’s a full morning offline if you had a leased line terminating in Telehouse North, floor 3.
</p>

<p class="biggerp">
  We saw a number of lines drop at 7:53am, and then come back, but hardly any customers went offline, and those that did came back quickly. The vast majority of Evolving Networks customers didn’t notice when they came into work that morning, even though we still had hundreds of individual lines offline after 9am.
</p>

### How we ensure resiliency {.green}

<p class="biggerp">
  Now bonding the lines is obviously one of the first levels of resiliency. If you don’t have more than one circuit, then you can’t possibly hope to eliminate the downtime of these kinds of events.
</p>

<p class="biggerp">
  But here is where we go several steps further.
</p>

<p class="biggerp">
  We make sure that not all of the lines that run to a customer’s site go through the same broadband platform. Even the best designed and maintained LNS clusters can go offline, and even those which will allow reconnection of an ADSL or FTTC circuit through a different datacentre need time to allow that failover to take place, which takes several minutes (sometimes up to half an hour or more) to fully recover. Most don’t even do that, even though they may peer with BT in more than one place.
</p>

<p class="biggerp">
  So not only do our customers benefit from a distribution of risk by having multiple DSL platforms for each bonded internet connection, they also benefit from our proactive management of those platforms, and what lines run where.
</p>

<p class="biggerp">
  We go further than any other provider, by making sure that the different DSL platforms we use are also diverse where they host their routers. It’s no good having two different broadband LNS clusters, managed by different teams of engineers, only to find they are both on the third floor of Telehouse North…
</p>

<p class="biggerp">
  We make sure that as far as is possible, the underlying circuits in any bonded ADSL or bonded FTTC connection are routed diversely, by DSL platform and by datacentre. This keeps them online. And it kept them online on Wednesday and Thursday last week, when people with more expensive leased lines were offline.
</p>

### Is broadband more reliable than a leased line? {.green}

<p class="biggerp">
  We’ve spent the last 8 years developing the network architecture, the tools, and the mind set to deliver just that.
</p>

<p class="biggerp">
  Connectivity that is resilient, intelligent and agile.
</p>

<p class="biggerp">
  Based on broadband.
</p>