---
layout: post
category: Draft
title:  "EnsembleSplice"
date:  2022-03-07 12:21:00 -0400
modified: 2022-05-03 12:48:00 -0400
permalink: "/res_ensemblesplice/"
image: /assets/images/MQOhQhF8WN0.jpg
description: "My reflections and thoughts on a research paper that I am trying to write. This is mostly for me to unleash some steam after spending a lot of time working on something that I do not believe is too important."
tags: [machine-learning, biology, research]
specifics: [DNA-splice-sites, ensemble-learning]
type: "Draft"
status: "Incomplete"
word_count: "yes"
reading_time: "yes"
---


## [Table of Contents](#top)
{:.no_toc}
* TOC
{:toc}
<!--
Orderings
TOC
Motivation
A Work in Progress
  Abstract
  Introduction
  Related Work
  Methodology
    Datasets
      HS3D
      Homo + Arab
    One Hot Encoding
    EnsembleSplice Pipeline
    Cross Validation, Training, and Testing
  Experiments and Results
    Evaluation Metrics
    Performance Benchmarking
  Conclusion
  Acknowledgements
Paper Breakdown (Issues)
  Incomplete Knowledge (abs, intro, rel)
  Ensembling, Really?
  Unoptimized Code
  Hyperparameter Tuning
  "State-of-the-art" (critique of other)
  Its Place in Science (where this falls within science)
Reflections
  Was it worth it?
  Did I have fun?
  Would I do it again?
Further Reading
_Research papers and Wikipedia pages that may be interesting if you found this
topic interesting_
External Links
Appendices
Link Bibliography (all links and citations, including additional tags
for some of the citations)
Footnotes
-->

## [Motivation](#motivation)
_My description of where this research enterprise started, where I currently am with it, and where I would like for it to end._

During the summer of the year 2021, I participated in an NSF-funded REU program on deep learning (DL) and bioinformatics. The paid internship was moderately difficult for me, at least relative to another REU I was in two years prior, and was aimed at having its students write and submit original research in DL. Each week the REU students, the advisors, and some PhD students had a group check-in on the REU student's research progress. Throughout the program, advisors, PhD students, and guest lecturers taught the REU students about various DL topics, such as natural language processing (NLP) and reinforcement learning (RL).

&emsp; All REU students had to present and submit their research progress on three separate occasions over the ten week period. These occasions were very, though not extremely, stressful. By the final presentation, the REU students were supposed to have their research ready to for submission to research journals. In my opinion, most of the research projects the REU students conducted (including my own) were low-impact - for a long time, I perceived them as "not worthy to be considered _actual science_", but have since updated this belief with the thought "while not particularly noteworthy, publicizing research is better than concealing it". All three advisors[^1] were set on getting the research of the REU students published, which makes sense, but my expectation for how intensely the advisors would push for publication was much too low. Generally speaking, the advisors were nice, albeit somewhat terse, and I frequently ate with them, especially with the school's NLP-guru + computer science department chair.

&emsp; While I wasn't programming, whiteboarding, or reading research papers, I spent some time hiking, looking for fossils, journaling, talking on the phone or on Discord, going on walks, hanging out with the PhD students, and exercising, among other things. I'm still in contact with one other REU student, who ended up merging his work from the summer with another student's work, which they submitted jointly about a month ago. From where things left off at the end of the summer, I'd estimate that most of the students got their work submitted to a journal[^2].

&emsp; I feel somewhat overwhelmed by how much I want to comment on all the various aspects and minutia of this "journey". During the remainder of my 2021 summer, I made incremental improvements to my work, but rapidly lost interest in the endeavor. This loss of interest was likely a consequence of capitulating from the exhaustion I accumulated during my time at program. I started the program less than one week after my spring semester ended, and felt that I really needed time to pursue things unrelated to my REU research. Additionally, there were some issues with my code and were some major tasks that still needed to be completed before I could submit my work for publication. These things weighed on me - I would find any excuse to not think about the project, or to avoid doing any work on the project.

&emsp; As time wore on, I contacted my advisor less frequently, and eventually found comfort in using the excuse that the start of my last semester at college meant I was unable to get much done on my research[^3]. For several months, I didn't touch EnsembleSplice, and only took it up again in December 2021. The same feelings of dread returned, and I didn't do much with my code or the draft I wrote at the end of the summer. I resolved to complete the work by the end of February 2022; this didn't occur of course (planning fallacy!), and as a result my internal monologue was polluted with statements like "you weren't meant for research", "look at REU student X, he was able to get it done so elegantly", "if you had done this incrementally, you'd already be done!", "this [me not having completed EnsembleSplice in February] is proof you are inferior", and "you are such a loser".

&emsp; In early March 2022, I had some sort of mental breakthrough while sitting on my couch. Some cognitive burden shifted, and now, rather than being inhibited by my fears that my work wasn't thorough, important, or efficient enough, I accepted that it was OK to completely refactor my code, to implement more tests, and to spend as much time as I wanted making things more efficient. I was motivated by a desire to leave no rock unturned in my research pipeline. As of 20 March 2022, this motivation persists. This newfound hope for EnsembleSplice also lead me to creating this page. In the rest of this post, I want to cover each of the prospective sections of my upcoming paper, and in detail, explain my reasoning, concerns, and doubts for them.

__Overview of my research project__: My work seeks to use a technique from machine learning (ML) called ensemble learning to outperform state-of-the-art DL models in the task of splice site prediction. In particular, I ensemble a group of artificial neural networks (ANNs). The contribution of EnsembleSplice to science can be thought of as "_an example of a method from ML/DL that has not been used for splice site prediction that outperforms some existing DL methods for splice site prediction_". This is a very small contribution and, as such, I consider it to fall into the following class of contributions: "_an example of a scientific problem humanity applied ML/DL to in the early 21st century_".

__Overview of this post__: In the remaining sections, I look at the state of my paper as of 25 March 2022. Much of the writing from this version remained unchanged since the end of the 2021 summer. After going through the paper, I comment on and analyze the content of each section in depth. I then include the version of the paper that I submitted for review. Finally, I include the accepted version of the paper, should it be accepted at some point.

[Back to top](#top)

---

## [Present State](#present-state)
_My current progress on EnsembleSplice._

### [Abstract](#abstract)
_The abstract of the paper; an overview of the topic and my contribution._

**Motivation:** Identifying splice site (SS) regions is an important step in the genomic DNA sequencing pipelines of both biomedical and pharmaceutical research. Within this research purview, efficient and accurate SS detection is highly desirable, and a variety of computational models have been developed towards this end. In particular, neural network (NN) architectures have recently been shown to outperform classical machine learning (ML) approaches for the task of SS prediction. Despite these advances, there is still considerable potential for improvement, especially in terms of model accuracy and inter-species generalizability.\\
**Results:** We contribute EnsembleSplice for the problem of splice site prediction. EnsembleSplice's ensemble learning framework consists of dense and convolutional neural networks, that, when ensembled, outperform existing state-of-the-art SS detection architectures. When evaluated on genomic DNA datasets for *Homo sapiens* and *Arabidopsis thaliana*, EnsembleSplice attained average accuracies of 96.02% for donor SS and 94.59% for acceptor SS.\\
**Availability:** Code is made available for reproducibility purposes at [GitHub repository].\\
**Contact:** [advisor's email address]

[Back to top](#top)

### [Introduction](#introduction)
_The introduction - an overview of the biology of splice sites._

Organismal genomes are studied primarily through genome annotation, which involves classifying genomic elements based on their function or location . This annotation is typically performed at the nucleotide-level to determine the locations of key genetic elements in DNA sequences, at the protein-level to evaluate proteomic function, or at the process-level to study the mechanisms underlying gene interaction.\\
&emsp; Genes responsible for protein coding are composed of alternating nucleotide regions called introns, which are the non-protein coding regions, and exons, which are the protein coding regions. During DNA transcription in eukaryotic cells, introns are cut out by spliceosomes and exons are combined together; this general process is called RNA splicing, and is critical for the creation of mature mRNA from pre-mRNA and for protein synthesis . The dinucleotides AG and GT are often present in the $3'$ intron boundary, or donor splice site (DoSS) region, and the $5'$ intron boundary, or acceptor splice site (AcSS) region, respectively, and are biological markers involved in RNA splicing  (see Figure ). Nucleotide-level annotation was designed to accurately detect the location of these splice sites, which can be used to identify genes in eukaryotic genomes; a variety of other computational approaches have also been developed for this purpose.

![](/assets/images/ensemblesplice/splicing.png){: width=40% }

&emsp; EnsembleSplice is one such computational method, and is a deep learning pipeline that employs ensemble learning for splice site prediction. Ensemble learning methods have been shown to enhance classification results, and have, in recent years, been successfully applied within the field of bioinformatics.\\
We contribute the following to research on splice site prediction:
- We develop EnsembleSplice, a DL architecture that learns from an ensemble of convolutional neural network (CNN) and dense neural network (DNN) architectures to achieve state-of-the-art performance at predicting splice sites.
- We evaluate the performance of EnsembleSplice across three datasets and two organisms.
% , comparing model accuracies across species and examining the transfer learning capabilities between genomes.
- We create a usage tutorial, detail all architectural design choices, and, for reproducibility, make the code available at [GitHub repository].

[Back to top](#top)

### [Related Work](#related-work)
_The related works - an overview of the history of splice site detection and classification._

The earliest research on genomic DNA splice site prediction primarily leveraged methods in machine learning and probabilistic modeling. GeneSplicer first achieved record accuracies with its Markov-model-enhanced maximal dependence decomposition decision trees, and this contributed to the popularity of Markov models for splice site prediction. . Markov models were also sometimes used as a preprocessing step for other methods, such as shallow neural networks, or were hybridized to enhance performance. Also integral to early progress on the problem of splice site prediction, support vectors machines (SVMs) were lauded for their simplicity and speed. While the intricacy of these machine learning models grew, their accuracy plateaued. This was due to both compute-power and the bottleneck of having to manually select the model's features.\\
&emsp; Deep learning (DL), along with better computing architectures, has largely solved these issues. In recent years, splice site prediction has been done using deep neural networks (NNs), including convolutional neural networks (CNNs) and recurrent neural networks (RNNs). CNNs are the most frequently adopted architecture, and deviate widely in their depth (number of layers) and parameters across studies. SpliceRover, SpliceFinder, DeepSplicer, DeepSS, Spliceator, and iss-CNN, among others, employ CNNs. In some instances, such as that of Splice2Deep, multiple CNN models are created and the results are aggregated to produce a best final estimate. Typically, human true and false donor and acceptor sites are one-hot-encoded and batch feed into these architectures, which perform automatic feature extraction, and exceed the earlier ML techniques in terms of their classification accuracy. Other DL methods such as the long-short term memory (LSTM) neural network or recurrent neural network (RNN), which both are sequence learning networks and often employed in time series analyses, have been used on genomic DNA. A notable example is SpliceViNCI, which consists of a bidirectional LSTM augmented with integrated gradients.

[Back to top](#top)


### [Methodology](#methodology)
_The methodology - datasets, architectures, design features, and procedures._

#### [Datasets](#datasets)

#### [HS3D](#hs3d)

#### *[Homo sapiens & Arabidopsis thaliana](#homo-arab)*

#### [One Hot Encoding](#one-hot-encoding)

#### [EnsembleSplice Pipeline](#pipeline)

#### [Cross Validation, Training, and Testing](#val-train-test)

[Back to top](#top)

### [Experiments and Results](#experiments-results)
_EnsembleSplice's performance relative to 3 other state-of-the-art DL methods for splice site detection._

#### [Evaluation Metrics](#evaluation-metrics)

#### [Performance Benchmarking](#performance-benchmarking)

[Back to top](#top)

### [Conclusion](#conclusion)
_How did EnsembleSplice do? and is it useful?_


### [Acknowledgements](#acknowledgments)
_Extending my thanks to some people (note this section is different from the that of the original paper)_

---

## [Paper Breakdown (Issues)](#issues)
_Criticisms of myself and the scientific community with regard to poor code implementations, researcher incentives, and minimum thresholds for scientific contributions._

### [Incomplete Knowledge](#incomplete-knowledge) (abs, intro, rel)
_Subjective estimates for how much I might be missing with my research._

<!-- Hehe ### [Ensembling, Really?](#ensembling)
_The elephant in the room - can EnsembleSplice really be said to use "ensemble learning"._ -->

### [Unoptimized Code](#unoptimized-code)
_Thoughts on how my code could be optimized, and a justification for why I don't think it is worth it to fully pursue these adjustments._

### [Hyperparameter Tuning](#hparam-tuning)
_A short discussion and series of questions on the effectiveness of hyperparamter tuning._

### ["State-of-the-art"](#state-of-the-art)
_A brief critique of research using deep learning for splice site prediction, and my thoughts on how researchers are wasting their time._

### [Place in Science](#place-in-science)
_Some commentary on where EnsembleSplice falls within science; what is its contribution,  and how will people regard it in the future?_

<!-- (where this falls within science) -->

---

## [Reflections](#reflections)

### [Was it worth it?](#worth-it-question)

### [Did I have fun?](#fun-question)

### [Would I do it again?](#again-question)

---

## [Further Reading](#further-reading)
_Research papers and Wikipedia pages that may be interesting if you found this topic interesting_

## [External Links](#external-links)

---


## [Appendices](#appendices)


### [Code Review](#code-review)

### [Sub-Model Figures](#sub-model-figures)

### [References](#references)

---

## [Link Bibliography](#link-bibliography)




>Each dataset used in this paper consists of both confirmed true (positive) DoSS/AcSS and confirmed false (negative) AcSS/DoSS. Evaluation of classification performance is separated by splice site type, which means that one model is trained to distinguish between false/true DoSS regions and another is trained to distinguish between false/true AcSS regions. It is important to note that EnsembleSplice is tested on both imbalanced datasets (HS$^3$D) and balanced ones (*Homo sapiens* and *Arabidopsis thaliana*). See Table .



>The Homo Sapiens Splice Sites Dataset (HS$^3$D) consists of human genomic DNA introns and exons extracted from the Primate Division of GenBank Rel.123. There are 2,796 confirmed positive DoSS regions, 2,880 confirmed positive AcSS regions, 271,937 confirmed negative DoSS regions, and 329,374 confirmed negative AcSS regions. This paper randomly selects 10000 false DoSS regions and 10000 false AcSS regions from the 271,937 and 329,374 available in the dataset, respectively; the Python code ```random.seed(123454)``` is used to shuffle the entire HS$^3$D dataset before the false DoSS and false AcSS subsets are selected. The nucleotide consensus AG for AcSS regions occurs at positions 69 and 70, and the nucleotide consensus GT for DoSS regions occurs at positions 71 and 72. The HS$^3$D dataset can be accessed at <http://www.sci.unisannio.it/docenti/rampone/>.



>The *Homo sapiens* and *Arabidopsis thaliana* datasets consist of splice site regions selected from annotated genomic DNA sequences for *Homo sapiens* and *Arabidopsis thaliana* in Ensembl . The peripheral nucleotide sequences padding each AcSS or DoSS were determined via Bedtools . Each splice  site region in the datasets is $602$ nucleotides long; each DoSS region has consensus GT at positions $301$ and $302$, and each AcSS has consensus AG also at positions $301$ and $302$. In the  *Homo sapiens* dataset, there are $250,400$ confirmed positive and negative DoSS regions, and $248,150$ confirmed positive and negative AcSS regions. The *Arabidopsis thaliana* dataset includes $110,314$ confirmed positive and negative DoSS regions, and $112,336$ confirmed positive and negative AcSS regions. The confirmed negative AcSS and DoSS regions were selected from chromosomes $21$, $2$, $2L$, $1$, and $I$. Again, this paper randomly selects $8000$ true/false DoSS regions and $8000$ true/false AcSS regions from both datasets. As with the HS$^3$D dataset, the Python code ```random.seed(123454)``` is used for shuffling the *Homo sapiens* and *Arabidopsis thaliana* datasets before the DoSS and AcSS subsets are selected. The *Homo sapiens* and *Arabidopsis thaliana* datasets can be accessed at <https://github.com/SomayahAlbaradei/Splice_Deep>.
>
![](/assets/images/ensemblesplice/t1.png){: width=40% }



>We now propose EnsembleSplice, a DL architecture that consists of an ensemble of three CNN and three DNN sub-models, for the task of splice site detection. See Figure 2 for the full architecture.
>
>The sub-models in EnsembleSplice generate predictions for whether genomic DNA input sequences are positive DoSS or negative DoSS, or if the AcSS model is being used, for whether the sequences are positive AcSS or negative AcSS. These binary predictions are then aggregated (stacked) into a new dataset, where each sub-model's predictions become a column vector, and this dataset is then fed into a Logistic Regression classifier, which produces the final predictions for the inputted sequences.
>
Consider a family \\[ \mathcal{D} = \{S_0, S_1, \dotsc, S_n\} \\] of nucleotide splice site regions. We have the ordered set \\[S_i = \{x_1, x_2, \dotsc, x_{\|S_i\|}\}\\] where $S_i$ is the $i$-th nucleotide splice site region, and \\[x_j \in X = \{\text{A}, \text{C}, \text{G}, \text{T}\}\text{, } 0 \leq j \leq \|S_i\| \\]
For all $0 \leq i \leq n$, $S_i$ is encoded as a $\|S_i\| \times \|X\|$ binary matrix through one-hot encoding. These encoded sequences are fed to the three CNNs and three DNNs.
>
>Each CNN sub-model in EnsembleSplice is composed of three convolutional layers and a dropout layer. The convolutional layers automatically extract local and global features from the AcSS or DoSS input sequences. In particular, these layers form complex representations of the sequences, and are the components of the CNN that allow it to accurately discriminate between the true/false acceptor/donor sites. The first layer has $72$ convolutional filters and a kernel size of $5$, the second layer has $144$ convolutional filters and a kernel size of $7$, and the third layer has $168$ convolutional filters and a kernel size of $7$. Each convolutional layer employs the $ReLU$ activation function as its final component; this removes noisy or otherwise irrelevant features, thus improving feature selection . Additionally, each convoluational layer has a stride size of $1$. Next, a dropout layer prunes a percentage ($20\%$) of each network's total convolutional nodes, which limits the co-dependencies each node in the network has on other nodes in the network, subsequently reducing model overfitting . Lastly, the output is fed through a $Softmax$ activation function, which produces, for each given input sequence, a probability of that sequence being a true/false acceptor/donor site. The ADAM optimizer with an inverse time decay learning rate schedule is used during model compilation . This architecture is consistent across the CNN sub-models, and is used for both AcSS prediction and DoSS prediction. The CNN architecture parameters were selected using hyperparameter tuning. For the hyperparameter tuning, see Table .
>
>The DNN sub-models in EnsembleSplice consist of two fully-connected dense layers, followed by a dropout layer, another fully-connected dense layer, and another dropout layer. The first two fully-connected dense layers have $704$ and $224$ nodes, respectively, and both use a kernel regularizer with an L2 regularization penalty of $0.025$. The third fully-connected densee layer has $512$ nodes, but uses no regularization penalties. The first dropout layer prunes $10\%$ of the DNN's nodes and the second dropout layer prunes $15\%$. Each fully-connected layer incorporates the $ReLU$ activation function. Identical to the CNN sub-models, the output layer is a $Softmax$ activation function and model compilation for the DNN sub-models is completed via the ADAM optimizer with an inverse time decay learning rate schedule. All DNN sub-models use this architecture for both AcSS prediction and DoSS prediction, and the parameters for this architecture were also selected using hyperparameter tuning.
>
> EnsembleSplice is implemented via the TensorFlow/Keras framework . For all experiments conducted, $30$ was the maximal number of epochs used for training. The early model stopping callback, which ceases training if the model's validation loss does not improve for a selected number of epochs, was used during training and validation, which occurred in Google Colaboratory <https://colab.research.google.com/>{https://colab.research.google.com/} and made use of Graphical Processing Unit (GPU) hardware. Cross validation was used for initial CNN and DNN sub-model architecture testing.
>
![](/assets/images/ensemblesplice/t2.png){: width=40% }



> Genomic DNA splice site regions are composed of four nucleotides - A (Adenine), C (Cytosine), G (Guanine), or T (Thymine). Given the input constraints of DL architectures, these nucleotides are encoded numerically, as opposed to categorically. Each nucleotide corresponds to a row in a $4 \times 4$ identity matrix. The encoding scheme utilized in this paper is that A corresponds to ```[1, 0, 0, 0]```, C corresponds to ```[0, 1, 0, 0]```, G corresponds to ```[0, 0, 1, 0]```, and T corresponds to ```[0, 0, 0, 1]```. Since each splice site region consists of some $N$ nucleotides, the final numerical representation for each splice site region is a $N \times 4$ matrix, where each row is a one-hot encoded nucleotide that occurs at the same index as it did in the splice site region's original representation.



>
The HS$^3$D, *Homo sapiens*, *Arabidopsis thaliana* dataset subsets were each split into a training ($80\%$ of the data) and a testing ($20\%$ of the data) subset. Cross-validation has been demonstrated to be an effective tool for model selection, and as such,
10-fold cross validation was used for evaluating alternative EnsembleSplice sub-model architectures . For each dataset, the training subset of that dataset was partitioned into $10$ approximately equal sized subsets. Every subset was used at some point to evaluate the performance of EnsembleSplice; for each of the $10$ runs,  training occurred on $9$ subsets, and testing occurred on the last subset. The cross-validation performance for a particular dataset was the average performance over the $10$ folds. Once the sub-model architectures for EnsembleSplice were chosen, EnsembleSplice was trained on the full training subset of each dataset, and then tested **once** on the testing subset of the respective dataset. No additional training or validation occurred following the final test run; the results reported for EnsembleSplice in this paper are the performances from this final test run.



>To measure the performance of EnsembleSplice, and to compare EnsembleSplice with with other splice site detection models, the counts of correctly identified true AcSS or DoSS (true positive, ``TP''), correctly identified false AcSS or DoSS (true negative, ``TN''), incorrectly identified true AcSS or DoSS (false positive, ``FP''), and incorrectly identified false AcSS or DoSS (false negative, ``FN'') are used. See Table 3.
>
![](/assets/images/ensemblesplice/t3.png){: width=40% }
>
From these metrics, additional metrics common to classification tasks can be used for evaluation: Accuracy (Acc) - the fraction of AcSS or DoSS correctly identified, Precision (Pre) - the fraction of positive classifications for AcSS or DoSS that were positive, Sensitivity (Sn) - the fraction of positive AcSS or DoSS with a positive classification (true positive rate), Specificity (Sp) - the fraction of negative AcSS or DoSS with a negative classification (true negative rate), Matthew's correlation coefficient (Mcc) - the correlation between true/false AcSS and DoSS and the classifications for them generated by the mode, and F$_1$ score - the harmonic means of the fraction of positive classifications for AcSS or DoSS that were positive and the fraction of positive AcSS or DoSS that were correctly identified. Lastly, the error rate measures how often the classifier misclassified the data. The equations for these metrics are in Table .

---

## [Notes](#notes)

### [Cover Image](#cover-image)

The [cover image][cover_image]{:target="_blank"} for this page was likely taken by [Jonas Denil][author]{:target="_blank"}. I found the photo on [Unsplash][unsplash]{:target="_blank"}. To my knowledge, my use of this photo is permissible under Unsplash's [license][lic]{:target="_blank"}:
> Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service.

[cover_image]: https://unsplash.com/photos/7ALIbwRkwig "https://unsplash.com/photos/7ALIbwRkwig"

[author]: https://unsplash.com/@jonasdenil "https://unsplash.com/@jonasdenil"

[lic]: https://unsplash.com/license "https://unsplash.com/license"

[unsplash]: https://unsplash.com/ "https://unsplash.com/"


### [Footnotes](#footnotes)

[^1]: One advisor specialized in NLP; the other in computational neuroscience (BCI's in particular); and the last in bioinformatics. One other student and I worked with the bioinformatics advisor, while the other six REU students were distributed evenly across the
other advisors.

[^2]: As of 20 March 2022, I am still working on getting my work finished and submitted.

[^3]: This excuse was partially true, and I still felt badly about not doing more during the remainder of my summer. Had I incrementally worked on my REU project during the fall semester, I might have gotten most of it done. Whenever I thought about the project during the semester, I felt some sort of mental collapse, and uttered
things akin to "no, no, I can't do this, I have other work to do" internally.


<!-- \bgroup
\def\arraystretch{1.2}%
\begin{table*}[htp!]
\caption{Ensemble Selection}
\begin{center}
\begin{tabular}{|c|c|c|c|c|c|c|c|c|c|c|}
    \hline

    Dataset & Splice Site & Metric & ENS1 & ENS2 & ENS3  & ENS4  & ENS5  & ENS6  & ENS7 & ENS8\\

    \hline

    \multirow{8}{*}{HS$^3$D} & \multirow{4}{*}{Acceptor} & Double-Fault & 0.043 & 0.000 & ? & 0.012  & ? & ? & ? & ?\\
    & & Correlation & 0.907 & 0.960 & ? & 0.874  & ? & ? & ? & ?\\
    & & Q-Statistic & 0.995 & 0.596 & ? & 0.782  & ? & ? & ? & ?\\
     & & Accuracy & 0.908 & 0.954 & ? & 0.952  & ? & ? & ? & ?\\ \cline{2-11}
    & \multirow{4}{*}{Donor} & Double-Fault & 0.027 & 0.000 & ? & 0.007  & ? & ? & ? & ?\\
    & & Correlation & 0.946 & 0.976 & ? & 0.926  & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.997 & 0.531 & ? & 0.766  & ? & ? &  ? & ?\\
    & & Accuracy & 0.936 & 0.965 & ? & 0.965  & ? & ? & ? & ?\\

    \hline

    \multirow{8}{*}{\textit{Arabidopsis thaliana}} & \multirow{4}{*}{Acceptor} & Double-Fault & 0.024 & 0.008 & ? & 0.014  & ? & ? & ? & ?\\
    & & Correlation & 0.963 & 0.933 & ? & 0.946  & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.990 & 0.993 & ? & 0.981  & ? & ? &  ? & ?\\
     & & Accuracy & 0.912 & 0.946 & ? & 0.944  & ? & ? &  ? & ?\\ \cline{2-11}
    & \multirow{4}{*}{Donor} & Double-Fault & 0.013 & 0.003 & ? & 0.006  & ? & ? & ? & ?\\
    & & Correlation & 0.973 & 0.965 & ? & 0.963  & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.992 & 0.985 & ? & 0.856  & ? & ? &  ? & ?\\
     & & Accuracy & 0.929 & 0.952 & ? & 0.954  & ? & ? &  ? & ?\\

    \hline

    \multirow{8}{*}{\textit{Homo sapiens}} & \multirow{4}{*}{Acceptor} & Double-Fault & 0.035 & 0.006 & ? & 0.016  & ? & ? & ? & ?\\
    & & Correlation & 0.954 & 0.948 & ? & 0.926 & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.992 & 0.988 & ? & 0.976  & ? & ? &  ? & ?\\
     & & Accuracy & 0.894 & 0.939 & ? & 0.938  & ? & ? &  ?& ?\\ \cline{2-11}
    & \multirow{4}{*}{Donor} & Double-Fault & 0.022 & 0.001 & ? & 0.009  & ? & ? & ? & ?\\
    & & Correlation & 0.964 & 0.976 & ? & 0.948  & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.993 & 0.861 & ? & 0.976  & ? & ? &  ? & ?\\
     & & Accuracy & 0.907 & 0.952 & ? & 0.950  & ? & ? &  ? & ?\\

    \hline

    \multirow{8}{*}{Averages} & \multirow{4}{*}{Acceptor} & Double-Fault & 0.034 & 0.004 & ? & 0.014  & ? & ? & ? & ?\\
    & & Correlation & 0.941 & 0.947 & ? & 0.915  & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.992 & 0.859 & ? & 0.913  & ? & ? &  ? & ?\\
     & & Accuracy & 0.905 & 0.946 & ? & 0.945  & ? & ? &  ? & ?\\ \cline{2-11}
    & \multirow{4}{*}{Donor} & Double-Fault & 0.021 & 0.001 & ? & 0.007  & ? & ? & ? & ?\\
    & & Correlation & 0.961 & 0.972 & ? & 0.946  & ? & ? &  ? & ?\\
    & & Q-Statistic & 0.994 & 0.792 & ? & 0.866  & ? & ? &  ? & ?\\
     & & Accuracy & 0.924 & 0.956 & ? & 0.956  & ? & ? &  ? & ?\\


    \hline
\end{tabular}
\end{center}
\label{table:all}
\end{table*} -->
