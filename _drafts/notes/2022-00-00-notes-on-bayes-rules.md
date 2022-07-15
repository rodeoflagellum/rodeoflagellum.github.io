---
layout: post
category: misc
title:  Bayes Rules!
date:  2022-05-02 10:30:18 -0400
last_edit: 2022-05-02 10:34:18 -0400
permalink: "/notes_bayes_rules/"
type: "Notes"
status: "Complete"
durability: "5/5"
desc: "Some notes for myself and friends on the 1st chapter of the book (2021) Bayes Rules! by Alicia A. Johnson, Miles Q. Ott, and Mine Dogucu."
---

General idea:

>
- In the Bayesian philosophy, a probability measures the relative plausibility of an event.
- The frequentist philosophy is so named for its interpretation of probability as the long-run relative frequency of a repeatable event.

The weight prior are given can, of course, change; the general pipeline is for a posterior estimate from prior knowledge and new data.

In relation to answering questions,

>
- A Bayesian hypothesis test seeks to answer: In light of the observed data, what’s the chance that the hypothesis is correct?
- A frequentist hypothesis test seeks to answer: If in fact the hypothesis is incorrect, what’s the chance I’d have observed this, or even more extreme, data?

> In general, __p-values__ measure the chance of having observed data as or more extreme than ours if in fact our original hypothesis is incorrect.

Models are subjective too.

> Our prior knowledge naturally informs what we measure, why we measure it, and how we model it.

Model types for some variable $Y$

- __Beta-Binomial Model__ takes binary categorical $Y$ can produces binary outcome
- __Gamma-Poisson Model__ takes sample counts $Y$ can produces a rate
- __Normal-Normal Model__ takes normally distributed $Y$ can produces average

Note:

> [These models] operate under the assumption of independence. That is, they assume that our data on the response and predictor variables $(Y,X_1,X_2,\dotsc,X_p)$ is a random sample – the observed values for any one subject in the sample are independent of those for any other subject.

Markov Chain Monte Carlo (MCMC) simulations can be used to approximate Bayesian models

Posterior analysis involves: posterior estimation, hypothesis testing, and prediction

Hierarchical models can operate on grouped data (i.e., data that does not satisfy independence)

___Informal Example___: I am applying for a job, and believe I am a decent candidate. If I want to predict whether I get the job, and my hypothesis is that I get it, what are the questions I should use to test my hypothesis, from both a frequentist and a bayesian perspective?[^1]

___Informal Example___: I am somewhat knowledgable about the Cretaceous paleontology of New Jersey. One hypothesis might be that I don't find a plesiosaur vertebrae (partial or whole) my next hunt. I probably have somewhere around 7 vertebrae and probably have gone fossil collecting between 100 and 300 times, so ~200 times, which means my prior probability should be around $\frac{7}{200} = 0.035$. This is a frequentist frame.

[^1]: Frequentist: What is the __long-run relative frequency__ of me getting similar jobs?<br>Bayesian: How __plausible__ is it that I get this job.

Imagine $A$ denotes the event "it rains tomorrow", and $B$ denotes the event "strong winds tonight". Note that if we know $B$ but not $A$, then $P(A\|B)$ refers to _the probability it rains tomorrow, given we know that there are strong winds tonight_.

If we know $A$ but not $B$, then $L(B\|A)$ (the likelihood of $B$ given $A$) refers to _how compatible the knowledge that it rains tomorrow is with the event that there are strong winds tonight._

Pretend the following is true:

| Event | Count | Percent |
| --- | --- | --- |
| Rain Tomorrow ($B$) | 25 | 0.15625 |
| No Rain Tomorrow ($B^c$) | 135 | 0.84375 |
| Total | 160 | 1.0 |

Also, pretend:

| Strong Winds Tonight ($A$) | Rain Tomorrow ($B$) | No Rain Tomorrow ($B^c$) |
| --- | --- | --- |
| FALSE | 15 | 105 |
| TRUE | 10 | 30 |
| Total | 25 | 135 |

> __Probability vs likelihood__
>
When B is known, the conditional probability function $P(\cdot \|B)$ allows us to compare the probabilities of an unknown event, $A$ or $A^c$, occurring with $B$: \\[P(A\|B) \text{ vs } P(A^c \| B)\\]

:

P(A|B) vs P(Ac|B).

When A
is known, the likelihood function L(⋅|A)=P(A|⋅) allows us to evaluate the relative compatibility of data A with events B or Bc

:

L(B|A) vs L(Bc|A).