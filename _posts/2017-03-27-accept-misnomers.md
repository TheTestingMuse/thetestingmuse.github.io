---
id: 250
title: 'Accept misnomers &#8211; The bigger picture is helping, not correcting language'
date: 2017-03-27T13:24:49+01:00
author: TheTestingMuse
layout: post
guid: http://thetestingmuse.uk/?p=250
permalink: /blog/accept-misnomers/
classic-editor-remember:
  - block-editor
site-sidebar-layout:
  - default
site-content-layout:
  - default
theme-transparent-header-meta:
  - default
image: /wp-content/uploads/2018/12/dictionary.jpeg
categories:
  - Agile
  - Communication
  - Language
  - Teams
  - Testing
---
EDIT: This post was mid-draft when I was reminded by <a style="font-size: 15px; background-color: #ffffff;" href="https://twitter.com/nicolasedgwick" target="_blank" rel="noopener noreferrer">@NicolaSedgwick</a> on Twitter of <a style="font-size: 15px; background-color: #ffffff;" href="https://twitter.com/PaulHolland_TWN" target="_blank" rel="noopener noreferrer">@PaulHolland_TWN</a>&#8216;s TestBash 99SecondTalk about not attacking people with a different understanding of terminology than you. I&#8217;m pretty sure there are improvements yet to be made on it but for the sake of remaining relevant, I&#8217;m re-publishing it now. 🙂

In life there are misnomers everywhere:

  * &#8220;Coffee beans&#8221; &#8211; they&#8217;re actually coffee &#8220;seeds&#8221;
  * &#8220;Dr Spock&#8221; (Star Trek) is actually Mr Spock
  * Panama hats were designed in Ecuador
  * &#8220;Personal PIN Number&#8221; &#8211; PIN is an abbreviation for &#8220;Personal Identification Number&#8221; so in effect you&#8217;re saying &#8220;Personal Personal Identification Number Number&#8221;
  * &#8220;Wherefore art thou Romeo,&#8221; is often understood to mean &#8220;where are you, Romeo?&#8221; When in actual fact &#8220;wherefore&#8221; means &#8220;why&#8221; &#8211; Juliet is asking why he is a Romeo, not where he is.
  * &#8220;Peanuts are nuts&#8221; &#8211; They&#8217;re not, they&#8217;re legumes as they grow under the ground, not on trees.
  * &#8220;A tomato is a vegetable&#8221; &#8211; It&#8217;s a fruit.
  * Koala Bears are not actually bears.
  * &#8220;Slider&#8221; is sometimes used to reference a gallery/slideshow/carousel function
  * &#8220;Checkbox&#8221; is frequently used to reference a radio button. Checkboxes though are multiple-selection &#8220;AND/OR&#8221; elements whereas radio buttons are single choice buttons.
  * &#8220;Drop down&#8221; has been know to reference an expandable  
    because the panel drops-down to display content.
  * &#8220;Quality Assurance&#8221; is regularly used to reference &#8220;Testing&#8221;

And so on.

So let&#8217;s use an example misnomer and discuss the potential states of it.

We&#8217;re working on a website that is early in development and has had no technical team members on it. There is a header section that expands when clicked to reveal additional content.

The project manager and project sponsors have always referred to them as a &#8220;header dropdown&#8221; as from their perspective that&#8217;s what it is; the header &#8220;drops down&#8221; when clicked.

With misnomers there are several states of understanding:

  1. The misnomer is accepted as being factually _correct_ and not questioned. This often occurs on projects where the beginning of the project starts with substantial planning from non-technical team members or those with less domain knowledge.
  2. The misnomer is known to be factually _incorrect_ but the person understands the context and sees no reason to correct the misnomer or hold a discussion about it. Using our example misnomer, a developer may start working on the project and as there is no other way to implement the required functionality (it is not achievable via an actual &#8220;drop down&#8221; element) there really is only one possible thing it can be _right now_ &#8211; an expandable  
    , so why waste everyone&#8217;s time holding a conversation about it?
  3. The misnomer is understood to be factually _incorrect_. The person feels it is necessary to correct the originator of the misnomer with their own understanding of the misnomer. OK so let&#8217;s say a tester joins the project and decides that in order to make sure everyone is using the correct terminology and avoid any ambiguity the current &#8220;header dropdown&#8221; misnomer should be corrected. This will ensure that any future functionality that may be added to the header is not confused with the misnomer, say for example a &#8220;language&#8221; drop-down is added. There is no room for discussion here; it **must** be corrected.
  4. The misnomer is known to be factually _incorrect_. A conversation takes place with the project facilitator to gauge any potential risk associated with the misnomer. An agreement is reached whereby the most efficient solution is implemented for the misnomer. Using our example let&#8217;s say the tester joins but instead of taking a &#8220;must have&#8221; approach they explain to the project facilitator that there are ambiguity risks with using the terminology but that those risks may be extremely low depending on the development plan for the project. For example, if there will never be anything added to the header of the site that resembles a drop-down then referring to the expandable  
    as a &#8220;dropdown&#8221; will have little impact. The project manager explains that once the site development is complete it will be handed over to a 3rd party and there will be no maintenance period and no future development on the project for the development team. The project is also only a 3-month project and there are no team member changes planned that could cause confusion with terminology. The &#8220;header dropdown&#8221; misnomer is then deemed to be unimportant and everyone is happy to use the misnomer rather than set about re-educating the team.

Inadvertent use of misnomers allows quicker communication in groups where there is a joint understanding of the domain being discussed and the context of the misnomer itself by **all** parties but herein lies the risk of not correcting or discussing a misnomer; there is an inevitable **assumption** that everyone has similar domain knowledge and understands the terminology used equally, hence there is no need to discuss or correct it.

Using terminology or descriptions which are even slightly ambiguous to those with different domain knowledge can create issues though.

From my perspective what we need to strive for is the establishment of a common &#8220;language&#8221; on projects that allow the participants the ability to discuss things in the most efficient manner possible adding as little ambiguity into the discussion as possible, not to pick apart people&#8217;s differing descriptions of the same thing.

I test software. I perform a quality analysis. If you say I am &#8220;QA&#8217;ing&#8221; your software and I understand the task to be &#8220;testing&#8221; the software then there&#8217;s little value in me trying to redefine your vocabulary or use of the English language. If anything it will make everything even less efficient as there will be a period of readjustment before the new vocabulary is &#8220;normal&#8221; in day-to-day work.

The approach I normally take is to reiterate the required task using the correct terminology, for example:

&#8220;We&#8217;ve added Search functionality to the header dropdown on the staging environment. Can you exploratory test it this morning please?&#8221;

&#8220;Oh cool, yep absolutely! Exploratory test the Search function in the expandable header &#8211; got it. I&#8217;ll start right after this test session and feedback as soon as possible.&#8221;

Now having said all if the above I do think there&#8217;s a huge benefit in establishing a common vocabulary within an industry or community where our &#8220;domain&#8221; is the industry itself. But that&#8217;s a whole new blog post! 😉