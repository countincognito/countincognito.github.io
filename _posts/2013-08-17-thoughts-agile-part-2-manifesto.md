---
title: "Thoughts on Agile (Part 2): the Manifesto"
date: 2013-08-17 23:54:00 +0000
categories:
type: posts
---
In my [previous post]({% link _posts/2013-07-27-thoughts-agile-part-1-fear-and-loathing.md %}) I let off a little steam by talking about some of the things that frustrate me about [Agile](https://en.wikipedia.org/wiki/Agile_software_development) (or rather, how many people choose to interpret it). To summarize, one of the ways I see Agile positioning itself is as a shift away from the rigidity of older software development styles, such as [Waterfall](https://en.wikipedia.org/wiki/Waterfall_model). Unfortunately, humans being the dumb animals that we are, the philosophy of Agile also gets used to promote narrow, pre-existing notions of software development, or simply as an excuse to not think ahead (or actively avoid thinking ahead).

For a long time I thought I understood Agile, but later realized that I was making the same mistake of taking it purely at superficial face value. My guess is that this sort of behaviour is a good example of a wide-spread [Dunning-Kruger effect](https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect): since the [Agile Manifesto](https://agilemanifesto.org/) is so short it only requires a minute's concentration for someone to read it through and think they know it, at which point it becomes insanely easy to disregard any new idea or suggestion simply by saying "that's not Agile" or "that's not in the Agile Manifesto". In order to understand how I could get the most out of Agile, I decided to go back to the Manifesto itself and see if I could spot a deeper meaning in the wording.

## The Actual Contents

Here is what the Manifesto actually says:

1. Individuals and interactions over processes and tools
1. Working software over comprehensive documentation
1. Customer collaboration over contract negotiation
1. Responding to change over following a plan

The first thing to notice is that each line is a prioritization statement, simply stating that one thing in particular is more important than another thing. For example, the second line says: "Working software **_over_** comprehensive documentation". Categorically it does **not** say "Working software **_instead of_** comprehensive documentation", and yet I am sure we all know at least one person who was willing to dismiss all four of the right-hand-side attributes because they have followed that interpretation.

Secondly, the word "software" is only mentioned once, and even then it is almost incidental; the second line could just as easily say "Working _products_ over comprehensive documentation" and the meaning would be virtually the same. Finally, there is absolutely no mention in the Manifesto of "estimation", "features", "user stories", "testing" or even "switching the computer on", but that does **not** mean that they cannot be part of the process.

There is a tendency for practitioners to focus overly on what they think Agile is _not_ rather than what they think it is. This leads to processes being stymied and developers becoming disenchanted because they feel that their hands are being constantly tied. The simple fact is that nobody can say whether Agile includes or excludes any one thing in particular, since it is basically a list of recommendations rather than strict diktats (it is meant to be _agile_ after all). 

## Line by Line

Breaking down each line of the Manifesto separately, it quickly becomes clear that the concepts behind Agile are more (substantially more) about business efficiency than they are about software development:

> **Individuals and interactions** _over_ processes and tools

This is about the importance of people and how they work together to achieve success, which could just as easily be applied to any type of business. In other words: having a well-oiled team that can gel and self-organize is more important than having the latest buzzword methodologies or development environments at your disposal. You would be better off with a group of smart, relatable team-players, who can communicate well and solve problems with a pen, a whiteboard and a jug of coffee, than a bunch of socially-immiscible mavericks armed to the teeth with 64-core workstations and Visual Studio 3000 (of course, if you can have the proper tools as well then so much the better).

When it comes to communication efficiency and human engagement, I also see this principle extending beyond the boundaries of the development team itself and encompassing product owners, business analysts, architects, project managers and stakeholders, all of whom are vital cogs in the development lifecycle.

> **Working software** _over_ comprehensive documentation

Obviously the primary goal of software development is to add value by creating a working product or service; without that you are no longer part of a going concern within your company and you run the risk of finding yourself in the unemployment line. So clearly the priority here should be about creating working software. There is little point in documenting something that is half-complete or worse, broken. But, again, this does not mean one should completely dismiss the need for effective documentation (note that it specifically says "_comprehensive_ documentation", not just "documentation"); once you have a working solution you will clearly need a way to communicate how it works to your customers, and there are a number of adequate ways to do this in the early stages other than written pages (e.g. e-Learning, consulting, in-house training, presentations, or even phone calls). Plus, by its very nature, software will change and evolve as requirements inevitably do, and having to go back and rewrite a thick tome of fully covered user instructions whenever new features are added will rapidly lead to resource haemorrhaging.

> **Customer collaboration** _over_ contract negotiation

When I first saw this I asked myself how customer collaboration and contract negotiation could possibly be related, but with a little extra thought I started to get an idea of where it might be coming from. Both are about customer interactions and, by extension, whether we regard our customers as allies or adversaries: contract negotiations are generally competitive (two parties focussing to secure the best individual deal for themselves) while collaborations are generally more convivial (two parties focussing to secure the best deal for everyone).

In an Agile environment, requirements and plans can change every day (sometimes every hour), and a team that works with customers to create the best product in a fluid manner will be maximally efficient when compared to a team that gets bogged down in finickity (and rapidly outdated) procedural details. Does that mean that contracts are unimportant? Absolutely not; all vital cards must be laid out on the table from the start so that both parties know where the boundaries lie, but those battles must be picked carefully so as not to waste time, goodwill or money.

While the wording is specific to (perhaps the most) important types of customer interaction, the general message is sound in its advice: treat customers as partners rather than obstacles, recognize the times when you must be flexible and when you must be firm, and work with them to determine the best solution for everybody.

> **Responding to change** _over_ following a plan

I suspect this line to be the single biggest cause of dissatisfaction with Agile: the perpetuation of the idea that Agile development cannot (or **must** not) follow a plan. Because who really needs a plan anyway? Software is easy to write and easy to change, and if something breaks at 3am on a Sunday then we can just wake up one of the code drones to come and fix it in production. That is what Agile is all about anyway, right? Well, I am glad to say, categorically _no_. But I have met those who think that having any sort of a development plan is nothing short of _anti_-Agile, and that jumping to the keyboard at the merest suggestion of a change in requirements is the only way to do _real_ Agile.

This is obviously an extreme view but it is also a dangerous one: designing and implementing a good project plan is difficult and requires attention, practice and skill, so naturally it would be much easier to dismiss the need for a plan and to not have to worry about any long-term cost to the business. The project is going to exceed its budget and overrun its schedule anyway, so why accept the responsibility for the inevitable failure?

The fact is that any business, regardless of size or shape, requires some form of plan (remember that the key phrase here is "over", not "instead of"). A business without a plan cannot be a going concern, and a business that is not a going concern is dead in the water; you may as well turn off the lights and go home. Plus, anyone who has worked in brownfield software development knows that software is **not** so easy to change (at least not reliably or safely) without some form of planning or consequence management behind it. There is a reason we reserve the term "brownfield" specifically for describing this type of activity: partly as a warning to would-be stakeholders, but also as a recognition that there are additional challenges to be faced when compared to greenfield work. The real question is how best to plan a project and orchestrate for maximum agility, if such a thing is even possible?

## Summary

Agile is not just about responding to change for change's sake. Software requirements are living, evolving creatures that do not stay static for very long, so being able to react efficiently to those changes is a vital facet of development. However, disregarding the need for occasionally stepping back, thinking, asking questions, productive discussion and challenging conventional wisdom is detrimental to the success of a business. Blind and immediate reaction to changing requirements leads to poorly defined features, over-emphasis on rapid output and unsustainable attempts at flexibility. This, in turn, damages long-term efficiency and the ability to manage workable commitments.

The take-home-message of Agile is a series of very simple but effective priorities. The Manifesto itself may have emerged from the software industry, but to me the concepts are more about _business efficiency_ than anything else. Going over the contents in detail, I can picture it applying equally well to any field of business where rapid response to change and logical problem-solving are core requirements. The real question is how best to maximize a team's agility and is it possible to do so in a predictable way, so as to provide sufficient structure to fit into a sustained business strategy? I believe it is possible to plan for this sort of agility, and I believe that the [12 principles behind the Manifesto](https://agilemanifesto.org/principles.html) emphasize this possibility as well. An idea that I will expand upon in [Part 3]({% link _posts/2013-10-19-thoughts-agile-part-3-principles.md %}).

## Other Posts in this Series

* [Thoughts on Agile (Part 1): Fear and Loathing]({% link _posts/2013-07-27-thoughts-agile-part-1-fear-and-loathing.md %})
* [Thoughts on Agile (Part 3): the Principles]({% link _posts/2013-10-19-thoughts-agile-part-3-principles.md %})
