---
title: Openreach’s FTTC Availability Checker Not as Accurate as it Needs to be
author: admin
type: post
date: 2014-08-05T13:03:11+00:00
url: /openreachs-fttc-availability-checker-not-as-accurate-as-it-needs-to-be/
featured_image: /wp-content/uploads/2014/08/small-where-and-when-image696.png
categories:
  - Blog
tags:
  - BT
  - FTTC
  - Openreach

---
BT Openreach has just updated (4 August 2014) it’s FTTC Availability Checker in order to supposedly give more accurate details for people searching for information on when they might get the Fibre to the Cabinet service (see above).

Unfortunately, because it only relies on a post code, it’s not even as accurate as the already existing full address checker that BT provide for general broadband availability (for ADSL and FTTC circuits), and looks like it will only serve to confuse consumers and businesses in a market already plagued with vagueness over the FTTC rollout.

## How We’ve Checked FTTC Availability Until Now

Until this point, we have used a variety of checking tools and systems to build a clear picture of what broadband types are available at a given location, and what might be available in the future.

We’ve known for some years now that the BT Openreach [Commercial Rollout of FTTC][1] was [favouring high density residential areas over business parks][2].  This was pure economics in the sense that in order to make a cabinet viable, it needs to have a certain amount of subscribers, and a likely percentage uptake of those subscribers.

In order to check availability, we look at the telephone exchange itself to see if it has been enabled for Fibre (FTTC and/or FTTP), or if it has a planned date (this date is normally quite vague).

We then run checks on a PSTN line (normal BT telephone number) from the location in question, and the full address.  If the PSTN and full address checker shows FTTC available, then great, we can place an order, but if not, then we need to dig further.

From the above checkers we can see whether the location is only served by Exchange Only lines (no FTTC I’m afraid), or if it does run to a cabinet (what BT Openreach call in the jargon a PCP &#8211; Primary Cross-connection Point).  We then get the Cabinet number, which has then allowed us to look up more detailed information about whether that cabinet is going to get FTTC.

We, like I’m sure a number of other organisations and consumers, have been using a website that until last week was a great source of information on cabinet level data. Unfortunately it was generated from information BT feel shouldn’t be in the public domain, and because they were launching their own supposedly “cabinet-level” checker, they forced the site to shut down.

What it gave us was a list of cabinets served by the given post code, and the current state of those cabinets.  It even included BDUK information, and some dates where possible for installation.  All in all it was very useful.  That unfortunately is not the case anymore, so we have had to start going through the raw data from BT ourselves, as the new Openreach checker is very much giving misleading or inaccurate data.

It may still be in “beta”, but the fact that better information exists in a raw format to Openreach partners, and that somebody already wrote a site that exploited it better, it seems odd that this new official site is so bad.

<div class="ask-a-question-bar">
  <div class="container">
    <p class="question">
      <img src="/wp-content/uploads/2014/07/Headset-Icon-White1.png" />Have a question? Contact us on <strong><span class="calltracks_evolvingnetuk-main">0330 55 55 333</span></strong>
    </p>
  </div>
</div>

## Consumers and Business have been misled for some time

The old Openreach checker was also a nightmare.  All it did was tell you if the telephone exchange you were connected to was upgraded for Fibre.  It had no location specific information at all, and so with the vast number of exchange catchment zones NOT getting fibre, it was very misleading.

It is a regular occurrence for our sales team to have to counter “I can get Fibre can’t I?” with “I’m really sorry, but it’s just not available”, because of this checker, and other ISPs making promises they couldn’t fulfil.

We also have instances where customers have not bought a bonded ADSL connection from us because they think FTTC is just round the corner, only to find that it has taken years, or in some cases hasn’t and will not arrive.

The [Broadband Delivery UK][3] (BDUK) projects have muddied this process even more, as although the extra government money is there to add more access to services such as FTTC, the information available from those projects is often sketchy.

As has been highlighted in select committee hearings in Parliament, in general the BDUK projects are left in the dark by BT over many aspects of delivery and availability, and often have only vague timelines without the ability to check a full address of PSTN number.

They also mix terms like Fibre and Superfast, which misleads consumers into thinking that as long as they get upgraded to FTTC, they will get Superfast (over 24mbps or 30mbps, depending on the definition – more vagueness) speeds at their house.

This is often not the case, with a minimum 2mbps still the target even for FTTC.

## Checking FTTC Broadband with a PSTN (Normal Telephone Number)

Using a [telephone number][4] (BT of course), to check for broadband availability has long been the most accurate way of checking for broadband availability.

It’s been the way to check for ADSL, ADSL Max and ADSL2+ availability since broadband first came to the UK, and it has certainly always been the most accurate check of when the next technology will be available.

The trouble is, that even though work can be physically carried out (upgrading an exchange, installing a fibre node, replacing cabinets) for the BDUK projects, the BT Broadband Availability Checker is almost always kept in the dark.

The cabinet level information has existed for some time, and there are even hints as to pending availability by looking for Street Side DSLAMs (the FTTC Cabinets themselves) in the address checker, but the normal (historically most accurate) check of a PSTN will give no data for FTTC/P availability.

What we’ve seen happen is that FTTC has to be completely installed and available to order before it appears on the Broadband Availability Checker.

Importantly though, if it is available, a PSTN check will definitely give you an accurate result – or at least the MOST accurate result for whether you can get FTTC or not right now.  The speed estimates are another thing entirely… but that’s for another post.

## Checking FTTC and ADSL Availability with a Full Address and Post Code

Checking with a [full address and postcode][5] for FTTC availability is a good way of seeing if a post code area is large, and served by more than one cabinet.

The full address checker can list all the address in a post code area if you just enter the post code, and you can then choose the most accurate address from the list, and also look at adjacent and neighbouring properties to check their FTTC status as well.

It is perfectly possible, and quite commonplace for a street or area to be served at different ends by different cabinets, and for one of those to be FTTC enabled, and another to not be.

This is where the problems of a [post code only checker][6] begin.

For locations that don’t show current FTTC availability, unless you can identify exactly which cabinet a property is served by, and then have a way of checking that cabinet directly, you can’t give a good indication of when FTTC may hit, or if it will hit at all.

<div class="ask-a-question-bar">
  <div class="container">
    <p class="question">
      <img src="/wp-content/uploads/2014/07/Headset-Icon-White1.png" />Have a question? Contact us on <strong><span class="calltracks_evolvingnetuk-main">0330 55 55 333</span></strong>
    </p>
  </div>
</div>

## Checking Broadband Availability with Just a Post Code

The [new Openreach checker][7] only uses a post code, so gets confused very easily when there are multiple cabinets serving a post code.

Take this post code as example: WV7 3BJ

These lucky people connected to the Albrighton exchange, have 3 cabinets serving their area and all have FTTC.

From information Evolving Networks has access to by being an Openreach partner, we can see these 3 cabinets (4, 8 and 9) are not part of the commercial rollout (which ended in Spring 2014 anyway), but they were all upgraded as part of the Shropshire BDUK project – Phase 11b.

These 3 cabinets are live right now with FTTC.

Yet the new Openreach checker gives a question mark, and says while it’s available in the area, they can’t tell if you can get it right now.

<img class="aligncenter size-full wp-image-998" src="/wp-content/uploads/2014/08/Untitled.png" alt="Untitled" width="692" height="380" />

This is crazy, as if you look up every single full address in that post code area, every single one of them can get FTTC, through one of the 3 cabinets listed above, with speed estimates and all.

## Cabinet Level Information for FTTC Checking

Cabinet level information is very useful, but you need to be sure what FTTC cabinet is serving your lines in order to use the information effectively.

As long as you can perform a [full address search][8] of a location or [search using a PSTN number][9], you can get an accurate read of your cabinet number, and then the cabinet information becomes useful.

We’re still looking for comprehensive date information for BDUK phases, as they don’t appear to be collated in one place, although our friends at <a href="http://www.increasebroadbandspeed.co.uk " target="_blank">increasebroadbandspeed.co.uk</a> have produced a good list of [BDUK projects][10] and what their targets are.

## New Openreach FTTC Availability Checker Doesn’t Identify Your Cabinet

The new BT Openreach FTTC Availability Checker doesn’t make any attempts to identify your cabinet, and so can’t give you a full run down of what FTTC you can or will get in the future.

Even the different statuses are odd.  After the simple “Accepting Orders” status, there are a full 5 distinct statuses which indicate you can get FTTC at some point, but they aren’t sure on the date.

<img class="aligncenter size-full wp-image-1001" src="/wp-content/uploads/2014/08/Map-Key.png" alt="Map Key" width="363" height="426" />

Our read of these is that they belong in the following order:

### AO &#8211; Accepting orders

It should be available (but don’t count on it until you’ve done a full address and PSTN check!)

### ?

As above, you really need to do a full address and PSTN check, as you just won’t know otherwise

### HD &#8211; High demand

Your cabinet has run out of FTTC capacity, so while you’re neighbours may have it, you just have to wait – and may have to wait months for an upgrade of the cabinet.

### EA &#8211; Enabled area

Sometime in the next few months?? Quite vague.

### CS &#8211; Coming Soon

6 months out – very vague

### PA – Planned Area

18 months – the vaguest prediction, and in our experience the longer the lead time, the less likely it will happen in that predicted timeframe.

### UR – Under review

There appears to be no way of getting more information about a cabinet under review, or when that review may conclude.  Don’t get your hopes up.

### ES – Exploring Solutions

This is surely the most misleading definition, and attempts to give the most positive spin on all those areas that just won’t get FTTC any time soon (in the next 5 years).

### NC – Not currently in plan?

&nbsp;

Some of our searches have come up with NC which isn’t even on the new key, but was an old status, which may just indicate that not all the data has been updated yet.

## Our Conclusion

The original BT Broadband Availability Checker (BBAC) has historically been the place to get an accurate check of the different broadband technologies, and when they become available.

Checking for when the 21CN rollout comes to an exchange, and when ADSL2+ will become available was achieved through this checker, and then when the FTTC commercial rollout started, it became the place to check for predicted dates for [FTTC availability][11] as well as predicted speeds for the service.

Now, not only does the BT Openreach website give misleading post code only information on FTTC availability, but the BBAC generally doesn’t get updated with BDUK information until the product is actually available to order.

In the absence of a definitive checker to find out not only what speeds you might get, but whether you will get FTTC at all in the next 5 years, we are making sure that all our customers and potential customers get a thorough check by a trained specialist, using data from all of the systems we have mentioned above, including cabinet level information we have obtained from Openreach directly.

In fact, we are rolling out this training to every staff member at Evolving Networks, so that everyone here understands how vague a promise FTTC availability is at the moment, and can help anyone phoning or emailing in with answering that important question.

Our development team are looking at creating a single master checking system that will have access to the cabinet level and full address data, along with BDUK project timescales as well, so that we can speed up the checking and quoting process.

We’d love to make this public, but considering Openreach have already forced a useful FTTC checker to shut down, it might be that we can’t go down that route.

As soon as we have something working, we’ll post an update here, but for now, if you want as accurate a check of your location as you can get for FTTC availability, don’t use the new Openreach checker.

We have the latest cabinet level information from BT, so [phone or email one of us][12] to get someone to do the digging for you, and build the story of how and when you might get FTTC.

**Nic Elliott &#8211; Technical Director**

 [1]: /end-of-bt-fttc-commercial-rollout-looms "End of BT FTTC Commercial Rollout Looms"
 [2]: /uk-broadband-not-fit-for-purpose-why-not-choose-bonding "UK Broadband ‘not fit for purpose’ – why not choose bonding?"
 [3]: https://www.gov.uk/government/publications/bduk-broadband-delivery-project "BDUK"
 [4]: http://www.dslchecker.bt.com/ "BT PSTN Checker"
 [5]: http://www.dslchecker.bt.com/adsl/ADSLChecker.Address?URL=&SP_NAME=a%20service%20provider&VERSION=39&MS=E&CAP=no&AEA=Y
 [6]: http://www.dslchecker.bt.com/adsl/ADSLChecker.Postcode?URL=&SP_NAME=a%20service%20provider&VERSION=39&MS=E&CAP=no&AEA=Y "BT Post Code Only Checker"
 [7]: http://www.superfast-openreach.co.uk/where-and-when/ "New Openreach FTTC Checker"
 [8]: http://www.dslchecker.bt.com/adsl/ADSLChecker.Address?URL=&SP_NAME=a%20service%20provider&VERSION=39&MS=E&CAP=no&AEA=Y "BT Address Level Checker"
 [9]: http://www.dslchecker.bt.com/ "BBAC PSTN Checker"
 [10]: http://www.increasebroadbandspeed.co.uk/superfast-fibre-broadband
 [11]: /fttc-is-coming-or-is-it
 [12]: /contact-us/ "Contact Us"