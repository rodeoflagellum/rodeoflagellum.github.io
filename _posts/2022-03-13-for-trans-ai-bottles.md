---
layout: post
title:  "General AI/DL Community vs. AI Safety"
date:  2022-04-09 12:00:00 -0400
last_edit: 2022-04-10 12:10:00 -0400
permalink: "/for_dl_ai_safety/"
status: "Draft"
certainty: "7.0"
importance: "8.5"
impact: "5.5"
tags: [forecasting, prediction, ai, ai-safety, governance]
image: /assets/images/urja-bhatt-ChlQ7O0bVsY-unsplash.jpg
desc: "A short essay for Metaculus on forecasting to what
degree principles of AI safety are and will be present in
the AI research community."
---

## Table of Contents
{:.no_toc}
* TOC
{:toc}

## [Outlook](#outlook)
_Here I provide a brief overview of the AI Safety landscape and introduce why characterizing AI Safety's place within the wider context of DL research is important_

[AI safety][ai_safety]{:target="_blank"} as a distinct discipline is relatively new; the earliest occurrence of the phrase "AI safety" I could find in academic literature appears to be in 2000, in the publication _Poopville_[^1]. The field is steadily growing both in terms of popularity[^2] and funding. In 2014, spending on strategical and technical interventions totaled [~1.75 million USD][impacts]{:target="_blank"} between the [Future of Humanity Institute][fhi]{:target="_blank"} (FHI) and the [Machine Intelligence Research Institute][miri]{:target="_blank"} (MIRI), two of the field's progenitors, and grew to ~9.1 million USD in 2017 (distributed across many new organizations), a ~5.2 fold increase[^3]. [Insert discussion on the Metaculus community and Open Philanthropy]

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/7418/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/7419/" width="100%" height="300"></iframe>

&emsp; Nestled in the wider [deep learning][dl]{:target="_blank"} (DL) and AI community, the "safety" in AI Safety stems from the concern that AI systems can be deleterious, in a variety of ways minor or grave, to humanity. AI systems and their wrath is often a theme of [science fiction][fict]{:target="_blank"}, captured by systems such as [HAL 9000][hal]{:target="_blank"} or [Prime Intellect][prime]{:target="_blank"}. Perhaps [the earliest][ai_risk]{:target="_blank"} formulation of the threat of AI systems was in [Samuel Butler][butler]{:target="_blank"}'s 1863 essay entitled _[Darwin among the Machines][dar]{:target="_blank"}_, in which he wrote[^4]

> The upshot is simply a question of time, but that the time will come when the machines will hold the real supremacy over the world and its inhabitants is what no person of a truly philosophic mind can for a moment question.

The complexity of the aims and problems within AI Safety is driven in part by the complexity of intelligence and of human values. From an informal viewpoint, the landscape of AI Safety can be understood by looking at organizations and individuals who broadcast concern regarding AI and who generate research. Here is one such map, created in 2017 by [Søren Elverlin][in_land]{:target="_blank"}[^5]. I believe that it's a safe bet that most people who work in AI Safety will have heard of many of the entities listed in this map.

![](/assets/images/ai_vs_dl/informal_map.png){: width=40% }

From a more formal viewpoint, the [Future of Life Institute][fli]{:target="_blank"}'s [AI Safety map][for_land]{:target="_blank"}[^6] has AI Safety as a root node containing five main branches (___Validation___, ___Control___, ___Verification___, ___Security___, and ___Foundations___)[^7].

![](/assets/images/ai_vs_dl/formal_map.png){: width=40% }

Speculation is diverse regarding the internal form or the embodiment that an extremely dangerous AI system might take, but researchers often frame risk from AI in terms of what an AI system can achieve rather than in terms of its complexity. For example, [Stuart Armstrong][arm]{:target="_blank"}, a prominent AI Safety researcher, writes in _[Smarter Than Us][smart]{:target="_blank"}_

> In fact, knowing AI behavior can be a lot more useful to us than understanding intelligence. Imagine that a professor claimed to have the world's most intelligent AI and, when asked about what it did, responded indignantly, "Do? What do you mean _do_? It doesn't _do_ anything! It's just really, really smart!" Well, we might or might not end up convinced by such rhetoric, but that machine is certainly not one we'd need to start worrying about. But if the machine started winning bin on the stock market or crafting convincing and moving speeches - well, we still might not agree that it's "intelligent," but it certainly would be something to start worrying about.

One particular threshold for considering the consequences of what sophisticated AI systems might "do" is in terms of human civilizational-wide change, akin to what occurred during the agricultural or industrial revolutions. In this vein, [Open Philanthropy][open_phil]{:target="_blank"} provides the following [definition][trans]{:target="_blank"} of _transformative AI_ as "AI that precipitates a transition comparable to (or more significant than) the agricultural or industrial revolution"[^8].

&emsp; As we have seen, AI Safety is a broad field, and transformative AI is but one of many formulations for understanding the potential impact of AI. Of course, considering the prospect of transformative AI, especially its timelines, is an important endeavor within AI Safety. Given the difficulties of forecasting [rare events][rare]{:target="_blank"}[^9], along with the current community consensus that no AGI has ever existed (an empty reference class), predicting the trajectory and impact of transformative AI is difficult. Nonetheless, it seems somewhat plausible that, in the event transformative AI is to created, it will stem from the DL research community; presently, 100 [Metaculus][meta]{:target="_blank"} community members assign a median probability of 70% that [artificial general intelligence][agi] (AGI) will be based on DL. Moreover, 121 Metaculus members believe that the date that "the first [strong and robotic] AGI [is] first developed and demonstrated" will be between 2037 and 2084 (1st quartile - 3rd quartile), with a median prediction of 2052.

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/4055/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/5121/" width="100%" height="300"></iframe>

The full extent of the negative impact that could be engendered by transformative AI, or by AI systems generally, is beyond the scope of this essay. However, taking the magnitude of risks from AI as given, these predictions, along with other trajectories researched by the AI Safety community, indicate the need for urgent monitoring and governance of AI systems, predominantly in the DL community.

&emsp; Instrumentally speaking, ensuring that those in the DL community are at least


<!-- (The DL community needs to key close to AI Safety)
(An idea to solve problems in AI Safety is to increase funding, and increasing talent)
(Some researchers in DL are not interested in AI Safety)
() -->

<!-- https://www.metaculus.com/questions/4055/will-the-first-agi-be-based-on-deep-learning/ -->



 <!-- but that such impacts might originate from the DL research community is useful in that -->

In this context, some prospective research questions to be addressed might be:

- How does the amount of funding and participation in the AI Safety community affect progress in AI Safety?
- How large is the AI Safety community relative to the general AI/DL research community? How will this change?
- How might this change with regard to funding, participation, and progress, among other things?
- How do the AI Safety and general AI/DL communities overlap?
- How might this change with regard to funding, participation, and progress, among other things?

<!-- [Search for DL with AI Safety terms and without AI Safety terms]
DL with, DL without, AI safety with DL, AI safety without,
timeliens and numbers

search for occurrence of words in
just titles
just abstracts
titles and abstracts
all of the paper  -->

__Contribution__:

__Disclaimer__:

<!-- I have never published peer-reviewed research on AI Safety. -->

## [Search Terms](#search-terms)
_Here I

### Metaculus Search Terms

- Interpretability and Explainability
  - "ai safety"
  - "ai alignment"
  - "aligned ai"
  - "value alignment problem"
  - "reward hacking"
  - "reward tampering"
  - "tampering problem"
  - "safe exploration"
  - "robust to distributional shift"
  - "scalable oversight"
  - "explainable AI"
  - "interpretable AI"
  - "explainable model"
  - "verification for machine learning"
  - "verifiable machine learning"
  - "interpretable model"
  - "interpretable machine learning"
  - "cooperative inverse reinforcement learning"
  - "value learning"
  - "iterated amplification"
  - "preference learning"
  - "AI safety via debate"
  - "reward modeling"
  - "logical induction"
- Natural Language Processing (NLP)

- Reinforcement Learning (RL)

- Multi-modal Learning


### LessWrong Search Categories

- Basic Alignment Theory
  - AIXI
  - Coherent Extrapolated Volition
  - Complexity of Value
  - Corrigibility
  - Decision Theory
  - Embedded Agency
  - Fixed Point Theorems
  - Goodhart's Law
  - Goal-Directedness
  - Infra-Bayesianism
  - Inner Alignment
  - Instrumental Convergence
  - Intelligence Explosion
  - Logical Induction
  - Logical Uncertainty
  - Mesa-Optimization
  - Myopia
  - Newcomb's Problem
  - Optimization
  - Orthogonality Thesis
  - Outer Alignment
  - Paperclip Maximizer
  - Recursive Self-Improvement
  - Solomonoff Induction
  - Treacherous Turn
  - Utility Functions
- Engineering Alignment
  - AI Boxing (Containment)
  - Conservatism (AI)
  - Debate (AI safety technique)
  - Factored Cognition
  - Humans Consulting HCH
  - Impact Measures
  - Inverse Reinforcement Learning
  - Iterated Amplification
  - Mild Optimization
  - Oracle AI
  - Reward Functions
  - Tool AI
  - Transparency / Interpretability
  - Tripwire
  - Value Learning
- Strategy
  - AI Governance
  - AI Risk
  - AI Services (CAIS)
  - AI Takeoff
  - AI Timelines
  - Computing Overhang
  - Regulation and AI Risk
  - Transformative AI
- Organizations
  - AI Safety Camp
  - CHAI (UC Berkeley)
  - DeepMind
  - FHI (Oxford)
  - Future of Life Institute (FLI)
  - MIRI
  - OpenAI
  - Ought
- Other
  - AI Capabilities
  - GPT
  - Language Models
  - Machine Learning
  - Narrow AI
  - Neuromorphic AI
  - Reinforcement Learning
  - Research Agendas
  - Superintelligence
  - Whole Brain Emulation

### EA Forum Search Terms

- Global Catastrophic Risk (AI)
  - Global Catastrophic Risk (AI)
  - AI alignment
  - AI boxing
  - AI ethics
  - AI forecasting
  - AI race
  - AI safety
  - AI skepticism
  - AI takeoff
  - AI winter
  - Alignment tax
  - Anthropic capture
  - Artificial intelligence
  - Artificial sentience
  - Basic AI drive
  - Brain-computer interfaces
  - Capability control method
  - Collective superintelligence
  - Comprehensive AI Services
  - Computation hazard
  - Economics of artificial intelligence
  - Governance of artificial intelligence
  - Human-level artificial intelligence
  - Indirect normativity
  - Infrastructure profusion
  - Instrumental convergence thesis
  - Intelligence explosion
  - Malignant AI failure mode
  - Mind crime
  - Motivation selection method
  - Oracle AI
  - Orthogonality thesis
  - Perverse instantiation
  - Quality superintelligence
  - Sovereign AI
  - Speed superintelligence
  - Superintelligence
  - Tool AI
  - Whole brain emulation
- Artificial Intelligence (organizations)
  - AI Impacts
  - AI Safety Camp
  - AI Safety Support
  - Aligned AI
  - Alignment Research Center
  - Anthropic
  - Center for Human-Compatible Artificial Intelligence
  - Center for Security and Emerging Technology
  - Centre for Long-Term Resilience
  - Centre for the Governance of AI
  - Charity Science Foundation
  - DeepMind
  - Leverhulme Center for the Future of Intelligence
  - Machine Intelligence Research Institute
  - Nonlinear Fund
  - OpenAI
  - Ought
  - People for the Ethical Treatment of Reinforcement Learners

__FLI AI Safety Search Areas__

- Foundations
  - Foundations of Rational Agency
    - Logical Uncertainty
    - Theory of Counterfactuals
    - Universal Algorithmic Intelligence
    - Theory of Ethics
      - Ethical Motivation
      - Ontological Value
      - Human Preference Aggregation
      - Infinite Ethics
      - Normative Uncertainty
    - Bounded Rationality
  - Consistent Decision Making
    - Decision Theory
      - Logical Counterfactuals
      - Open Source Game Theory
    - Safer Self-Modification
      - Vingean Reflection
        - Abstractly Reason About Superior Agents
        - Reflective Induction Confidence
        - Löbian Obstacle
      - Optimal Policy Preservation
      - Safety Technique Awareness
    - Goal Stability
      - Nontransitive Options
  - Projective Behavioral Bounds
    - Computational Complexity
- Verification
  - Formal Software Verification
    - Verified Component Design Approaches
    - Adaptive Control Theory
    - Verification of Cyberphysical Systems
    - Making Verification More User Friendly  
  - Automated Vulnerability Finding
  - Verification of Intelligent Systems
    - Verification of Whole AI Systems
    - Verification of Machine Learning Components
  - Verification of Recursive Self-Improvement
  - Implementation Testing
- Validation
  - Averting Instrumental Incentives
    - Error-Tolerant Agent Design
    - Domesticity
      - Impact Measures
        - Values-Based Side Effect Evaluation
        - Avoiding Negative Side Effects
          - Reward Uncertainty
          - Multi-agent Approaches
          - Penalize Influence
        - Follow-on Analysis
        - Impact Regularizers
          - Defined Impact Regularizer
          - Learned Impact Regularizer
      - Safe exploration
        - Risk-Sensitive Performance Criteria
        - Simulated Exploration
        - Bounded Exploration
        - Multiobjective Reinforcement Learning
        - Human Oversight
        - Buried Honeypot Avoidance
      - Mild Optimization
        - Optimization Measures
        - Quantilization
        - Multiobjective Optimization
      - Computational Humility
        - Generalized Fallibility Awareness
        - Resource Value Uncertainty
        - Temporal Discount Rates
    - Averting Paranoia
  - Avoiding Reward Hacking
    - Pursuing Environmental Goals
      - Environmental Goals
      - Predicting Future Observations
      - Model Lookahead
      - History Analysis
      - Detecting Channel Switching
    - Counterexample Resistance
    - Adversarial Reward Functions
    - Variable Indifference
    - Careful Engineering
    - Reward Capping
    - Reward Pretraining
    - Multiple Rewards
  - Value Alignment
    - Ethics Mechanisms
      - Grounded Ethical Evolution
        - Moral Trade
      - Value Specification
        - Classical Computational Ethics
        - Value Structuring
          - Values Geometry
          - Action and Outcome Evaluations
          - Game Theoretic Framing
          - Unified Ethics Spaces
        - Capability Amplification
      - Value Learning
        - Operator Value Learning
        - Value Elicitation
          - Value Sourcing
          - Value Interrogation
          - Value Factoring
        - Collaborative Values Learning
      - Ethical Ensembles
      - Structured and Privileged Ethical Biases
      - Drives and Affect
    - Degrees of Value Evolution
    - Robust Human Imitation
      - Inverse Reinforcement Learning
        - Cooperative Inverse Reinforcement Learning
      - Imitation Statistical Guarantees
        - Generative Adversarial Networks
        - Other Generative Models
      - Operator Modeling
      - Reversible Tasks via Variational Autoencoding
      - Distance from User Demonstration
      - Narrow Value Learning
      - Scaling Judgement Learning
  - Increasing Contextual Awareness
    - Realistic World-Models
      - Expressive Representations
      - Unsupervised Model Learning
        - Concept Drift
        - Ontology Identification
        - Ontology Update Thresholds
        - Episodic Contexts
      - Correlations of Dynamics
      - World-Embedded Solomonoff Induction
      - Perceptual Distance Agnostic World Models
      - Knowledge Representation Ensembles
    - Endowing Common Sense
      - Common Sense Reasoning
      - Bootstrapped Common Sense
      - Seeded Common Sense
      - Metareasoning
      - Lengthening Horizons
    - Concept Geometry
      - Implicit Human Concepts
      - Conservative Concepts
        - Dimensionality Reduction With Anomaly Detection
      - Multilevel World-Models
      - World Model Connectedness
    - Uncertainty Identification and Management
      - Inferring Latent Variables
      - Inductive Ambiguity Identification
        - Scalable Oversight of Ambiguities
        - Bayesian Feature Selection
        - Non-Bayesian Confidence Estimation
        - Active Learning
        - Realistic-Prior Design
        - Knows-What-It-Knows Learning
        - Robustness to Distributional Shift
          - Covariate Shift
          - Unsupervised Risk Estimation
          - Causal Identification
          - Limited-Information Maximum Likelihood
          - Active Calibration
          - Reachability Analysis
          - Robust Policy Improvement
          - Counterfactual Reasoning
          - ML with Contracts
          - Model Repair
      - Resource-Aware Reasoning
        - Decision Under Bounded Computational Resources
        - Logical Induction
          - Logical Priors
          - Impossible Possibilities
    - Symbolic-Subsymbolic Integration
      - Use of Structured Knowledge In Subsymbolic Systems
      - Use of Subsymbolic Processing In Symbolic Systems
  - Psychological Analogues
    - Cognitive Parallels
    - Developmental Psychology
    - Dysfunctional Systems of Thought
    - Whole Brain Emulation Safety
  - Testing and Quality Assurance
- Security
  - Standard IT Security
    - Verified Downstack Software
    - Utility Function Security
    - AI to Support Security
    - Security-Validated Software Engineering
  - Red Team Analysis
    - Penetration Testing
  - Tripwires
  - Containment
  - Handling Improper External Behavior
    - Adversarial ML
      - Dealing with Adversarial Testing
    - Statistical-Behavioral Trust Establishment
    - Modeling Operator Intent
    - Sensibility-Triggered Defence
    - Detecting and Managing Low Competence
  - Privileged Biases
  - Norm Denial of Service
  - Misuse Risk
- Control
  - Computational Deference
    - Corrigibility
      - Interruptability
    - Utility Indifference
      - Switchable Objective Functions
    - Control Transfer
  - Oversight
    - Scalable Oversight
      - Supervised Reward Learning
      - Semisupervised Reward Learning
      - Active Reward Learning
      - Unsupervised Value Iteration
      - Distant Supervision
      - Hierarchical Reinforcement Learning
      - Trust Policy Oversight
      - Cooperative Inverse Reinforcement Learning
      - Human Judgement Learner
      - Informed Oversight
    - Controlling Another Algorithm
    - Capability Distillation
    - Rich Understanding of Human Commands
    - Monitoring
      - Transparency of Whiteboxes
        - Transparent Reinforcement Learners
      - Interpretability of Blackboxes
      - Adversarial Transparency
      - Visualization and Situation Awareness
      - Detailed Audit Trails
      - Report Sufficiency
      - Causal Accounting




### Full Search Terms


<!-- Node size is word count OR paper count in 2 networks
Edges sizes are given by how many papers use both these terms

Searched with AI &
Source | Sublevel | Term | Search Term | Post Count | Paper Count | Post Word Count | Paper Word Count  

Searched with DL &
Source | Sublevel | Term | Search Term | Post Count | Paper Count | Post Word Count | Paper Word Count  

Searched with AI Safety &
Source | Sublevel | Term | Search Term | Post Count | Paper Count | Post Word Count | Paper Word Count  

Searched with AI Alignment &
Source | Sublevel | Term | Search Term | Post Count | Paper Count | Post Word Count | Paper Word Count  
-->

## Querying Methods
__

__ArXiv__

__OpenAlex__

__LessWrong, EAF, Alignment Forum__

__Google Scholar__

<!--
Develop search terms (pooled)
Develop combinations
  (DL / AI) + all_terms
  (AI Safety / AI Alignment) + all terms

Post on FLI landscape + quotes + your findings
 -->

## Forecasting Questions

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/5899/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/6586/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/5961/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/6299/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/6576/" width="100%" height="300"></iframe>


<!-- num word count in posts,
num of posts with this tags,
break down into AI safety tags and
general deep learning tags using
FLI map

LW, EAF tags all searched
on LW, EAF, Alignment

link to all these tags-->

# how to categorize Safety tags

## Appendix



## Link Bibliography

(these are currently unordered and lack descriptions; my apologies - I will try to fix this in the near-term future)

[agi]: https://en.wikipedia.org/wiki/Artificial_general_intelligence "https://en.wikipedia.org/wiki/Artificial_general_intelligence"

[meta]: https://www.metaculus.com/questions/ "https://www.metaculus.com/questions/"

[rare]: https://www.lesswrong.com/posts/Yb26htyo6SMirnzqt/forecasting-rare-events "https://www.lesswrong.com/posts/Yb26htyo6SMirnzqt/forecasting-rare-events"

[smart]: https://intelligence.org/smarter-than-us/ "https://intelligence.org/smarter-than-us/"

[trans]: https://www.openphilanthropy.org/blog/some-background-our-views-regarding-advanced-artificial-intelligence#Sec1 "https://www.openphilanthropy.org/blog/some-background-our-views-regarding-advanced-artificial-intelligence#Sec1"

[arm]: https://www.fhi.ox.ac.uk/team/stuart-armstrong/ "https://www.fhi.ox.ac.uk/team/stuart-armstrong/"

[fli]: https://futureoflife.org/ "https://futureoflife.org/"

[fict]: https://en.wikipedia.org/wiki/Artificial_intelligence_in_fiction "https://en.wikipedia.org/wiki/Artificial_intelligence_in_fiction"

[hal]: https://en.wikipedia.org/wiki/HAL_9000 "https://en.wikipedia.org/wiki/HAL_9000"

[prime]: https://en.wikipedia.org/wiki/The_Metamorphosis_of_Prime_Intellect "https://en.wikipedia.org/wiki/The_Metamorphosis_of_Prime_Intellect"

[in_land]: https://aisafety.com/2017/09/26/map-ai-safety-community/ "https://aisafety.com/2017/09/26/map-ai-safety-community/"

[for_land]: https://futureoflife.org/landscape/ "https://futureoflife.org/landscape/"

[dl]: https://en.wikipedia.org/wiki/Deep_learning "https://en.wikipedia.org/wiki/Deep_learning"

[dar]: https://en.wikipedia.org/wiki/Darwin_among_the_Machines "https://en.wikipedia.org/wiki/Darwin_among_the_Machines"

[butler]: https://en.wikipedia.org/wiki/Samuel_Butler_(novelist) "https://en.wikipedia.org/wiki/Samuel_Butler_(novelist)"

[ai_risk]: https://en.wikipedia.org/wiki/Existential_risk_from_artificial_general_intelligence#History "https://en.wikipedia.org/wiki/Existential_risk_from_artificial_general_intelligence#History"

[miri]: https://intelligence.org/ "https://intelligence.org/"

[fhi]: https://www.fhi.ox.ac.uk/ "https://www.fhi.ox.ac.uk/"

[impacts]: https://aiimpacts.org/changes-in-funding-in-the-ai-safety-field/ "https://aiimpacts.org/changes-in-funding-in-the-ai-safety-field/"

[open_phil]: https://www.openphilanthropy.org/ "https://www.openphilanthropy.org/"

[ai_safety]: https://intelligence.org/why-ai-safety/ "https://intelligence.org/why-ai-safety/"

[ai_fict]: https://en.wikipedia.org/wiki/Artificial_intelligence_in_fiction "https://en.wikipedia.org/wiki/Artificial_intelligence_in_fiction"

## Notes

#### *Cover Photo*

The [cover photo](https://unsplash.com/photos/ChlQ7O0bVsY){:target="_blank"} for this page was likely taken by [Urja Bhatt](https://unsplash.com/@urjabhatt){:target="_blank"}. I found the photo on [Unsplash](https://unsplash.com/){:target="_blank"}. To my knowledge, my use of this photo is permissible under Unsplash's [license](https://unsplash.com/license){:target="_blank"}: "_Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service._"

#### *Footnotes*


[^1]: Query results on OpenAlex and then on Google Scholar and ArXiv for earliest.

[^2]: The rest of this essay will focus on the growing popularity AI Safety.

[^3]: I did not spend too much time on accumulating data on the current (04/10/2022) landscape of funding for research in AI Safety, but from anecdotal evidence, funding seems to be plentiful and to be supporting the surging number of researchers from physics, software development, and data science, among other fields, migrating to AI Safety.

[^4]: I did not spend much time exploring the earliest historical incidences of thinking on intelligent machines or on the risks incurred by developing artificial intelligence, so please don't assign much confidence that this is in fact the first written instance of thinking about AI risk.

[^5]: I did not spend any time researching how this is, or what their influence on AI Safety has been. The accuracy of the map as an informal representation of the AI Safety community seems on point, but I am biased as someone who has only spectated the development of the field.

[^6]: Given my present experience, I am unsure of how important the FLI is as a pioneer of AI Safety. I am not familiar with its history or influence in the field, other than the fact that, anecdotally, the organization seems important.

[^7]: I did not look for a description of how many named disciplines there were or for a description of how important each listed entity is for AI Safety (I am assuming that the size of the entity is roughly proportional to its influence on AI Safety, for the time being).

[^8]: Open Philanthropy provides a second definition of transformative AI, given how nebulous the first definition is. The second definition (one or more of the descriptions must hold): <br><br>__(1)__ _AI systems capable of fulfilling all the necessary functions of human scientists, unaided by humans, in developing another technology (or set of technologies) that ultimately becomes widely credited with being the most significant driver of a transition comparable to (or more significant than) the agricultural or industrial revolution. Note that just because AI systems could accomplish such a thing unaided by humans doesn’t mean they would; it’s possible that human scientists would provide an important complement to such systems, and could make even faster progress working in tandem than such systems could achieve unaided. I emphasize the hypothetical possibility of AI systems conducting substantial unaided research to draw a clear distinction from the types of AI systems that exist today. I believe that AI systems capable of such broad contributions to the relevant research would likely dramatically accelerate it._,<br><br>__(2)__ _AI systems capable of performing tasks that currently (in 2016) account for the majority of full-time jobs worldwide, and/or over 50% of total world wages, unaided and for costs in the same range as what it would cost to employ humans. Aside from the fact that this would likely be sufficient for a major economic transformation relative to today, I also think that an AI with such broad abilities would likely be able to far surpass human abilities in a subset of domains, making it likely to meet one or more of the other criteria laid out here._,<br><br>__(3)__ _Surveillance, autonomous weapons, or other AI-centric technology that becomes sufficiently advanced to be the most significant driver of a transition comparable to (or more significant than) the agricultural or industrial revolution. (This contrasts with the first point because it refers to transformative technology that is itself AI-centric, whereas the first point refers to AI used to speed research on some other transformative technology.)_

[^9]: See <https://stats.stackexchange.com/questions/93523/how-do-we-predict-rare-events> and <https://www.semanticscholar.org/paper/The-limits-of-forecasting-methods-in-anticipating-Goodwin-Wright/c1d3c776a5f8bb131ee9e0cc3a939ab80c7cc0c6>

<!-- Personal Notes
Read https://www.openphilanthropy.org/blog/some-background-our-views-regarding-advanced-artificial-intelligence#Sec1 on Transformative AI
Come up with a disclaimer
Either research changing landscape/popularity of "control mechanisms"
(Alignment Forum, LessWrong, Google Trends, OpenAlex research base)
Or look into restrictions and other parameters concerning computability
(look for quotes or research that discuss this)

Goals
1. rigorous and nuanced thinking about the future of AI
2. provide an arena for discussion and exchange of ideas regarding the future of AI, and especially the likelihood, timing, and impacts of transformative AI

Original and Creative
Synthesize at least some of the predictions made in the Forecasting AI Progress tournament
Are well and clearly written, so that it is comprehensible and enjoyable to read

⅔ weight given to essay quality, and ⅓ weight given to relevance

Forum query methods; https://forum.effectivealtruism.org/posts/SCqRu6shoa8ySvRAa/big-list-of-cause-candidates

https://api.openalex.org/works?search=transformative%20ai,ai%20safety

Search all LessWrong tags relating to AI in the literature

Additional Topics
Can we map the disagreements between notable figures in the AI risk community, as presented in the Late 2021 MIRI Conversations, onto disagreements about quantifiable predictions? Which views do we expect to imply predictions that we think are likely to fare better, and why?

Build off of Reframing Superintelligence
Is Deep Learning sufficient for achieving Transformative AI (roughly, AI that precipitates a transition comparable to the agricultural or industrial revolution), if not, how many new substantial insights might be needed?

What fraction of the field of AI will be dedicated to working on AI Safety, broadly defined? Will the field have substantial influence on how AI systems are designed, tested and/or deployed? Justify your views with, amongst other things, reference to quantitative predictions.-->


<!-- ### LessWrong

### EA-Forum

### Alignment Forum

### OpenAlex

## Question 1

## Question 2

## Question 3

## Discussion

## Forecasts  

## Conclusion -->

<!--
and seems to be steadily growing both in terms of popularity and funding. Concern regarding AI systems or intelligent machines has been around for some time f

with the one of first concerns regarding AI systems  emerging earlier in [fiction][ai_fict], and seems to be steadily growing both in terms of popularity and funding.

- AI Safety as a distinct discipline is relatively new.
- The first use of the term AI safety occurred [here].
- There have been concerns on ML intelligence for a long time, especially in science fiction.
- Tranformative AI timelines are important.
- People are discussing funding AI researchers
- The full history of AI Safety and of progress in AI systems, generally, is beyond the scope of this essay.





From a formal viewpoint, such as that provided

https://www.lesswrong.com/posts/vaHgLF2BCEdK3KxQd/convincing-all-capability-researchers

Start with this post, talking about what transformative AI is including multiple definitions
and 1 or 2 questions on takeoffs (along with community predictions, included pooled community
  forecasts and some thoughts on how hte community consensus and Open Phils (see the priors post) have
  changed over time). Then discuss the Logan post and whether more researcehrs would make a difference
  use this as a seqway to discussing a list of questions on different sizes of the communities and
  on their intersection, then go into analyzing the numbers -->

<!-- ---
_Disclaimers and Epistemic Status_

https://aisafety.com/2017/09/26/map-ai-safety-community/


--- -->


<!-- LessWrong (by tag, word count)
EAF (by tag, word count)
Alignment Forum (by tag, word count)
ArXiV (by abstract/title, word count)
OpenAlex (by abstract/title, word count)

How many researchers working on or using AI systems relative to those who work on AI safety?
Would more researchers focusing on AI safety make a difference?
When does having more researchers improve safety?

Generate csv of the tags counts  Count appeared unique post | Number of times overall | Average count per year
Graphs of counts over time for batches of ~15 tags -->
