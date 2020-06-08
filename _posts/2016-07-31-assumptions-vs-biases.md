---
id: 453
title: Assumptions vs Biases
date: 2016-07-31T18:41:37+01:00
author: TheTestingMuse
layout: post
guid: https://thetestingmuse.uk/?p=453
permalink: /blog/assumptions-vs-biases/
classic-editor-remember:
  - classic-editor
site-sidebar-layout:
  - default
site-content-layout:
  - default
theme-transparent-header-meta:
  - default
image: /wp-content/uploads/2020/01/biases.png
categories:
  - Agile
  - Communication
  - Language
  - Testing
---
Originally posted on 31/07/2016

On Wednesday of last week the Software Testing Clinic held yet another excellent event in London; this time at the Thoughtworks offices in the West End (I \*love\* your London office space Thoughtworks!) and the topic this month was Exploratory Testing.

During the clinic there was a lot of discussion as you&#8217;d imagine from a room of extremely intelligent and passionate testers and on one subject I made a comment along the lines of:

&#8220;I think there&#8217;s a difference between an assumption and a bias &#8211; a bias is always negative and an assumption mainly positive&#8221;

At that point I was _(correctly!)_ questioned on that assertion by my friend [Tony Bruce](https://twitter.com/tonybruce77) on why I think one is positive and one negative.

_\*cue mind melt in front of the whole group\*_

I felt 100% that a bias is a bad thing that serves no purpose in the mind of an exploratory tester but I couldn&#8217;t articulate why. I also knew that generally speaking the thought of assumptions doesn&#8217;t give me anywhere near the type of negative reaction than the thought of a bias does, but again I couldn&#8217;t explain why. So I did the best thing I could &#8211; I stopped to question my opinion and whether it was actually an assumption or bias about assumptions and biases. 🙂

Let me start my thought process with two definitions:

## **bias**

Pronunciation: /Ààb å…™…ôs/ **NOUN**

**1** &#8211; Inclination or prejudice for or against one person or group, especially in a way considered to be unfair:

  * &#8220;there was evidence of bias against black applicants&#8221;
  * &#8220;the bias towards younger people in recruitment&#8221;

## **assumption**

Pronunciation: /…ôÀàs åm(p) É(…ô)n/ **NOUN**

**1** &#8211; A thing that is accepted as true or as certain to happen, without proof:

  * &#8220;they made certain assumptions about the market&#8221;
  * &#8220;we&#8217;re working on the assumption that the time of death was after midnight&#8221;

The same as I thought; one is &#8220;_considered to be unfair_&#8221; which lends to the negative connotation in my mind. The other is neither negative, nor positive; it is just something that has not been proven one way or the other.

### Assumptions

How does that apply to my testing? Well from my perspective an assumption is something active &#8211; it&#8217;s the deliberate initiation of a thought designed to bring that thought to the front of my mind while testing so that I can prove/disprove it (Tony Bruce defined this as a &#8216;test idea&#8217; which is definitely another great description for it &#8211; thanks Tony!) Some examples would be:

  1. I assume that the logo at the top of this page will have a hyperlink back to the homepage.
  2. I assume that the navigation items all have hyperlinks to their correct pages.
  3. I assume that if I do not enter the mandatory fields on this form that some validation will take place and I will be presented with a suitable error explaining that the form could not be submitted in its current state and that I need to make some specific corrections in order for the form data to be submitted correctly.

All of those assumptions are things I actively think about and set out to prove or disprove during my testing. They are active, mainly positive thoughts used during testing. One of my amazing colleagues [Deborah](https://twitter.com/deborah_reid19) also added that for seasoned testers it&#8217;s more likely that experience and domain knowledge over the years leads to a filtering of assumptions too; any time an assumption has been made in the past and it was wrong it was probably moved it out of a tester&#8217;s internal &#8220;safe&#8221; assumptions list and into an internal &#8220;unsafe&#8221; assumptions list (or in my case it&#8217;s removed from being an assumption completely and treated instead as an &#8220;unknown&#8221;)

### Biases

A bias on the other hand is something passive and that I&#8217;m often unaware of until I break my normal processes, sit down and ask myself whether there&#8217;s any bias being applied. It&#8217;s something I likely do as a natural process without realising it, whether that process came from previous experience, heuristics or just the way I think normally. A bias for me is generally a negative thing as it can potentially lead me away from things to explore that may be important or ways of working that are more efficient. Some examples would be:

  1. I have a bias to navigating websites with my mouse; I use the mouse wheel to scroll, I move the mouse cursor to elements and click links rather than using keyboard navigation to scroll, tabbing through elements and select them with Space/Return. Unless I actively think about that (and in the process turn that bias into an assumption that tabbing through links and selecting them will be as effective as clicking) I could miss the fact that the tab order is completely erratic because of that bias.
  2. When testing new websites for clients I have a bias toward believing what the browser Status Bar tells me a link is. I know there&#8217;s a possibility the link displayed in the Status Bar won&#8217;t necessarily be the \*actual\* link but as I see no reason for a project owner to deceive me I trust that the link shown is the link that will be opened. It may be that the client has decided to make links look &#8216;neat&#8217; by adding a hover status to them and I wouldn&#8217;t initially know because of that bias.
  3. I have a bias toward using my Windows machine for my test tools. Unless there&#8217;s a specific tool I need that is better on Linux or Mac I use what I&#8217;ve used for years. There are likely lots of excellent tools on other environments that I don&#8217;t know of because those environments aren&#8217;t used enough by me. My efficiency is undoubtedly compromised occasionally because of that bias.

So there you have it; my (possibly over-thinking it!) definition of how I see Assumptions vs Biases in exploratory testing.

_EDIT: In this post I&#8217;m talking about the **bias itself**, not the outcome of the bias (which could be positive, neutral, negative or anywhere in between) which is a separate topic 😉_