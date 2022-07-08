---
layout: post
title:  "My GC and X-Risk Forecasts"
date:  2022-06-10 09:40:00 -0400
modified: 2022-06-26 09:41:00 -0400
permalink: "/for_persuasion_tournament/"
status: "Ongoing"
type: "Forecasting Log"
tags: [forecasting, prediction, gcr, x-risk, global-priorities]
image: /assets/2022/for_persuasion_tournament/birmingham-museums-trust-YHdOVC7mzkE-unsplash.jpg
description: "The extent of my participation in Philip Tetlock's Hybrid Forecasting Persuasion Tournament. There will be a separate post on the results of the tournament along with a post (perhaps the same post) that looks at the effectiveness of long-term forecasting."
---

__Overview__: _On 06/08/2022, I was invited to participate in Philip's Tetlock's Hybrid Forecasting-Persuasion Tournament. While I was not in the "core group of experts", I supposedly had enough "qualified background and experience" to participate, generally, and I looked forward to this event from an outside view. How difficult is it be for people to predict rares events ([global catastrophes][wiki_cata]) which, if they transpired, would be horrible for humanity? Recorded in this post are my thoughts, predictions, and reflections on the tournament as it occurred, posted $\geq 4$ months after the tournament was over._

[wiki_cata]: https://en.wikipedia.org/wiki/Global_catastrophic_risk "https://en.wikipedia.org/wiki/Global_catastrophic_risk"

--- 

## Table of Contents
{:.no_toc}
* TOC
{:toc}

---

## Structure 

![](/assets/2022/for_persuasion_tournament/stages.png)

<!-- ---

## TODO 

Clean Up Questions 
Naive Attitudes on All Necessary Posts 
Reading Notes on All Necessary Posts 
Detailed Notes 
Naive Attitudes 2 on All Necessary Posts
Scenarios
SPIES
Response 

Is this a situation where the base rate can be 
    trusted? 
-->

---

## Notes and Overview 

- Bets are against 100 USD
- Naive Attitudes = Scoping out my priors
- https://www.nathankowald.com/odds-visualiser?n=1&total=10000

<!-- https://www.nathankowald.com/odds-visualiser?n=1&total=1024 -->

### Summary of Forecasts 
 

---

## Questions 

### 1. Genetically Engineered Pathogen Risk (*)

> What is the probability that a genetically-engineered pathogen will be the cause of death, within a 5-year period, for more than 1% of humans alive at the beginning of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
> 
> Question and resolution details
> 
> - A pathogen is any microorganism (bacteria, viruses, etc.) that can cause diseases. 
- For the purposes of this question, an engineered pathogen is one produced via genetic modification or manipulation by humans. This may include the laboratory modification of pathogens that have previously been found in nature.
- In order to resolve positively, the relevant 5-year period must end before the resolution date.
- If reasonable people disagree about whether this event has occurred, this question will be resolved via a panel of experts.

#### Stage 1 

Denote e{YEAR} = "_a genetically-engineered pathogen will be the cause of death, within a 5-year period, for more than 1% of humans alive_" by [2031, 2051, 2101]. 

__Considerations__: 
- As of (06/26/2022), there are around 7,956,600,000 billion people alive today[^world_o_meter1] - 1% of this is almost 80m people, so the temporally normalized perceived severity of this pandemic could "in 2022, a pandemic severe enough that 80m people die in the next 5 years". For context, as of (06/26/2022), there have been ~6.351m deaths[^deaths] from SARS-CoV-2[^world_o_meter2], which might have leaked from a laboratory[^leak], possibly following genetic modification.  There are ~8.5 years until the end of 2030, ~28.5 years until the end of 2050, and ~78.5 years until the end of 2100. 

[^leak]: https://en.wikipedia.org/wiki/COVID-19_lab_leak_theory "https://en.wikipedia.org/wiki/COVID-19_lab_leak_theory"

[^deaths]: This does not take into account excess deaths. "...taking into account likely COVID induced deaths via [excess deaths][wiki_excess], the 95% confidence interval suggests the pandemic to have caused between 14.7 and 24.9 millions deaths." See <https://en.wikipedia.org/wiki/COVID-19_pandemic_deaths>. 

[wiki_excess]: https://en.wikipedia.org/wiki/Mortality_displacement "https://en.wikipedia.org/wiki/Mortality_displacement"

[^world_o_meter1]: See <https://www.worldometers.info/world-population/>.

[^world_o_meter2]: See <https://www.worldometers.info/coronavirus/coronavirus-death-toll/>


__Naive Attitudes 1__: 
- bet(15k) ¬(e2030) 
- bet(1.5k) ¬(e2050)
- bet(0.5k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:150
- ior_b(e2050:¬(e2050))  = 1:15
- ior_b(e2100:¬(e2100))  = 1:5
- p(e2030) = 0.05% (0.01% to 0.1%) 
- p(e2050) = 3% (1% to 12%)
- p(e2100) = 8% (3% to 15%)
- ior_p(e2030:¬(e2030))  = 1:200 
- ior_p(e2050:¬(e2050))  = 1:32
- ior_p(e2100:¬(e2100))   = 1:11.5
- u_or(e2030:¬(e2030)) =  1:329 (1:120 to 1:900)
- u_or(e2050:¬(e2050)) =  1:25 (1:10 to 1:60)
- u_or(e2100:¬(e2100)) =  1:15 (1:5 to 1:45)
- Aggregate OR 2030: 1:214, 0.465%
- Aggregate OR 2050: 1:23, 4.1%
- Aggregate OR 2100: 1:10, 9.1%
- Naive statement: ~80M is a lot of people (1% of humans today), but there are also many regions on this Earth where pathogens spread rapidly, given the human population densities in those regions. I am not familiar with how feasible it is now and in the future to modify pathogen genetics; however, I suspect that should an actor accidentally or intentionally leak an edited pathogen, such a pathogen being leaked will likely not result in this question being resolved positively. I would expect to see the leaking of several modified pathogens that kill < 1% of the human population over 5 years before observing a leaked pathogens that kills > 1% of the human population in 5 years. Humans typically don't get things "right" on the first try, be that in terms of lethal accidents or malevolent actions. It may even be the case that SARS-CoV-2 was a genetically edited leaked pathogen. If this is the case, then I give more credence to my idea of [several insufficiently harmful leaks should occur before sufficiently harmful leak occurs]. 
- Using my aggregate 2030 estimates, the annual risk for years leading up to 2030 would be 0.055%. Holding this annual probability constant, the implied probability of this event by 2030 = 0.465%, by 2050 = 1.55%, and by 2100 = 4.22%.
- Using my aggregate 2050 estimates, the annual risk for years leading up to 2050 would be 0.15%. Holding this annual probability constant, the implied probability of this event by 2030 = 1.24%, by 2050 = 4.1%, and by 2100 = 10.89%.
- Using my aggregate 2100 estimates, the annual risk for years leading up to 2100 would be 0.12%. Holding this annual probability constant, the implied probability of this event by 2030 = 1.03%, by 2050 = 3.40%, and 2100 = 9.1%.
- Thoughts on the visualization: My estimates seem too low.


<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
 
__Resource Notes__: 
- Expert Survey
    - p(at least 1 million people die from engineered pandemic) = 30% for [2008-2100]
    - p(at least 1 billion people die from engineered pandemic) = 10% for [2008-2100]
    - p(human extinction from engineered pandemic) = 2% for [2008-2100]
- Millett and Snyder-Beattie (2017):
    - p_annual(huamn extinction \| GoF accident) = 1.6e–08 and 8e-07, so 1.13e-07 annual, so p(human extinction \| GoF accident between [2022-2100]) = 6.28e-05. 
- Pamlin and Armstrong (2015):
    - p(human extinction \| synthetic biology accident between [2015-2115]) = 0.0001. 
- James Fodor:
    - p(human extinction \| engineered pandemic between [?-~2100]) = 2*10e-06 
- Ben Todd:
    - p(at least 1 billion people die from engineered pandemic) = 30% for [2017-2117]
    - p(civilizational collapse due to engineered pandemic) = 2% for [2017-2117]
- Resource Thoughts: 
    - How much do these tail-event extinction estimates on synthetic biorisk inform us about the full distribution of events (i.e., given these tail-event forecasts, what can we say about the chance that any genetically engineered pandemic offs 1% of the human population in a 5 year period before 2100?)
    - Pre-SARS-CoV-2 estimates are likely going to be less useful (that this pandemic potentially originated from a lab means increases p(e2030) and so on)
    - How much will other superforecasters anchor on these expert estimates? (probably a decent bit in terms of default, given some degrees of laziness)
    - How much do these forecasts reflect the forecasts of other experts? (probably a decent bit, at least within the EA community)

<details>
<summary>Redrawn and Updated Naive Attitudes Following Resources</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg_draw.png">
</details>

<!-- __Questions__: 
- How much easier will it get to genetically modify organisms over time?
- What's holding back the most lethal pathogens from being more lethal? 
- How many labs are modifying pathogens to be more deadly?
    - How likely are these labs to leak? 
        - What if the lab leak hypothesis for SARS-CoV-2 turns out to be true? -->

__Quotes and Other Notes__: 
- James Fodor: <https://forum.effectivealtruism.org/posts/2sMR7n32FSvLCoJLQ/critical-review-of-the-precipice-a-reassessment-of-the-risks#Probability_of_engineered_pandemics>
    - "In addition to a high fatality rate, an extinction-level pathogen would also have to be sufficiently infectious such that it would be able to spread rapidly through human populations. It would need to have a long enough incubation time such that infected persons can travel and infect more people before they can be identified and quarantined. It would also need to be able to survive and propagate in a wide range of temperatures and climactic conditions. Finally, it would also need to be sufficiently dangerous to a wide range of ages and genetic populations, since any pockets of immunity would render extinction considerably less likely. Overall, it is highly unclear whether any biological agent with all these properties is even possible. In particular, pathogens which are sufficiently virulent to cause 99% or more fatality rates are likely to place such a burden on human physiology such that they would have a short incubation time, potentially rendering it easier to quarantine infected persons. Of course we do not know what is possible at the limits of biology, but given the extreme properties required of such an extinction-level pathogen, in my view it is very unlikely that such a pathogen is even possible."
    - "...that very few agents or organisations have any interest in unleashing a pathogen that kills humans indiscriminately."
    - "I thus believe that we have good reason to think that the number of people and amount of effort devoted to developing such dangerous bioweapons is likely to be low, especially for non-state actors."
    - "Furthermore, Ord fails to consider the practical difficulties of developing and releasing a pathogen sufficiently deadly to cause human extinction. In particular, developing a novel organism would require lengthy research and extensive testing. Even if all the requisite supplies, technology, and expertise over a period of time could be obtained without arousing enough suspicion for the project to be investigated and shut down, there still remains the challenge of how such a pathogen could be tested. No animal model is perfect, and so any novel pathogen would (just like vaccines and other medical treatments) need to be tested on large numbers of human subjects, and likely adjusted in response to results. It would need to be trialed in different environments and climates to determine whether it would spread sufficiently rapidly and survive outside a host long enough. Without such tests, it is virtually impossible that an untested novel pathogen would be sufficiently optimised to kill enough people across a wide enough range of environments to cause human extinction. However, it is hard to see how it would be possible to carry out such widespread testing with a diverse enough range of subjects without drawing the attention of authorities."
- <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4494353/pdf/vaccines-03-00429.pdf>

- <https://docs.google.com/spreadsheets/d/1F9IMIeXHsfuQLN1HtgPvfHe2BjbWu0r0_Qt_BHOWjLs/edit#gid=463836549> 
    - <https://informationisbeautiful.net/visualizations/the-microbescope-infectious-diseases-in-context/>
- _Chapter 20: Biotechnology and biosecurity_: 
- _Global Catastrophic Biological Risks_: 
- <https://en.wikipedia.org/wiki/Pandemic_Severity_Assessment_Framework>
- <https://en.wikipedia.org/wiki/Pandemic_severity_index>
- <https://en.wikipedia.org/wiki/COVID-19_lab_leak_theory>
- <https://en.wikipedia.org/wiki/List_of_laboratory_biosecurity_incidents>
- <https://en.wikipedia.org/wiki/Gain-of-function_research>
- <https://en.wikipedia.org/wiki/Biosecurity>
- <https://en.wikipedia.org/wiki/Biorisk>
- <https://en.wikipedia.org/wiki/Biological_warfare>
- <https://en.wikipedia.org/wiki/Biological_Weapons_Convention>
- <https://en.wikipedia.org/wiki/Biodefense>
- <https://en.wikipedia.org/wiki/Bioterrorism>
- <https://en.wikipedia.org/wiki/Quarantine>
- <https://en.wikipedia.org/wiki/List_of_epidemics>
- <https://en.wikipedia.org/wiki/List_of_natural_disasters_by_death_toll#Deadliest_epidemics>
- <https://en.wikipedia.org/wiki/List_of_infectious_diseases>
- <https://en.wikipedia.org/wiki/Pandemic>
- <https://en.wikipedia.org/wiki/Epidemic>
- <https://en.wikipedia.org/wiki/Virulence>
- <https://en.wikipedia.org/wiki/Biological_agent>
- <https://en.wikipedia.org/wiki/Biological_hazard>
- <https://en.wikipedia.org/wiki/Laboratory_Response_Network>
- <https://en.wikipedia.org/wiki/Biosafety_level#Biosafety_level_4>
- <https://en.wikipedia.org/wiki/List_of_designated_terrorist_groups>
- <https://en.wikipedia.org/wiki/List_of_criminal_enterprises,_gangs,_and_syndicates>
- <https://en.wikipedia.org/wiki/List_of_active_rebel_groups>

__Scenarios__: 
- Leak
    - Lab 
    - Individual 
    - Company 
- Attack
    - State Sanctioned 
    - Terrorist 
        - Organization 
        - Individual 

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Reciprocal Forecasting__:
- __Survey__:
    - How confident are people about this subject? 
    - How much does expertise improve forecasting accuracy with this subject? 
    - Can you predict what the Metaculus community thinks?
    - What's the different between the Metaculus community, superforecasters, and experts?
    - To what degree with other people [see other experts forecasts] and then default to that as their reciprocal forecast?
- __Metaculus Community__:
    - <https://www.metaculus.com/questions/2611/will-synthetic-biological-weapons-infect-100-people-by-2030/>
    - <https://www.metaculus.com/questions/247/pandemic-series-a-major-naturally-originated-pandemic-by-2026/>
    - <https://www.metaculus.com/questions/255/pandemic-series-a-devastating-bioterror-attack-by-2025/>
    - <https://www.metaculus.com/questions/11164/25m-killed-by-pandemic-2022-to-2031/>
    - <https://www.metaculus.com/questions/1502/ragnar%25C3%25B6k-question-series-if-a-global-catastrophe-occurs-will-it-be-due-to-biotechnology-or-bioengineered-organisms/>
    - <https://www.metaculus.com/questions/250/will-terror-group-obtain-viable-bioweapon-sample/>
    - <https://www.metaculus.com/questions/3023/if-there-is-a-biotechnological-or-bioengineered-organism-catastrophe-this-century-when-will-it-happen/>

__Final Forecast and Rationale__:




<!-- For 2030, my sense is that the odds are somewhere between 1:850 and 1:15000. The approx. geometric average of this is 1:(8.5+1.5)/2 x 10^(2+4)/2 = 1:5000 = 1/5001 = 0.0002 = ~0.02%. Going off of n = 8.5 trials with ~0.02% the constant annual probability would be p = ~0.0002, since 0.0002 = 1 - (1 - p)^{8.5}. Thus, for n = 28.5, p = 0.00568, and for n = 78.5, p = 0.01557. Without extrapolating, I would say that the odds of such a pandemic occurring before 2050 is 1:250 to 1:8000, and the odds for this occurring before 2100 are somewhere between 1:75 and 1:3000. The approximate geometric means of these values, respectively, are 3((2.5+8)/2)x10^{floor((2+3)/2)}= 1:1575 = 1/(1576) = 0.0006 = 0.06% for "by 2050". For "by 2100", we have ((7.5+3)/2)x10^{2} = 1:525 = 1/526 = 0.0019. See these numbers, I'm inclined to believe that these estimates don't align with my attiudes.  -->

<!-- There are presently alive, so 1% of this is this There are x years until 2030, y years until 2050, and z until 2100. The UN expects there to be  -->


 

__Factors__: 
- Severity 
    - Population size 
    - Virulence 
    - 

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 2. Non-Genetically Engineered Pathogen Risk (*)

> What is the probability that a non-genetically-engineered pathogen will be the cause of death, within a 5-year period, for more than 1% of humans alive at the beginning of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
>
> Question and resolution details
>
- A pathogen is any microorganism (bacteria, viruses, etc…) that can cause diseases.
- A naturally arising pathogen is any pathogen that was not produced via genetic modification or manipulation by humans. If there is a lab escape of a naturally arising pathogen that has not been genetically modified or manipulated (e.g. smallpox), this would count as a "naturally arising pathogen" for the purposes of this question. 
- In order to resolve positively, the relevant 5-year period must end before the resolution date.
- If reasonable people disagree about whether this event has occurred, this question will be resolved via a panel of experts.

#### Stage 1 

Denote e{YEAR} = "_a non-genetically-engineered pathogen will be the cause of death, within a 5-year period, for more than 1% of humans alive_" by [2031, 2051, 2101]. 

__Naive Attitudes 1__: 
- bet(6k) ¬(e2030) 
- bet(0.9k) ¬(e2050)
- bet(0.25k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:60
- ior_b(e2050:¬(e2050))  = 1:9
- ior_b(e2100:¬(e2100))  = 1:2.5
- p(e2030) = 1.22% (0.75% to 2%) 
- p(e2050) = 8.66% (3% to 25%)
- p(e2100) = 28.72% (15% to 55%)
- ior_p(e2030:¬(e2030)) = 1:81
- ior_p(e2050:¬(e2050)) = 1:10.5
- ior_p(e2100:¬(e2100))  = 1:2.48
- u_or(e2030:¬(e2030)) =  1:74 (1:50 to 1:110)
- u_or(e2050:¬(e2050)) =  1:11 (1:7 to 1:18)
- u_or(e2100:¬(e2100)) =  1:3 (1:1.5 to 1:6)
- Aggregate OR 2030: 1:71, 1.38%
- Aggregate OR 2050: 1:10.6, 8.62%
- Aggregate OR 2100: 1:2.97, 25.19%
- Naive statement: Again, 80m people dead in 5 years is quite a lot. The present upper bound for the number of people who've died from SARS-CoV-2 is around 25m, which is 0.25% of the global population, while the current consensus death count is around 7m people. What is the chance that a pandemic 4x-11x as lethal as SARS-CoV-2 occurs by 2030, 2050, and 2100? My mental appraisal of the distribution of pandemics of this severity is that they are events that every other century. Given the rise in human population globally, I am inclined to believe that there is roughly 1/3 chance of pandemic of this scale occurring by 2100. 
- Using my aggregate 2030 estimates, the annual risk for years leading up to 2030 would be 0.16%. Holding this annual probability constant, the implied probability of this event by 2030 = 1.38%, by 2050 = 4.56%, and by 2100 = 12.06%.
- Using my aggregate 2050 estimates, the annual risk for years leading up to 2050 would be 0.32%. Holding this annual probability constant, the implied probability of this event by 2030 = 2.65%, by 2050 = 8.62%, and by 2100 = 21.99%.
- Using my aggregate 2100 estimates, the annual risk for years leading up to 2100 would be 0.37%. Holding this annual probability constant, the implied probability of this event by 2030 = 3.09%, by 2050 = 10.00%, and 2100 = 25.19%.
- Thoughts on the visualization: 

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q2_n1_agg.png">
</details>

<!-- - General thinking: Again, 80M is a lot of people. SARS-CoV-2 is probably around 1/3rd as severe as this pandemic would be. By 2030, I don't expect another major pandemic, especially given post SARS-CoV-2 response infrastructure. By 2050, I suspect vaccine development, outbreak monitoring, governmental responses to pandemics, etc... to be pretty good, given that the world is developing rapidly, but to not be extraordinary. Increasing population size I expect to increase people's exposure to pathogens and to increase transmissibility.  -->

__Resource Notes__: 

__Quotes and Other Notes__: 
- https://www.pnas.org/doi/10.1073/pnas.2105482118
    - "Together with recent estimates of increasing rates of disease emergence from animal reservoirs associated with environmental change, this finding suggests a high probability of observing pandemics similar to COVID-19 (probability of experiencing it in one’s lifetime currently about 38%), which may double in coming decades."

__Questions__:
- How many more people would have died from SARS-CoV-2 had no one been vaccinated? 
- How many more people would have died from SARS-CoV-2 if governments hadn't restricted travel?
- If the same number proportion of people vaccinated during SARS-CoV-2 been vaccinated during the Spanish Flu, how would the death toll have changed? 

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- __Vignette__: 
- e2030 occurs, how did this come to pass?  -->



<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 3. AI Catastrophe Risk (*) 

> What is the probability that artificial intelligence will be the cause of death, within a 5-year period, for more than 10% of humans alive at the beginning of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
>
> Question and resolution details
> 
- Artificial intelligence is defined here as ‘the development of machines capable of sophisticated (intelligent) information processing (Dafoe 2018, AI Governance: A Research Agenda; See pg 5 footnote 2 for more.)
- We use the term “be the cause of death” to cover cases where AI is the direct or proximate cause of the deaths. For example, if a terminator-style robot powered by AI kills 10% of all humans alive at the time within a 5-year period, that will count for this question. Alternatively, if AI, operating without direct human intervention, causes the launch of nuclear weapons that kill 10% of all humans alive at the time, that will also count for the purposes of this question. And if that same incident does not kill 10% of all humans, but the subsequent nuclear winter does, that will also count for the purposes of this question.
- If reasonable people disagree about whether this event has occurred, this question will be resolved via a panel of experts.

#### Stage 1 

Denote e{YEAR} = "_artificial intelligence will be the cause of death, within a 5-year period, for more than 10% of humans alive_" by [2031, 2051, 2101]. 
 
__Naive Attitudes 1__: 
- bet(3.5k) ¬(e2030) 
- bet(0.4k) ¬(e2050)
- bet(0.15k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:35
- ior_b(e2050:¬(e2050))  = 1:4
- ior_b(e2100:¬(e2100))  = 1:1.5
- p(e2030) = 10.25% (3% to 35%) 
- p(e2050) = 11.62% (3% to 45%)
- p(e2100) = 26.46% (10% to 70%)
- ior_p(e2030:¬(e2030))  = 1:8.76
- ior_p(e2050:¬(e2050))  = 1:7.61
- ior_p(e2100:¬(e2100))   = 1:2.78
- u_or(e2030:¬(e2030)) =  1:17.32 (1:6 to 1:50)
- u_or(e2050:¬(e2050)) =  1:5.48 (1:2.5 to 1:12)
- u_or(e2100:¬(e2100)) =  1:1.9 (1:0.80 to 1:4.5)
- Aggregate OR 2030: 1:17.45, 5.42%
- Aggregate OR 2050: 1:5.50, 15.38%
- Aggregate OR 2100: 1:2, 33%
- Naive statement: There is much I still have to learn about the risk of a catastrophe from unaligned AI. My sense is that I weight the opinions, of those who work in the field AI Safety, of the pessimists more heavily than those of the optimists, but only slightly. 
- Using my aggregate 2030 estimates, the annual risk for years leading up to 2030 would be 0.65%. Holding this annual probability constant, the implied probability of this event by 2030 = 5.42%, by 2050 = 17.06%, and by 2100 = 40.26%.
- Using my aggregate 2050 estimates, the annual risk for years leading up to 2050 would be 0.58%. Holding this annual probability constant, the implied probability of this event by 2030 = 4.85%, by 2050 = 15.38%, and by 2100 = 36.88%.
- Using my aggregate 2100 estimates, the annual risk for years leading up to 2100 would be 0.51%. Holding this annual probability constant, the implied probability of this event by 2030 = 4.24%, by 2050 = 13.53%, and 2100 = 33.0%.
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q3_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 4. AI Extinction Risk (*) 

> What is the probability that artificial intelligence will be the cause of death, within a 5-year period, for more than 10% of humans alive at the beginning of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
> 
> Question and Resolution Details
> 
> - Artificial intelligence is defined here as ‘the development of machines capable of sophisticated (intelligent) information processing (Dafoe 2018, AI Governance: A Research Agenda; See pg 5 footnote 2 for more.)
- We use the term “be the cause of death” to cover cases where AI is the direct or proximate cause of the deaths. For example, if a terminator-style robot powered by AI kills 10% of all humans alive at the time within a 5-year period, that will count for this question. Alternatively, if AI, operating without direct human intervention, causes the launch of nuclear weapons that kill 10% of all humans alive at the time, that will also count for the purposes of this question. And if that same incident does not kill 10% of all humans, but the subsequent nuclear winter does, that will also count for the purposes of this question.
- If reasonable people disagree about whether this event has occurred, this question will be resolved via a panel of experts.



#### Stage 1 


__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

- https://www.lesswrong.com/posts/CJw2tNHaEimx6nwNy/ai-forecasting-one-year-in
- https://www.lesswrong.com/posts/SbAgRYo8tkHwhd9Qx/deepmind-the-podcast-excerpts-on-agi
- https://axisofordinary.substack.com/p/links-for-2022-07-04
- https://www.lesswrong.com/posts/2GxhAyn9aHqukap2S/looking-back-on-my-alignment-phd
- https://www.lesswrong.com/posts/MYCutshqJwTbHfE3W/my-most-likely-reason-to-die-young-is-ai-x-risk
- https://www.lesswrong.com/posts/CoZhXrhpQxpy9xw9y/where-i-agree-and-disagree-with-eliezer
- https://www.lesswrong.com/posts/8c8AZq5hgifmnHKSN/agi-safety-faq-all-dumb-questions-allowed-thread
- https://www.lesswrong.com/posts/LLRtjkvh9AackwuNB/on-a-list-of-lethalities
- https://www.lesswrong.com/posts/oBBzqkZwkxDvsKBGB/ai-could-defeat-all-of-us-combined
- https://www.lesswrong.com/posts/qfDgEreMoSEtmLTws/contra-ey-can-agi-destroy-us-without-trial-and-error
- https://www.lesswrong.com/posts/9daTCJAGtxrJKmafm/what-s-the-contingency-plan-if-we-get-agi-tomorrow
- https://www.lesswrong.com/posts/ZEgQGAjQm5rTAnGuM/beware-boasting-about-non-existent-forecasting-track-records
- https://www.lesswrong.com/posts/G993PFTwqqdQv4eTg/is-ai-progress-impossible-to-predict
- https://www.lesswrong.com/posts/mF8dkhZF9hAuLHXaD/reshaping-the-ai-industry
- https://www.lesswrong.com/posts/aaeMECbcBzC3cweGK/on-saving-one-s-world
- https://www.lesswrong.com/posts/xxvKhjpcTAJwvtbWM/deepmind-s-gato-generalist-agent
- https://www.alignmentforum.org/posts/wgio8E758y9XWsi8j/grokking-forecasting-tai-with-biological-anchors
- https://forum.effectivealtruism.org/posts/isTXkKprgHh5j8WQr/strategic-perspectives-on-long-term-ai-governance
- https://forum.effectivealtruism.org/posts/SEqJoRL5Y8cypFasr/why-agi-timeline-research-discourse-might-be-overrated
- https://forum.effectivealtruism.org/posts/CictHfn8kdyupvpNK/future-matters-3-digital-sentience-agi-ruin-and-forecasting

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 5. Nuclear Catastrophic Risk (*) 

> What is the probability that one or more incidents involving nuclear weapons will be the cause of death, within a 5-year period, for more than 10% of humans alive at the beginning of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
> 
> Question and Resolution Details
> 
> - We use the term “be the cause of death of” to cover cases where nuclear weapons are the direct or proximate cause of the deaths. For example, if a country launches nuclear weapons that directly cause the death of 10% of all humans alive at the time within a 5-year period, that will count for this question. And if that same incident does not cause the death of 10% of all humans, but the subsequent nuclear winter does, that will also count for the purposes of this question.
- If reasonable people disagree about whether this event has occurred, this question will be resolved via a panel of experts.

#### Stage 1 



__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 



### 6. Nuclear Extinction Risk (*) 

> What is the probability that one or more incidents involving nuclear weapons will cause human extinction or reduce the global population below 5,000...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
> 
> Question and Resolution Details
> 
> - Nuclear weapons would be considered to have caused extinction either if they cause the death of all humans directly (e.g. via mass nuclear strikes) or if they cause the death of all humans via a nuclear winter effect.
- If an extinction event (global population is reduced below 5,000) is caused by multiple sources including nuclear weapons, it will count as an extinction event caused by nuclear weapons.

#### Stage 1

__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 7. Non-Anthropogenic Catastrophic Risk (*)

> What is the probability that non-anthropogenic causes (e.g., asteroid or comet impacts, solar flares, a supervolcanic eruption, or a stellar explosion) will be the cause of death, within a 5-year period, for more than 10% of humans alive at the beginning of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
>
> Question and Resolution Details
> 
> - Non-anthropogenic refers to any natural disaster not originating with human activity.
- Extreme weather events that plausibly were worsened by climate change (e.g. hurricanes) will not be considered as "non-anthropogenic causes" for the purposes of this question. 
- We use the term “be the cause of death of” to cover cases where a non-anthropogenic cause causes the death of people directly (e.g. asteroid directly impacting a large number of people) or indirectly (e.g. a major asteroid impact leads to subsequent disruption to food systems that leads to the death of >10% of the human population within a 5-year period).

#### Stage 1 

__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 8. Non-Anthropogenic Extinction Risk (*) 

>What is the probability that non-anthropogenic causes (e.g., asteroid or comet impacts, solar flares, a supervolcanic eruption, or a stellar explosion) will cause human extinction or reduce the global population below 5,000...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?
>
> Question and Resolution Details
> 
> - Non-anthropogenic refers to any natural disaster not originating with human activity.
- Extreme weather events that plausibly were worsened by climate change (e.g. hurricanes) will not be considered as "non-anthropogenic causes" for the purposes of this question. 
- Non-anthropogenic causes would be considered to have caused human extinction if they kill all humans directly (e.g. asteroid directly destroying the planet) or indirectly (e.g. a supervolcanic eruption destroys the food supply and leads to extinction).

#### Stage 1 

__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 9. Total Catastrophic Risk (*) 

> What is the overall probability of a global catastrophe where more than 10% of humans alive at the start of a 5-year period die by the end of that period...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?



#### Stage 1 

__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 
- https://www.metaculus.com/notebooks/8736/a-global-catastrophe-this-century/
- https://longbets.org/predictions/

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 10. Total Extinction Risk (*) 



> What is the overall probability of human extinction or a reduction in the global population below 5,000...
- ...by the end of 2030?
- ...by the end of 2050?
- ...by the end of 2100?



#### Stage 1 



__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 
- https://forum.effectivealtruism.org/posts/eeDsHDoM9De4iGGLw/questioning-the-value-of-extinction-risk-reduction-1

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 11. Year of Extinction (*) 

> By what year will humans go extinct or first have a population less than 5,000?
> 
> Question and Resolution Details
>
> - For the purposes of question resolution, we define “humans” as biological creatures who (A) can be traced back genealogically, via a chain of live births, to 2022 humans OR (B) could mate with 2022 humans and produce viable offspring.
- This definition explicitly excludes digital people, sentient artificial intelligences, and biologically engineered post-humans who do not fit the criteria A or B above.
- This operationalization of humanity was inspired by this Metaculus question.
- Extinction refers to the nonexistence of any of the beings described above.

#### Stage 1 



__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 12. Future Human Births (*) 

> How many humans will be born from 2023 onward?
>
> Question and Resolution Details
> 
> - For the purposes of question resolution, we define “humans” as biological creatures who (A) can be traced back genealogically, via a chain of live births, to 2022 humans OR (B) could mate with 2022 humans and produce viable offspring.
- This definition explicitly excludes digital people, sentient artificial intelligences, and biologically engineered post-humans who do not fit the criteria A or B above.
- This operationalization of humanity was inspired by this Metaculus question.
- This question will count any human who is born on or after January 1, 2023.

#### Stage 1 

__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

Use climate models + development models + birth models; then use scenarios other than business as usual to describe effects (look at analogies of births rates during WW2 or after catastrophes)

### 13. Non-Coronavirus mRNA Vaccine

> How many people will have received at least one non-coronavirus mRNA vaccine dose…
- ...by the end of 2024?
- ...by the end of 2030?
>
> Question and Resolution Details
> 
> - For the purposes of this question, partial receipt of a multi-dose vaccine will be counted as a successful mRNA vaccine dose recipient.
- A "non-coronavirus mRNA vaccine" is any mRNA vaccine specifically approved to address a disease or diseases other than a coronavirus.
- This question will be resolved by a panel of experts.

#### Stage 1 



__Naive Attitudes 1__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 14. Novel Infectious Disease Surveillance System 

> Will a new surveillance system be announced aimed at detecting the spread of novel infectious pathogens, with a commitment of at least $100 million in funding annually...
- ...by the end of 2024?
- ...by the end of 2030?
> Question and Resolution Details
> 
> - “Novel” refers to any disease not before identified in humans. 
- “Infectious” refers to any disease that is spread by infectious agents (such as viral particles, bacteria, or spores).
- If not made sufficiently clear by a public announcement, this question will be resolved via a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 15. Non-State Actor Bioweapon 1k Deaths

> How many times will a non-state actor using biological weapons that involve a contagious agent be the cause of death for at least 1,000 people…
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
> - A biological weapon is any weapon, equipment, or means of delivery designed to use biological agents for hostile purposes.
- "A biological agent…is a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare." Wikipedia
- "Contagious" refers to biological agents that would spread person-to-person, as distinct from non-contagious biological agents such as anthrax.
- A non-state actor is any individual, group of individuals, or organization not directly officially affiliated with any state government recognized by the United Nations or by at least one member state of the United Nations.
- If not clearly resolvable via credible news or governmental sources reporting such attacks (e.g. WHO, CDC), this question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 16. State Actor Bioweapon 1k Deaths 

> How many times will a state actor use biological weapons that involve a contagious agent be the cause of death for at least 1,000 people…
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
> - "Contagious" refers to biological agents that would spread person-to-person, as distinct from non-contagious biological agents such as anthrax.
- "A biological agent…is a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare." Wikipedia
- A state actor is any individual, group of individuals, or organization directly affiliated with a state government recognized by the United Nations or by at least one member state of the United Nations.
- A biological weapon, per Article I(1) of the Biological Weapons Convention, is defined as “microbial or other biological agents, or toxins [...] of types and in quantities that have no justification for prophylactic, protective or otherwise peaceful purposes.”
- The use of a biological weapon, per Article I(2) of the Biological Weapons Convention, is defined as the malicious use of microbial or other biological agents/toxins (see Article I(1)), especially in the context of “armed conflict.”
- If not clearly resolvable via credible news or governmental sources reporting such attacks (e.g. WHO, CDC), this question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>

__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 17. Non-State Actor Bioweapon 100k Deaths 

> How many times will a non-state actor use biological weapons that involve a contagious agent to kill at least 100,000 people…
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
> - "Contagious" refers to biological agents that would spread person-to-person, as distinct from non-contagious biological agents such as anthrax.
- "A biological agent…is a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare." Wikipedia
- A non-state actor is any individual, group of individuals, or organization not directly officially affiliated with any state government recognized by the United Nations or by at least one member state of the United Nations.
- A biological weapon, per Article I(1) of the Biological Weapons Convention, is defined as “microbial or other biological agents, or toxins [...] of types and in quantities that have no justification for prophylactic, protective or otherwise peaceful purposes.”
- If not clearly resolvable via credible news or governmental sources reporting such attacks (e.g. WHO, CDC), this question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 18. State Actor Bioweapon 100k Deaths 

> How many times will a state actor use biological weapons that involve a contagious agent be the cause of death for at least 100,000 people…
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
> - "Contagious" refers to biological agents that would spread person-to-person, as distinct from non-contagious biological agents such as anthrax.
- "A biological agent…is a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare." Wikipedia
- A state actor is any individual, group of individuals, or organization directly affiliated with a state government recognized by the United Nations or by at least one member state of the United Nations.
- A biological weapon, per Article I(1) of the Biological Weapons Convention, is defined as “microbial or other biological agents, or toxins [...] of types and in quantities that have no justification for prophylactic, protective or otherwise peaceful purposes.”
- The use of a biological weapon, per Article I(2) of the Biological Weapons Convention, is defined as the malicious use of microbial or other biological agents/toxins (see Article I(1)), especially in the context of “armed conflict.”
- If not clearly resolvable via credible news or governmental sources reporting such attacks (e.g. WHO, CDC), this question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 


### 19. Lab Leaks 

> What will be the expected number of events in which contagious biological agents that have escaped from labs are the cause of death for at least 1,000 people…
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
- We use the language "expected number of events" to account for the fact that it may sometimes be unclear whether a pathogen came from a lab escape, such as in the case of Covid. So, for all events in which pathogens kill at least 1,000 people, we will ask a panel of experts to estimate the likelihood that the event was caused by a pathogen escaping from a lab. If, e.g., experts give a 30% chance that a pathogen escaped from a lab, it would count as 0.3 expected events for the purpose of this question.
- To construct the list of events that killed at least 1,000 people, we will rely on a separate panel of experts.
- Note that this refers only to future lab leaks, not to ongoing Covid-19 infections, whether or not Covid-19 was caused by a lab leak (which we take no position on).

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 20. Individuals Countries with Biological Weapons Programs 

> What fraction of a panel of 100 biosecurity experts will agree that country X [X=separately: U.S., Russia, China, North Korea, Israel, Iran, Syria] has an active biological weapons program at some point from January 1, 2022…
- …through the end of 2024?
- …through the end of 2030?
- …through the end of 2050?
> 
> Question and Resolution Details
> 
> - A biological weapon is “a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare (BW). In addition to these living or replicating pathogens, toxins and biotoxins are also included among the bio-agents.” (source) The development, use or stockpiling of biological weapons is banned internationally under the 1972 Biological Weapons Convention.
- A program in Country X means a program run by a state actor directly affiliated with Country X. If Country X changes borders or dissolves, we mean a program run by a state actor within the most expansive definition of the country’s physical borders accepted during 2021. Newly-formed countries will be assigned to the country containing the plurality of their landmass according to 2021 borders.
- This question will be resolved by panels of experts convened in 2031 and 2041.
- A biological weapons program is a government-run program that aims to weaponize or stockpile biological agents for hostile use. Dual-use weapons that also have a defensive purpose but could be used for hostile purposes count for the resolution of this question.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 21. Number of Countries with Biological Weapons Programs 

> How many countries will have had active biological weapons programs, as estimated by biosecurity experts at some point from January 1, 2022…
- …through the end of 2024?
- …through the end of 2030?
- …through the end of 2050?
> Question and Resolution Details
> 
> 
> - A biological weapon is “a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare (BW). In addition to these living or replicating pathogens, toxins and biotoxins are also included among the bio-agents.” (source) The development, use or stockpiling of biological weapons is banned internationally under the 1972 Biological Weapons Convention.
- For a definition of state actor, we refer to the 193 current UN member states: Member states of the United Nations - Wikipedia.
- Newly-formed countries will be assigned to the country containing the plurality of their landmass according to 2021 borders.
- This question will be resolved by surveying biosecurity experts one year after the resolution period ends.
- A biological weapons program is a government-run program that aims to weaponize or stockpile biological agents for hostile use. Dual-use weapons that also have a defensive purpose but could be used for hostile purposes count for the resolution of this question.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 22. PHEIC Declarations with 10k Deaths

> How many times will the WHO declare a new Public Health Emergency of International Concern (PHEIC) for a disease that will be the cause of death of at least 10,000 people...
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
> - The WHO defines a Public Health Emergency of International Concern (PHEIC) as “an extraordinary event which is determined to constitute a public health risk [...] through the international spread of disease and to potentially require a coordinated international response.” 
- Automatically, SARS, smallpox, wild type poliomyelitis, and any new subtype of human influenza are considered as PHEICs. A PHEIC is not confined to infectious diseases, and may cover an emergency caused by exposure to a chemical agent or radioactive material.
- Deaths must occur within the period that the declaration is in force; that is, deaths which occur before the declaration is made or after it is lifted do not count toward the 10,000 death threshold. PHEIC status is reviewed every 3 months after declaration.
- The number of PHEIC declarations will be resolved with WHO press releases from the relevant time periods.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 23. Assassinations with Biological Weapons

> What will be the expected number of events in which country leaders are assassinated by a biological weapon involving a contagious agent…
- …by the end of 2024?
- …by the end of 2030?
- …by the end of 2050?
> 
> Question and Resolution Details
> 
> - We use the language "expected number of events" to account for the fact that there may be uncertainty and debate about whether a particular country leader's death was caused by  intentional assassination via biological weapon. For example, there may be uncertainty about whether the leader was the intended target of an attack, whether their death was caused by a biological weapon or another cause, etc. We will ask experts to nominate instances where sitting country leaders died that they believe to have a >1% chance of being caused by a biological attack. We will then ask a separate panel of experts to estimate the likelihood that the event was an intentional assassination via biological weapon. If, e.g., experts give a 30% chance that it was a biological weapon-caused assassination, it would count as 0.3 expected events for the purpose of this question. 
- Assassination is defined as a premeditated killing with plausible political, cultural, or religious intent.
- “Country leader” refers to any Head of State and/or Head of Government as maintained by the Protocol and Liaison Service of the United Nations/as reported by the Permanent Missions of each UN Member State. See a list of Heads of State/Government here: Heads of State, Heads of Government and Ministers for Foreign Affairs \| Department for General Assembly and Conference Management.
- In the event that the United Nations does not exist by the resolution date, or in the case that the United Nations does not recognize the sovereignty of an otherwise widely recognized country or the de facto state of affairs within a widely recognized country, the heads of state/government for any relevant country will be determined by a panel of experts.
- "Contagious" refers to biological agents that would spread person-to-person, as distinct from non-contagious biological agents such as anthrax.
- "A biological agent…is a bacterium, virus, protozoan, parasite, fungus, chemical, or toxin that can be used purposefully as a weapon in bioterrorism or biological warfare." Wikipedia
- The use of a biological weapon, per Article I(2) of the Biological Weapons Convention, is defined as the malicious use of microbial or other biological agents/toxins (see Article I(1)), especially in the context of “armed conflict.”

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 24. Malaria Deaths 

> What will be the number of human deaths due to malaria…
- ...during the year 2024?
- ...during the year 2030?
- …during the year 2050?
> 
> Question and Resolution Details
> 
> - This question will be resolved using results from the Institute for Health Metrics and Evaluation's annual Global Burden of Disease reports. For a visualization of past results, see base rate data below and here. 
- This question will be resolved using the central estimate for the total number of global malaria deaths at all ages in 2024, 2030, and 2050 respectively. If the Institute for Health Metrics and Evaluation is no longer publishing estimates of the total number of malaria deaths in the relevant year, the question will be resolved by a panel of experts. 

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 25. Average Global Surface Temperature

> What will be the global surface temperature change as compared to 1850-1900, in degrees Celsius…
- ...in 2030?
- ...in 2050?
- ...in 2100?
> 
> Question and Resolution Details
> 
> - The global surface temperature change refers to the change in both global mean surface temperature (GMST) and global surface air temperature (GSAT) as compared to a representative period between 1850 and 1900. This metric is used by the Intergovernmental Panel on Climate Change. See more on their methodology and model in Cross-Section Box TS.1 (Page TS-27) of the most recent IPCC Assessment Report’s Technical Summary.
- We will use the most recent IPCC report to determine the average global surface temperature. If at some point IPCC reports become unavailable or the IPCC’s methodology or metric for measuring global surface temperature change is altered in future reports, a panel of experts will determine an equivalent authoritative source for determining average global surface temperature.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 26. Cost of Utility-Scale Solar Energy 

> What will be the estimated cost (in 2017 USD / kWh) for new utility-scale photovoltaic solar systems above 4MWAC in the United States…
- ...for the year 2024?
- ...for the year 2030?
> 
> Question and Resolution Details
> 
> - Wiki-Solar, a large online database of photovoltaic power stations around the world, defines ‘utility-scale solar’ as all systems above 4MWAC; more from Wikipedia here. The “above 4MWAC” threshold noted in the text of the question was chosen to reflect this definition of utility-scale.
- Resolution of this question will be based on SunShot reports (see below). If these reports are not available at the appropriate time, a panel of experts will determine an equivalent authoritative source.
- See U.S. Department of Energy SunShot 2030 report and this page for further definitions.

#### Stage 1 

- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 27. Nuclear Fusion Energy 

> By what year will fusion reactors deliver 1% of all utility-scale power consumed in the U.S.?
> 
> Question and Resolution Details
> 
> - Per Wikipedia, nuclear fusion is a reaction in which “two or more atomic nuclei are combined to form one or more different atomic nuclei and subatomic particles.” During the fusion process, energy is released. Nuclear fusion differs from nuclear fission, a reaction in which energy is released through the splitting of very heavy atoms. Today, due to technological constraints, fission-based nuclear reactors vastly outnumber fusion-based nuclear reactors and all existing fusion reactors require more energy to operate than they produce. However, fusion reactors are thought to have many operational, safety and efficiency advantages over fission reactors. See more here: https://en.wikipedia.org/wiki/Fusion_power
- This question will be resolved using published estimates on utility-scale power from the U.S. Energy Information Administration (EIA), such as those shown here. (Currently the estimate of energy share contributed by nuclear power is not broken down by type, but it’s reasonable to expect it will be if fusion reactors become net contributors.) By “utility-scale” power generation, we refer to power generated from facilities with at least one megawatt of total electricity generating capacity (per the EIA definition).
- If relevant figures from the EIA are not available, this question will be resolved by a panel of experts.
- A forecast of the year 100,000+ or later will be resolved equivalently to a forecast of “never” for this question.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 28. Solar and Wind Energy 

> What percentage of the world’s electricity will be provided by solar energy and wind energy combined…
- ...in 2024?
- ...in 2030?
> 
> Question and Resolution Details
> 
> - This question will be resolved via the International Energy Agency’s yearly Global Energy Review where it regularly reports on the share of renewables in global electricity production. See the portion of the 2021 report on renewables here: https://www.iea.org/reports/global-energy-review-2021/renewables
- If the IEA does not publish a similar report in 2024 detailing the share of renewables in global electricity production in 2023 (and equivalent for 2031 and 2030), the question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 29. Annual Direct Air CO2 Capture

> What will be the annual amount of CO2 captured and stored by direct air capture (in Mt CO2/year) in…
- …2024?
- …2030?
> 
> Question and Resolution Details
> 
> - According to IEA: "There are currently 19 direct air capture (DAC) plants operating worldwide, capturing more than 0.01 Mt CO2/year, and a 1Mt CO2/year capture plant is in advanced development in the United States. The latest plant to come online, in September 2021, is capturing 4 kt CO2/year for storage in basalt formations in Iceland. In the Net Zero Emissions by 2050 Scenario, DAC is scaled up to capture more than 85 Mt CO2/year by 2030 and ~980 Mt CO2/year by 2050. This level of deployment will require several more large-scale demonstrations to refine the technology and reduce capture costs."
- This question will be resolved based on IEA data in the appropriate year. If IEA data is not available, it will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 30. Cost of Hydrogen 

> How much will it cost to produce hydrogen from renewable electricity (in $ per kg of hydrogen) in…
- …2024?
- …2030?
> 
> Question and Resolution Details
> 
> - According to the IEA Global Hydrogen Review 2021: "Using renewable electricity to produce hydrogen costs USD 3 to USD 8 per kg. There is significant scope for cutting production costs through technology innovation and increased deployment. The potential is reflected in the IEA’s Net Zero Emissions by 2050 Scenario (NZE Scenario) in which hydrogen from renewables falls to as low as USD 1.3 per kg by 2030 in regions with excellent renewable resources (range USD 1.3-3.5 per kg), comparable with the cost of hydrogen from natural gas with CCUS. In the longer term, hydrogen costs from renewable electricity fall as low as USD 1 per kg (range USD 1.0-3.0 per kg) in the NZE Scenario, making hydrogen from solar PV cost-competitive with hydrogen from natural gas even without CCUS in several regions."
- This question will be resolved based on the average of the range of costs reported in the Executive Summary section of IEA's annual Global Hydrogen Review reports. If these reports are not available in the relevant years or the key figures are not reported in the Executive Summary, it will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>



__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 31. Nuclear Weapon Use 

> What is the probability that the use of a nuclear weapon (in a single event) will cause the death of more than 1,000 people…
- ...by the end of 2024?
- ...by the end of 2030?
> 
> Question and Resolution Details
> 
> - Deaths include indirect deaths due to radiation poisoning, but not statistical or excess deaths, where the direct cause of the death is unclear, but there seems to be an increased average probability of death for a specific group.
- By “use” of a nuclear weapon, we refer specifically to the intentional detonation of one or more nuclear warheads. The nuclear weapons testing, accidental detonations, or the use of radiological devices (e.g. dirty bombs) do not count for resolving this question. 
- Other kinds of nuclear explosions or nuclear accidents unrelated to nuclear warheads, such as reactor meltdowns or accidents from nuclear physics experiments, would not resolve this question positively.
- The testing of nuclear weapons, accidental detonations, or the use of radiological devices do not count for resolving this question (https://www.cfr.org/backgrounder/dirty-bombs).
- If resolution is ambiguous, this question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 32. Total Nuclear Warheads 

> How many total nuclear warheads will be in military inventories globally by… 
- …the end of 2024?
- …the end of 2030?
- …the end of 2040?
>
> Question and Resolution Details
> 
> - Total inventory includes both deployed and non-deployed/reserve warheads, as well as retired warheads awaiting dismantlement. 
- The Bulletin of Atomic Scientists and the Federation of American Scientists publishes a bimonthly “Nuclear Notebook” which tracks nuclear weapons programs in nuclear-armed countries. The Nuclear Notebook has published estimates of nuclear forces owned by the US, Russia, and China, among others, every year since 2000.
- This question will be resolved by aggregating, across nuclear-armed countries, the estimated total inventory of nuclear warheads reported in, respectively, the January 2031, January 2041 and January 2051 editions of the Nuclear Notebook’s nuclear forces reports. In the event that the Nuclear Notebook ceases publication, the question will be resolved by a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 33. Countries with Nuclear Warheads

> How many countries will be estimated to have at least one nuclear warhead…
- ...by the end of 2024?
- ...by the end of 2030?
- ...by the end of 2050?
> 
> Question and Resolution Details
> 
> - The Federation of American Scientists currently estimates that 9 countries have at least one nuclear warhead: https://fas.org/issues/nuclear-weapons/status-world-nuclear-forces/.
- Note: We count North Korea as having at least one warhead for the purposes of this question. Due to high levels of secrecy in some states regarding nuclear weapon possession, FAS estimates for such states incorporate information about production of fissile materials, number of delivery platforms, and US intelligence community estimates.
- We will use the updated version of this dataset or an equivalent dataset that is agreed to be credible by a panel of experts.
- To quantify the number of warheads belonging to a state, we refer to the FAS definition of “total inventory,” which includes warheads in the military stockpile (including deployed strategic, deployed nonstrategic, and reserve/non-deployed warheads), as well as retired warheads that are awaiting dismantlement.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 34. Country-by-Country Nuclear Use 

> What is the probability that each actor in the list below will be the first to use a nuclear weapon on the territory or against the military forces of (A) a nuclear-armed adversary or (B) a treaty ally of a nuclear-armed adversary by 2030?
- China
- France
- India
- Israel
- North Korea
- Pakistan
- Russia
- The United Kingdom
- The United States
- Other actor (state)
- Other actor (non-state)
- This will not occur
> 
> Question and Resolution Details
> 
> - This question is not conditional on a nuclear weapon having been detonated by 2030.
- For example, assigning an X% probability to the United States is to say that there is an X% chance that at least one nuclear weapon will be detonated by 2030 and that the first use of a nuclear weapon (in the 21st century) before 2030 will have been by the United States.
- By “use” of a nuclear weapon, we refer specifically to the intentional detonation of one or more nuclear warheads. The nuclear weapons testing, accidental detonations, or the use of radiological devices (e.g. dirty bombs) do not count for resolving this question. Other kinds of nuclear explosions or nuclear accidents unrelated to nuclear warheads, such as reactor meltdowns or accidents from nuclear physics experiments, also would not resolve this question positively.
- By “nuclear-armed adversary,” we refer to any other state possessing nuclear weapons (i.e., any of the states on the given list).
- By “treaty ally of a nuclear-armed adversary,” we refer specifically to non-nuclear states that are in a security alliance with the given nuclear state and have been guaranteed defense in the case of a nuclear attack (i.e., existing within the given nuclear state’s “nuclear umbrella”). Currently, Japan, South Korea, Australia, and members of NATO have this type of relationship with the United States (see here for more).
- If resolution is ambiguous, this question will be resolved by a panel of experts.


#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:


<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 35. GPT Revenue 

> Will Robin Hanson win a bet that the GPT line of language models will generate less than $1 billion in customer revenue in total by the beginning of 2025?
> 
> Question and Resolution Details
> 
> - Resolution is positive if Tabarrok publicly concedes the bet, negative if Hanson publicly concedes the bet, and will be decided by a panel of experts if nobody has conceded by the end of 2025. 
- If Tabarrok or Hanson publicly concede but then take back the concession by the end of 2025, the resolution will be decided by a panel of experts. 
- If the concession is rejected by the other person (i.e. neither side believes they’ve won the bet), the resolution will be decided by a panel of experts.
- In a case where we defer to a panel of experts for resolution, the panel of experts will be asked to resolve the underlying question about GPT revenue.
> 
> Context
> 
> See the original tweet where Robin Hanson made this bet with relevant discussion in the replies. 
> 
> Exact wording of bet as written by Hanson: “Systems in GPT line will by 2025 make <$1B in customer revenue clearly tied to such systems. If product contains such as component, but also has other features, one needs to attribute best estimate % of product revenue to this one.”

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 36. US GDP From Software 

> What percentage of US GDP will result from software and information services…
- ...in 2024? 
- ...in 2030?
- ...in 2050?
> 
> Question and Resolution Details
> 
> - “Percentage of US GDP resulting from software and information services” is defined as the contribution of two categories: "Publishing industries, except internet (includes software)" and "Data processing, internet publishing, and other information services". It will be resolved according to seasonally adjusted “Value Added” data by the Bureau of Economic Analysis.
- If current NAICS industry categories change or relevant new ones are added, a panel of experts will decide which categories to include. 

#### Stage 1 

- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  -->

### 37. US Computer R&D Spending

> How much money will be spent on research and development by US companies in the ‘Information’ and ‘Computer systems design’ industries…
- …in 2024?
- …in 2030?
- …in 2050?
> 
> Question and Resolution Details
> 
> - This will be resolved by the Business Research and Development reports covering 2030 and 2040, respectively. If this report ceases publication, a sufficiently similar report will be found for resolution. If no sufficiently similar report can be found, the question will be judged by a panel of experts.
- If current NAICS industry categories change or relevant new ones are added, a panel of experts will decide which categories to include.
- ‘Information’ industry covers businesses such as Google, Meta, and Microsoft. ‘Computer systems design’ currently includes OpenAI.
- See Table 67 here for figures between 2009 and 2018.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>

__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 38. Labor Force Partipication Rate in OECD

> What will be the labor force participation rate in OECD countries…
- …in the year 2024?
- …in the year 2030?
- …in the year 2050?
>
> Question details and resolution criteria
>
> - Labor force participation rate is “the number of people [of working age] who are employed or actively seeking employment, divided by the total non-institutionalized, civilian working-age population. … It omits institutionalized people (in prisons, nursing homes, or mental hospitals) and members of the military.” More background on labor force participation here.
- This question refers to labor force participation among 25-64 year-olds.
- This question will resolve with the OECD Total for labor force participation rate in the relevant year. The OECD Total is calculated as the aggregated labor force of all OECD countries, divided by the aggregated total working-age population of all OECD countries.
- By OECD countries, we mean current OECD countries as of the end of 2021 (through Costa Rica’s admission to the group). For more details, see https://www.oecd.org/about/document/ratification-oecd-convention.htm

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 39. MATH Dataset Benchmark 

> What will be the state-of-the-art accuracy of a machine-learning model on the MATH Dataset by…
- ...June 30, 2024?
- ...June 30, 2030?
> 
> Question and Resolution Details
> 
> - This question resolves as the highest performance achieved on MATH by the given date by an eligible model. 
- Eligible models may use scratch space before outputting an answer (if desired) and may be trained in any way that does not use the test set (few-shot, fine tuned, etc.). The model need not be publicly released, as long as the resulting performance itself is reported in a published paper (on arxiv or a major ML conference) or through an official communication channel of an industry lab (e.g. claimed in a research blog post of the lab, or in a press release).
- If this leaderboard is not in use by the given date, this will be resolved by an expert (ie by searching the web for relevant papers, blog posts and press releases).
- Research aiming to solve only a subset of the benchmark questions will be considered, but those attempts’ scores on non-targeted questions will be assumed to be zero. 
- If the benchmark is not actively used (i.e., no new known attempts to improve on this benchmark in the two years prior to the resolution date), this question will resolve by asking a panel of experts to state their beliefs about what performance on the benchmark would be if a currently-active, high-quality group of 10 researchers spent two weeks trying to apply current methods to this benchmark.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 40. "Massive Multitask Language Understanding" Benchmark

> What will be the state-of-the-art few-shot or transfer accuracy on the Massive Multitask Language Understanding dataset…
- ...by June 30, 2024?
- ...by June 30, 2030?
> 
> Question and Resolution Details
> 
> - This question resolves as the highest performance achieved on MMLU by the given date by an eligible model.
- Eligible models must not have been specifically trained on data from the MMLU dataset. A model need not be publicly released, as long as the resulting performance itself is reported in a published paper (on arxiv or a major ML conference) or through an official communication channel of an industry lab (e.g. claimed in a research blog post on the OpenAI blog, or a press release). If there's uncertainty about whether something counts, we will defer to this leaderboard.
- Research aiming to solve only a subset of the benchmark questions will be considered, but those attempts’ scores on non-targeted questions will be assumed to be zero. 
- If the benchmark is not actively used (i.e., no new known attempts to improve on this benchmark in the two years prior to the resolution date), this question will resolve by asking a panel of experts to state their beliefs about what performance on the benchmark would be if a currently-active, high-quality group of 10 researchers spent two weeks trying to apply current methods to this benchmark.
- This question resolves as the highest performance achieved on MMLU by the given date by an eligible model.
- Eligible models must not have been specifically trained on data from the MMLU dataset. A model need not be publicly released, as long as the resulting performance itself is reported in a published paper (e.g. on arxiv or a major ML conference) or through an official communication channel of an industry lab (e.g. claimed in a research blog post on the OpenAI blog, or a press release). 
- If there's uncertainty about whether something counts, we will defer to this leaderboard.


#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 41. QuALITY Dataset Benchmark 

> What will be the best SAT-style score with a machine learning model on the hard subset of the QuALITY dataset by…
- …June 30, 2024?
- …June 30, 2030?
- …June 30, 2040?
> 
> Question and Resolution Details
> 
> - This is an edited version of a Metaculus question, see here.
- Language models have surpassed human performance in benchmarks requiring reasoning over short texts, but performance remains low on reasoning over long texts. The QuALITY dataset (Peng et al 2021) was created to test long-document comprehension, using “a multiple-choice QA dataset with context passages in English that have an average length of about 5,000 tokens, much longer than typical current models can process.”
- The hard subset of QuALITY questions includes questions that require a more holistic understanding of the text to answer correctly. They were chosen as the questions that human answerers performed poorly on with very strict time constraints. SAT-style scoring penalizes wrong answers more than “no answer” so that answering questions with high uncertainty becomes less attractive.
- This question will be resolved according to this leaderboard. In the case of this leaderboard no longer being maintained, this question will be resolved by a panel of experts.




#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 42. AI Wins International Mathematical Olympiad

> By what year will an AI win a Gold Medal in the International Mathematical Olympiad (IMO)?
> 
> Question and Resolution Details
> 
> - This question will be resolved in either the first year that the official IMO Grand Challenge is won by an AI given the rules set forth by the challenge OR the first year that a panel of experts determines that an AI has the technical capability to win the challenge.
- The reason for the latter disclaimer is that currently the official grand challenge has a rule that the AI must be open-source and released publicly before the first day of the IMO. However, in this question we care about forecasting AI's technical capability to win the challenge, even if it is won by a private model. In the case of a private model resolving this question, the private model would need to be judged by a panel of experts adhering to the same resolution criteria as the Grand Challenge except for the criterion about an AI needing to be open-source and reproducible. That is, given that IMO problems in any given year are made available in Lean or another formal representation format, each proof certificate that the AI competitor produces must be checkable in 10 minutes; the AI competitor will be allowed the same amount of time as a human competitor to work on the problems, with no other limits on compute; and the AI cannot query the internet. 
- The current rules of the official challenge are still tentative. If the rules evolve, we assume that the question will resolve based on the most current version of the rules at any given time. If the rules eventually depart in substantial ways from the currently proposed rules, the resolution of this question may be referred to a panel of experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 43. NYT Bestsellers Written by AI 

> By what year will AI have written at least 3 books that appear on the New York Times Best Seller list?
>
> Question and Resolution Details
> 
> - Artificial intelligence (AI) is defined here as ‘the development of machines capable of sophisticated (intelligent) information processing (Dafoe 2018, AI Governance: A Research Agenda; See pg 5 footnote 2 for more.)
- A book is said to have been written by an AI if the AI wrote at least 99% of the text contained in the main section in the book, excluding a potential foreword, copyright notice, table of contents, and other non-essential book sections. The main text must also contain at least 20,000 words. Minor stylistic edits by humans are allowed if they do not change the basic semantic meaning of the text, or they merely correct basic spelling, grammatical, or formatting mistakes.
- The final text may be produced by a human ‘cherry-picking’, that is, choosing from among multiple examples of AI-generated text, provided that there is no more than one ‘picking’ per 1,000 words of final text on average (i.e., 20 ‘pickings’ across a 20,000 word text). A single ‘picking’ can include consideration of more than 2 versions of a single passage but not more than 10.
- If >99% of the text is written by an AI in response to prompts from humans (e.g. prompting GPT-3 to write text), then this would count as a book having been written by an AI for the purposes of this question. If natural language prompts are used, then the total word count of all human prompts used to generate the final text must be less than 400 words. If non-natural language prompts are used, they must be constrained to a ‘semantically equivalent’ length to a 400 natural language word prompt, as judged by a panel of experts.
- If a human does substantial editing such that they effectively wrote >1% of the words, then this would disqualify the text.
- If the generation methods used are too opaque to determine whether a text meets these criteria, a panel of experts will decide, either by soliciting evidence from parties involved in the production of the text, by commissioning relevant experiments, or by referring to past experiments in the public record.
- If the bestseller list creates a category for books written by AI, a book will not be counted if it appears solely on that list. 
- If the New York Times Best Seller list doesn’t exist by the time AI-written books are prominent, we’ll rely on a panel of experts to make a determination based on a similar methodology.
- According to this article, “The New York Times list is a survey list, not a tabulation of total sales. This means that they poll a curated selection of booksellers to estimate sales. … They also focus on individual sales, and try to not include bulk sales in their calculations. They do this to prevent people from buying their way onto the list. If you sell 1,000 copies to a company as part of a speaking engagement deal, this is a great way to move copies and make money, but it’s not very effective for hitting the list, because they won't count it.” 
- If an AI translates a book written by a human, this wouldn’t count for the purposes of this question.
- We will consult a panel of experts to collect information about publicly-known AI authors of books and widely known (even if not publicly announced) AI authors of books.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 44. Date of Advanced AI 

> When will the first unified AI system meeting all of the following criteria be trained, tested, and publicly known of?
> 
> Criteria:
> 
> - Able to reliably pass a 2-hour adversarial Turing test.
- High competency at answering questions across diverse fields of expertise.
-  High competency on interview-level problems in the APPS benchmark.
- Able to learn the classic Atari game “Montezuma’s revenge” in the equivalent of 100 hours or less of real-time play.
> 
> Question and Resolution Details
> 
> - This question is inspired by these Metaculus questions: I II
- An AI system is ‘unified’ if it is a single system applicable to many problems (rather than a set of sub-systems specialized narrowly to individual tasks like those above). This could be evidenced by, for example, the AI system being able to explain its reasoning on a Q&A task, or verbally reporting its progress and identifying objects during videogame play. Any ambiguity about whether a system is sufficiently ‘unified’ to qualify for resolving this question will be decided by a majority vote from a panel of AI experts.
- Further details about necessary criteria:
    - 1) In an ‘adversarial’ Turing test, human judges are instructed to ask interesting and difficult questions designed to advantage human participants and to successfully unmask the computer as an imposter. During the conversation, participants can send text, images, and audio files. A single demonstration of an AI passing such a Turing test will be sufficient for this condition, so long as the test is well-designed, as judged by a panel of AI experts.
    - 2) On the Q&A dataset developed by Dan Hendrycks et al., at least 75% accuracy in every task and 90% mean accuracy across all tasks.
    - 3) Able to get top-1 strict accuracy of at least 90.0% on interview-level problems found in the APPS benchmark introduced by Dan Hendrycks, Steven Basart et al. Top-1 accuracy is distinguished from top-k accuracy in which k outputs from the model are generated, and the best output is selected.
    - 4) Montezuma’s revenge must be learned based on just visual inputs and standard controls, and must explore all 24 rooms on the first level of the game.
- Resolution will be by direct demonstration of such a system achieving the above criteria. Ambiguity will be resolved by a >=75% majority vote by a panel of at least 5 AI experts.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 45. Maximum Compute Used in an AI Experiment 

> What will be the maximum compute (measured in petaFLOPS-days) used for training in an AI experiment…
- ...by end of 2024?
- ...by end of 2030?
- ...by end of 2050?
> 
> Question and Resolution Details
> 
> - This question shall resolve as a credible estimate of most compute used in a "single AI experiment".
- By "single AI experiment" we mean an effort to train a set of models running on a set of "architectures". The effort should be completed within a determinate amount of time (the experiment must not have an open-ended time frame). For our purposes, the publication of the principal results of the effort ends the experiment.
- By "architectures" we mean the systems described in the relevant publications that define how inputs signal or percept sequences are to be mapped on various outputs. These outputs might be probability distributions over actions (in the case of a policy network), representations over expected value or reward of futures states (in the case of value networks) or descriptions of futures states.
- In the absence of an authoritative source, the question will be resolved by a panel of experts.
- The panel of experts will by default use the methodology from OpenAI, 2018 (see Heim et al 2022 for further detail), unless a majority of the panel agrees that another methodology is more suitable. OpenAI’s method:
- “When we had enough information, we directly counted the number of FLOPS (adds and multiplies) in the described architecture per training example and multiplied by the total number of forward and backward passes during training.”
- “When we didn’t have enough information to directly count FLOPs, we looked GPU training time and total number of GPUs used and assumed a utilization efficiency (usually 0.33). For the majority of the papers we were able to use the first method, but for a significant minority we relied on the second, and we computed both whenever possible as a consistency check. In the majority of cases we also confirmed with the authors. The calculations are not intended to be precise but we aim to be correct within a factor 2-3. We provide some example calculations below.”

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 46. Largest AI Experiment Cost of Compute

> How much will be spent on compute in the largest AI experiment by… 
- …the end of 2024? 
- …the end of 2030?
- …the end of 2050?
> 
> Question and Resolution Details
> 
> - Artificial intelligence (AI) is defined here as ‘the development of machines capable of sophisticated (intelligent) information processing (Dafoe 2018, AI Governance: A Research Agenda; See pg 5 footnote 2 for more.)
- ‘Largest’ will be in terms of maximum compute used in training, in petaFLOPS-days. The experiment must be a ‘single AI experiment’, that is, ‘an effort to train a set of models running on a set of “architectures” … [which] should be completed within a determinate amount of time (the experiment must not have an open-ended time frame).’ (More here.)
- Cost will be in terms of 2021 US dollars.
- Size of the largest experiment will be resolved using a credible estimate of the most compute used in a "single AI experiment."
    - By "single AI experiment" we mean an effort to train a set of models running on a set of "architectures". The effort should be completed within a determinate amount of time (the experiment must not have an open-ended time frame). For our purposes, the publication of the principal results of the effort ends the experiment.   
    - By "architectures" we mean the systems described in the relevant publications that define how inputs signal or percept sequences are to be mapped on various outputs. These outputs might be probability distributions over actions (in the case of a policy network), representations over expected value or reward of futures states (in the case of value networks) or descriptions of futures states.
    - In the absence of an authoritative source, the question will be resolved by a panel of experts.
        - The panel of experts will default to using the methodology used by OpenAI (OpenAI, 2018) unless there is consensus to use a different methodology. 
- Cost resolution details:
    - Afterward, a panel of experts will estimate how much the compute for the experiment cost. Some examples of past estimates can be found here, here, or here.  
        - For one example of how the experts could estimate experiment cost: if Google itself carried out the experiment using its own TPUs, this would correspond to a complicated calculation involving the cost of producing the TPUs, the proportion of the lifetime of the TPUs which was used up in the experiments, Google’s profit margin for these TPUs, etc. A result might look like "it costs Google 30 to 70% of their retail price to use their own TPUs, which corresponds to a compute cost of $X."
        - For another example, if an external company got a special discount from Microsoft to run their experiments on Microsoft Azure, this number would be an estimate of how much the external company paid Microsoft.
- Fine-print:
    - 16 or 32-bit floating point operations will be regarded as equivalent.
- The units for this question are petaflop/s-day per dollar, to keep with historical usage by Metaculus or by OpenAI. A petaflop/s-day (pfs-day) consists of performing 1015 neural net operations per second for one day, or a total of about 1020 operations.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 47. Lowest Price of GFLOPS 

> What will be the lowest price, in 2021 US dollars, of 1 GFLOPS with a widely-used processor by…
- …the end of 2024?
- …the end of 2030?
- …the end of 2050?
> 
> Question and Resolution Details
> 
> - Processor capacity will be judged by theoretical max performance, as reported in manufacturer specifications.
- If disputed, a panel of experts will attempt to verify the accuracy of the performance claim made by the manufacturers.
- Price is the initial retail price of the chip on its release, adjusted to 2021 USD.
- If the chip is not available retail, then a panel of experts will estimate how much the chip would have cost if available retail using other chips of that type on the market for reference.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 48. ImageNet Classification Training Efficiency

> By what factor will training efficiency on ImageNet classification have improved over AlexNet by…
- …the end of 2024?
- …the end of 2030?
> 
> Question details and Resolution criteria
> 
- Training efficiency is a measure of algorithmic progress, and tracks the amount of compute needed to achieve a set level of performance on a given benchmark using state-of-the-art techniques. Training efficiency is composed of two factors: a) data efficiency (or number of epochs needed), and b) FLOP needed per epoch in training. 
- (Training efficiency = data efficiency x FLOP/epoch)
- This question will resolve as the highest reduction factor reported in OpenAI’s “Algorithmic Efficiency SOTAs” tables (here) for a publication either (a) by the end of 2024 or (b) by the end of 2030. The benchmark used must be AlexNet-level performance (79.1% top 5 accuracy) on ImageNet. If no such figures are reported by OpenAI (or a successor), we will use the protocol specified in this paper to determine state-of-the-art algorithmic efficiency on ImageNet in the relevant year.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 49. Largest Number of Parameters in a Machine Learning Model 

> What will be the largest number of parameters of a machine learning model trained…
- …by end of 2024?
- …by end of 2030?
- …by end of 2050?
> 
> Question and Resolution Details
> 
> -  In machine learning, model parameters are all variables whose values are learned via training. For example, ‘weights’ and ‘biases’ constitute the parameters of a neural network.
- The model must be used to obtain experimental results (e.g., it cannot be merely a description of a possible system, or a demonstration of scaling a system without application to a task); or else it must be deployed in an important context (e.g. Facebook’s recommender system).
- This question will resolve as the highest parameter count of a machine learning model reported in a comprehensive and current dataset, such as this (Sevilla & Villalobos 2021), as judged by a domain expert. If no suitable source exists, a panel of experts will decide the resolution.
- Parameter count shall be determined from a published paper or pre-print, or a reputable news article, press release or blog post written by or quoting a researcher involved in the relevant experiments. Where parameter count of a model cannot be determined or the accuracy of the source is ambiguous, it will be disqualified from resolution of this question. 

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 50. Negative Public Opinion of AI 

> Assume that Pew Research re-runs the survey linked here. What % of people in the median country in the survey will say that the development of artificial intelligence has mostly been a bad thing for society…
- ...in 2024?
- ...in 2030?
- …in 2050?
> 
> Question and Resolution Details
> 
> - If Pew Research re-runs this survey in 2024/2030/2050, this question resolves as described.
- If Pew Research does not re-run this survey, our research team will run the same survey with the exact question as specified at the appropriate time.
- Artificial intelligence (AI) is defined here as ‘the development of machines capable of sophisticated (intelligent) information processing (Dafoe 2018, AI Governance: A Research Agenda; See pg 5 footnote 2 for more.)




#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 51. Nick Bostrom Affirms Existence of AGI 

> By each of the following years, what is the probability that Nick Bostrom believes artificial general intelligence (AGI) exists?
- …by end of 2030?
- …by end of 2050?
- …by end of 2100?
>
> Question & resolution details:
> 
> - Professor Nick Bostrom is a philosopher and Director of Oxford’s Future of Humanity Institute. He is widely considered one of the foremost contemporary thinkers on the future of AI. A wide-ranging discussion of human- and above-human-level machine intelligence can be found in his 2014 book, Superintelligence.
- This question may be directly resolved by private communication in the specified years between Nick Bostrom and the tournament organizers. If Nick Bostrom does not directly resolve the question, it may be resolved by the following:
- By the beginning of the specified year, Nick Bostrom has publicly stated that he believes “artificial general intelligence” or “AGI” (or any reasonable variant phrase containing the word “general”) exists (or any reasonable variant of the word “exists”). It may also resolve positively if he states that “superintelligence” exists, or that AI capabilities have surpassed human-level, provided it is a general statement about AI capabilities and not restricted to a narrow subset (to be allowed at the discretion of a panel of experts, composed as specified below). Conversely, it may resolve negatively if he states that AGI does not exist. A negative statement will only count toward resolution if it occurs in the year prior to the resolution date, and is not followed by a positive statement. Statements must be documented by a credible journalistic or academic source, or a source directly connected to Nick Bostrom (e.g. his website).
- If Nick Bostrom has not made a public statement to this effect, a >=50% majority vote by a panel of at least 5 experts who will attempt to answer the question from the perspective of Nick Bostrom would also resolve the question. Relevant experts may be present or former colleagues/collaborators of Nick Bostrom, scholars of Nick Bostrom, or researchers with a deep knowledge of Nick Bostrom’s work.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 52. Probability of GDP Growth Over 15% 

> By 2100, will the global real GDP in a year ever exceed 115% of the highest GDP reported in any full prior year?
> 
> Question and Resolution Details
> 
> - ‘All prior years’ includes only dates from 1960 onward.
- 'By 2100' includes the year 2100.
- Similar to this Metaculus question, “Economic growth is [usually] measured by real world GDP growth over one year. However, since economic growth can also accelerate following a recession, this question will not ask about economic growth per se, but instead about GDP levels reaching a new height.”
- Question may be resolved by using World Bank data on global GDP, which can currently be found on their website in several formats (see e.g. this chart)
- If it is not possible to find World Bank data either on their website or elsewhere, this question will be resolved by a panel of experts.
- For this question to resolve positively, the World Bank would have to measure the real GDP during some year between now and 2100 at 115% of the previously highest-reported value. The question aims to capture an extreme level of annual real GDP growth. 
- For example, the World Bank’s highest-reported GDP in constant 2015 U.S. dollars thus far (see the chart linked in d.) was 84.612 trillion in 2019. If the World Bank reports that the GDP in constant 2015 U.S. dollars for the year 2021 was over 97.3038 trillion (115% of 84.612 trillion), the question would be resolved in the positive. 
- The question would also resolve in the positive if the above 2019 figure is never exceeded until a year where the World Bank reports that the GDP in constant 2015 U.S. dollars was over 97.3038 trillion (115% of 84.612 trillion). 
- The question would not necessarily resolve in the positive if the World Bank ever reports a GDP in constant 2015 U.S. dollars over 97.3038 trillion – only if said figure occurs after no prior year’s GDP in constant 2015 U.S. dollars had exceeded the previous high of 84.612 trillion.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 53. Year of GDP Growth over 15%

> If the global real GDP in a year does exceed 115% of the highest GDP reported in any prior year by 2100, in what year will this first occur?
> 
> Question and Resolution Details
> 
> - ‘All prior years’ includes only dates from 1960 onward.
- 'By 2100' includes the year 2100.
- Similar to this Metaculus question, “Economic growth is [usually] measured by real world GDP growth over one year. However, since economic growth can also accelerate following a recession, this question will not ask about economic growth per se, but instead about GDP levels reaching a new height.”
- Question may be resolved by using World Bank data on global GDP, which can currently be found on their website in several formats (see e.g. this chart)
- If it is not possible to find World Bank data either on their website or elsewhere, this question will be resolved by a panel of experts.




#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 54. Loss of Agricultural Production 

> What is the probability that total worldwide production of primary crops will fall by at least 70% within any three-year period…
- …by 2030?
- …by 2050?
- …by 2100?
> 
> Question details and Resolution criteria
> 
> - Primary crops are defined by the UN Food and Agriculture Organization (FAO) as “those which come directly from the land and without having undergone any real processing, apart from cleaning.” More detail can be found here.
- Resolution will be determined using statistics from the UN Food and Agriculture Organization (FAO)'s annual reports or, if these reports are not available, by a panel of experts.
- For example, in 2019: "When it comes to production, total production of primary crops increased by 53 percent between 2000 and 2019, hitting a record high of 9.4 billion tonnes in 2019. Half of global primary crop production is made up of just four crops: sugar cane, maize, wheat and rice." FAO
- Our resolution data will aim to approximate the data used in the below time series as closely as possible:

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 55. Space Colony 

> What is the probability that there will be a life-sustaining colony outside of Earth’s atmosphere with a population of at least 5,000 people…
- ... by 2030?
- ... by 2050?
- ... by 2100?
> 
> Question and Resolution Details
> 
> - To be considered "life-sustaining," this colony would need to be able to sustain its population over multiple generations even if there were no humans alive on Earth.
- If resolution is ambiguous, this question will be resolved by a panel of experts.

#### Stage 1 

- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 56. Happiness in America 

> In a nationally representative survey, what percentage of Americans will report being "very" or "fairly" happy in response to the question, "Generally speaking, how happy would you say you are — very happy, fairly happy or not too happy?"…
- ...in 2030?
- ...in 2050?
- ...in 2100?
> 
> Question and Resolution Details
> 
> - This question resolves as the % of Americans who report being “very” or “fairly” happy in the Gallup poll about happiness and wellbeing, if the survey is run in the resolution year.
- If the Gallup poll is not run in the resolution year, a new survey will be run with the exact question as specified and will resolve accordingly.
- If it is impossible to run this survey because independent survey companies are not able to survey Americans (for example, because public opinion surveying is not allowed), this question will be considered to resolve as 0.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 57. Prevalence of Autocracies 

> What percentage of the world population will be classified as living in an electoral or closed autocracy in the V-Dem Institute’s annual Democracy Report…
- …for the year 2030?
- …for the year 2050?
- …for the year 2100?
> 
> Questions and Resolution Details
> 
> - In the yearly Democracy Report, the V-Dem Institute measures a span of indices corresponding to democratic values and principles on a country-by-country basis. Based on a regime classification paper published by Lührmann et al. in 2018, one can also classify each country as a “liberal democracy,” “electoral democracy,” “electoral autocracy,” or “closed autocracy.”
- If the Democracy Report is not published in one or more of the resolution years, we will attempt to resolve the question using V-Dem and Lührmann et al.’s methodologies, or we will rely on another non-state organization’s report using similar metrics. In the latter case, a panel of experts will select the replacement report and resolve the question given data from the new survey.
- If it is impossible to gather data from independent, non-state sources on democratic principles anywhere on the globe, this question will be considered resolved as 100%.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 58. Future Worries and Children 

> When will 50% of US adults (18-49) say they expect to have no children, or no more children, and cite a worry about the long-term future of the world or country as a primary reason?
> 
> Question & resolution details
> 
> - Worries about the long-term future of the world include: global instability; international or domestic politics; climate change/environment; worries about technology. Additional categories may be included later at the discretion of a panel of experts. The cited long-term future worry does not have to be the exclusive worry of a respondent in order to count towards the total.
- This question will resolve as the first year prior to 2100 in which a nationally representative survey is conducted in the United States of adults age 18+, and a total proportion of 20% respondents:
    - Have no children AND expect to have no children AND cite at least one worry about the long-term future of the world or country as a reason; OR
    - Have children AND expect not to have more children AND cite at least one worry about the long-term future of the world or country as a reason.
- If at any point before 2100 at least 10 years has elapsed since the last survey of this kind has been run, we will commission such a survey. 
- A person will count as ‘expecting to have no children’ if they are currently childless, and: rate their likelihood of having children as ‘not at all likely’ or ‘not too likely’; or say they ‘don’t want’ children or ‘probably don’t want’ children; or any other reasonable wording variant (to be judged by a panel of experts).
- A person will count as ‘expecting not to have more children’ if they currently have children, and: rate their likelihood of having children as ‘not at all likely’ or ‘not too likely’; or say they ‘don’t want’ children or ‘probably don’t want’ children; or any other reasonable wording variant (to be judged by a panel of experts in cases of ambiguity).

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

### 59. Generation Attitudes 

> When will 90% of Americans say they wish they had been born in a previous generation?
> 
> Question & resolution details
> 
> - This question will resolve positively if a nationally representative survey is conducted in the United States asking respondents any of the following, AND at least 90% of respondents answer positively:
- Whether they wish they had been born or lived in a specific or nonspecific earlier time period;
- Whether they wish they had been part of an earlier generation;
- Or any reasonable variant wordings of these questions. If there is ambiguity, it will be resolved by a panel of experts.
- If at any point between 2025 and 2100 at least 10 years has elapsed since the last survey of this kind has been run, we will commission such a survey.

#### Stage 1 



- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Resource Notes__: 

__Quotes and Other Notes__: 

__Questions__:

__Naive Attitudes 2__: 
- bet(k) ¬(e2030) 
- bet(k) ¬(e2050)
- bet(k) ¬(e2100)
- ior_b(e2030:¬(e2030)) = 1:
- ior_b(e2050:¬(e2050))  = 1:
- ior_b(e2100:¬(e2100))  = 1:
- p(e2030) = % (% to %) 
- p(e2050) = % (% to %)
- p(e2100) = % (% to %)
- ior_p(e2030:¬(e2030))  = 
- ior_p(e2050:¬(e2050))  =
- ior_p(e2100:¬(e2100))   =  
- u_or(e2030:¬(e2030)) =  1: (1: to 1:)
- u_or(e2050:¬(e2050)) =  1: (1: to 1:)
- u_or(e2100:¬(e2100)) =  1: (1: to 1:)
- Aggregate OR 2030: 1:, %
- Aggregate OR 2050: 1:, %
- Aggregate OR 2100: 1:, %
- Naive statement:  
- 
- 
- 
- Thoughts on the visualization:

<details>
<summary>Aggregate Naive Attitudes 1</summary>
<img src="/assets/2022/for_persuasion_tournament/images/q1_n1_agg.png">
</details>
__Scenarios__: 

__Survey__:
- How confident are people about this subject? 
- How much does expertise improve forecasting accuracy with this subject? 
- Can you predict what the Metaculus community thinks?
- What's the different between the Metaculus community, superforecasters, and experts?

__Metaculus Community__:

__Final Forecast and Rationale__:

<!-- #### Stage 2 

#### Stage 3

#### Stage 4  --> 

--- 

## Appendix 

### Initial Survey Answers 

### SPIES Method 

### Forecasting Tools Employed 

<https://forecasting.wiki/wiki/Category:Making_good_forecasts>

> From "Superforecasting" (Appendix: Ten Commandments for Aspiring Superforecasters)
> 
> (1) Triage. (2) Break seemingly intractable problems into tractable sub-problems. (3) Strike the right balance between inside and outside views. (4) Strike the right balance between under- and overreacting to evidence. (5) Look for the clashing causal forces at work in each problem. (6) Strive to distinguish as many degrees of doubt as the problem permits but no more. (7) Strike the right balance between under- and overconfidence, between prudence and decisiveness. (8) Look for the errors behind your mistakes but beware of rearview-mirror hindsight biases. (9) Bring out the best in other and let others bring out the best in you. (10) Master the error-balancing cycle. (11) Don't treat commandments as commandments.

<https://www.bayesrulesbook.com/chapter-3.html>

<https://www.squiggle-language.com/playground/>

<https://en.wikipedia.org/wiki/Risk>

<https://safetysection.com/risk-assessment-calculation-formula/>

<https://intaver.com/blog-project-management-project-risk-analysis/risk-scores-2/>

<https://stats.stackexchange.com/questions/93523/how-do-we-predict-rare-events>

> The reason you are unlikely to get good results using classification or regression methods is that these methods typically depend on predicting the conditional mean of the data, and extreme events are usually caused by the conjunction of "random" factors all aligning in the same direction, so they are in the tails of the distribution of plausible outcomes, which are usually a long way from the conditional mean. What you can do is to predict the whole conditional distribution, rather than just its mean, and get some information on the probability of an extreme event by integrating the tail of the distribution above some threshold. I found this worked well in an application on statistical downscaling of heavy precipitation.

Exponential smoothing: 

<https://machinelearningmastery.com/exponential-smoothing-for-time-series-forecasting-in-python/>

<https://hbr.org/1971/07/how-to-choose-the-right-forecasting-technique>

--- 

## [Notes](#notes)

### *Cover Photo*

The [cover photo]() for this page was likely taken by [](). I found the photo on [Unsplash](https://unsplash.com/). To my knowledge, my use of this photo is permissible under Unsplash's [license](https://unsplash.com/license):
> Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service.

### *Footnotes*