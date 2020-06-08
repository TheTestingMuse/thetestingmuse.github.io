---
id: 466
title: Overthinking it (I can, therefore I will!)
date: 2017-04-10T08:38:35+01:00
author: TheTestingMuse
layout: post
guid: https://thetestingmuse.uk/?p=466
permalink: /blog/overthinking-it/
classic-editor-remember:
  - classic-editor
site-sidebar-layout:
  - default
site-content-layout:
  - default
theme-transparent-header-meta:
  - default
image: /wp-content/uploads/2020/01/Thinking.jpg
categories:
  - Heuristics
  - Testing
  - Thinking
---
Originally posted on 10/04/2017

<strong style="font-size: 16px; font-style: normal;"><img class="alignright size-medium wp-image-467" src="https://thetestingmuse.uk/wp-content/uploads/2020/01/paper-planes-300x280.png" alt="Paper planes" width="300" height="280" srcset="https://thetestingmuse.uk/wp-content/uploads/2020/01/paper-planes-300x280.png 300w, https://thetestingmuse.uk/wp-content/uploads/2020/01/paper-planes-1024x955.png 1024w, https://thetestingmuse.uk/wp-content/uploads/2020/01/paper-planes-768x716.png 768w, https://thetestingmuse.uk/wp-content/uploads/2020/01/paper-planes-1536x1432.png 1536w, https://thetestingmuse.uk/wp-content/uploads/2020/01/paper-planes.png 2038w" sizes="(max-width: 300px) 100vw, 300px" /></strong>

At TestBash Brighton 2016, one of the superb talks was on &#8220;Building the Right Thing&#8221; with [Lisa ](https://twitter.com/lisacrispin)[Crispin](https://twitter.com/lisacrispin) and [Emma Armstrong](https://twitter.com/emmaatester) and the talk started with a very basic task &#8211; &#8220;make something that flies through the air&#8221;. My first thought on hearing this task was, &#8220;_I&#8217;ll scrunch up the paper and throw it; that would be funny_&#8221; quickly followed by &#8220;_but I&#8217;m sure they don&#8217;t mean that and anyway I can make superb paper planes which would be more fun_&#8221;

I made a plane ready to fly and then we were told that the requirement was one of Minimum Viable Product (I hate this phrase but that&#8217;s a separate blog post!) so my initial thought would have been spot on. Gutted!

**I&#8217;d completely over thought the task at hand.**

This year at TestBash Brighton in their excellent mentoring workshop [Shey Crompton](https://twitter.com/sheymouse) and [Nicola Sedgewick](https://twitter.com/nicolasedgwick) tasked us with something similar; the task was to build an actual &#8220;_paper plane_&#8221; this time though so I got to make a great paper plane and be on task for the challenge. Win win!

This time I knew that as it was a mentoring workshop there would **_likely_** be a challenge to teach and learn what we created so I decided to design my plane in as simple a way as I could think of; I based it on a simple dart shape rather than complex wing design with the idea being that if I threw it hard enough and it would fly a nice long way anyway but there would be a benefit of being able to _easily teach the design_. As predicted it flew across the room and happy was I!

We were then told to describe the process of building our planes to a partner (nice to know my intuition was right on that).

I was also confident that I could easily describe the process for my partner to replicate my plane… except that what is simple for me isn&#8217;t **necessarily** simple for others; I understand what **my** mind can process, understand and retain easily in terms of instructions, but I can&#8217;t know that of someone else, especially someone I&#8217;d never met until that moment.

My partner did successfully follow my instructions successfully, although it was **far from as easy as I&#8217;d envisioned** &#8211; I&#8217;d have been better off making an even more simple plane that was not as detailed, with the trade-off in &#8220;flight capability&#8221; being matched in &#8220;reproduction capability&#8221;.  
(**K**)eep (**I**)t (**S**)imple (**S**)tupid

As testers, we often can&#8217;t see the wood for the trees. We look at a system or a website or an app to be tested and immediately our mind fills with the potential things we can subject the system to in order to test it. Sometimes our mind is exactly on-task and the intended tests are precisely what&#8217;s needed. Other times though we over-think it and end up wasting time in convoluted tests or bug investigations that could have been much simpler and allowed us to move on to other important tests.

We also try to make judgements and estimations of others&#8217; capabilities, whether it&#8217;s in our bug reports, test scripts (ugh!) clients demand, or in meetings we have with our team.

Let&#8217;s look at some practical examples:

### Example #1 &#8211; &#8220;I&#8217;m going to create a tool for test data creation&#8221;

You have a website to test where many accounts can all be in differing states. You decide you need to create 10 test accounts on the system. Rather than go through the monotony of creating them all individually by hand you decide to create a snippet of JavaScript to automate it for you.

The JavaScript takes you 2 hours to write, debug and run successfully. Job done!

Except that each account takes 2 minutes to create, and there&#8217;s a 1 minute server-side block on being able to create additional accounts.

The project only has 2 days of test time, and the automation took 2.5 hours to create the accounts. In reality you would have used less time just doing it manually for the duration of this project.

**You completely over-thought it! D&#8217;oh!**

### Example #2 &#8211; &#8220;The main banner image is missing on one specific browser&#8221;

You&#8217;re testing a website and your baseline is Google Chrome. You&#8217;re happy with your coverage on the baseline and you move on to test on other browsers. Firefox passes with flying colours, Edge is happy and so is Internet Explorer 11. Safari has a couple of minor issues that you report and the next browser on your hit list is Internet Explorer 10.

You boot the clean image test machine, clear down cookies and cache and load the page but the main banner is missing.

A quick investigation verifies that the image is declared correctly in the code and it exists on the server when the URL is added straight into the navigation bar of the browser so it seems like a rendering issue. Better bug it!

<img class="size-medium wp-image-468 alignleft" src="https://thetestingmuse.uk/wp-content/uploads/2020/01/sherlock-300x300.jpg" alt="Sherlock Holmes" width="300" height="300" srcset="https://thetestingmuse.uk/wp-content/uploads/2020/01/sherlock-300x300.jpg 300w, https://thetestingmuse.uk/wp-content/uploads/2020/01/sherlock-150x150.jpg 150w, https://thetestingmuse.uk/wp-content/uploads/2020/01/sherlock-768x768.jpg 768w, https://thetestingmuse.uk/wp-content/uploads/2020/01/sherlock.jpg 880w" sizes="(max-width: 300px) 100vw, 300px" /> Except that you reckon you can track down the exact cause of the problem and provide the developer with a load more info than a simple &#8220;Banner image on Internet Explorer 10 does not display&#8221; bug report.

You end up spending a further hour figuring out the full problem (the CMS uses a handler that&#8217;s declaring a different mime-type than the image actually had) and you report the full details. How great is that?

Wait‚ **you used an entire test session to investigate** that? So now there&#8217;s another charter that needs to be dropped or postponed?

Maybe just bugging it after 2 mins of investigation and letting the developers investigate the actual cause was a better plan even if you were providing far less information with that bug report.

**Over thought it again (and ironically thought nothing about the other charters impacted by over-thinking this one thing)**

So you see, as testers it&#8217;s very easy for us to get carried away with our work, over-think the task at hand and produce **less value** to the long term project targets in favour of short term value to that single task.

**Try to be mindful of Pareto&#8217;s Principle &#8211; you&#8217;ll get 80% of the output from 20% of the input and most of the time 80% is more than adequate.** If you know you **can** investigate further, perhaps add that offer into the bug and discuss it at the next scrum or with your project manager and allow them to decide.