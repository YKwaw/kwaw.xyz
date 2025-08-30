---
title: "Design Review Checklist"
date: 2025-08-24
Description: "How to conduct a design review as a product manager"
categories: ["Product Management Handbook"]
tags: ["product managment"]
url: /design-review/
---
This is an attempt to codify the things that I consider during a design review. This list is by no means prescriptive, but will hopefully act as a useful guide to someone. Or at the very least myself.

There are 3 key areas that should be considered when reviewing designs for new features:

* Customer Need
* The Big Picture
* Development Readiness

I'm going to go through each in turn, and highlight some of the questions that I like to ask myself.

## Customer Need

At the end of the day we are building functionality for people to use. So these people, our customers, should be at the forefront of our minds when reviewing designs.

1. Is the core use case clear and obvious?
2. Can the user easily achieve their desired outcomes?
	1. Are fields clearly marked?
	2. Is the copy good?
3. Is the core use case as simple as it could be?
4. Can the user self teach use of the functionality, or will they need some guidance?
	1. Depending on the feature and the sector you work in needing some guidance may not be a deal breaker
5. Do we effectively help the user when things go wrong or they make a mistake?

## The Big Picture

Features don't exist in isolation. They are generally going to slot in to an existing product. Therefore we should consider:

1. Have we used existing design patterns or have we reinvented the wheel?
2. Is the look and feel in keeping with the rest of the platform (app, website etc.)?
3. Are the language and terms used in line with the app in general?
4. Have you considered how a users will access this feature from the wider app, and to leave it when they have done their work?
5. Sense check: do we actually need to build this? Is there a simpler option?
	1. Building something comes with the implicit promise that it will be maintained going forward. You should not enter into this lightly.

## Ready to develop?

The ideas and outputs of a designer don't always map 1:1 with that of the person that will be building the feature. The developer. So it's good to to think with your developer had on, and identify some of the things that they'll need to know:

1. What should the loading states look like?
2. What should the error states look like?
3. Are we going to be able to reuse existing components?
	1. It's very easy to make superficial/unnecessary tweaks in design that could increase development time/effort for little benefit


It's always helpful to get a developer in the mix as early as possible to help you consider some things as well. So they can help you interrogate:

1. Data requirements
	1. Do we have the relevant data available to us?
	2. Are there already APIs that supply this data to the front end?
	3. Are there elements of the design that are "nice to have" but have the most onerous data requirements?
		1. Should probably descope - or consider for a v2
2. Interactions
	1. Are there any cool new integrations that have been introduced that would be challenging to develop?
3. Permissions
	1. Have we thought about which users can use this functionality?
	2. Does this have any bearing on the design?



{{< alert info >}}
*Developers tend to be on the cautious side. Pointing out all of the things that will be challenging/take time. So be wary of not diluting your feature too much. The customer need still comes first. But there are often things that are "cool additions" in the design phase, that no one is really wedded to, that can be a real development headache. Doing this exercise with a developer is an attempt to spot this areas, and ultimately get a feature out to users sooner.*
{{< /alert >}}

---

That's it for now. I may update at a later date if I change my process or want to add something.