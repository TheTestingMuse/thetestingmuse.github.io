---
layout: post
title: NOT testing is powerful!
subtitle: 25th Nov 2016
description: ""
date: 2016-11-25 08:06:54 +00:00
author: David
permalink: /blog/not-testing-is-powerful/
featured_image: /images/posts/same-same.jpg
categories:
  - Heuristics
  - Testing
  - Thinking
---
Recently, at an event, I overheard a conversation between two testers in which one tester was describing some examples he'd apply to an email field.

As the conversation went on there were a lot of "tests" he described, that I found to be basically pointless, and it got me thinking about how as professional testers we automatically use our experience, knowledge and heuristics to decide on the best approach and best set of tests/checks to run  from applying every test known to man to no tests at all, with anything in between.

The tester in question had used an example of:

> "So in the First Name field you might try a vowel, a consonant, two consonants, two vowels, a vowel and a consonant etc"

_Huh?_

To quote the phenomenal [Michael Bolton](https://twitter.com/michaelbolton) - "In traditional parlance, domain testing involves identifying equivalence classes; sets of things that we expect the program to (mis)treat in the same way" and to my mind from a pure functionality perspective, whether a consonant or vowel is used to check an input field's validation or submission makes no difference.

If I was looking at physical character size, letter widths etc that's a different story completely, as would be checking Ascii, Extended Ascii, or Unicode characters, but to my mind those tests I overheard are simply a waste of time.

Sometimes testing isn't just about what we DO test/check, it's about what we DON'T as well; This narrows our scope and gives us more time to concentrate on the higher risk important areas.

Source: [Master of Your Domain](http://www.developsense.com/articles/2006-10-MasterOfYourDomain.pdf)
