---
layout: post
title: Accept misnomers - The bigger picture is helping, not correcting language
description: "... What we need to strive for is the establishment of a common "language" on projects that allow the participants the ability to discuss things in the most efficient manner possible adding as little ambiguity into the discussion as possible, not to pick apart people's differing descriptions of the same thing."
date: 2017-03-27 13:24:49 +01:00
author: David
permalink: /blog/accept-misnomers/
featured_image: /images/posts/dictionary.jpeg
categories:
  - Agile
  - Communication
  - Language
  - Teams
  - Testing
---
EDIT: This post was mid-draft when I was reminded by [@NicolaSedgwick](https://twitter.com/nicolasedgwick") on Twitter of [@PaulHolland_TWN](https://twitter.com/PaulHolland_TWN)'s TestBash 99SecondTalk about not attacking people with a different understanding of terminology than you. I'm pretty sure there are improvements yet to be made on it but for the sake of remaining relevant, I'm re-publishing it now. 🙂

In life there are misnomers everywhere:

* "Coffee beans" - they're actually coffee "seeds"
* "Dr Spock" (Star Trek) is actually Mr Spock
* Panama hats were designed in Ecuador
* "Personal PIN Number" - PIN is an abbreviation for "Personal Identification Number" so in effect you're saying "Personal Personal Identification Number Number"
* "Wherefore art thou Romeo," is often understood to mean "where are you, Romeo?" When in actual fact wherefore" means "why" - Juliet is asking why he is a Romeo, not where he is.
* "Peanuts are nuts" - They're not, they're legumes as they grow under the ground, not on trees.
* "A tomato is a vegetable" - It's a fruit.
* Koala Bears are not actually bears.
* "Slider" is sometimes used to reference a gallery/slideshow/carousel function
* "Checkbox" is frequently used to reference a radio button. Checkboxes though are multiple-selection "AND/OR" elements whereas radio buttons are single choice buttons.
* "Drop down" has been know to reference an expandable because the panel drops-down to display content.
* "Quality Assurance" is regularly used to reference "Testing"

And so on.

So let's use an example misnomer and discuss the potential states of it.

We're working on a website that is early in development and has had no technical team members on it. There is a header section that expands when clicked to reveal additional content.

The project manager and project sponsors have always referred to them as a "header dropdown" as from their perspective that's what it is; the header "drops down" when clicked.

With misnomers there are several states of understanding:

1. The misnomer is accepted as being factually _correct_ and not questioned. This often occurs on projects where the beginning of the project starts with substantial planning from non-technical team members or those with less domain knowledge.
2. The misnomer is known to be factually _incorrect_ but the person understands the context and sees no reason to correct the misnomer or hold a discussion about it. Using our example misnomer, a developer may start working on the project and as there is no other way to implement the required functionality (it is not achievable via an actual "drop down" element) there really is only one possible thing it can be _right now_ - an expandable, so why waste everyone's time holding a conversation about it?
3. The misnomer is understood to be factually _incorrect_. The person feels it is necessary to correct the originator of the misnomer with their own understanding of the misnomer. OK so let's say a tester joins the project and decides that in order to make sure everyone is using the correct terminology and avoid any ambiguity the current "header dropdown" misnomer should be corrected. This will ensure that any future functionality that may be added to the header is not confused with the misnomer, say for example a "language" drop-down is added. There is no room for discussion here; it **must** be corrected.
4. The misnomer is known to be factually _incorrect_. A conversation takes place with the project facilitator to gauge any potential risk associated with the misnomer. An agreement is reached whereby the most efficient solution is implemented for the misnomer. Using our example let's say the tester joins but instead of taking a "must have" approach they explain to the project facilitator that there are ambiguity risks with using the terminology but that those risks may be extremely low depending on the development plan for the project. For example, if there will never be anything added to the header of the site that resembles a drop-down then referring to the expandable as a "dropdown" will have little impact. The project manager explains that once the site development is complete it will be handed over to a 3rd party and there will be no maintenance period and no future development on the project for the development team. The project is also only a 3-month project and there are no team member changes planned that could cause confusion with terminology. The "header dropdown" misnomer is then deemed to be unimportant and everyone is happy to use the misnomer rather than set about re-educating the team.

Inadvertent use of misnomers allows quicker communication in groups where there is a joint understanding of the domain being discussed and the context of the misnomer itself by **all** parties but herein lies the risk of not correcting or discussing a misnomer; there is an inevitable **assumption** that everyone has similar domain knowledge and understands the terminology used equally, hence there is no need to discuss or correct it.

Using terminology or descriptions which are even slightly ambiguous to those with different domain knowledge can create issues though.

From my perspective what we need to strive for is the establishment of a common "language" on projects that allow the participants the ability to discuss things in the most efficient manner possible adding as little ambiguity into the discussion as possible, not to pick apart people's differing descriptions of the same thing.

I test software. I perform a quality analysis. If you say I am "QA'ing" your software and I understand the task to be "testing" the software then there's little value in me trying to redefine your vocabulary or use of the English language. If anything it will make everything even less efficient as there will be a period of readjustment before the new vocabulary is "normal" in day-to-day work.

The approach I normally take is to reiterate the required task using the correct terminology, for example:

"We've added Search functionality to the header dropdown on the staging environment. Can you exploratory test it this morning please?"

"Oh cool, yep absolutely! Exploratory test the Search function in the expandable header - got it. I'll start right after this test session and feedback as soon as possible."

Now having said all if the above I do think there's a huge benefit in establishing a common vocabulary within an industry or community where our "domain" is the industry itself. But that's a whole new blog post! 😉
