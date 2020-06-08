---
title: A Polarising opinion!
date: 2020-01-21T08:12:53+00:00
author: David Williams @TheTestingMuse
layout: post
permalink: /blog/a-polarising-opinion/
image: /images/posts/post-polarised.png
categories:
  - Testing
---
How many of you drive a car?

And when it’s sunny, you likely wear sunglasses, right? Maybe polarised ones to benefit from additional UV blocking?

<img src="images/posts/polarised.jpeg" alt="Dark spots in car window" style="float:right; margin-left: 10px; width:225px; height:225px;" />

And have you ever noticed, while driving, and wearing your polarised sunglasses, the dark spotting in some of your car windows?

The dark patches are caused by stress birefringence when the glass is being tempered and rapidly cooled. The tempering process causes patchy polarisation of light, which to the naked eye is not easily seen, however when you put your sunnies on, they also have polarisation, which blocks some of the light, and it’s that combination of the two polarised surfaces causes the patterns you see (and if you tilt your head, the darker spots move or disappear because the polarisation orientation changes).

With only one of these polarised surfaces, things would be fine:

  * Only Window &#8211; Fine
  * Only Polarised lenses &#8211; Fine

In order to have a clear view through car windows, often you need to look through non-polarised lenses.

As experienced testers we have different ‘testing lenses’ depending on the risks we’re testing for, the available time, the scope of the work, the testability to us etc:

  * Data lens &#8211; What data do we have/need? How is the data being created? How does the data flow through the system? How is the data used by the system or user? How is the data transformed?
  * UI Lens &#8211; Does the UI look good? Does it function as expected? Is it useable? Is it Accessible?
  * Performance Lens &#8211; How fast does the feature work? Can it be faster? Is there a tradeoff between speed and cost? Can it deal with high loads? How does concurrency look? And so on…

Most of the time, the lens we use is well-suited to the work we’re doing, but have you ever stopped to ask yourself whether there’s a ‘_**better**_’ lens to use in that situation?

Is the lens you’re using showing you ‘defects’ that your customers really won’t care about, or that may not actually be defects at all? Or that impact the time it will take to be confident with the testing you’ve done?

A couple of examples of tools to help drive a team discussion on the correct lenses for the task in hand:

  * Exploratory testing Charters &#8211; <https://club.ministryoftesting.com/t/test-charter-template/23138>
  * TestSphere cards &#8211; <https://www.ministryoftesting.com/testsphere>

Can you think of others?
