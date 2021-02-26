---
layout: post
title: Do you like it dirty?
subtitle: 1st November 2016
description: "... I completely see the benefit to all levels of dirtiness in testing setups but what I struggle with is lack of time on our many one hit waterfall projects and prioritising those levels of dirtiness in terms of time spent setting up versus bugs encountered versus time spent investigating and ruling out other system interactions as the cause etc...."
date: 2016-11-01 12:00:0 +01:00
author: David
permalink: /blog/do-you-like-it-dirty/
featured_image: /images/posts/dirty.jpg
categories:
  - Technical
  - Environments
  - Testing
---
# Do you like it dirty?

When I arrive at work after my morning tube commute the first thing I do is use some antibacterial hand gel before I check my emails and tasks for the day. I’d rather kill any cold or virus germs asap but not enough to walk from the ground floor up to the 3rd floor.

After I’ve checked emails, tasks and anything else urgent I’ll head upstairs to the second floor to make a coffee and en route I’ll pop up one more floor into the bathroom and wash my hands so that they’re clean as well as germ free.

I’m a clean kind of chap; not OCD clean but perhaps cleaner than I _need_ to be.

With my testing I like my environments to also be as clean ~as necessary~ for the system under test:

* Websites (including mobile sites) – No unnecessary programs running in the background and a cleared down browser with no addons enabled that may affect the site.
* Mobile apps – Factory reset device with no unnecessary apps installed or accounts that aren’t essential to the OS. No backgrounded apps or non-test-app push notifications enabled (except for deliberate testing)

The idea behind this is to reduce any false positives – Any issues I discover will almost certainly be a problem with the system under test and I won’t be incorrectly reporting issues that are centred around interaction with other software, much of which could be unique to my own preference of apps.

For instance if I was testing software on a system that had an IDE installed on it and I was unaware that the software had a reliance on certain runtimes that were previously installed and were not native to the operating system I’d completely miss the fact that the software may not even run for many users.

Similarly certain setups from previous testing sessions may not have been returned to their base state so I could end up spending unnecessary time troubleshooting proxy/DNS settings, environmental variables that should be changed etc.

I’ve spoken to quite a few people about their test system preference and generally there seems to be two camps:

1. The Angelically Clean Crew – Their machine/device is a freshly imaged desktop machine or mobile device irrelevant of any previous testing. If for example the only other testing that had been done on that environment was website testing and there’d be an almost non-existent chance of any false positives it doesn’t matter – "Image all the things!"
2. The Dirty Dozen – A more "real world" approach – Machines/devices are more often than not their development machines or personal mobiles and filled with other apps, accounts, push notifications for lots of apps enabled, backgrounded apps etc – "But real users don’t have perfect environments"

There doesn’t seem to be many people with a "good enough" approach when it comes to test environments for some reason. That may be a completely factual statement but also it may be that the people I’ve spoken to have tacit knowledge about what they would accept and it’s not entirely clean/dirty but a happy Goldilocks place.

I completely see the benefit to all levels of dirtiness in testing setups but what I struggle with is lack of time on our many "one hit" (waterfall) projects and prioritising those levels of dirtiness in terms of time spent setting up versus bugs encountered versus time spent investigating and ruling out other system interactions as the cause etc.

I think until we have the time to perform mirrored testing on both a clean and dirty device simultaneously across many projects to prove one way or other how much impact there is to time due to device cleaning versus false positives sticking to a an "everything immaculately clean" approach is the best option, even if it’s overkill.

What are your thoughts? How dirty do you like it? Do you have any real world experience or statistics of the value between clean/dirty?
