---
layout: page
title: About
permalink: /about/
---

<!-- Considerations for this post:
What is this site about?
Why does this site exist?
Who are you?
  What are your goals?
  What are your instruments?-->

_This page exists as an attempt to communicate the scope of this site's content, along with what I hope to get out of this site; additionally, I provide some information about myself, mostly pertaining to my interests_.

### This Site

This site came into being late into the year 2021, in response to my desire for a place to concentrate and publicize my thinking on various, mostly technologically oriented subjects. There are other excuses for the site's existence as well; most notably, that having it might result in me writing more, and might improve my writing (and my thinking!), and less notably but still important to me, that it could serve as personal collection of resources, such as links and research findings.

__Motivation__

Since the year 2018, I've been exposed to the [Rationality](https://www.overcomingbias.com/) and [Effective Altruism](https://www.effectivealtruism.org/) movements, and in being exposed to these, have had the pleasure in life to come across the writing of ([Scott Alexander](https://www.lesswrong.com/users/scottalexander) & [Gwern Branwen](https://www.lesswrong.com/users/gwern)) and ([Alexey Guzey](https://www.lesswrong.com/users/guzey) & [Neel Nanda](https://www.lesswrong.com/users/neel-nanda-1)), among others (the first group being much more influential on my thinking than the second). These people's websites - [Astral Codex Ten](https://astralcodexten.substack.com/) (ACX), [Slate State Codex](https://slatestarcodex.com/) (SSC), [Gwern.net](https://www.gwern.net/), [Guzey.com](https://guzey.com/), [Neelnanda.io](https://www.neelnanda.io/) - have been a major motivation for me creating this site, partly because they examine many of things I find interesting, such as forecasting, technological development, life optimization, and the future of humanity.

__Tags and Content__

We'll see what happens over time, but currently I expect the scope of content on this site to cover, generally, topics connecting to the future of human civilization. This categorization is pretty vague, and leaves out a lot of the content I intend to write, but I think it is one that captures my inclination to explore [futurist](https://en.wikipedia.org/wiki/Futures_studies) and [transhumanist](https://en.wikipedia.org/wiki/Transhumanism) thinking. It is a safe bet to assume that topics I investigate on this site will also be engaged with on at least one of [[LessWrong](https://www.lesswrong.com/), [EA-Forum](https://forum.effectivealtruism.org/), [ACX](https://astralcodexten.substack.com/)]. My unofficial writing directive is "write about interesting and/or consequential things, accurately and thoroughly, and in a manner that others can easily understand and get use out of".

&emsp; I employ tags to sort my posts, but usually find that it's difficult to determine whether a particular tag I've made is useful or could be subsumed by another take. An example of this internal debate are the _forecasting_ and _prediction_ tags: my intention is to communicate with _forecasting_ that the post involves the process of forecasting, and with _prediction_, that the post includes a specific prediction. Should these two tags simply be the single tag _forecasting_? My tags are loosely influenced by [LessWrong's concepts](https://www.lesswrong.com/tags/all) and the [EA-Forum Wiki](https://forum.effectivealtruism.org/tags/all), along with [Steve Hsu](https://twitter.com/hsu_steve)s' [Information Processing](https://infoproc.blogspot.com/2021/07/polygenic-embryo-screening-comments-on.html). These are all my tags that are currently in use:

{% capture temptags %}
  {% for tag in site.tags %}
    #{{ tag[0] }}#
  {% endfor %}
{% endcapture %}
{% assign sortedtemptags = temptags | split:' ' | sort_natural %}
<ul>
{% for temptag in sortedtemptags %}
  {% assign tagitems = temptag | split: '#' %}
  {% capture tagname %}{{ tagitems[1] }}{% endcapture %}
  {% assign words = tagname | split: '-' %}
  {% capture titlecase %}
  {% for word in words %}
    {% if word.size <= 3 %}
      {{ word | upcase }}
    {% else %}
    {{ word | capitalize }}
    {% endif %}
  {% endfor %}{% endcapture %}
   <li style="display: inline-block; margin-right: 20px"><a href="/tag/{{ tagname }}"><em> {{ titlecase }} </em></a></li>
{% endfor %}
</ul>

&emsp; The infrastructure of expression consists of literature reviews, which aim to thoroughly examine a question, topic, or idea (these will likely be the longest posts); reviews, which also aim to examine a question, topic, or idea, but less thoroughly than in a literature review, as I find this content less interesting or less pressing; notes, which is a general category covering book, research paper, and online article summaries and notes; tutorials and examples; and research I've done. I'm fairly certain that this partition of content will change in the future; my goal with any partitioning is to help concentrate my writing, and to prevent myself from spending more time than I should researching something (maximize increasing or constant returns, minimize [diminishing returns](https://en.wikipedia.org/wiki/Diminishing_returns)). Beyond this, I also include forecasts I've made, challenges or contests I've participated in, and content I've written for other sites. I expect my content to not adhere precisely these categories, and with this sentiment, it might be more accurate to reimagine the earlier part of this paragraph as a statement for what form of content I would like to publish on my site.

__Status, Certainty, Importance, and Impact Metrics__

I really, really appreciate Gwern's use of status, importance, and certainty tags on his website, and I've decided to use them as well on this site, though not in the exact fashion as Gwern. Along with Gwern's three metrics, I also use an impact metric. With the status metric, I want to convey what the state of my writing is; the certainty metric, how accurate or reliable what I've written or presented is; the importance metric, how relevant or consequential the topic of a post might be now and in the future; the impact metric, how influential the post I've written is or might be.

&emsp; Not all of my posts use all of the metrics, but every post has a _Page Epistemics_ section that details my metric choices for that post, including reasons for why I believe any metrics shouldn't apply to it. It's also worth noting explicitly that my subjective estimates for the value of these metrics might be far off from what you think the values should be, and to this I say that my estimates are simply one more piece of information for you to form a judgement about how much you should trust my writing and the content I cover, and that my estimates are crude; on this last point, I'm not sure how best to measure "status", "certainty" (accuracy), "importance", and "impact". I've thought, for a short amount of time, about connecting these metrics to external metrics such as number of page views, number of external references, web traffic, etc... and ranking my posts this way, but the cost of doing this seems too high at the moment, and I am not _too concerned_ about my subjective estimates of these metrics being really wrong or being really consequential. More thoughts on these metrics can be found in my post [Some Epistemical Considerations for This Site]().  

### Me

It is usually a straightforward process for people to form judgements of others, so I provide you with some discriminatory characteristics; these come from my memory of demographics surveys I've answered and from things that come to mind when I think of myself.

__Discriminating Characteristics__

I used Python's ```random.shuffle()``` 1 time on the bullet points below (the points were originally ordered differently; I'm unsure as to why I don't want people knowing the original order that these bullets came to my mind). Also, note that ~Y (x%) means "I am x% confident that approximately Y applies to me" and that ~x% means "I believe I am x%".

- Suspected Weight: ~160 lbs / ~72.6 kg (80%)
- Tribes: Effective Altruism movement,  Rationality movement
- Race: Caucasian
- Gender Identity: ~60% heterosexual  
- Disabilities or Cognitive Abnormalities: None diagnosed
- Favorite Nourishment: dark chocolate, almonds, coffee
- Suspected IQ: ~110 (65%)
- Education: B.A. Neuroscience and Mathematics
- Suspected Cognitive Abnormalities: low empathy (75%), mild autism (60%), some attention deficit (60%)
- Age: 20-30 years
- Predominant Life Location: United States

&emsp; This list could be much longer, but I am content to leave it be for the time being. Ideally, 'rodeo flagellum' or 'cirrostratus whispers' is not directly identified with my person. I am a proponent for online anonymity and privacy, but I don't allocate much effort to this beyond using FireFox with privacy extensions, and occasionally using Tor. I have not thought much about what metadata I generate by participating online, and about whether I should take measures to limit how much data I generate.  

__Interests__

While many of my interests can be gleaned from the tags I've listed earlier, there are also less well defined topics that I want to include here. These topics are things I want to learn more about and believe might be promising areas to work on; I do not yet have a _raison d'être_, but would like to find one. There's still great uncertainty on my end, but deep learning for forecasting or data analysis for longevity research might be the fields of study I begin, overwhelmingly, to allocate my time to. Justifications for my interests precede the areas of research and progress I find interesting. There is a lot of overlap between the justifications and interests areas not included under them and between interest areas - this list just serves as a rough blueprint for where my attention goes.

- I don't like when people suffer or die &rarr; _longevity research, measurement of well-being, global health and development_
- I want to know what might happen in my own life, and with humanity &rarr; _judegemental forecasting, quantitative modeling, machine/deep learning_
- I want to live long and be healthy &rarr; _nutrition, health, psychology_
- I want to make good decisions and be less wrong &rarr; _rationality, decision theory, bayesian inference_
- I want humanity to continue existing and to realize new modes of being &rarr; _global catastrophic risk reduction, global priorities research, civilizational stability, human enhancement_
- I want to hasten progress &rarr; _progress studies, superintelligence, meta-science_
- I want to understand how minds and life works &rarr; _neuroscience, origins of life research, biotechnology_
- I want my children to intelligent, kind, and well-off generally &rarr; _embryo selection, polygenic screening, genetic-engineering_

__Personality__

Following Gwern's example, I've taken a slew of personality and morals surveys on the  website [YourMorals.org](https://yourmorals.org/), whose contributors perform social psychology research. I have an entire post on this called [My Personality and Morals](https://rodeoflagellum.github.io/my_personality_morals/), but will summarize the findings below.

__Contact__

Either email: rodeo.flagellum@gmail.com or Discord: rodeo_flagellum#5395 works.
