---
id: 463
title: NOT testing is powerful!
date: 2016-11-25T08:06:54+00:00
author: TheTestingMuse
layout: post
guid: https://thetestingmuse.uk/?p=463
permalink: /blog/not-testing-is-powerful/
classic-editor-remember:
  - classic-editor
site-sidebar-layout:
  - default
site-content-layout:
  - default
theme-transparent-header-meta:
  - default
image: /wp-content/uploads/2020/01/same-same.jpg
categories:
  - Heuristics
  - Testing
  - Thinking
---
Originally posted on 25/11/2016

Recently, at an event, I overheard a conversation between two testers in which one tester was describing some examples he&#8217;d apply to an email field.

As the conversation went on there were a lot of &#8220;tests&#8221; he described, that I found to be basically pointless, and it got me thinking about how as professional testers we automatically use our experience, knowledge and heuristics to decide on the best approach and best set of tests/checks to run &#8211; from applying every test known to man to no tests at all, with anything in between.

The tester in question had used an example of:

> &#8220;So in the First Name field you might try a vowel, a consonant, two consonants, two vowels, a vowel and a consonant etc&#8221;

_Huh?_

To quote the phenomenal [Michael Bolton](https://twitter.com/michaelbolton) &#8211; &#8220;In traditional parlance, domain testing involves identifying equivalence classes; sets of things that we expect the program to (mis)treat in the same way&#8221; and to my mind from a pure functionality perspective, whether a consonant or vowel is used to check an input field&#8217;s validation or submission makes no difference.

If I was looking at physical character size, letter widths etc that&#8217;s a different story completely, as would be checking Ascii, Extended Ascii, or Unicode characters, but to my mind those tests I overheard are simply a waste of time.

Sometimes testing isn&#8217;t just about what we DO test/check, it&#8217;s about what we DON&#8217;T as well&#8230; This narrows our scope and gives us more time to concentrate on the higher risk important areas.

Source: <http://www.developsense.com/articles/2006-10-MasterOfYourDomain.pdf>