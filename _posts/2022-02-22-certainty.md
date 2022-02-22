---
layout: post
title: Content Certainty, Status, and Impactfulness
permalink: /cert_stat_impact/
certainty: "Somewhat Doubtful"
status: Draft
tags: epistemics
---

_This page exists to describe the metrics "Certainty", "Status", and "Impactfulness" that I use on many of my posts. I provide explanations of these metrics, and offer some justifications for why I include them on posts._

## Certainty 

The _certainty_ metric on each page corresponds to an estimate of my subjective confidence about the accuracy of what I've written. "The accuracy of what I've written" refers to whether distribution of feelings engendered in readers by what I've written matches what I intended to have engendered, to how well the set of all claims in a particular post fit together, to how evidenced my claims are, to how well I evaluate how evidenced my evidence is, to how thorough I am in revealing what my uncertainies are, and, among other things, to how predictive what I've written is.

&emsp; I generated the entries in this list in $< 5$ minutes, so I believe that I am likely missing some important considerations for "content accuracy". At some point, I will likely 1) spend more time researching best-practices for content communication 2) critize my older posts 3) become better at determining the epistemic accuracy of each claim I make, in addition to the entire "message" that my writing conveys. Learning to be less wrong is a journey and, at least thus far, is something that doesn't feel automatic or particularly easy. 

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

## Status 

The website build (I am not sure of what term to use here for what I want to refer to, but basically I am hosting this site on [GitHub pages](https://pages.github.com/) and am using [Jekyll](https://jekyllrb.com/)) I am utilizing permits use of a drafts folder, but this is separate from the status metric I use on my posts.

&emsp; These tags come directly from Gwern's site, although the ones I incorporate are very likely different from his (I currently don't know which categories fall under the Status tag on his website, and can only remember seeing "draft" and "notes" for Status on some posts). This table describes all of the status tags I will use. 

|Status Tag|Explanation|
|:---|:---|
|Log|A post or page that I intend to keep populating with entries. I suspect there'll be some instances where I no longer add to a log.|
|Notes|A post or page that is, for the most part, a collection of notes, quotes, resources, etc... pertaining some topic(s). I suspect that these pages will have the term "Notes" in their title.|
|Rant|A post or page that I am fairly uncertain about in terms of "where it fits in on the site" and that I did not labor much to make structured or accurate. These writing pieces are likely to fall into the category of "flow of consciousness" and help me quickly expose my unexamined feelings or thoughts about a subject. |
|Draft|A post or page that is the start of some piece of writing that I intend to complete at some point. Drafts can vary widely in length and are different from Notes in that I attempt to structure their content.|
|Working Draft | A post or page that could exist on its own, but I believe I am somewhat likely to expand.|
|Likely Finished | A post or page that I somewhat believe I will no longer edit.|
|Finished | A post or page that I strongly believe I will no longer edit.|

<!-- |Update|A post or page that provides major updated perspectives, responses, or beliefs on another post or page on the site, especially if I believe the content of my original writing was largely incorrect. This status may turn into a tag. | -->

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

### Epistemics of This Page

***Status***

"Draft": I expect to make major changes to this page over time, especially given how doubtful I am about it's overall utility. 

***Certainty***

"Somewhat Doubtful": I suspect that a decent number of justifications for my decisions are weak and vague; that there are more efficient means of going about what I want to achieve with these epistemic metrics; and that the scope of the terms "certainty", "status", and "impactfulness" in this post is too large, i.e. the terms are not defined clearly or rigorously. 

***Impactfulness*** 

_Decision Importance_ = 4/10 since I believe that the existence of this page on my site might result in you trusting me more, which I believe might affect the behaviors: [the speed of reading (I expect an increase in this because I believe people read things they agree with more quickly than things they disagree with), number of criticisms (I expect a decrease in this because people often don't critize things they agree with), time spent thinking about content (I expect a decrease in this ) ] 