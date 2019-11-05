---
title: Bandwidth Is Not Speed
author: admin
type: post
date: 2014-02-18T17:41:04+00:00
url: /bandwidth-is-not-speed/
categories:
  - Blog
tags:
  - Technical

---
We try to be as consistent and accurate as we can at Evolving Networks.  We don’t want to be misleading, and we don’t want to be too pedantic either.  But here is where it can get tricky.

Industry-wide there are problems with terminology.  Speed, bandwidth, latency, Superfast, Next Generation, “up to”; the list goes on.

The trouble is that a lot of these terms and their supposed meanings have become ingrained, and it’s then difficult for a provider such as us to actually tackle the inaccuracies or bad feeling that some of the terms have generated over time.

Speed, and the testing of an internet connection in general, is one of those areas fraught with historical problems, and modern day issues.

Speed is not the same as bandwidth.  We provide internet connections with an amount of bandwidth available.  Think of this as the capacity of the connection.  To go back to a popular analogy, imagine a pipe carrying water.  The higher the bandwidth, the bigger the pipe.  More water can get through it than a smaller pipe.

That’s about where that analogy ends though!  When we deliver an internet connection, we are giving a customer a “pipe” to the edge of our network – to the internet.  The internet is merely a series of networks connected together &#8211; each advertising directions on how to get to it, passing that information on to the adjacent networks.

Internet transit and peering are the terms we use for connections at the edge of our network to the internet.  Without getting any more technical than that, this is actually where bandwidth is relatively cheap.  Or put it another way, the individual circuit and bandwidth charges from carriers such as BT are much more expensive than internet transit.  So the pipes to the internet are big – lots of bandwidth and resilience too.

So if you have more bandwidth, what does that really mean? Does it mean it’s faster?  Here is where it should be simple, but it isn’t.

Speed is measured by dividing distance by time.  Distance in network terms is actually latency – the time it takes for a packet to get to its destination (not to be mistaken for ping time which is the time it takes to get back as well or round trip time).

If someone wants to know how fast the connection is, I bet they don’t want to know the ping speeds to a particular server…

Well in many ways, they should want to know!  Latency is a key measure in how you can USE your bandwidth.

Here’s where it gets more technical – sorry.

When people talk about speed, they talk about flow rate – kilobits per second, megabits per second, megabytes per second, that kind of thing.

Confusingly most computer programs measure things in bytes and not bits.  Straight away this means figures can be out by a factor of 8.

I bet you are already bored by this blog post because it’s all so dull and dry.  Well unfortunately it is.

If it was me, we would measure things in one way, but it’s not up to me, so on we go…

People are concerned (rightly) with how much data they can shift in a short space of time.  Because it’s the amount of data divided by time, you can see why people call it speed.

Back to the way we deliver an internet connection – we go to the edge of our network, where we have plenty of bandwidth for everyone.  From this point on, we cannot offer any level of service or guarantee with how quickly a download or upload will complete, or how fast a web page will load.

If your connection is 10mbps (megabits per second), and somewhere between the edge of our network and the webserver it’s less than 10mbps, then straight away you can’t use all your bandwidth.

Even if it does have 10mbps all the way there, what about the other 9 people wanting to get to that webserver? That would mean you all get 1mbps each…

What if the webserver isn’t very powerful – It’s not just bandwidth that controls how quickly a web page loads.  If loads of people are using a web site then it needs enough processing power to handle it.

How about other people using your connection? If you have 10mbps, and 9 other users want to use the connection to other web servers, then again you will share the bandwidth and all get 1mbps each.  (It is a bit more complicated than that, but not much).

Finally, it comes back to latency – the time it takes for packets to travel between your computer and the webserver.

The higher the latency, the smaller the amount of bandwidth you can use in a single stream of data.  There are some simple maths equations involved, but the way TCP works with things called its Window Size, as well as the actual TCP packets themselves (think of TCP as the traffic cops making sure your data gets to where it needs to go) means that you can’t just expect to get the full bandwidth by just clicking download on a file.

Is this bad news?  Well, not really.  For starters, the internet has worked like this for a long time, so it’s nothing new.  Also, most internet connections in businesses are inherently used by more than one person, so there are always multiple streams of data passing over the connection.

Websites themselves aren’t loaded in a single stream of data.  Each element of the page (image, text, etc.) is loaded simultaneously (ish) in multiple streams.

Can we get around it?  We can if we need to.

First of all, there are programs called download managers designed to utilise the full amount of bandwidth you have (to the detriment of others on your internet connection!) by connecting to servers multiple times using multiple streams.

What we also have is a technology that we can turn on which mimics this behaviour for standard web downloads and uploads.  By taking your single stream of data and turning it into multiple streams of data (even though its already bonded), we can maximise the throughput and use as much bandwidth as we can, reducing the time it takes, and making it feel “faster”.

Do we have a problem with terminology? I think we do, and I think it’s industry-wide.

I also think we have a problem with so called speed test websites claiming to be able to accurately measure the bandwidth of a connection while solely relying on advertising revenue and fostering a “mine’s bigger than yours” culture.

Throughput is important, but it’s not the be all and end all.  If you want to use VoIP, bandwidth isn’t very important. Likewise with Terminal Services and Remote Desktop traffic.  A high quality internet connection is measured in a number of different ways, but first and foremost it should do what your business needs it to do.

With a full suite of technologies available to us, including Bonding, <a href="/so-what-do-we-mean-by-qos" target="_blank">Quality of Service</a>, <a href="/introducing-bandwidth-amplification" target="_blank">Bandwidth Amplification</a>, TCP Optimisation, Transparent Multi-Streaming and more, we are well placed to be able to deliver internet connections that really take that next evolutionary leap.

**Nic Elliott &#8211; Technical Director**