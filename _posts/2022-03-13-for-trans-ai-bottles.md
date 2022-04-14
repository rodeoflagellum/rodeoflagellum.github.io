---
layout: post
title:  "AI Safety ∩ AI/DL Research "
date:  2022-04-09 12:00:00 -0400
last_edit: 2022-04-12 12:10:00 -0400
permalink: "/for_dl_ai_safety/"
status: "Draft"
certainty: "7.0"
importance: "8.5"
impact: "5.5"
tags: [forecasting, prediction, ai, ai-safety, governance]
image: /assets/images/urja-bhatt-ChlQ7O0bVsY-unsplash.jpg
desc: "The full version of an essay I wrote on some trends in the AI Safety and general DL/AI communities for Metaculus's AI Progress Contest."
---

<!-- ⊂ -->

__Contribution__: In this essay, I contribute a first-pass search of research terms relevant to research in AI Safety, Deep Learning (DL), and Artificial Intelligence (AI), using [Google Scholar][gs], the [LessWrong][lw_pi]/[EAF][ea_Pi] API, [OpenAlex][openalex], and [ArXiV][arxiv][^1]. I perform a brief analysis of AI research trends based on term frequency, and find that AI Safety roughly accounts for 0.04497% of AI/DL research, and that for every AI Safety search result, there are roughly 1830 and 880 disjoint search results for research involving AI and DL, respectively. Additionally, I forecast the near-term future of select topics in AI Safety and DL/AI research. These forecasts and this preliminary review of research term frequency could be useful for AI risk reduction (1) through detailing which topics in AI Safety might be neglected, (2) through capturing how neglected AI Safety might be as a whole, relative to general research in AI/DL, and (3) through assessing how certain areas within DL that are relevant to AI risk might change over the coming years.

__Disclaimer and Epistemic Status__: I have a Bachelor's degree in Mathematics and Neuroscience, and have only been invested in AI Safety for several years; I have never published research or written academically on topics within AI Safety. There are issues with some of the methodologies I've used for this first-pass search, but I take care to make any of these shortcomings abundantly clear. I am fairly confident that my findings here will be useful for a more thorough attempt at estimating the size, influence, and future of the AI Safety research base relative to the general AI/DL research base.  

## Table of Contents
{:.no_toc}
* TOC
{:toc}

## [Outlook](#outlook)
_Here I examine the landscape of AI Safety and introduce some questions relating to how the general DL/AI research community handles AI risk_

[AI safety][ai_safety]{:target="_blank"} as a distinct discipline is relatively new; the earliest occurrence of "AI Safety" or "Safe AI" I could find in academic literature appears to be in 1995, in M. G. Rodd's publication _[Safe AI - is this Possible?][f]_, but the origins of AI Safety as a field are less obvious[^2]. In any case, the field is growing rapidly, both in terms of popularity[^3] and funding. In 2014, spending on strategical and technical interventions totaled [~1.75 million USD][impacts]{:target="_blank"} between the [Future of Humanity Institute][fhi]{:target="_blank"} (FHI) and the [Machine Intelligence Research Institute][miri]{:target="_blank"} (MIRI), two of the field's progenitors, and grew to at least ~9.1 million USD in 2017 (distributed across many new organizations), a ~5.2 fold increase[^4].

&emsp; More recently, [Open Philanthropy][open_phil] donated ~80 million USD across 2019 and 2020 towards reducing risks from AI. Should Open Philanthropy continue exist, the [Metaculus][meta]{:target="_blank"} community predicts that the funding for AI Safety will continue to increase, with median predictions of 78 million USD and 121 million USD for the years 2025 and 2030, respectively.

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/7418/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/7419/" width="100%" height="300"></iframe>

Why so much newfound funding for decreasing risk from AI? Nestled within the wider [deep learning][dl]{:target="_blank"} (DL) and AI research community, the field of AI Safety stems from the concern that AI systems can be deleterious, in a variety of ways minor or grave, to humanity, presently and in the future. AI systems and their wrath are often themes of [science fiction][fict]{:target="_blank"}, captured by systems such as [HAL 9000][hal]{:target="_blank"} or [Prime Intellect][prime]{:target="_blank"}. Perhaps [the earliest][ai_risk]{:target="_blank"} formulation of the threat of AI systems was in [Samuel Butler][butler]{:target="_blank"}'s 1863 essay entitled _[Darwin among the Machines][dar]{:target="_blank"}_, in which he wrote[^5]

> The upshot is simply a question of time, but that the time will come when the machines will hold the real supremacy over the world and its inhabitants is what no person of a truly philosophic mind can for a moment question.

The complexity of the aims and problems within AI Safety is driven in part by the complexity of intelligence and human values. From an informal viewpoint, the landscape of AI Safety can be understood by looking at the organizations and individuals who broadcast concern regarding AI and who generate research oriented around these concerns.

&emsp; One such map, created in 2017 by [Søren Elverlin][in_land]{:target="_blank"}[^6], attempts to capture the AI Safety community; I believe that it's a safe bet that most people who work in AI Safety will have heard of many of the entities listed in Elverlin's map.

![](/assets/images/ai_vs_dl/informal_map.png){: width=40% }

From a more formal viewpoint, the [Future of Life Institute][fli]{:target="_blank"}'s [AI Safety map][for_land]{:target="_blank"}[^7] has AI Safety as a root node containing five main branches of concern (___Validation___, ___Control___, ___Verification___, ___Security___, and ___Foundations___)[^8].

![](/assets/images/ai_vs_dl/formal_map.png){: width=40% }

Speculation is diverse regarding the internal form or the embodiment that an extremely dangerous AI system might take, but researchers often frame risk from AI in terms of what an AI system can achieve rather than in terms of how [complex it is or whether it's conscious][orth]. For example, [Stuart Armstrong][arm]{:target="_blank"}, an AI Safety researcher at the FHI, writes in _[Smarter Than Us][smart]{:target="_blank"}_

> In fact, knowing AI behavior can be a lot more useful to us than understanding intelligence. Imagine that a professor claimed to have the world's most intelligent AI and, when asked about what it did, responded indignantly, "Do? What do you mean _do_? It doesn't _do_ anything! It's just really, really smart!" Well, we might or might not end up convinced by such rhetoric, but that machine is certainly not one we'd need to start worrying about. But if the machine started winning bin on the stock market or crafting convincing and moving speeches - well, we still might not agree that it's "intelligent," but it certainly would be something to start worrying about.

One benchmark for considering the extent of what sophisticated AI systems might "do" is the degree of change they engender in human civilization. In this vein of thinking, Open Philanthropy provides the following definition of _[transformative AI][trans]{:target="_blank"}_ as "AI that precipitates a transition comparable to (or more significant than) the agricultural or industrial revolution"[^9].

<!-- Of course, considering the prospect of transformative AI, especially its timelines, is an important endeavor within AI Safety. -->

&emsp; As we have seen, AI Safety is a broad field, and transformative AI is but one of many framings for understanding the potential impacts of AI. Given the difficulties of forecasting [rare events][rare]{:target="_blank"}[^10], along with the current consensus that no AGI has ever existed (an empty reference class), predicting the trajectory and impact of transformative AI seems difficult. Nonetheless, it's somewhat plausible that, in the event transformative AI is created, it will stem from the DL research community; presently, 100 Metaculus members assign this possibility (i.e., [artificial general intelligence][agi] (AGI) will be based on DL) a median probability of 70%. Moreover, 121 Metaculites believe that the date that "the first [strong and robotic] AGI [is] first developed and demonstrated" will be between 2037 and 2084 (1st quartile - 3rd quartile), with a median prediction of 2052.

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/4055/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/5121/" width="100%" height="300"></iframe>

The full extent of the poor outcomes for humanity that could be engendered by transformative AI, or by AI systems generally, is beyond the scope of this essay. However, taking the magnitude of the severity of AI risks as given, these predictions, along with other trajectories researched by the AI Safety community, indicate the need for urgent monitoring and governance of AI systems and computing resource, predominantly in the DL community.

&emsp; Instrumentally speaking, ensuring that those in the general AI/DL research community are lucidly aware of the risks from AI might greatly improve the outcomes for humanity. As such, characterizing the size, influence, and general parameters of AI Safety within the broader context of AI/DL research might be a first step towards achieving this, and could benefit investigations on how much bottlenecks in mitigating AI risk relate to funding, interest, or talent. An example of such discussion regarding approaches to tackle AI alignment can be found in [Logan Riggs][riggs] recent [LessWrong][lw] post _[Convincing All Capability Researchers][rig_post]_ regarding [Not Relevant][nr]'s [comment][comment]:

> Give the world's thousand most respected AI researchers \\$1M each to spend 3 months working on AI alignment, with an extra \\$100M if by the end they can propose a solution alignment researchers can't shoot down. I promise you that other than like 20 industry researchers who are paid silly amounts, every one of them would take the million. They probably won't make any progress, but from then on when others ask them whether they think alignment is a real unsolved problem, they will be way more likely to say yes. That only costs you a billion dollars! I literally think I could get someone reading this the money to do this (at least at an initially moderate scale) - all it needs is a competent person to step up.

So, some questions to address AI Safety's place within the DL/AI community might be:

- How much has AI safety been researched, relative to the amount of research on AI/DL systems generally?
- How do the AI Safety community and general AI/DL research community overlap? How much of general AI/DL research, independent of AI Safety, addresses AI risk?
- How does the amount of interest in, funding in, and participation in the AI Safety community affect progress in AI Safety?

## [Querying](#query)

To begin answering these questions, and to lay some groundwork for future meta-science investigations of AI Safety, I decided that one reasonable method might be to query some of the research APIs and databases I frequently use when reading about AI Safety, or about DL/AI, to see how much work had been done in different areas. There are two main groupings I explored:

- Group 1: The intersection of AI Safety and DL, and the intersection of AI Safety and AI
- Group 2: Subfields of DL/AI such as Natural Language Processing (NLP), Reinforcement Learning (RL), and Mulimodal Learning (MM) that are important to AI Safety[^11]

For all groups, I searched through the years 2000 through 2022, and cut off 2022 in the graphs. The abbreviations are (AR) = ArXiV; (GS) = Google Scholar, no citations; (GS, R) = Google Scholar Reviews only, no citations; and (OA) = OpenAlex. In every search, I looked for exact phrases (e.g., "AI Safety" rather than AI Safety).

__Intersection of AI Safety and AI/DL__

![](/assets/images/ai_vs_dl/arxiv_gs_openalex_research.png)

The data in this graph comes from searching "AI Safety" and "Deep Learning", or from searching "AI Safety" and "Artificial Intelligence". The raw data for the years 2000 through 2022 can be found in the Appendix. Note that "AI Safety + DL (OA)" and "AI Safety + AI (OA)" produced no results, which I don't have an explanation for.

&emsp; The first noteworthy finding from this search, which is not too surprising, is that AI Safety overlaps more with work on Artificial Intelligence than it does on Deep Learning ($265 - 149 = 116$ more results for non-review Google Scholar search). The trend for ArXiV (this may be more useful for detecting _research_ signals in these fields, since Google Scholar produces many non-research results) is similar ($51 \text{ for AI } > 5 \text{ for DL }$)

__AI Safety, Deep Learning, and Artificial Intelligence__

![](/assets/images/ai_vs_dl/arxiv_gs_openalex_research_ai_dl_safe.png)

__Close Up of AI Safety Queries__

![](/assets/images/ai_vs_dl/CLOSE.png)

__Fields Related to AI Safety, and AI Safety__

![](/assets/images/ai_vs_dl/arxiv_research.png)


### Search 1

__Goal__

__Deficits__

__Results__

### Search 2

__Goal__

- Search individual terms related to AI Safety, Deep Learning, Reinforcement Learning, Multimodal Learning, and Natural Language Processing in OpenAlex, Google Scholar, ArXiV,
LessWrong, and the EA Forum as a first pass.

__Deficits__

__Results__

| Search Term | OpenAlex | ArXiV |
| :---: | :---: | :---: | :---: |
| Machine Learning | 134805 | 121092 |
| Artificial intelligence | 53193 | 50704 |
| Reinforcement Learning | 35951 | 12696 |
| Containment | 12381 | 22272 |
| Language Models | 7886 | 25976 |
| Computational Complexity | 3195 | 27626 |
| Active Learning | 15379 | 9269 |
| Interruptability | 22587 | 502 |
| Generative Adversarial Networks | 8087 | 7110 |
| Operator Modeling | 230 | 14126 |
| Natural Language Processing | 7553 | 6577 |
| Myopia | 12986 | 17 |
| Research Agendas | 12479 | 262 |
| Other Generative Models | 0 | 11123 |
| Value Learning | 162 | 10883 |
| interpretable model | 391 | 9178 |
| Brain-computer interfaces | 8806 | 485 |
| Optimization Measures | 232 | 7611 |
| Fixed Point Theorems | 7637 | 202 |
| Utility Functions | 2003 | 4947 |
| Oversight | 6738 | 111 |
| Q-learning | 3906 | 2098 |
| Decision Theory | 2033 | 3644 |
| Complexity of Value | 82 | 5508 |
| explainable model | 101 | 5472 |
| Implementation Testing | 137 | 5362 |
| Unsupervised Model Learning | 0 | 5115 |
| interpretable machine learning | 545 | 4405 |
| Multiobjective Optimization | 4562 | 198 |
| Value Structuring | 285 | 4227 |
| Follow-on Analysis | 613 | 3712 |
| Value Specification | 11 | 4097 |
| Simulated Exploration | 8 | 3060 |
| Impact Measures | 317 | 2642 |
| preference learning | 436 | 2485 |
| reward modeling | 155 | 2623 |
| Deep Q Network | 491 | 2202 |
| Penetration Testing | 2506 | 143 |
| Reward Functions | 358 | 2172 |
| Bounded Rationality | 2011 | 483 |
| Value Factoring | 173 | 2318 |
| Expressive Representations | 8 | 2482 |
| Temporal difference learning | 393 | 2070 |
| Multi-agent Approaches | 820 | 1480 |
| History Analysis | 1542 | 758 |
| Ought | 2154 | 145 |
| Domesticity | 1867 | 352 |
| Multi-modal Learning | 117 | 2055 |
| multimodality learning | 481 | 1584 |
| Value Sourcing | 99 | 1898 |
| Standard IT Security | 92 | 1896 |
| Bounded Exploration | 7 | 1908 |
| multi-modality learning | 117 | 1751 |
| Control Transfer | 157 | 1631 |
| Developmental Psychology | 1622 | 40 |
| Concept Drift | 1273 | 317 |
| explainable AI | 656 | 895 |
| Correlations of Dynamics | 74 | 1440 |
| Anthropic | 1421 | 9 |
| Reachability Analysis | 982 | 439 |
| GPT | 853 | 538 |
| Multimodal Machine Learning | 73 | 1273 |
| cross-modal learning | 71 | 1125 |
| verification for machine learning | 35 | 1121 |
| Inverse Reinforcement Learning | 694 | 441 |
| multimodal fusion | 562 | 542 |
| Hierarchical Reinforcement Learning | 514 | 567 |
| MIRI | 959 | 11 |
| Multi-modal Machine Learning | 15 | 935 |
| Capability control method | 0 | 920 |
| Multimodal deep Learning | 229 | 685 |
| multimodal representation | 123 | 779 |
| verifiable machine learning | 2 | 852 |
| Consistent Decision Making | 6 | 839 |
| Operator Value Learning | 0 | 821 |
| Engineering Alignment | 0 | 816 |
| multi-modal fusion | 214 | 591 |
| Distant Supervision | 448 | 351 |
| Inferring Latent Variables | 0 | 788 |
| Tool AI | 6 | 760 |
| Multiple Rewards | 15 | 750 |
| AI Capabilities | 19 | 736 |
| Realistic World-Models | 1 | 750 |
| Predicting Future Observations | 1 | 743 |
| Multi-modal deep Learning | 53 | 688 |
| multi-modal feature learning | 7 | 731 |
| DQN | 268 | 454 |
| AI ethics | 270 | 449 |
| Value Alignment | 107 | 543 |
| multimodal representation learning | 43 | 599 |
| multimodal artificial intelligence | 3 | 637 |
| Values Geometry | 2 | 630 |
| interpretable AI | 36 | 573 |
| Mild Optimization | 0 | 609 |
| Impossible Possibilities | 42 | 558 |
| multi-modal representation learning | 12 | 584 |
| multimodal feature learning | 8 | 563 |
| AI Impacts | 20 | 549 |
| Adaptive Control Theory | 64 | 504 |
| Formal Software Verification | 19 | 544 |
| Covariate Shift | 267 | 274 |
| logical induction | 7 | 516 |
| Logical Induction | 7 | 516 |
| Model Repair | 106 | 416 |
| safe exploration | 72 | 416 |
| Impact Regularizers | 2 | 477 |
| Economics of artificial intelligence | 33 | 423 |
| multi-modal artificial intelligence | 0 | 442 |
| AI Risk | 29 | 410 |
| Concept Geometry | 5 | 430 |
| Human-level artificial intelligence | 20 | 405 |
| OpenAI | 59 | 361 |
| Robustness to Distributional Shift | 6 | 412 |
| robust to distributional shift | 6 | 411 |
| Transparency / Interpretability | 3 | 406 |
| Proximal policy optimization | 143 | 261 |
| Environmental Goals | 202 | 202 |
| Motivation selection method | 0 | 398 |
| Supervised Reward Learning | 2 | 393 |
| Reward Uncertainty | 50 | 339 |
| Quantilization | 4 | 379 |
| Robust Policy Improvement | 2 | 380 |
| Logical Uncertainty | 8 | 370 |
| ai safety | 55 | 311 |
| AI safety | 55 | 311 |
| TD learning | 60 | 299 |
| Report Sufficiency | 0 | 359 |
| Counterfactual Reasoning | 194 | 164 |
| Theory of Ethics | 258 | 91 |
| Careful Engineering | 0 | 342 |
| Factored Cognition | 11 | 329 |
| Transformative AI | 9 | 331 |
| Adversarial ML | 12 | 327 |
| Drives and Affect | 22 | 307 |
| Sarsa | 248 | 78 |
| AI Governance | 80 | 239 |
| Goal Stability | 3 | 301 |
| Logical Priors | 1 | 298 |
| Active Reward Learning | 11 | 281 |
| Governance of artificial intelligence | 49 | 241 |
| Utility Function Security | 1 | 281 |
| multimodal observations | 8 | 263 |
| Monitoring AI | 4 | 264 |
| multi-modal observations | 3 | 264 |
| Causal Accounting | 40 | 217 |
| Active Calibration | 37 | 214 |
| Common Sense Reasoning | 82 | 164 |
| AI boxing | 1 | 242 |
| Testing and Quality Assurance | 123 | 120 |
| Controlling Another Algorithm | 0 | 239 |
| Intelligence Explosion | 10 | 213 |
| Intelligence explosion | 10 | 213 |
| Causal Identification | 35 | 186 |
| Bayesian Feature Selection | 43 | 172 |
| Learned Impact Regularizer | 0 | 211 |
| Collaborative Values Learning | 0 | 204 |
| Capability Distillation | 0 | 203 |
| Knows-What-It-Knows Learning | 0 | 197 |
| Computation hazard | 0 | 181 |
| DeepMind | 42 | 139 |
| value alignment problem | 8 | 169 |
| Normative Uncertainty | 40 | 136 |
| Superintelligence | 141 | 33 |
| ai alignment | 12 | 161 |
| aligned ai | 12 | 155 |
| Adversarial Reward Functions | 0 | 158 |
| Value Elicitation | 65 | 88 |
| Utility Indifference | 134 | 15 |
| Distance from User Demonstration | 0 | 138 |
| Ontological Value | 14 | 123 |
| multimodal AI | 12 | 106 |
| Universal Algorithmic Intelligence | 3 | 112 |
| Verification of Intelligent Systems | 2 | 111 |
| Realistic-Prior Design | 0 | 111 |
| tampering problem | 3 | 105 |
| Optimal Policy Preservation | 0 | 108 |
| Modeling Operator Intent | 0 | 106 |
| Episodic Contexts | 35 | 70 |
| Cognitive Parallels | 6 | 98 |
| Action and Outcome Evaluations | 1 | 99 |
| Conservative Concepts | 8 | 91 |
| Tripwire | 92 | 5 |
| Tripwires | 92 | 5 |
| Metareasoning | 84 | 12 |
| Embedded Agency | 54 | 39 |
| AI forecasting | 6 | 86 |
| multi-modal AI | 1 | 88 |
| Multimodal reinforcement learning | 7 | 81 |
| Machine Intelligence Research Institute | 0 | 87 |
| Theory of Counterfactuals | 17 | 70 |
| Ethics Mechanisms | 4 | 83 |
| Ethical Motivation | 34 | 51 |
| Model Lookahead | 3 | 80 |
| Adversarial Transparency | 0 | 83 |
| Limited-Information Maximum Likelihood | 12 | 70 |
| Multi-modal reinforcement learning | 4 | 77 |
| AI race | 16 | 64 |
| Knowledge Representation Ensembles | 0 | 77 |
| Inner Alignment | 0 | 75 |
| Visualization and Situation Awareness | 11 | 62 |
| Outer Alignment | 0 | 68 |
| Computational Deference | 0 | 67 |
| Narrow AI | 3 | 62 |
| Ontology Identification | 6 | 58 |
| AIXI | 32 | 29 |
| AI to Support Security | 0 | 61 |
| Instrumental Convergence | 0 | 59 |
| Robust Human Imitation | 0 | 59 |
| Safety Technique Awareness | 0 | 57 |
| Human Oversight | 18 | 39 |
| Misuse Risk | 17 | 39 |
| Automated Vulnerability Finding | 1 | 52 |
| Verified Component Design Approaches | 0 | 52 |
| Verification of Machine Learning Components | 0 | 49 |
| Resource Value Uncertainty | 0 | 49 |
| Goal-Directedness | 45 | 1 |
| Global Catastrophic Risk | 40 | 6 |
| Solomonoff Induction | 11 | 33 |
| Degrees of Value Evolution | 0 | 43 |
| Recursive Self-Improvement | 5 | 37 |
| Logical Counterfactuals | 0 | 42 |
| Reward Pretraining | 0 | 42 |
| Implicit Human Concepts | 0 | 42 |
| Goodhart's Law | 32 | 9 |
| iterated amplification | 0 | 40 |
| Iterated Amplification | 0 | 40 |
| Regulation and AI Risk | 0 | 40 |
| Multiobjective Reinforcement Learning | 25 | 15 |
| Narrow Value Learning | 0 | 39 |
| Oracle AI | 7 | 30 |
| Neuromorphic AI | 3 | 34 |
| Dimensionality Reduction With Anomaly Detection | 6 | 31 |
| Unsupervised Risk Estimation | 2 | 34 |
| Increasing Contextual Awareness | 1 | 34 |
| Dealing with Adversarial Testing | 0 | 35 |
| Projective Behavioral Bounds | 0 | 34 |
| Resource-Aware Reasoning | 0 | 33 |
| AI Safety Support | 0 | 32 |
| Penalize Influence | 0 | 31 |
| Newcomb's Problem | 24 | 6 |
| Corrigibility | 25 | 3 |
| Defined Impact Regularizer | 0 | 28 |
| Open Source Game Theory | 1 | 26 |
| Comprehensive AI Services | 0 | 26 |
| Human Preference Aggregation | 0 | 26 |
| Security-Validated Software Engineering | 0 | 26 |
| Interpretability of Blackboxes | 0 | 26 |
| Detecting Channel Switching | 0 | 25 |
| Unsupervised Value Iteration | 0 | 25 |
| Informed Oversight | 3 | 21 |
| cooperative inverse reinforcement learning | 7 | 16 |
| Cooperative Inverse Reinforcement Learning | 7 | 16 |
| Multilevel World-Models | 0 | 23 |
| Basic Alignment Theory | 0 | 22 |
| Indirect normativity | 5 | 17 |
| Non-Bayesian Confidence Estimation | 0 | 21 |
| Game Theoretic Framing | 3 | 16 |
| Orthogonality Thesis | 4 | 14 |
| Whole Brain Emulation | 16 | 2 |
| AI winter | 2 | 16 |
| Temporal Discount Rates | 5 | 13 |
| reward hacking | 2 | 15 |
| Alignment Research Center | 0 | 17 |
| Decision Under Bounded Computational Resources | 0 | 17 |
| Risk-Sensitive Performance Criteria | 3 | 13 |
| Moral Trade | 6 | 10 |
| Scaling Judgement Learning | 0 | 16 |
| Avoiding Negative Side Effects | 4 | 11 |
| Value Interrogation | 1 | 14 |
| ML with Contracts | 0 | 15 |
| Capability Amplification | 0 | 14 |
| AI Timelines | 0 | 12 |
| Values-Based Side Effect Evaluation | 0 | 12 |
| Reward Capping | 0 | 12 |
| Basic AI drive | 1 | 10 |
| Uncertainty Identification and Management | 0 | 10 |
| reward tampering | 2 | 7 |
| Center for Security and Emerging Technology | 0 | 9 |
| Ethical Ensembles | 0 | 9 |
| Infinite Ethics | 2 | 6 |
| Red Team Analysis | 0 | 8 |
| Computing Overhang | 0 | 7 |
| Artificial sentience | 4 | 3 |
| World Model Connectedness | 0 | 7 |
| Symbolic-Subsymbolic Integration | 0 | 7 |
| Mesa-Optimization | 0 | 6 |
| Mind crime | 2 | 4 |
| Bootstrapped Common Sense | 0 | 6 |
| AI skepticism | 0 | 5 |
| Nonlinear Fund | 1 | 4 |
| Verification of Cyberphysical Systems | 2 | 3 |
| Imitation Statistical Guarantees | 0 | 5 |
| Endowing Common Sense | 0 | 5 |
| Privileged Biases | 0 | 5 |
| Error-Tolerant Agent Design | 0 | 4 |
| Variable Indifference | 0 | 4 |
| scalable oversight | 0 | 3 |
| AI safety via debate | 1 | 2 |
| Coherent Extrapolated Volition | 2 | 1 |
| Alignment tax | 0 | 3 |
| Centre for the Governance of AI | 0 | 3 |
| Pursuing Environmental Goals | 0 | 3 |
| Counterexample Resistance | 0 | 3 |
| Psychological Analogues | 0 | 3 |
| Statistical-Behavioral Trust Establishment | 0 | 3 |
| Scalable Oversight | 0 | 3 |
| Rich Understanding of Human Commands | 0 | 3 |
| Transparent Reinforcement Learners | 0 | 3 |
| AI Takeoff | 0 | 2 |
| Collective superintelligence | 1 | 1 |
| Perverse instantiation | 0 | 2 |
| Sovereign AI | 0 | 2 |
| Foundations of Rational Agency | 2 | 0 |
| Grounded Ethical Evolution | 0 | 2 |
| Classical Computational Ethics | 0 | 2 |
| Unified Ethics Spaces | 0 | 2 |
| Seeded Common Sense | 0 | 2 |
| Switchable Objective Functions | 1 | 1 |
| Trust Policy Oversight | 0 | 2 |
| Detailed Audit Trails | 0 | 2 |
| Anthropic capture | 0 | 1 |
| Instrumental convergence thesis | 0 | 1 |
| Speed superintelligence | 0 | 1 |
| Center for Human-Compatible Artificial Intelligence | 0 | 1 |
| Reflective Induction Confidence | 0 | 1 |
| Making Verification More User Friendly | 0 | 1 |
| Verification of Whole AI Systems | 0 | 1 |
| Avoiding Reward Hacking | 0 | 1 |
| Use of Subsymbolic Processing In Symbolic Systems | 0 | 1 |
| Semisupervised Reward Learning | 0 | 1 |
| Human Judgement Learner | 0 | 1 |
| Transparency of Whiteboxes | 0 | 1 |
| Infra-Bayesianism | 0 | 0 |
| Paperclip Maximizer | 0 | 0 |
| Treacherous Turn | 0 | 0 |
| Humans Consulting HCH | 0 | 0 |
| AI Services (CAIS) | 0 | 0 |
| AI Safety Camp | 0 | 0 |
| CHAI (UC Berkeley) | 0 | 0 |
| Future of Humanity Institute (FHI) | 0 | 0 |
| Future of Life Institute (FLI) | 0 | 0 |
| Infrastructure profusion | 0 | 0 |
| Malignant AI failure mode | 0 | 0 |
| Quality superintelligence | 0 | 0 |
| Centre for Long-Term Resilience | 0 | 0 |
| Charity Science Foundation | 0 | 0 |
| Leverhulme Center for the Future of Intelligence | 0 | 0 |
| People for the Ethical Treatment of Reinforcement Learners | 0 | 0 |
| Safer Self-Modification | 0 | 0 |
| Vingean Reflection | 0 | 0 |
| Abstractly Reason About Superior Agents | 0 | 0 |
| Löbian Obstacle | 0 | 0 |
| Nontransitive Options | 0 | 0 |
| Verification of Recursive Self-Improvement | 0 | 0 |
| Averting Instrumental Incentives | 0 | 0 |
| Buried Honeypot Avoidance | 0 | 0 |
| Computational Humility | 0 | 0 |
| Generalized Fallibility Awareness | 0 | 0 |
| Averting Paranoia | 0 | 0 |
| Structured and Privileged Ethical Biases | 0 | 0 |
| Reversible Tasks via Variational Autoencoding | 0 | 0 |
| Ontology Update Thresholds | 0 | 0 |
| World-Embedded Solomonoff Induction | 0 | 0 |
| Perceptual Distance Agnostic World Models | 0 | 0 |
| Lengthening Horizons | 0 | 0 |
| Inductive Ambiguity Identification | 0 | 0 |
| Scalable Oversight of Ambiguities | 0 | 0 |
| Use of Structured Knowledge In Subsymbolic Systems | 0 | 0 |
| Dysfunctional Systems of Thought | 0 | 0 |
| Whole Brain Emulation Safety | 0 | 0 |
| Verified Downstack Software | 0 | 0 |
| Handling Improper External Behavior | 0 | 0 |
| Sensibility-Triggered Defence | 0 | 0 |
| Detecting and Managing Low Competence | 0 | 0 |
| Norm Denial of Service | 0 | 0 |

## Discussion

## Forecasting

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/5899/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/6586/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/5961/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/6299/" width="100%" height="300"></iframe>

<iframe src="//d3s0w6fek99l5b.cloudfront.net/s/1/questions/embed/6576/" width="100%" height="300"></iframe>

## Final Thoughts

## Appendix

### Search Terms

(coming soon)

### Querying Google Scholar

(coming soon)

### Querying OpenAlex

(coming soon)

### Querying ArXiV

(coming soon)

### Querying LW/EAF

(coming soon)


### Raw Output for Graphs

{'NLP': [122, 79, 66, 55, 54, 25, 52, 66, 70, 91, 86, 125, 225, 333, 557, 832, 1693, 2398, 3729, 5390, 7135, 8067, 2173], 'NLP_SAFE': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0], 'RL': [1, 5, 6, 6, 4, 2, 5, 5, 14, 17, 22, 47, 78, 72, 78, 135, 326, 770, 1392, 2280, 3044, 3367, 984], 'RL_SAFE': [1, 5, 6, 6, 4, 2, 5, 5, 14, 17, 22, 47, 78, 72, 78, 135, 326, 768, 1390, 2275, 3038, 3358, 978], 'MULT': [0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0, 1, 3, 3, 12, 19, 45, 71, 92, 184, 245, 78], 'MULT_SAFE': [0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0, 1, 2, 2, 9, 17, 37, 62, 83, 158, 221, 68], 'SAFE': [1, 1, 1, 0, 0, 1, 1, 0, 0, 2, 0, 7, 6, 5, 11, 7, 59, 79, 126, 277, 415, 558, 158], 'AI_SAFETY_AR': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 6, 5, 6, 19, 13, 14, 4], 'DL_AR': [0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 2, 2, 10, 54, 99, 305, 679, 1716, 3273, 4678, 6532, 6955, 1928], 'AI_AR': [128, 69, 129, 140, 169, 163, 176, 196, 284, 398, 514, 848, 1468, 1879, 1231, 1210, 2070, 3048, 4765, 5554, 8516, 13587, 3971], 'DL_AI_SAFETY_AR': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 4, 0, 0, 0], 'AI_AI_SAFETY_AR': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 5, 5, 4, 13, 10, 11, 3], 'AI_SAFETY': [0, 0, 0, 0, 3, 0, 0, 0, 1, 1, 0, 0, 0, 0, 1, 2, 4, 14, 33, 57, 76, 63, 10], 'AI_SAFETY_R': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0, 1, 3, 0], 'SAFE_DL': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 2, 6, 22, 30, 39, 43, 7], 'SAFE_DL_R': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 2, 0], 'SAFE_AI': [0, 0, 0, 0, 3, 0, 0, 0, 1, 1, 0, 0, 0, 0, 1, 2, 4, 14, 33, 57, 76, 63, 10], 'SAFE_AI_R': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 1, 0, 1, 3, 0], 'DL': [40, 25, 50, 54, 56, 91, 107, 106, 141, 157, 234, 202, 299, 459, 938, 2050, 4760, 10300, 25000, 59100, 60400, 57000, 4430], 'DL_R': [2, 2, 0, 1, 0, 1, 2, 3, 2, 4, 4, 2, 7, 7, 11, 15, 49, 96, 206, 350, 544, 810, 62], 'AI': [3590, 3020, 3420, 5010, 6270, 7080, 9340, 12100, 15900, 21100, 20700, 20600, 19200, 18100, 19900, 28300, 37000, 55600, 78800, 87100, 71700, 56800, 4340], 'AI_R': [26, 28, 24, 33, 38, 36, 44, 65, 87, 112, 109, 130, 118, 150, 134, 190, 239, 287, 443, 591, 840, 988, 99],'OP_DL': [6, 10, 12, 13, 15, 27, 29, 21, 32, 49, 44, 97, 106, 183, 392, 814, 1858, 4338, 9048, 14930, 21059, 27829, 6328], 'OP_AI': [317, 308, 345, 341, 429, 533, 558, 540, 551, 650, 636, 753, 784, 848, 894, 918, 1284, 1958, 4086, 7058, 11074, 14984, 3399], 'OP_SAFE': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 2, 4, 7, 13, 11, 16, 1], 'OP_DL_SAFE': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], 'OP_AI_SAFE': [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]}

### General Code

## Link Bibliography

(these are currently unordered and lack descriptions; my apologies - I will try to fix this in the near-term future)

[orth]: https://www.lesswrong.com/tag/orthogonality-thesis "https://www.lesswrong.com/tag/orthogonality-thesis"

[f]: https://sci-hubtw.hkvisa.net/10.1016/0952-1976(95)00010-x "https://sci-hubtw.hkvisa.net/10.1016/0952-1976(95)00010-x"

[gs]: https://scholar.google.com/ "https://scholar.google.com/"

[arxiv]: https://arxiv.org/ "https://arxiv.org/"

[openalex]: https://openalex.org/ "https://openalex.org/"

[lw_pi]: https://www.lesswrong.com/graphiql "https://www.lesswrong.com/graphiql"

[ea_Pi]: https://forum.effectivealtruism.org/graphiql "https://forum.effectivealtruism.org/graphiql"

[nr]: https://www.lesswrong.com/users/not-relevant "https://www.lesswrong.com/users/not-relevant"

[comment]: https://www.lesswrong.com/posts/j9Q8bRmwCgXRYAgcJ/miri-announces-new-death-with-dignity-strategy?commentId=kPBhEMBLGD2u9uicq "https://www.lesswrong.com/posts/j9Q8bRmwCgXRYAgcJ/miri-announces-new-death-with-dignity-strategy?commentId=kPBhEMBLGD2u9uicq"

[rig_post]: https://www.lesswrong.com/posts/vaHgLF2BCEdK3KxQd/convincing-all-capability-researchers "https://www.lesswrong.com/posts/vaHgLF2BCEdK3KxQd/convincing-all-capability-researchers"

[lw]: https://www.lesswrong.com/ "https://www.lesswrong.com/"

[riggs]: https://www.lesswrong.com/users/elriggs "https://www.lesswrong.com/users/elriggs"

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

[^1]: What is my reasoning for using Google Scholar, OpenAlex, LessWrong, EAF, and ArXiV? These entities came to mind when I questioned "How could I accumulate research on AI Safety or DL/AI generally?". In learning about AI Safety, most of my time has been spent on the EA Forum and LessWrong, along with an occasional look at the Future of Humanity Institute's work, and an occasional Google Scholar / Wikipedia / ArXiV query. I did not spend too much time looking for other research APIs or search tools. I used OpenAlex mostly because it is new and I wanted to get a feel for it, but also because it seems to contain much more research than standard research APIs. As will soon become apparent in this essay, I was limited in my use of Google Scholar because Google Scholar would boot me out after only a few hundred queries, and querying all the things I want to query would take too long to perform manually. For the EAF and LessWrong, I downloaded all or most of the posts (7089 and 16416 results, respectfully) from their APIs, but have ran out of time to create a decent method to search through them for all the research terms. I will send you the files containing the URLs to these posts upon request - just email me at rodeo DOT flagellum AT gmail DOT com. Also, please email me (or comment) links to other research databases that I should have known about or should have searched.

[^2]: I queried Google Scholar to find the earliest instances of the exact phrases "AI Safety" or "Safe AI". Of course, M.G. Rodd's paper likely does not mark the "dawn of the field of AI Safety". I am not familiar enough with AI Safety to know whether there is a consensus on some origin or major turning point for the field. If there is such an event, please point it out to me, so I can add it in the Outlook section.

[^3]: The rest of this essay will focus on aspects of the growing popularity AI Safety.

[^4]: I did not spend too much time on accumulating data on the current (04/10/2022) landscape of funding for research in AI Safety, but from anecdotal evidence, funding seems to be plentiful and to be supporting the surging number of researchers from physics, software development, and data science, among other fields, migrating to AI Safety.

[^5]: I did not spend much time exploring the earliest historical incidences of thinking on intelligent machines or on the risks incurred by developing artificial intelligence, so please don't assign much confidence that this is in fact the first written instance of thinking about AI risk.

[^6]: I did not spend any time researching how this is, or what their influence on AI Safety has been. The accuracy of the map as an informal representation of the AI Safety community seems on point, but I am biased as someone who has only spectated the development of the field.

[^7]: Given my present experience, I am unsure of how important the FLI is as a pioneer of AI Safety. I am not familiar with its history or influence in the field, other than the fact that, anecdotally, the organization seems important.

[^8]: I did not look for a description of how many named disciplines there were or for a description of how important each listed entity is for AI Safety (I think it would not be reasonable to assume that the size of the entity is roughly proportional to its influence).

[^9]: Open Philanthropy provides a second definition of transformative AI, given how nebulous the first definition is. The second definition (one or more of the descriptions must hold): <br><br>__(1)__ _AI systems capable of fulfilling all the necessary functions of human scientists, unaided by humans, in developing another technology (or set of technologies) that ultimately becomes widely credited with being the most significant driver of a transition comparable to (or more significant than) the agricultural or industrial revolution. Note that just because AI systems could accomplish such a thing unaided by humans doesn’t mean they would; it’s possible that human scientists would provide an important complement to such systems, and could make even faster progress working in tandem than such systems could achieve unaided. I emphasize the hypothetical possibility of AI systems conducting substantial unaided research to draw a clear distinction from the types of AI systems that exist today. I believe that AI systems capable of such broad contributions to the relevant research would likely dramatically accelerate it._,<br><br>__(2)__ _AI systems capable of performing tasks that currently (in 2016) account for the majority of full-time jobs worldwide, and/or over 50% of total world wages, unaided and for costs in the same range as what it would cost to employ humans. Aside from the fact that this would likely be sufficient for a major economic transformation relative to today, I also think that an AI with such broad abilities would likely be able to far surpass human abilities in a subset of domains, making it likely to meet one or more of the other criteria laid out here._,<br><br>__(3)__ _Surveillance, autonomous weapons, or other AI-centric technology that becomes sufficiently advanced to be the most significant driver of a transition comparable to (or more significant than) the agricultural or industrial revolution. (This contrasts with the first point because it refers to transformative technology that is itself AI-centric, whereas the first point refers to AI used to speed research on some other transformative technology.)_

[^10]: See <https://stats.stackexchange.com/questions/93523/how-do-we-predict-rare-events> and <https://www.semanticscholar.org/paper/The-limits-of-forecasting-methods-in-anticipating-Goodwin-Wright/c1d3c776a5f8bb131ee9e0cc3a939ab80c7cc0c6>

[^11]: Rather than using Google Scholar and OpenAlex to explore these fields, I decided to only use ArXiV because the Metaculus questions on these subjects used search queries unique to ArXiV.
