---
layout: post
title: The ”Red Rag” Heuristic
subtitle: 24th Sep 2016
description: ""
date: 2016-09-24 10:31:00 +01:00
author: David
permalink: /blog/red-rag-heuristic/
featured_image: /images/posts/RedRag.jpg
categories:
  - Heuristics
  - Testing
  - Thinking
---
A few weeks ago there was a problem with our phone system in the office; whenever the main phone rang and was picked up from a _different_ phone the main phone registered the call as "missed"

There was a discussion about how nobody was answering calls except for the office manager, and various people were told off who had been in the office at the time, even though everybody insisted that no calls had been missed.

A discussion took place the following morning where the following phrase came up:

> "It's a simple phone system so it can't be broken; it has to be the testers not picking up incoming calls!"

As you'd imagine, this assertion immediately got my Testy Senses tingling, so I set out to prove the opposite; that the phone system can indeed have a defect and quite possibly did (or our domain knowledge of the phone system needs improving to understand why it's behaving in a way that seems unnatural).

My internal response to the assertion was instant, powerful and absolutely 100% **necessary** for me to investigate _immediately_  this couldn't wait and I would stay late that day if I needed to!

I time boxed 15 minutes to investigate the issue, started straight away and did indeed find a bug with the system as expected.

After the fact, I realised that the intensity of the reaction I'd had (which made me want to investigate desperately) was caused by the assertion itself  it was a statement of **believing absolute fact with no evidence** to back it up and my experience as a veteran tester immediately disagreed with it being "absolute".

And that was the moment my "red rag" heuristic was born:

**"The red rag heuristic"  Having an almost uncontrollable urge to charge straight into a situation with no pre-planning, no thought for the consequences or what effect there will be on other things that require your time or skill.**
