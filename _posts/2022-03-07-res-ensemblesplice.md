---
layout: post
title:  "EnsembleSplice"
date:  2022-03-07 12:21:00 -0500
last_edit: 2022-03-25 12:48:00 -0500
permalink: "/res_ensemblesplice/"
status: "Notes"
certainty: "Likely"
importance: "3"
impact: "5"
tags: [machine-learning, biology, research]
image: /assets/images/MQOhQhF8WN0.jpg
desc: "My reflections and thoughts on a research paper that I am trying to write."
---

## Table of Contents
{:.no_toc}
* TOC
{:toc}

## [Motivation](#motivation)

During the summer of the year 2021, I participated in an NSF-funded REU program on deep learning (DL) and bioinformatics. The paid internship was moderately difficult for me, at least relative to another REU I was in two years prior, and was aimed at having its students write and submit original research in DL. Each week the REU students, the advisors, and some PhD students had a group check-in on the REU student's research progress. Throughout the program, advisors, PhD students, and guest lecturers taught the REU students about various DL topics, such as natural language processing (NLP) and reinforcement learning (RL).

&emsp; All REU students had to present and submit their research progress on three separate occasions over the ten week period. These occasions were very, though not extremely, stressful. By the final presentation, the REU students were supposed to have their research ready to for submission to research journals. In my opinion, most of the research projects the REU students conducted (including my own) were low-impact - for a long time, I perceived them as "not worthy to be considered _actual science_", but have since updated this belief with the thought "while not particularly noteworthy, publicizing research is better than concealing it". All three advisors[^1] were set on getting the research of the REU students published, which makes sense, but my expectation for how intensely the advisors would push for publication was much too low. Generally speaking, the advisors were nice, albeit somewhat terse, and I frequently ate with them, especially with the school's NLP-guru + computer science department chair.

&emsp; While I wasn't programming, whiteboarding, or reading research papers, I spent some time hiking, looking for fossils, journaling, talking on the phone or on Discord, going on walks, hanging out with the PhD students, and exercising, among other things. I'm still in contact with one other REU student, who ended up merging his work from the summer with another student's work, which they submitted jointly about a month ago. From where things left off at the end of the summer, I'd estimate that most of the students got their work submitted to a journal[^2].

&emsp; I feel somewhat overwhelmed by how much I want to comment on all the various aspects and minutia of this "journey". During the remainder of my 2021 summer, I made incremental improvements to my work, but rapidly lost interest in the endeavor. This loss of interest was likely a consequence of capitulating from the exhaustion I accumulated during my time at program. I started the program less than one week after my spring semester ended, and felt that I really needed time to pursue things unrelated to my REU research. Additionally, there were some issues with my code and were some major tasks that still needed to be completed before I could submit my work for publication. These things weighed on me - I would find any excuse to not think about the project, or to avoid doing any work on the project.

&emsp; As time wore on, I contacted my advisor less frequently, and eventually found comfort in using the excuse that the start of my last semester at college meant I was unable to get much done on my research[^3]. For several months, I didn't touch EnsembleSplice, and only took it up again in December 2021. The same feelings of dread returned, and I didn't do much with my code or the draft I wrote at the end of the summer. I resolved to complete the work by the end of February 2022; this didn't occur of course (planning fallacy!), and as a result my internal monologue was polluted with statements like "you weren't meant for research", "look at REU student X, he was able to get it done so elegantly", "if you had done this incrementally, you'd already be done!", "this [me not having completed EnsembleSplice in February] is proof you are inferior", and "you are such a loser".

&emsp; In early March 2022, I had some sort of mental breakthrough while sitting on my couch. Some cognitive burden shifted, and now, rather than being inhibited by my fears that my work wasn't thorough, important, or efficient enough, I accepted that it was OK to completely refactor my code, to implement more tests, and to spend as much time as I wanted making things more efficient. I was motivated by a desire to leave no rock unturned in my research pipeline. As of 20 March 2022, this motivation persists. This newfound hope for EnsembleSplice also lead me to creating this page. In the rest of this post, I want to cover each of the prospective sections of my upcoming paper, and in detail, explain my reasoning, concerns, and doubts for them.

__Overview of my research project__: My work seeks to use a technique from machine learning (ML) called ensemble learning to outperform state-of-the-art DL models in the task of splice site prediction. In particular, I ensemble a group of artificial neural networks (ANNs). The contribution of EnsembleSplice to science can be thought of as "_an example of a method from ML/DL that has not been used for splice site prediction that outperforms some existing DL methods for splice site prediction_". This is a very small contribution and, as such, I consider it to fall into the following class of contributions: "_an example of a scientific problem humanity applied ML/DL to in the early 21st century_".

__Overview of this post__: In the remaining sections, I look at the state of my paper as of 25 March 2022. Much of the writing from this version remained unchanged since the end of the 2021 summer. After going through the paper, I comment on and analyze the content of each section in depth. I then include the version of the paper that I submitted for review. Finally, I include the accepted version of the paper, should it be accepted at some point.

## [A Work in Progress](#a-work-in-progress)

### [Abstract](#abstract)


> **Motivation:** Identifying splice site (SS) regions is an important step in the genomic DNA sequencing pipelines of both biomedical and pharmaceutical research. Within this research purview, efficient and accurate SS detection is highly desirable, and a variety of computational models have been developed towards this end. In particular, neural network (NN) architectures have recently been shown to outperform classical machine learning (ML) approaches for the task of SS prediction. Despite these advances, there is still considerable potential for improvement, especially in terms of model accuracy and inter-species generalizability.
>
**Results:** We contribute EnsembleSplice for the problem of splice site prediction. EnsembleSplice's ensemble learning framework consists of dense and convolutional neural networks, that, when ensembled, outperform existing state-of-the-art SS detection architectures. When evaluated on genomic DNA datasets for *Homo sapiens* and *Arabidopsis thaliana*, EnsembleSplice attained average accuracies of 96.02% for donor SS and 94.59% for acceptor SS.
>
**Availability:** Code is made available for reproducibility purposes at [GitHub repository].\\
**Contact:** [advisor's email address]

### [Introduction](#introduction)

___Version 0___

Organismal genomes are studied primarily through genome annotation, which involves classifying genomic elements based on their function or location . This annotation is typically performed at the nucleotide-level to determine the locations of key genetic elements in DNA sequences, at the protein-level to evaluate proteomic function, or at the process-level to study the mechanisms underlying gene interaction .

Genes responsible for protein coding are composed of alternating nucleotide regions called introns, which are the non-protein coding regions, and exons, which are the protein coding regions. During DNA transcription in eukaryotic cells, introns are cut out by spliceosomes and exons are combined together; this general process is called RNA splicing, and is critical for the creation of mature mRNA from pre-mRNA and for protein synthesis . The dinucleotides AG and GT are often present in the $3'$ intron boundary, or donor splice site (DoSS) region, and the $5'$ intron boundary, or acceptor splice site (AcSS) region, respectively, and are biological markers involved in RNA splicing  (see Figure ). Nucleotide-level annotation was designed to accurately detect the location of these splice sites, which can be used to identify genes in eukaryotic genomes; a variety of other computational approaches have also been developed for this purpose.

EnsembleSplice is one such computational method, and is a deep learning pipeline that employs ensemble learning for splice site prediction. Ensemble learning methods have been shown to enhance classification results, and have, in recent years, been successfully applied within the field of bioinformatics  .

We contribute the following to research on splice site prediction:
- We develop EnsembleSplice, a DL architecture that learns from an ensemble of convolutional neural network (CNN) and dense neural network (DNN) architectures to achieve state-of-the-art performance at predicting splice sites.
- We evaluate the performance of EnsembleSplice across three datasets and two organisms.
- We create a usage tutorial, detail all architectural design choices, and, for reproducibility, make the code available at <https://github.com/tmartin2/EnsembleSplice>

### Related Work

___Version 0___

The earliest research on genomic DNA splice site prediction primarily leveraged methods in machine learning and probabilistic modeling. GeneSplicer first achieved record accuracies with its Markov-model-enhanced maximal dependence decomposition decision trees, and this contributed to the popularity of Markov models for splice site prediction. . Markov models were also sometimes used as a preprocessing step for other methods, such as shallow neural networks, or were hybridized to enhance performance . Also integral to early progress on the problem of splice site prediction, support vectors machines (SVMs) were lauded for their simplicity and speed . While the intricacy of these machine learning models grew, their accuracy plateaued. This was due to both compute-power and the bottleneck of having to manually select the model's features.

Deep learning (DL), along with better computing architectures, has largely solved these issues. In recent years, splice site prediction has been done using deep neural networks (NNs), including convolutional neural networks (CNNs) and recurrent neural networks (RNNs). CNNs are the most frequently adopted architecture, and deviate widely in their depth (number of layers) and parameters across studies. SpliceRover, SpliceFinder, DeepSplicer, DeepSS, Spliceator, and iss-CNN, among others,   employ CNNs. In some instances, such as that of Splice2Deep, multiple CNN models are created and the results are aggregated to produce a best final estimate . Typically, human true and false donor and acceptor sites are one-hot-encoded and batch feed into these architectures, which perform automatic feature extraction, and exceed the earlier ML techniques in terms of their classification accuracy. Other DL methods such as the long-short term memory (LSTM) neural network or recurrent neural network (RNN), which both are sequence learning networks and often employed in time series analyses, have been used on genomic DNA. A notable example is SpliceViNCI, which consists of a bidirectional LSTM augmented with integrated gradients .

### Methodology

#### Datasets

___Version 0___

Each dataset used in this paper consists of both confirmed true (positive) DoSS/AcSS and confirmed false (negative) AcSS/DoSS. Evaluation of classification performance is separated by splice site type, which means that one model is trained to distinguish between false/true DoSS regions and another is trained to distinguish between false/true AcSS regions. It is important to note that EnsembleSplice is tested on both imbalanced datasets (HS$^3$D) and balanced ones (*Homo sapiens* and *Arabidopsis thaliana*). See Table .


#### EnsembleSplice Pipeline

#### One-hot Encoding

#### Cross Validation, Training, and Testing

### Experiments and Results

#### Evaluation Metrics

#### Model Benchmarking

### Conclusion

### References

## Final Submission

## Appendix

## Link Bibliography

## Notes

#### *Cover Photo*

The [cover photo](https://unsplash.com/photos/7ALIbwRkwig) for this page was likely taken by [Jonas Denil](https://unsplash.com/@jonasdenil). I found the photo on [Unsplash](https://unsplash.com/). To my knowledge, my use of this photo is permissible under Unsplash's [license](https://unsplash.com/license): "_Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service._"

#### *Footnotes*

[^1]: One advisor specialized in NLP; the other in computational neuroscience (BCI's in particular); and the last in bioinformatics. One other student and I worked with the bioinformatics advisor, while the other six REU students were distributed evenly across the
other advisors.

[^2]: As of 20 March 2022, I am still working on getting my work finished and submitted.

[^3]: This excuse was partially true, and I still felt badly about not doing more during the remainder of my summer. Had I incrementally worked on my REU project during the fall semester, I might have gotten most of it done. Whenever I thought about the project during the semester, I felt some sort of mental collapse, and uttered
things akin to "no, no, I can't do this, I have other work to do" internally.
