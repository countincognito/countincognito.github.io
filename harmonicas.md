---
title: "Harmonicas"
type: pages
---
Here beginneth the harmonica pages.

My aim here is to give as much advice I can to budding harp players ("harp" being a vernacular for "harmonica" within the relavent circles) simply because I had to teach myself how to play, and I know how difficult it can be for people who sincerely want to learn. For a few short anecdotes and reading tips you can read [my own personal introduction]({% link _harmonicas/01-introduction.md %}).

Initially I thought I might be able to write my own set of harmonica lessons, but I am not a professional music teacher and, since I have not got that much time to dedicate to my website, I did not want to do the job half-heartedly. Plus there are other sites that offer more general advice and guidence than I could ever provide by myself.

So instead I decided the best thing to do was to find out which sites give the best advice, and concentrate on writing about a select few aspects of harmonica music that are very difficult and (hence) rarely talked about: namely [harmonica theory and positions]({% link _harmonicas/02-theory.md %}). I have also provided a [page displaying the main scales]({% link _harmonicas/12-scale-charts.md %}) used by harmonica players, and [list of resources]({% link _harmonicas/13-resources.md %}) that I found most useful when I was teaching myself to play.

N.B. This tutorial is written specifically for the diatonic/blues variety of harmonica, i.e. the small ones with ten holes. However, there is plenty of theory that is also applicable to all the other styles of harmonica playing.

If you already know a little about music theory, then you will probably get through the early stages relatively quickly. But be warned that there may be some aspects with which you are not totally familiar.

If you have any suggestions for how this tutorial could be improved, please feel free to leave a comment and I will do my best to follow it up.

I hope this helps any budding harmonica players out there. Good luck!

{% assign harmonicas = site.harmonicas | sort: 'order' %}
{% for item in harmonicas %}

* [{{ item.title }}]({{ item.url }})

{% endfor %}