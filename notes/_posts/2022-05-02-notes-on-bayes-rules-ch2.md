---
layout: post
category: misc
title:  Bayes Rules!, Chapter 2
date:  2022-05-02 13:15:18 -0400
last_edit: 2022-05-04 17:30:18 -0400
permalink: "/notes_bayes_rules_ch2/"
type: "Notes"
status: "Complete"
durability: "4/5"
desc: "Some notes for myself and friends on the 2nd chapter of the book (2021) Bayes Rules! by Alicia A. Johnson, Miles Q. Ott, and Mine Dogucu."
---

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

If we want to

> __Probability vs likelihood__
>
When B
is known, the conditional probability function P(⋅|B) allows us to compare the probabilities of an unknown event, A or Ac, occurring with B

:

P(A|B) vs P(Ac|B).

When A
is known, the likelihood function L(⋅|A)=P(A|⋅) allows us to evaluate the relative compatibility of data A with events B or Bc

:

L(B|A) vs L(Bc|A).
