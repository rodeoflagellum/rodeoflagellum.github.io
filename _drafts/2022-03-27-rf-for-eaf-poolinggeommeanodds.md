---
layout: post
title: "Notes on Epistemology"
date: 2022-03-27 15:34:57 -0400
permalink: "/pooling/"
status: "Notes"
tags: [epistemics]
---

## Table of Contents
{:.no_toc}
* TOC
{:toc}

## Summary
_A brief summary of this writing piece, including my ratings of the piece's durability and writing impact._

If you are making or collecting multiple predictions on some phenomenon, and you desire to make an aggregate prediction, then rather than use the arithmetic mean of your predictions, it is more accurate to use the geometric mean of the odds of your predictions.

## Core Ideas and Claims
_Claims, evidence sequences, and ideas I find in the writing as they come along._

- Geometric mean of odds (GMnO) is more accurate than arithmetic mean of probabilities (AMnP), especially when there are extreme predictions.
- AMnP is one way predictions can be aggregated.
- GMnO is another way predictions can be aggregated.
- Academic literature indicates that GMnO robustly outperforms AMnP in terms of Brier Score.
- Prediction "odds" are given by $\frac{p}{1-p}$, where $p$ is a prediction (a probability).
- AMnP is $p = \frac{p_1+\dotsc+p_N}{N}$, where $p_i$ is prediction $i$.
- GMnO is $o = \sqrt[N]{o_1 \times \cdots \times o_N}$, where $o_i$ is the $i$-th prediction odd.
- Extremizing is raising the GMnO (or other aggregated prediction) to a power $a > 1$.
    - Extremizing is useful for when experts are unconfident/uncertain (it is meant to correct underconfidence).
- Some literature points to GMnO being similar to AMnO, but those studies are lack extreme predictions.
- Some literature using simulations support GMnO over AMnO.
- GMnO satisfies external Bayesianity.
- External Bayesianity means that there is expert consensus for each piece of evidence relevant to a prediction, aggregation makes no difference.
- AMnP is less sensitive to extreme predictions.
- The difference between AMnP and GMnP is small oftentimes, but is still important for certain questions.
- The difference between AMnP and GMnP grows as the predictions becomes more extreme.
- An equivalent expression for GMnP is $$p = \frac{\prod^N_{i=1}p_i^{\frac{1}{N}}}{\prod^N_{i=1}p_i^{\frac{1}{N}} + \prod^N_{i=1}(1-pd_i)^{\frac{1}{N}}}$$.


## Practical Statements
_Statements or ideas that are instrumentally valuable to me that arise as a consequence of me reading this piece._

- Use GMnP over AMnP when aggregating predictions.


## All Questions
_Any questions I come with as I read the piece, including contentions._

- Why might pooling forecasts be useful?
    - How should forecasts be pooled?
    - How should extreme values in forecasts be classified?
    - Which natural phenomena are more prone to having extreme values?
    - How informative is a single, aggregate prediction?
    - How does geometric mean of odds (GMnO) outperform arithmetic mean of probabilities (AMnP)?
- When is extremizing an aggregated prediction useful?
- What is external Bayesianity?
    - Why is external Bayesianity relevant to aggregating forecasts?


## Notable Quotes
_Quotes in the piece that I like or that are succinct explanations for phenomena I'm interested in._

    - N/A


## Resources
_Resources such as links, articles, or books that I find as a result of reading this piece._

- How likely is a nuclear exchange between the US and Russia?; <https://forum.effectivealtruism.org/posts/PAYa6on5gJKwAywrF/how-likely-is-a-nuclear-exchange-between-the-us-and-russia>
- Combining multiple probability predictions using a simple logit model; <https://www.sciencedirect.com/science/article/abs/pii/S0169207013001635?subid1=20210831-0347-5383-a803-d0425dbe2b3b&via%3Dihub>
- Combining Probability Forecasts; <https://stat.uw.edu/sites/default/files/files/reports/2008/tr543.pdf>
- Brier Score; <https://en.wikipedia.org/wiki/Brier_score>
- Bayes' rule: Vector form; <https://arbital.com/p/bayes_rule_multiple/>
- A Characterization Theorem for Externally Bayesian Groups; <https://www.jstor.org/stable/2240984>
- Assessing Probability with Multiple Individuals: Group Interaction Versus Mathematical Aggregation; <https://apps.dtic.mil/sti/pdfs/ADA073363.pdf>
- Probability Aggregation Methods in Geoscience; <https://link.springer.com/article/10.1007/s11004-012-9396-3>
- Externally Bayesian Groups; <https://www.rand.org/content/dam/rand/pubs/research_memoranda/2008/RM4141.pdf>
- Two Reasons to Make Aggregated Probability Forecasts More Extreme; <https://faculty.wharton.upenn.edu/wp-content/uploads/2015/07/2015---two-reasons-to-make-aggregated-probability-forecasts_1.pdf>


## To Memorize
_Raw text translations for potential Anki cards to be generated from this piece._

- N/A
