---
title: "Open Source Licences in Business"
type: pages
---
### This information is for general guidance and is NOT legal advice

I have been a [supporter and advocate of Free/Open Source Software](https://www.gnu.org/thankgnus/2013supporters.html) (FOSS) for as long as I can remember. One aspect in particular that has always fascinated me is how international copyright law has been used as a means to enforce the principles behind FOSS in the form of numerous licences; principles that would normally be the antithesis of what copyright law was originally designed to achieve.

My reasons for wanting to write this tutorial are twofold:

1. To highlight the often under-appreciated fact that FOSS licences are (in and of themselves) a glorious form of 'hack', in [the classical sense of the word](https://en.wikipedia.org/wiki/Hack_(programmer_subculture)); and
1. To help people understand the basics of the most common FOSS licences, and provide a platform from which they can make an concerted effort to abide by the conditions of those licences (with a particular emphasis on their use in business).

Right from the start, I must point out that [I AM NOT A LAWYER](https://en.wikipedia.org/wiki/IANAL), and **none of what is contained in this tutorial should be considered legal advice**. These are purely the opinions of an educated layman with an interest in the machinations of FOSS licensing. If you require formal legal advice on how to make use of FOSS licensing, or how to make proper use of FOSS components and libraries in a specific setting, I suggest you consult an appropriately qualified expert for your jurisdiction.

{% assign os-licences = site.open-source-licences-in-business | sort: 'order' %}
{% for item in os-licences %}

* [{{ item.title }}]({{ item.url }})

{% endfor %}