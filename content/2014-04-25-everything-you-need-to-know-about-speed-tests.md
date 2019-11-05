---
title: Everything You Need to Know About Speed Tests
author: admin
type: post
date: 2014-04-25T11:00:02+00:00
url: /everything-you-need-to-know-about-speed-tests/
categories:
  - Blog
tags:
  - Speed Tests

---
Here are some phrases we hear most days from customers, regarding online speed test websites:

“It’s a guide innit?”

“They a good indication”

“I know you don’t like speed tests, but….”

As most readers of this blog will know, the last statement is certainly right, in that we don’t like speed tests.  What I’m hoping to do is explain some of the many reasons why.

Sometimes, some of them apply, in various combinations, but there is essentially no time we can accept a speed test result as evidence of anything, because of these reasons, and because better diagnostic tools exist.

Let’s go back to the beginning though – why do customers feel the need to run them in the first place?  We care greatly about the customer experience, and we pride ourselves on delivering high quality connections with whatever bandwidth is available at a customer’s location.

What good is a customer that isn’t happy?

## History

I think there is a lot of history we have to contend with here.  ISPs seem to have been placed into that group of untrustworthy companies, like big oil and energy, and insurance.

“They must be out to get me.”

The trouble is, there is a lot of justification for that view.  BT are the biggest culprit, and because to a large extent all ISPs have to use BT for some of their service, they are affected by the decisions BT take.

But it’s the lack of management of circuits (historically from BT, and then now from other providers), that has caused this problem.

If you install a line, then let it fail, and wait for the customer to moan, then that’s just, well, rubbish isn’t it?

What it bred was a desire for some sort of comfort blanket, and people’s desire to check what they had bought, in case it wasn’t quite what they thought it was.

The speed test was born.

Its motives were pure.  Its methods quickly became suspect.

So here we go – all the reasons why speed tests are bad.

## Other traffic on the connection

This is such a common one, and always exacerbated by business users, because the internet connection could be used by hundreds.

The speed test doesn’t pause everyone else’s traffic so you can run your test, it just fights with everything else, so it will never be accurate while the connection is in use.

We provide eView Live for exactly this reason – see what you are already doing.  The chances are you are already showing how much bandwidth you can use in a nice live graph (or look an hour ago and see what you were doing then, and how much you were uploading and downloading).

## It’s not like other internet traffic

If you are making an internet phone call (VoIP), then why run a test of bandwidth?  VoIP calls take only a few kbps, so available bandwidth is unlikely to be the problem.

How about testing the kind of traffic that you actually use, and in the combination that you actually use it?

## I want to get from A to C, not A to B

If you test something from A to B (B being the speed test server), then expect to get the same results from C, the actual server you want to talk to, then don’t be surprised if the results are different.

How do you know how good the speed test server is, or where it is?

How do you know how many other people are saturating the speed test server’s connection?

Bear in mind that you might get a blisteringly good result from the speed test server, and still suffer problems getting to the actual server you want to use.

This is because you will be taking a different route across the internet to that server (it may even be in a different country), and it may also be jammed with people, or just not beefy enough.

## London or Edinburgh?

It’s like saying it takes 1 hour to drive to London, but London isn’t the only place you want to visit.  If Edinburgh is where you need to go, then driving to London won’t help you, and if Edinburgh doesn’t have as many roads going into it then it can’t accept as many cars as London.

Your internet connection is subject to the rest of the traffic on the internet and in particular the traffic trying to get to the same places as you.

It also depends on how much bandwidth, and how fast the servers are at your destination.

## Ad-sponsored

Speed test sites are there to make money.  Most are sponsored by advertising that pervades the site, that is designed to look like it’s authoritative, and part of the speed test itself.

It’s not, it’s there to get you to click on it, and to make money.  Why are you trusting something that behaves like that?

## Carriers don’t accept them

We can’t go to BT Wholesale or TalkTalk Business, or Virgin Media Business and say “we’ve just run a speed test”.  They would laugh us out of the room.

Go and find a speed test on the Virgin Media Business website for fibre Ethernet circuits – if they are so good, why haven’t they built one?

Hang on, I hear you say, BT Wholesale have a speed test!  Yes they do, and here is where most of our customer’s get it wrong unfortunately.

The trend recently has been for people to run the BTW speed test over their BONDED connection, and then send the results to us triumphantly with an “A-ha! I told you so!”.

Well that test is for individual circuits, designed to isolate circuits, and report on what they should perform.  It’s the BT Wholesale speed test – it’s for BT Wholesale lines!  If you run the test over multiple lines (some of them not BT Wholesale), then out of our internet transit, back into BT, you will get inaccurate results.

This test is for circuits, and it’s designed to bypass the ISP network, and compare against a SINGLE line.  In reality it’s even more complicated than that, but the only time to do a BTW speedtest is on a single line, and if other tests show there might be a line fault – note a line fault, not a bonded connection fault.

## Science and Accuracy

Even in benign and ideal conditions (no one else using the connection, no LAN or firewall issues, no line faults), you can still get dodgy results from speed tests.

People seem to explain away the dodgy results by saying:

“You need to run quite a few tests and take an average” – What? How is that scientific?

“Make sure you run tests to different speed test servers” – Why? Because they aren’t all good?

They are there under the guise of some kind of public service, but they aren’t regulated in any way, and they aren’t transparent, not showing you server specification, server load, network congestion or anything useful that might help you understand the result.

The assumption is that it must be your end that is at fault – you’d better go and call your ISP and have a moan!

No matter how many times we’ve tried to make speed tests scientific, we just can’t.  It’s not like we haven’t spent days and weeks trying.

It would be easier if they did work, as we would be able to use them to diagnose faults, but we can’t, because they are inaccurate.

And here’s the biggest issue of all – they CAN be accurate.  But because they are often not, how would you know?

We come across scenarios on a regular basis, where someone’s speed test result shows, for argument’s sake 5mbps, and we can see them using 10mbps and not just in some random spike.

The key thing is, though, that once it’s been inaccurate, you can’t trust it.  It might be right, but it might be wrong.  That doesn’t mean “it’s a guide”, it means it’s wrong, plain and simple.

## Diagnostics and the need for accuracy

We need testing tools that don’t have the error rate of uncontrollable, ad sponsored, unreliable speed tests.

Any medical doctor will tell you that the diagnostic process is massively important.  You need to work out what the problem is before you try and fix it.

Otherwise, you might be doing things that are completely unnecessary.

Bonded internet connections are by their very nature made up of more component parts than single circuits, so it’s very important that the right tests are performed, and in the right order, to that their results can be interpreted and a course of action can be determined.

It might be that certain tests are designed to eliminate certain types of problem, and that more than one test is required, but the more tests that are run, the closer to the answer you are.

## Monitoring and its importance

Why wait for some tests to be run? Specifically why wait for a fault?

The more you can do in advance, and the more you can do constantly, the better the position you will be in when a fault does occur.

In fact, you can actually predict and prevent certain problems by catching changes as they happen.

So monitoring is very important.  It’s why from day one, we started building eView Live, so we could turn the idea of broadband just going in and being forgotten about on its head.

Where are most of the problems? With the circuits themselves.  So let’s build something that keeps a constant eye on all the circuits.  Something no other ISP does.

## eView Live is accurate

We have to buy bandwidth at various points in and out of our network – from carriers, and to the internet.

Because of this, and to maintain a contention-free network, we have to know exactly what is in use 24/7.  So the figures you see on eView Live for live bandwidth usage are totally accurate.

## Connections are getting faster

With the advent of FTTC, and Fibre on Demand coming soon, connections are getting bigger and bigger, and can shift more and more data at once.

The bigger they get, the more difficult it is to reliably test how much bandwidth you have.

This is primarily because even though you have lots of bandwidth, the servers and networks you are connecting to do not.  They haven’t scaled up their connections, and server capacity to accommodate all the new faster connections people can now get, and how many people want to access them at once.

## We won’t ask you ever run a speed test on your connection

The BT Wholesale test is for individual circuits, and even then, its for when you are plugged directly into the modem, not through your firewall or your bonded internet gateway.

On your overall connection, and through your firewall and your LAN, don’t run online speed tests.  We can’t accept their results and neither can our carriers.

## We’re not trying to hide from problems

If you do have a problem, then get in touch.  We’re not saying there isn’t a fault somewhere, we’re just saying running a speed test won’t help find it, and it certainly won’t help solve it.

It’s not in our interest to misdiagnose problems, and we hope that by putting eView Live front and centre, we can’t hide from issues, just work as hard as we can to fix them, and prevent them wherever we can.

**Nic Elliott &#8211; Technical Director **