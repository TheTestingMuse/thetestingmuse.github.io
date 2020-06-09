---
title: Assumptions vs Biases
date: 2016-07-31T18:41:37+01:00
author: David
layout: post
permalink: /blog/assumptions-vs-biases/
image: /images/posts/biases.png
categories:
  - Agile
  - Communication
  - Language
  - Testing
---
# Assumptions vs Biases

_Originally posted on 31/07/2016_

On Wednesday of last week the Software Testing Clinic held yet another excellent event in London; this time at the Thoughtworks offices in the West End (I \*love\* your London office space Thoughtworks!) and the topic this month was Exploratory Testing.

During the clinic there was a lot of discussion as you'd imagine from a room of extremely intelligent and passionate testers and on one subject I made a comment along the lines of:

"I think there's a difference between an assumption and a bias ; a bias is always negative and an assumption mainly positive"

At that point I was _(correctly!)_ questioned on that assertion by my friend [Tony Bruce](https://twitter.com/tonybruce77) on why I think one is positive and one negative.

_\*cue mind melt in front of the whole group\*_

I felt 100% that a bias is a bad thing that serves no purpose in the mind of an exploratory tester but I couldn't articulate why. I also knew that generally speaking the thought of assumptions doesn't give me anywhere near the type of negative reaction than the thought of a bias does, but again I couldn't explain why. So I did the best thing I could ; I stopped to question my opinion and whether it was actually an assumption or bias about assumptions and biases. 🙂

Let me start my thought process with two definitions:

## **bias**

Pronunciation: /Ààb å…™…ôs/ **NOUN**

**1** ; Inclination or prejudice for or against one person or group, especially in a way considered to be unfair:

  * "there was evidence of bias against black applicants"
  * "the bias towards younger people in recruitment"

## **assumption**

Pronunciation: /…ôÀàs åm(p) É(…ô)n/ **NOUN**

**1** ; A thing that is accepted as true or as certain to happen, without proof:

  * "they made certain assumptions about the market"
  * "we're working on the assumption that the time of death was after midnight"

The same as I thought; one is "_considered to be unfair_" which lends to the negative connotation in my mind. The other is neither negative, nor positive; it is just something that has not been proven one way or the other.

### Assumptions

How does that apply to my testing? Well from my perspective an assumption is something active ; it's the deliberate initiation of a thought designed to bring that thought to the front of my mind while testing so that I can prove/disprove it (Tony Bruce defined this as a &#8216;test idea' which is definitely another great description for it ; thanks Tony!) Some examples would be:

  1. I assume that the logo at the top of this page will have a hyperlink back to the homepage.
  2. I assume that the navigation items all have hyperlinks to their correct pages.
  3. I assume that if I do not enter the mandatory fields on this form that some validation will take place and I will be presented with a suitable error explaining that the form could not be submitted in its current state and that I need to make some specific corrections in order for the form data to be submitted correctly.

All of those assumptions are things I actively think about and set out to prove or disprove during my testing. They are active, mainly positive thoughts used during testing. One of my amazing colleagues [Deborah](https://twitter.com/deborah_reid19) also added that for seasoned testers it's more likely that experience and domain knowledge over the years leads to a filtering of assumptions too; any time an assumption has been made in the past and it was wrong it was probably moved it out of a tester's internal "safe" assumptions list and into an internal "unsafe" assumptions list (or in my case it's removed from being an assumption completely and treated instead as an "unknown")

### Biases

A bias on the other hand is something passive and that I'm often unaware of until I break my normal processes, sit down and ask myself whether there's any bias being applied. It's something I likely do as a natural process without realising it, whether that process came from previous experience, heuristics or just the way I think normally. A bias for me is generally a negative thing as it can potentially lead me away from things to explore that may be important or ways of working that are more efficient. Some examples would be:

  1. I have a bias to navigating websites with my mouse; I use the mouse wheel to scroll, I move the mouse cursor to elements and click links rather than using keyboard navigation to scroll, tabbing through elements and select them with Space/Return. Unless I actively think about that (and in the process turn that bias into an assumption that tabbing through links and selecting them will be as effective as clicking) I could miss the fact that the tab order is completely erratic because of that bias.
  2. When testing new websites for clients I have a bias toward believing what the browser Status Bar tells me a link is. I know there's a possibility the link displayed in the Status Bar won't necessarily be the \*actual\* link but as I see no reason for a project owner to deceive me I trust that the link shown is the link that will be opened. It may be that the client has decided to make links look 'neat' by adding a hover status to them and I wouldn't initially know because of that bias.
  3. I have a bias toward using my Windows machine for my test tools. Unless there's a specific tool I need that is better on Linux or Mac I use what I've used for years. There are likely lots of excellent tools on other environments that I don't know of because those environments aren't used enough by me. My efficiency is undoubtedly compromised occasionally because of that bias.

So there you have it; my (possibly over-thinking it!) definition of how I see Assumptions vs Biases in exploratory testing.

_EDIT: In this post I'm talking about the **bias itself**, not the outcome of the bias (which could be positive, neutral, negative or anywhere in between) which is a separate topic 😉_
