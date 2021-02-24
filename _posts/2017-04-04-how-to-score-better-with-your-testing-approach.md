---
layout: post
title: Fore! How to score better with your testing approach
subtitle: 4th April 2017
description: "... Do people in YOUR context regularly evaluate your testing tools and techniques to make suggestions on improvements or do you sit quietly and not question the status quo? As testers we should strive to read about tools, try tools out, make mental notes on how you might use those tools best in your daily testing work and then maybe leave the tool alone until the task at hand DEMANDS that tool!..."
date: 2017-04-04 12:00:00 +01:00
author: David
permalink: /blog/how-to-score-better-with-your-testing-approach/
featured_image: /images/posts/fore.jpeg
categories:
  - Testing
  - Team Quality
---
# Fore! How to score better with your testing approach

Recently I did an extremely nervous 99 second talk at [TestBash Brighton 2017](https://dojo.ministryoftesting.com/events/testbash-brighton-2017) in Brighton in which I compared golf to testing:

[TestBash 2017 99 Second Talks](https://dojo.ministryoftesting.com/lessons/99-second-talks-testbash-brighton-2017)

Now I know golf is a rather dull subject to many people who may have never played it, so I’ll try not to bore you all too much.

The thing with golf, as anyone who has ever watched it on TV knows, is that you only ever need a **single** golf club to play golf at the highest level... Rory McIlroy, Sergio Garcia, Seve Ballasteros, Tiger Woods... They all only ever used one club! All the rest of the clubs, the caddie to carry them etc are an elaborate hoax!

Let me explain...

* Those guys tee off using a **driver** to hit the ball as far as possible. BOOM and down the fairway the ball flies.
* Then they use the **driver again** to punch the ball down the fairway or onto the green.
* And if they hit it into the rough or a bunker, guess what club they teach for? That’s right, the **driver**!
* Then they’re a foot from the pin where just a nice little tap in with a putter will win the hole. What club do they use?

**Driver!**

Except that actually **nobody uses one club all the time** because at the very best professional level in golf it would be inefficient (and for the vast majority of weekend warriors it makes the game completely inaccessible and not even remotely enjoyable)

**Every golf club has a purpose and an ideal use case**; some clubs have multiple purposes, or several use cases, but no club fits **all** the purposes and **all** the use cases. Yet, I’ve met testers who apply that _"one tool fits all"_ mentality to their testing, daily!

I’ve met testers who use one set of browser developer tools and never try others (even berating others without trying them!)

I’ve met testers who have a certain tool choice for tracking their exploratory test coverage, and they _never_ look into other possibilities:
* Who will be reading the report? What would they prefer?
* Is a notepad doc sufficient, useful and logical for others to read?
* Would Rapid Reporter give the notes more structure?
* Would a mindmap be clearer?
* Is the time trade-off worth the benefit to _your_ context?
* Should you be tracking coverage in a spreadsheet because your client is a 3rd party who requires a visual representation of the testing done?
* Does your tool integrate directly with your issue tracker? Should it?

Do people in _your_ context regularly evaluate your testing tools and techniques to make suggestions on improvements, or do you sit quietly and not question the status quo?

For a long time I myself had one **single** choice of Proxy software to analyse what’s being sent from and fired back to a test app. I knew what I could do with it so I never looked into others; what was the point when I knew my choice of app well?

Sometimes tools can be used for purposes other than the intended one, much like someone may choose to "bump and run" a golf ball from the fringe of the green with a club normally intended for long shots off the fairway – For that specific shot it’s a great option. For that specific test you want to do perhaps [cURL](https://curl.haxx.se/) + [JQ](https://stedolan.github.io/jq/) is a superb option to pull in some JSON and reorder it for comparison, but for the rest of your testing there may be little value in those tools.

As testers we should strive to read about tools, try tools out, make mental notes on how you might use those tools best in your daily testing work and then maybe leave the tool alone until the task at hand **demands** that tool!

Maybe that will put us in a far less biased position when it comes to using the right tool for the job and it will expose us to more tools, better tools and ultimately make us more efficient in our day to day work.

**The driver is almost never the best club for all shots, all the time...**