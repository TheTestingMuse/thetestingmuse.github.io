---
layout: post
title: Fire all your testers?
subtitle: 31st Jan 2021
description: "... If you're confident that your engineers are doing work to a standard where the risks to their work are low enough for your risk appetite, and you're happy for them to learn quality and testing practices on the job, I sincerely see no reason for you to have quality folks on your team..."
date: 2021-01-31 10:31:57 +01:00
author: David
permalink: /blog/fire-all-your-testers/
featured_image: /images/posts/fired.jpg
categories:
  - People
  - Community
  - Testing
  - Team Quality
---
# Fire all your testers?

Over the last few years I've seen many blog posts, tweets and talks about companies getting rid of their Testers, or specifically people who have purely a testing skillset.

Normally I take Paul McGee's advice on them, and I [S.U.M.O](https://www.thesumoguy.com/), but I also recently read a couple of blog posts by [Jesper Ottosen](https://jlottosen.wordpress.com/2021/01/25/the-testing-not-the-testers/) and another by [Maaret Pyhäjärvi](https://visible-quality.blogspot.com/2021/01/having-testers-makes-quality-worse.html) both of which address the main arguments many others don't, and I felt like I should share my own view on the subject.

## Let me start with an analogy

We moved into our current home in early 2019 as first time buyers, and of course there were many things we needed to fix, clean, decorate and update. One of those things was the garden, which was overgrown, had a pond in the middle of it, had half dead grass, a decrepit and rotten shed husk at the end of it, and a rotten and broken mish-mash of fencing.

With spring only a few months away, we decided to improve it. Over several months, into summer, here's what we did:

- We drained the old pond and filled it in for safety around the children
- I smashed and removed a concrete pathway running the full length of the garden to give us a wider garden to work with
- I ripped-up the old mossy grass to replace it
- We cleared junk from the end of the garden, including a rotten pile of wood that resembled an old shed
- We created a flower bed border
- I created a railway sleeper flower bed, the length of the area we wanted artificial turf
- We ordered and ferried several tonnes of soil and sand from the front garden, around to the back, where the artificial turf would go
- We levelled the soil and sand, and I hired a whacker plate and compacted it
- I fitted a layer of shock absorber/membrane and then artificial turf to that area
- I ordered and built a 6x4 wooden shed for storage
- We ordered and built a rattan seating area with parasol
- I ordered and built some outdoor bin storage
- I ordered and built a 6ft climbing pyramid area for the kids, and put down wood chip for safety

Then it came to tackling the fencing. Our fence drops by around 30cm across the length of the section that needed replacing, and was something I'd not done before, plus something which I felt had a high risk of a low quality result if I'd tackled it myself (despite having done all of the above).

For me the risks were:

- **Low quality in appearance** - With uneven ground and no knowledge of the underlying groundwork, the fence could have been uneven, leaning or generally unsightly.
- **Low quality in stability** - Without solid footing, the fence could topple onto the kids, the neighbours, or generally break apart from other panels.
- **Not secure** - If the fence was not fixed correctly, it would create a security issue where it could be easy to get into the garden.
- **Low quality in performance** - Unless the fence was erected correctly, it's perfectly possible that it would not last as long as a correctly erected fence.

I _could_ have accepted those risks, which naturally occur when somebody lesser experienced performs a task for the first time, but I decided that the risk was too great for my personal risk appetite, and that I wanted to mitigate them if possible.
One way to do that was to pay for the expertise of someone with many years of experience (or who had been trained well) and who would understand the brief, define a strategy to tackle the work, have specialist tools to do the task, and who would provide assurances to that work.

**I hired a professional to replace the fence.**

Would I have hired an expert, if I had the training or experience myself, to mitigate the perceived risks sufficiently? Not even remotely! If I knew that I could perform that task to a standard of "good enough", I'd have accepted the risks, as they'd have been lower, and I'd have saved myself a big chunk of money doing so!

## So, what does this have to do with testers and testing?

Well let's imagine that my garden fence is some software to be written, and that there are two teams both tackling that same task, both with the same team makeup (no Quality Expert on either team), and both with the same tech/tooling at the same time:

### Team A

Team A are a traditional "waterfall" engineering team. Until recently they had a Quality Engineer who would write automated checks against everything that was defined by the Project Manager, Picked up and developed by the Developers and marked as "Ready for QA". They would write some "end to end" checks to confirm the Acceptance Criteria, in a suite that ran before things went to production, and then they would pick up the next ticket to do the same with. The team's QE eventually decided to seek a different opportunity, and they left the business.

This team have very little training or experience of Quality, Testing, or Checking practices.

### Team B

Team B are a more "Agile" engineering team. Until recently they too had a Quality Engineer.

Their Quality Engineer would be involved from the very start, asking questions about the context and value of the work, about the metrics driving the work, about the risks to the work (and _from_ the work), about dependencies, how it should be tested, what type of automated checking would make sense, and how they could help the engineers understand those decisions, and how to add that checking to the right place for the shortest feedback loops, and fastest confidence levels.

Their QE would pair with developers and talk about the assumptions being made, how to validate those assumptions, and discuss edge cases and the value in adding different types of check, versus accepting the risks associated with not adding those.

Their QE would perform regular Exploratory Testing and surface information regularly. Information around the expected, the unexpected, the negative and positive, the curious and serendipity of their exploration and the team would discuss that information to decide as a team what to do with it.

Their QE would continuously work with all team members to make sure everyone is aware of what's going on, potential issues that may arise, whether things are going as expected, and if not raise the point for discussion to make sure there were no surprises.

Their QE would create the right automated checking frameworks for the right type of feedback, and teach the rest of the team what was created, why, how it works, how it _doesn't_ work, how to evaluate the status of it, and how to troubleshoot both the framework itself, and the checks within the framework, too.

They would spend time focusing on the next most important quality-focused thing for the team to be more confident in their work.

Their QE got to the point where the team themselves were proactively doing all of the above, both solo and with each other, and the value of that QE eventually decreased, and they moved to a different role.

This team have been continuously learning and practicing Quality, Testing and Checking practices.

**Of these two teams, which would you have more confidence in, for building your software, without recruiting a replacement QE?**

Depending on the software being created, it's perfectly feasible that the team actually don't _need_ a Quality Engineer, if their risks are low enough (or if their risk appetite is sufficient for the risks around not having a QE)

## So what about teams who have never had a QE?

So, what about teams who have never had a Quality Expert on the team?

I would expect, that over a period of time there would be instances of pain.

There will be times when things go wrong, when things cost a lot to fix, when things come back with negative feedback from customers, and I would expect that those teams are like to _learn from that pain_, and try to address the shortfall that occurred which made that situation happen.

_They may not learn as quickly_ as having an expert on the team to help and teach them, but they will still learn, and the risk level of not having a QE may still be low enough **for their context**

## So, fire all our testers, then?

If you're confident that your engineers are doing work to a standard where the risks to their work are low enough for your risk appetite, and you're happy for them to learn quality and testing practices "on the job", I sincerely see no reason for you to have quality folks on your team.

Having said the above, I've not worked on/with any team even _close_ to that level of quality focus in my 18 years in the quality/testing industry. Every single role I've held, from "Tester" to "Head of Quality Engineering" and everything in between has been in companies and engineering functions where Quality Experts were **absolutely essential** to the work being done, when taking into account the associated risks.

_Can_ you fire all your testers? Sure...

_Should_ you fire all your testers? Probably not!
