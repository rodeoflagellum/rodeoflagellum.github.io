---
layout: post
title: Site
date: 2022-02-21 12:00:00 -0400
last_edit: 2022-04-21 12:00:18 -0400
permalink: /site/
status: "Notes"
tags: [epistemics, site, personal]
image: /assets/images/hunting_scene_with_a_harbor_1970.17.103.jpg
desc: "I want what I write to be accurate, measured, honest, and clear (there are more, but these stand out to me). This page describes considerations relevant to most content on the site, and exists as a place for me to brainstorm and refine my writing ideas; this page is a TODO list in some ways."
---

__Disclaimer__: I am in the process of creating the content for this page. More broadly, I am still sorting out how I would like to communicate in writing on this site, what I want to do with it, and what I expect's it place in the greater ecosystem of the Internet to be.

---

## [Table of Contents](#top)
{:.no_toc}
* TOC
{:toc}

---

## Top of Page

For most of my content, I expect the top of the page to have perhaps 2 to 10 labels informing the reader about facets of the post. Many blogs on the Internet do something like this (e.g., Nintil has "(edit date; last-update) (wordcount - reading time) (tags) (Is this article wrong?)" and Gwern has "(summary) (tags) (edit date-last-edit) (status) (confidence) (importance) (backlinks) (bibliography)") and it seems to be a meme that has stuck, which makes sense because it is probably useful to most people (it is useful to me). The line between too many meta-labels and too few is what I am trying to figure out.

&emsp; Presently, I think a 1-3 sentence summary of the post, which maybe could include a reflection on it or my thoughts on "where it stands", seems very useful. Which tags or categories the post covers also seems very useful. Seeing the estimated reading time, word count, readability, and word frequency would be cool, but if I had to choose, I think that only the read-time would be worth retaining.

&emsp; There are some epistemic considerations as well that should be considered: importance, confidence, impact, extent, inadequacies, and status. I will get into these more in depth in some time. Deciding which of these to include in each post is often difficult for me.

&emsp; Next, I would like to see how much my work has been viewed, so a _views_ label (like a button) might be appropriate. Like Gwern, I think bibliographies are nice to have for a post, but I am additionally considering having the labels (page-epistemics) (updates) (disagree?), where (page-epistemics) could be a file with all my considerations for the post, updates could be a file including any minor or major updates to my beliefs about what I posted (perhaps after criticism), and disagree? could be a link to a place to rebuke any claim or argument I make.

### The Art

I enjoy looking at art and pictures; as such, I've incorporated free photos and artwork across most of my posts. There is no theme, and it is often not the case that I spend a long time looking for an artwork appropriate for the topic that I am writing on or learning about.

&emsp; I also enjoy black backgrounds with light text, and would like to eventually have an option on this site for this (night/day theme). Additionally, if people find the pictures distracting, I want eventually to have something that can disable them.

### Informal Tags

I use a system of abbreviations to sort research papers, HTML pages of articles, and books. These abbreviations are by topic, and a single file can have multiple abbreviations - the general format is "abbr1_abb2_abbrN_CondensedTitle_Year.extension". There is some overlap with these abbreviations and the permalinks on this site, but I haven't yet made it formal. In the future, I might make it so posts can be sortable or findable by these informal tags, but for now there's nothing systematic about it. I might list these informal tags in this section at some point, but it's not currently a priority.   

### Formal Tags

Find here the formal tags currently in use on the site.

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

These tags are

#### Specifics

### Status

### Impact

### Confidence

Here are some different kinds of support you might have for a claim:

>
- another detailed analysis you wrote
- careful examination of one or more studies you feel qualified to assess
- careful examination of one or more studies you feel only weakly able to assess
- shallow skimming of one or more studies you feel qualified to assess
- shallow skimming of one or more studies you feel only weakly able to assess
- verifiable facts you can easily provide sources for
- verifiable facts you can’t easily provide sources for
- expert opinion you feel comfortable assessing
- expert opinion you can’t can’t easily assess
- a vague impression you have based on reading various sources, or talking to various experts, or something else
- a general intuition you have about how the world works
- a simple argument that seems robust to you
- a simple argument that seems questionable to you
- a complex argument that nevertheless seems strong to you
- a complex argument that seems questionable to you
- the claim seems to follow logically from other supported claims plus general background knowledge
- a source you can’t remember, except that you remember thinking at the time it was a trustworthy source, and you think it would be easy to verify the claim if one tried4
- a combination of any of the above

### Importance

### Readability

### Durability

### Extent

I would like to convey how much time I've spent reviewing something before writing about it. More generally, I want to convey how experienced I am in the topic I am writing on. "Extent" refers to the extent that I have reviewed some topic. This is an experimental category, which means that I haven't yet committed to or found a system that seems useful or seems to "correct".

One way of breaking this down might be roughly by the amount of Internet querying and thinking I've done.

- My brain (writing it to get it written) (1)
- Internet querying and/or thinking < 5 minutes (2)
- Internet querying and/or thinking < 60 minutes (3)
- 1 to 5, 60 minute Internet querying and/or thinking sessions (4)
- 6 - 15, 60 minute Internet querying and/or thinking sessions (5)
- > 15, 60 minute Internet querying and/or thinking sessions (6)

Another way

### Post-Notes

### Bibliography

### Word Count

### Views

### Inadequacies

### Reading Time

### Contentions

### Enjoyment

---

## After Top of Page

### [Summary](#summary)

### [Takeaways](#takeaways)

### [Epistemic Status](#epistemic-status)

### [Contribution](#contribution)

- Hanson's simple breakdown
(Type: Review, Personal Research Summary,
Summary of Research, Forecast, )

### [Disclaimer](#disclaimer)

General transparency

>
- Has the author presented a fair or biased presentation of evidence and arguments on this topic?
- How much expertise does the author have in this area?
- How trustworthy is the author in general?
- What are their biases and conflicts of interest?
- What was the research process that led to this analysis? What shortcuts were taken?
- What rough level of confidence does the author have in each of their substantive claims?
- What support does the author think they have for each of their substantive claims?
- What does the author think are the most important takeaways, and what could change the author’s mind about those takeaways?
- If the analysis includes some data analysis, how were the data collected, which analyses were done, and can I access the data myself?

### [Glossary](#glossary)

---

## [Content](#content)

### [Preferences](#preferences)

#### [The Problems](#problems)

#### [Forecasting](#forecasting)

### [Typography](#typography)

### [Meta-Science Pipeline](#meta-science)

### [Elicitations](#elicitations)

There are many things that I would like to do more.

#### Opinions

#### Surveys

#### Questions

#### Feedback

I operate by Crocker's Rules (I found this here https://www.alignmentforum.org/users/daniel-kokotajlo)

> Declaring yourself to be operating by "Crocker's Rules" means that other people are allowed to optimize their messages for information, not for being nice to you.  Crocker's Rules means that you have accepted full responsibility for the operation of your own mind - if you're offended, it's your fault.  Anyone is allowed to call you a moron and claim to be doing you a favor.  (Which, in point of fact, they would be.  One of the big problems with this culture is that everyone's afraid to tell you you're wrong, or they think they have to dance around it.)  Two people using Crocker's Rules should be able to communicate all relevant information in the minimum amount of time, without paraphrasing or social formatting.  Obviously, don't declare yourself to be operating by Crocker's Rules unless you have that kind of mental discipline.
>
Note that Crocker's Rules does not mean you can insult people; it means that other people don't have to worry about whether they are insulting you.  Crocker's Rules are a discipline, not a privilege.  Furthermore, taking advantage of Crocker's Rules does not imply reciprocity.  How could it?  Crocker's Rules are something you do for yourself, to maximize information received - not something you grit your teeth over and do as a favor.
>
"Crocker's Rules" are named after Lee Daniel Crocker.

#### Noticing Biases

#### Forecasts

#### Storytelling

#### Visualization

#### Syntheses

#### Experimental Designs

#### Estimates

(esp. fermi estimates)

#### Locating Beliefs and Thoughts

(when conclusions seem obvious to me)
finding beliefs
cached thoughts

#### [Beliefs Updates

bayesian updates of beliefs

#### Inadequacies

#### Missing Pieces

### [Questionings](#questioning)

(questions from paper)

### [Writing Styles and Advice](#writing-style-advice)

### [Future Post Ideas](#future-posts)

### [Storing Things](#storage)

### [Heuristics](#heuristics)

- Aim to outperform Wikipedia
- You are likely not the first person to have come up with this question, or to have started answering it
- Search every question on Google at least once
- Search every concept on Google at least once

### [Bloom's Taxonomy](#bloom)

---

## [Bottom of Page](#bottom)

### [Appendix](#appendix)

### [References](#references)

### [See Also](#see-also)

### [Further Reading](#further-reading)

### [External Links](#external-links)

### [Footnotes](#footnotes)

---

## [Other](#other)

### [Design Feature Wish List](#feature-wish-list)

 - Term glossary
 - Questions
 - Notes
 - Archive
 - Topics
 - Popular posts
 - Internet Archive
 - Gwern's popups
 - Convert to PDF
 - Raw text
 - Image captions
 - Linkchecker
 - Link graphs
 - SPIES tool
 - Time clock
 - Back to top button
 - Night/day themes

### [Me Page](#about-page)

### [Influences](#role-models)

### [Reading List](#reading-list)

### [Clock Page](#clock-page)

### [Site Name](#site-name)

<!-- ## Main Pipeline

Presently, my posts and writing pieces are not well organized, partly because I am still trying to get into the habit of writing often and because I am trying to populate this site with content. I believe that my abilities to "define" a unit of knowledge or to really _feel_ a concept are weak - I find myself struggling often with answering questions such as "how much do I actually know" or "how many nodes of evidence to I need to confidently make a claim". The fogginess that blankets my general understanding of the ways things work, except when I am pressed to produce knowledge in narrow knowledge domains, leads me to find solace in the use of measurement and metrics to characterize things. I want to understand the properties of my writing and of the concepts I write on from a meta-level perspective.

- Think about what I want to write in terms of what I intend to contribute on the topic, both in terms of my own understanding of it and in terms of how it might benefit others -->

My use of the _status_ metric was inspired directly from Gwern's site, although the ones I incorporate are very likey different from his[^1], and it seems pretty intuitive to give some concise description of a post's general degree of completion. This table describes all of the _status_ metrics I employ.

|Status Tag|Explanation|
|:---|:---|
|Log|A post or page that consists almost entirely of an ongoing list. I suspect there'll be instances where I no longer update some logs.|
|Notes|A post or page that is, for the most part, a collection of notes, quotes, resources, etc... pertaining some topic(s). I suspect that these pages will have the term "Notes" in their title.|
|Rant|A post or page that I am fairly uncertain about in terms of "where it fits in on the site" and that I did not labor much to make structured or accurate. These writing pieces are likely to fall into the category of "flow of consciousness", i.e. things that help me quickly expose my unexamined feelings or thoughts about a subject. |
|Draft|A post or page that is the start of some piece of writing that I intend to complete at some point. Drafts can vary widely in length and are different from Notes in that I attempt to structure their content.|
|Working Draft | A post or page that could exist on its own, but I believe I am somewhat likely to expand.|
|Likely Finished | A post or page that I somewhat believe I will no longer edit.|
|Finished | A post or page that I strongly believe I will no longer edit.|

<!-- |Update|A post or page that provides major updated perspectives, responses, or beliefs on another post or page on the site, especially if I believe the content of my original writing was largely incorrect. This status may turn into a tag. | -->

## Certainty

The _certainty_ metric on each page corresponds to an estimate of my subjective confidence about the accuracy of my writing and of the content I am hosting. What does "The accuracy of my writing..." refer to? Okay, in my mind, this is my sense of whether the distribution of feelings and thoughts engendered by reading my content matches what I intended to have engendered, to how well the set of all claims in a particular post are synthesized, to how evidenced my claims are, to how well I evaluate how evidenced my evidence is, to how thorough I am in revealing my uncertainty, and, among other things, to how predictive what I've written is. At some future point, I might prune my writing for examples of each of these things (e.g., this is an evidence claim, this is an un-evidenced claim), but please just know, if you already haven't developed this notion, that my _certainty_ metrics are subjective, and should not be taken as law (e.g., if my certainty is "Quite Certain", this does not mean that my claims are bullet proof! This simply means that I believe my claims are bullet proof; since no one, including myself, has really taken the time to develop a track record of my accuracy, )

&emsp; I generated the entries in this list in $\leq 5$ minutes, so I believe that I am likely missing some important considerations for "content accuracy". At some point, I will likely 1) spend more time researching best-practices for content communication 2) criticize my older posts 3) become better at determining the epistemic accuracy of each claim I make, in addition to the entire "message" that my writing conveys. Learning to be less wrong is a journey and, at least thus far, is something that doesn't feel automatic or particularly easy.

&emsp; With regard to this last entry in my list - "how predictive what I've written is" - the "[Anticipated Experiences](https://www.lesswrong.com/tag/anticipated-experiences)" page on [LessWrong](https://www.lesswrong.com/), especially the post _[Making Beliefs Pay Rent (in Anticipated Experiences)](https://www.lesswrong.com/posts/a7n8GdKiAZRX86T5A/making-beliefs-pay-rent-in-anticipated-experiences)_ by Eliezer Yudkowsky, captures what I want to achieve with the beliefs I express in my writing.

> When you argue a seemingly factual question, always keep in mind which difference of anticipation you are arguing about. If you can’t find the difference of anticipation, you’re probably arguing about labels in your belief network—or even worse, floating beliefs, barnacles on your network.
>
> ...
>
> Above all, don’t ask what to believe—ask what to anticipate. Every question of belief should flow from a question of anticipation, and that question of anticipation should be the center of the inquiry. Every guess of belief should begin by flowing to a specific guess of anticipation, and should continue to pay rent in future anticipations. If a belief turns deadbeat, evict it.

My use of these certainty tags was inspired directly by [Gwern](https://www.gwern.net/About#confidence-tags). I believe the following excerpt from Gwern's website is likely illustrative of his thoughts on confidence tags:

> The “confidence” tag is a little more unusual. I stole the idea from [Muflax’s “epistemic state”](https://www.gwern.net/docs/www/webcitation.org/12f0765625025b91cf4160759f55ec997ab13b1a.html) tags; I use the same meaning for “log” for collections of data or links (“log entries that simply describe what happened without any judgment or reflection”) personal or reflective writing can be tagged “emotional” (“some cluster of ideas that got itself entangled with a complex emotional state, and I needed to externalize it to even look at it; in no way endorsed, but occasionally necessary (similar to fiction)”), and “fiction” needs no explanation (every author has some reason for writing the story or poem they do, but not even they always know whether it is an expression of their deepest fears, desires, history, or simply random thoughts). I drop his other tags in favor of giving my subjective probability using the [“Kesselman List of Estimative Words”](https://www.gwern.net/docs/statistics/bayes/2008-kesselman.pdf)
>
> 1. “certain”
> 2. “highly likely”
> 3. “likely”
> 4. “possible” (my preference over Kesselman’s “Chances a Little Better [or Less]”)
> 5. “unlikely”
> 6. “highly unlikely”
> 7. “remote”
> 8. “impossible”
>
> These are used to express my feeling about how well-supported the essay is, or how likely it is the overall ideas are right. (Of course, an interesting idea may be worth writing about even if very wrong, and even a long shot may be profitable to examine if the potential payoff is large enough.)

After skimming the word tables in the _Kesselman List of Estimative Words_, I chose to use this one, which I found on page 20:

|Verbal Expression|Probability|
|:---|:---|
|Impossible|0.00|
|Small Possibility|0.10|
|Small Chance|0.20|
|Somewhat Doubtful|0.30|
|Possible|0.40|
|Toss-up|0.50|
|Somewhat Likely|0.60|
|Likely|0.70|
|Very Likely|0.80|
|Quite Certain|0.90|
|Certain|1.00|

When I use a particular Verbal Expression in this list for a post of mine, I am saying that the corresponding Probability for that Verbal Expression is what I believe to be a decent estimate the holistic accuracy of my post. For example, if I set the certainty of my post _[Deaths by Synthetic Biological Weapons](https://rodeoflagellum.github.io/synthetic_biological_weapons_deaths/)_ to "Somewhat Likely", I am saying that my forecasts and analyses in the post, along with what evidence I base these things off of, are roughly 60% correct. Across the board, I believe slightly more than half of what I've written is sound.

&emsp; There are many types of posts I make on this site. For some posts, the interpretation of the certainty tag might be more ambiguous, such as with my dreams posts (e.g., _[Dream With Summer Camp Art](https://rodeoflagellum.github.io/summer_camp_art_dream/)_). In such posts, I may not make any claims _about_ something. If there are no claims or beliefs explicated, then my subjective certainty usually pertains to how well I believe I am remembering something. I intend to have, at the end of each post, an explanation of my subjective certainty for that post.

&emsp; I suspect that, as I write more on this website, I will be able to better define what each Verbal Expression means to me. As a closing note to this topic of certainty tags, here are some considerations and questions I generated for my future self to engage with.  

 <!-- but for now, here is an attempt: Impossible - ("I would bet my life on what I've written here being untrue, unobservable, or impossible. Equivalently, I am fully lying to you."); Small Possibility - ("From what I have read, experienced, thought, etc... I really don't think the topic of my writing will  ) -->

- Should your certainty tags correspond to how much you believe "this is suspect" applies to what you've written; to the bets you'd make on the amount of evidence that you or others would find that contradict or invalidate your claims; to what percent of readers will agree with you?
- Should some posts not have the certainty tag?
- How should certainty tags apply to different categories, such as _forecasting_, _dreams_, _lists_, _genetic-engineering_, _reviews_, etc...? How should one interpret "Somewhat doubtful" for a list post versus for a dream post versus for a forecasting post?
- Should you calibrate your certainty by first estimating the certainty, then using a metric (perhaps Bayesian Inference) to quantify the reasonableness of the claims in the post, and then adding a discussion of the difference in the part of your post where you describe how you came to your particular estimatation of certainty for that post?

## Impactfulness

I consider myself an [Effective Altruist](https://www.effectivealtruism.org/), which means to me that I should allocate some cognitive bandwidth towards assessing what impact I make on the world. The term "impact" here is nebulous, but I believe "the impactfulness of my writing content" should refer to some mixture of the following: effects on reader well-being, effects on collective human well-being, effects on reader decision-making (this includes behavior), and effects on preserving long-term human potential. This is not an exhaustive list and, ideally, I would like to come up with some way to measure each of these things, normalize them, and then use them together to create the Impactfulness score.

&emsp; For measuring the impact of the content I generate or host, I could ask: How does this make the reader feel? Will any reader's interests shift towards the topic of my writing? Might this post be hazardous in some manner to humanity's long term potential, or might it result in suffering? How probable is it that this post changes people's behavior, for better or worse? These serve as a first pass at gauging my impact, but I would like to do better, and will likely spend more time in the coming years thinking about what factors to consider when assessing how _consequential_ a post of mine is.

&emsp; At the present moment, I am not familiar with many "impactfulness" scoring rubics, and the only one the comes to mind was from [Eli Lifland's](https://twitter.com/eli_lifland), [yagudin's](https://www.lesswrong.com/users/yagudin), and [sam_atis's](https://www.lesswrong.com/users/sam_atis) LessWrong post _[Impactful Forecasting Prize for forecast writeups on curated Metaculus questions](https://www.lesswrong.com/posts/hTHhiZ9kGEo7r8YRS/impactful-forecasting-prize-for-forecast-writeups-on-curated)_. In this post, they incentivize people to explain their forecasts on a set of Metaculus questions that they scored using the following rubric

|Impact Dimension|Explanation|
|:---|:---|
|Decision importance|The importance of the decisions which will be affected by this question. Should combine cause area importance + importance within cause area.|
|Decision relevance| How much of an impact would this have on actual decisions if the forecast changed by a substantial amount? This factor is re-used from Nuño Sempere’s [An estimate of the value of Metaculus questions](https://forum.effectivealtruism.org/posts/zyfeDfqRyWhamwTiL/an-estimate-of-the-value-of-metaculus-questions)|
|Ease of contribution| ​​How easy will it be for a "median generalist forecaster" to make a contribution to the analysis on this question within a few hours? e.g. questions requiring lots of domain expertise or background reading would score low here.|
|Neglectedness of contributions| How few contributions have there been on this specific question so far? How in need of attention is it? This should be subjectively evaluated using the existing count of forecasts and quantity + quality of comments/writeups.|

They also write

> A curation score was calculated, weighing decision importance at twice the other three due to it feeling like the most important factor. We chose a set of 25 questions based mainly on the curation score, but also including a diversity of cause areas and question types.

Their scoring system is appealing to me, and I expect myself to incorporate it into my writing somehow, at least until I develop a better system for measuring the impact of my posts. Since their measure of impactfulness mostly pertains to Effective Altruism oriented forecasting questions, I have modified the system to be more flexible, particularly for the content I post on this website. I use a 1-10 scale for each of the following entries in the table, and also weigh decision importance twice as much. Instead of summing the weighted scores, I multiply them and then divide by $20 \cdot 10 \cdot 10 \cdot 10 = 20000$ (the maximal impactfulness score) before multplying by 100 to convert this value into a percentage.  

|Impact Dimension|More Flexible Explanation|
|:---|:---|
|Decision importance|The importance of the reader's decisions affected by this post.|
|Decision relevance| If the content on of a post changed substantially, how much would the reader's decisions change, relative to how the reader's decisions before the change? |
|Ease of contribution| ​​How easy will it be for a reader to make a contribution to the analysis on this post?|
|Neglectedness of contributions| How much have people thought about the content in this post? How in need of attention is the content in this post?|

## External Links

[pending]

## Page Epistemics

___Status___

"Draft": I expect to make major changes to this page over time, especially given how doubtful I am about it's overall utility.

___Certainty___


"Somewhat Doubtful": I suspect that a decent number of justifications for my decisions are weak and vague; that there are more efficient means of going about what I want to achieve with these epistemic metrics; and that the scope of the terms "certainty", "status", and "impactfulness" in this post is too large, i.e. the terms are not defined clearly or rigorously.

___Importance___

___Impact___

_Decision Importance_ = 4/10 since I believe that the existence of this page on my site might result in you trusting me more, which I believe might affect the behaviors: [the speed of reading (I expect an increase in this because I believe people read things they agree with more quickly than things they disagree with), number of criticisms (I expect a decrease in this because people often don't critize things they agree with), time spent thinking about content (I expect a decrease in this)]

## [Notes](#notes)

### [Cover Image](#cover-image)

This [cover image](https://www.nga.gov/collection/art-object-page.52247.html) is an American 18th Century oil on canvas artwork entitled _Hunting Scene with a Harbor_, 18th century associated with Bruce, Ailsa Mellon, Mrs.. The image can be found on the [National Gallery of Art](https://www.nga.gov/collection-search-result.html?sortOrder=DEFAULT&artobj_downloadable=Image_download_available&pageNumber=1&lastFacet=artobj_downloadable)'s website, and is in the public domain:
> __Open Access Policy for Images of Works of Art Presumed in the Public Domain__
>
With the launch of NGA Images, the National Gallery of Art implemented an open access policy for digital images of works of art that the Gallery believes to be in the public domain. Images of these works are available free of charge for any use, commercial or non-commercial, under Creative Commons Zero (CC0). Users do not need to contact the National Gallery for authorization to use these images. They are available for download on nga.gov object pages. See Policy Details below for specific instructions and notes for users.

___Footnotes___

[^1]: I currently don't know which categories fall under the Status tag on his website, and can only remember seeing "draft" and "notes" for Status on some posts.


<!-- Comments on Notes  -->
