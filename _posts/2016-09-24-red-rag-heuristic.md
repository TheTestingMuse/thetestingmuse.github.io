---
id: 441
title: The ”Red Rag” Heuristic
date: 2016-09-24T10:31:00+01:00
author: TheTestingMuse
layout: post
guid: https://thetestingmuse.uk/?p=441
permalink: /blog/red-rag-heuristic/
classic-editor-remember:
  - block-editor
site-sidebar-layout:
  - default
site-content-layout:
  - default
theme-transparent-header-meta:
  - default
image: /wp-content/uploads/2020/01/d877521f-3b56-448c-8c2f-528c60e166f9-35677-0000194128a3001c.jpg
categories:
  - Heuristics
  - Testing
  - Thinking
---
Originally posted on 24/09/2016

* * *

A few weeks ago there was a problem with our phone system in the office; whenever the main phone rang and was picked up from a _different_ phone the main phone registered the call as &#8220;missed&#8221;

There was a discussion about how nobody was answering calls except for the office manager and various people were told off who had been in the office at the time even though everybody insisted that no calls had been missed.

A discussion took place the following morning where the following phrase came up:

> &#8220;It&#8217;s a simple phone system so it can&#8217;t be broken; it has to be the testers not picking up incoming calls!&#8221;

As you&#8217;d imagine, this assertion immediately got my Testy Senses tingling, so I set out to prove the opposite; that the phone system can indeed have a defect and quite possibly did (or our domain knowledge of the phone system needs improving to understand why it&#8217;s behaving in a way that seems unnatural).

My internal response to the assertion was instant, powerful and absolutely 100% **<span style="text-decoration: underline">necessary</span>** for me to investigate _immediately_ &#8211; this couldn&#8217;t wait and I would stay late that day if I needed to!

I time boxed 15 minutes to investigate the issue, started straight away and did indeed find a bug with the system as expected.

After the fact, I realised that the intensity of the reaction I&#8217;d had (which made me want to investigate desperately) was caused by the assertion itself &#8211; it was a statement of **<span style="text-decoration: underline">believing absolute fact with no evidence</span>** to back it up and my experience as a veteran tester immediately disagreed with it being &#8220;absolute&#8221;.

And that was the moment my &#8220;red rag&#8221; heuristic was born:

**&#8220;The red rag heuristic&#8221; &#8211; Having an almost uncontrollable urge to charge straight into a situation with no pre-planning, no thought for the consequences or what effect there will be on other things that require your time or skill.**