---
layout: post
title:  "DNA Digital Data Storage"
date:  2022-06-05 12:00:00 -0400
modified: 2022-06-15 12:00:00 -0400
permalink: "/for_digital_dna/"
status: "In Progress"
type: "Essay"
image: /assets/2022/for_digital_dna/urja-bhatt-HcxlQto32mI-unsplash.jpg
tags: [prediction, forecasting, biology]
specifics: [dna, data-storage]
description: "Frame: An brief scan of DNA digital data storage with some forecasting questions mixed in."
word_count: "yes"
reading_time: "yes"
---

__Takeaways__:

__General Transparency__:

__Acknowledgements__:

__Overview__: I first discuss, very briefly, biological information storage, and then move on to discussing some properties of DNA. Next, I look at how much digital data there is on Earth, and how people store this data. I illustrate some present and upcoming issues with the current paradigms for data and data storage. Finally, I look at DNA digital data storage, introducing properties of DNA that make it a good candidate for storing data.  


<!-- Search DNA Digital Data Storage on
google scholar
first 16 pages,
dont keep all

search web of science
google scholar  

answer what 
-->

---

## [Table of Contents](#toc)

{:.no_toc}
* TOC
{:toc}

---

## [Musings on DNA](#what-is-it)

[wiki_DNA]: https://en.wikipedia.org/wiki/DNA "https://en.wikipedia.org/wiki/DNA"

[wiki_E_age]: https://en.wikipedia.org/wiki/Age_of_Earth "https://en.wikipedia.org/wiki/Age_of_Earth"

[^Eage]: _...roughly 4.54 billion years old_: Dalrymple, G. Brent. "The age of the Earth in the twentieth century: a problem (mostly) solved." Geological Society, London, Special Publications 190, no. 1 (2001): 205-221. See <https://creationismonline.com/YEC/Dalrymple_B.pdf>. Quote: (pp.1) "...the first calculation by Patterson in 1953 of a valid age for the Earth of 4.55Ga, using the primordial meteoritic lead composition and samples representing the composition of modern Earth lead. The value for the age of the Earth in wide use today was determined by Tera in 1980, who found a value of 4.54 Ga from a clever analysis of the lead isotopic compositions of four ancient conformable lead deposits. Whether this age represents the age of the Earth's accretion, of core formation, or of the material from which the Earth formed is not yet known, but recent evidence suggests it may approximate the latter."

[^Eage2]: _...roughly 4.54 billion years old_: Manhes, Gérard, Claude J. Allègre, Bernard Dupré, and Bruno Hamelin. "Lead isotope study of basic-ultrabasic layered complexes: Speculations about the age of the earth and primitive mantle characteristics." Earth and Planetary Science Letters 47, no. 3 (1980): 370-382. Quote: (pp.1) "If these two bodies are considered as pieces of a “primitive” closed-system mantle, a4.55 ± 0.01 age of the earth can be calculated from their Pb initial ratios."

[timeline_of_life]: https://en.wikipedia.org/wiki/Timeline_of_the_evolutionary_history_of_life "https://en.wikipedia.org/wiki/Timeline_of_the_evolutionary_history_of_life"

[life_began]: https://en.wikipedia.org/wiki/Earliest_known_life_forms "https://en.wikipedia.org/wiki/Earliest_known_life_forms"

[rna_world]: https://en.wikipedia.org/wiki/RNA_world "https://en.wikipedia.org/wiki/RNA_world"

[^rnaW]: _this hypothesis is called the RNA World Hypothesis, and posits that RNA preceded proteins and deoxyribonucleic acid (DNA)_: Cech, Thomas R. "The RNA worlds in context." Cold Spring Harbor perspectives in biology 4, no. 7 (2012): a006742. See <https://cshperspectives.cshlp.org/content/4/7/a006742.full.pdf>. Quote: (pp.1) "Did an RNA world exist? Some of the most persuasive arguments in favor of an RNA world are as follows. First, RNA is both an informational molecule and a biocata- lyst—both genotype and phenotype—whereas protein has extremely limited ability to transmit information (as with prions). Thus, RNA should be capable of replicating itself, and indeed RNA can perform the sort of chemistry required for RNA replication (Cech 1986). Second, it is more parsimonious to conceive of a single type of molecule replicating itself than to posit that two different molecules (such as a nucleic acid and a protein capable of replicating that nucleic acid) were synthesized by random chemical reactions in the same place at the same time. Third, the ribosome uses RNA catalysis to perform the key activity of protein synthesis in all extant organisms, so it must have done so in the Last Universal Common Ancestor (LUCA). Fourth, other catalytic activities of RNA—activities that RNA would need in an RNA world but that have not been found in contemporary RNAs—are generally already present in large combinatorial libraries of RNA sequences and can be discovered by SELEX. Fifth, RNA clearly preceded DNA, because multiple enzymes are dedicated to the biosynthesis of the ribonucleotide precursors of RNA, whereas deoxyribonucleotide biosynthesis is derivative of ribonucleotide synthesis, requiring only two additional enzymatic activities (thymidylate synthase and ribonucleotide reductase.) Finally, a primordial RNA world has the attractive feature of continuity; it could evolve into contemporary biology by the sort of events that are well precedented, whereas it is unclear how a self-replicating system based on completely unrelated chemistry could have been supplanted by RNA." 

[abio]: https://en.wikipedia.org/wiki/Abiogenesis "https://en.wikipedia.org/wiki/Abiogenesis"

[earliest_life]: https://en.wikipedia.org/wiki/Earliest_known_life_forms "https://en.wikipedia.org/wiki/Earliest_known_life_forms" 

[^early]: _the first microorganisms appeared between "at least 3770 and possibly 4290 million years..."_ : Dodd, Matthew S., Dominic Papineau, Tor Grenne, John F. Slack, Martin Rittner, Franco Pirajno, Jonathan O’Neil, and Crispin TS Little. "Evidence for early life in Earth’s oldest hydrothermal vent precipitates." Nature 543, no. 7643 (2017): 60-64. See <https://discovery.ucl.ac.uk/id/eprint/1536298/1/Dodd_et_al_2017_Nature_accepted.pdf>. Quote: (pp.1) "Here we report putative fossilised microorganisms at least 3770 and possibly 4290 million years old in ferruginous sedimentary rocks, interpreted as seafloor-hydrothermal vent-related precipitates, from the Nuvvuagittuq belt in Canada."

[^cell_book]: _...deoxyribonucleic acid (DNA), the other major nucleic acid, rather than RNA, is the platform for the genetic-material of all cells on Earth today_: Cooper, Geoffrey M., Robert E. Hausman, and Robert E. Hausman. The cell: a molecular approach. Vol. 8. Washington, DC, USA:: ASM press, 2007. Quote: (pp.6) "As discussed further in Chapter 4, all present-day cells use DNA as the genetic material and employ the same basic mechanisms for DNA replication and expression of the genetic information. Genes are the functional units of inheritance, corresponding to segments of DNA that encode proteins or RNA molecules. The nucleotide sequence of a gene is copied into RNA by a process called transcription. For RNAs that encode proteins, their nucleotide sequence is then used to specify the order of amino acids in a protein by a process called translation."

[wiki_rna]: https://en.wikipedia.org/wiki/RNA "https://en.wikipedia.org/wiki/RNA" 

[wiki_coding]: https://en.wikipedia.org/wiki/Genetic_code "https://en.wikipedia.org/wiki/Genetic_code"

[wiki_decoding]: https://en.wikipedia.org/wiki/Translation_(biology) "https://en.wikipedia.org/wiki/Translation_(biology)"

[wiki_regulation]: https://en.wikipedia.org/wiki/RNA_interference "https://en.wikipedia.org/wiki/RNA_interference"

[wiki_expression]: https://en.wikipedia.org/wiki/Gene_expression "https://en.wikipedia.org/wiki/Gene_expression"

[wiki_genes]: https://en.wikipedia.org/wiki/Gene "https://en.wikipedia.org/wiki/Gene"

[wiki_DNA]: https://en.wikipedia.org/wiki/DNA "https://en.wikipedia.org/wiki/DNA"

[wiki_nucleics]: https://en.wikipedia.org/wiki/Nucleic_acid "https://en.wikipedia.org/wiki/Nucleic_acid"

[wiki_lipids]: https://en.wikipedia.org/wiki/Lipid "https://en.wikipedia.org/wiki/Lipid"
 
[wiki_proteins]: https://en.wikipedia.org/wiki/Protein "https://en.wikipedia.org/wiki/Protein"

[wiki_carbs]: https://en.wikipedia.org/wiki/Carbohydrate "https://en.wikipedia.org/wiki/Carbohydrate"

[wiki_macros]: https://en.wikipedia.org/wiki/Macromolecule "https://en.wikipedia.org/wiki/Macromolecule"

[wiki_life]: https://en.wikipedia.org/wiki/Life "https://en.wikipedia.org/wiki/Life"

[wiki_nucleos]: https://en.wikipedia.org/wiki/Nucleotide "https://en.wikipedia.org/wiki/Nucleotide"

[wiki_mRNA]: https://en.wikipedia.org/wiki/Messenger_RNA "https://en.wikipedia.org/wiki/Messenger_RNA"

[wiki_nitro_bases]: https://en.wikipedia.org/wiki/Nucleobase "https://en.wikipedia.org/wiki/Nucleobase"

[wiki_gua]: https://en.wikipedia.org/wiki/Guanine "https://en.wikipedia.org/wiki/Guanine"

[wiki_ura]: https://en.wikipedia.org/wiki/Uracil "https://en.wikipedia.org/wiki/Uracil"

[wiki_ade]: https://en.wikipedia.org/wiki/Adenine "https://en.wikipedia.org/wiki/Adenine"

[wiki_cyto]: https://en.wikipedia.org/wiki/Cytosine "https://en.wikipedia.org/wiki/Cytosine"

[wiki_vir]: https://en.wikipedia.org/wiki/Virus "https://en.wikipedia.org/wiki/Virus"

[wiki_geno]: https://en.wikipedia.org/wiki/Genome "https://en.wikipedia.org/wiki/Genome"

[wiki_polymer]: https://en.wikipedia.org/wiki/Polymer "https://en.wikipedia.org/wiki/Polymer"

[wiki_polynu]: https://en.wikipedia.org/wiki/Polynucleotide "https://en.wikipedia.org/wiki/Polynucleotide"

[wiki_doub]: https://en.wikipedia.org/wiki/Nucleic_acid_double_helix "https://en.wikipedia.org/wiki/Nucleic_acid_double_helix"

[wiki_gentc]: https://en.wikipedia.org/wiki/Genetics "https://en.wikipedia.org/wiki/Genetics" 

[wiki_repo]: https://en.wikipedia.org/wiki/Reproduction "https://en.wikipedia.org/wiki/Reproduction" 

[wiki_org]: https://en.wikipedia.org/wiki/Organism "https://en.wikipedia.org/wiki/Organism" 

[wiki_polys]: https://en.wikipedia.org/wiki/Polysaccharide "https://en.wikipedia.org/wiki/Polysaccharide"

<!-- [^alt_def_dna]: _defining these_: Here are some alternate definitions of DNA: From <https://www.genome.gov/about-genomics/fact-sheets/Deoxyribonucleic-Acid-Fact-Sheet>; "Deoxyribonucleic acid (DNA) is a molecule that contains the biological instructions that make each species unique. DNA, along with the instructions it contains, is passed from adult organisms to their offspring during reproduction." NEED 

[^alt_def_rna]: _defining these_: Here are some alternate definitions of RNA. NEED  

[^alt_def_rna]<sup>,</sup>[^alt_def_dna]-->

[wiki_RNP]: https://en.wikipedia.org/wiki/Nucleoprotein#Ribonucleoproteins "https://en.wikipedia.org/wiki/Nucleoprotein#Ribonucleoproteins"

[^wiki_dna_img]: From Wikipedia: <https://commons.wikimedia.org/wiki/File:Difference_DNA_RNA-EN.svg>. Credit: File:Difference DNA RNA-DE.svg: Sponk / *translation: Sponk, CC BY-SA 3.0 <https://creativecommons.org/licenses/by-sa/3.0>, via Wikimedia Commons

[wiki_dogma]: https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology "https://en.wikipedia.org/wiki/Central_dogma_of_molecular_biology"

[^dogma]: _As originally stated by Francis Crick_: Crick, Francis HC. "On protein synthesis." In Symp Soc Exp Biol, vol. 12, no. 138-63, p. 8. 1958. See [here](https://d1wqtxts1xzle7.cloudfront.net/31353481/Symp_Soc_Exp_Biol_1958_Crick_on_protein_synthesis-with-cover-page-v2.pdf?Expires=1654880735&Signature=glAwa258T3TTy4fxqd-~07IsWvg0joqi7rzuDePEqjj3xoixZjKxxDbzPjHObOFlSS3YfLLShkkK1c7PcrdbWD7UkW~WyKJaCBlYBCoLN9gqfRSpqbR0di7tyY~x6k0pu1jhne7hVEAlGROYtP47~5KPRTFAsQj4Sr6Vif2I9jADAMGXi06AClr~AgqBFZqQ~vvIUwpS8po7WOx52su9Lf2KCtaEUwPVPhD1cvox0di8aN4IVjDsxLKFSgL0grDOvvpK-OPk5acCnll3XTRjrOjcVf4l3yW8tC6iDihmBh4Lh3ET4EhPtDZk3IYsQjTPTP2ZauV6W6uvuNKasm~LCQ__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA). Quote: (pp.153). 

For those currently unaware, radiometric dating research places the [age of the Earth][wiki_E_age] at roughly 4.54 billion years old[^Eage]<sup>,</sup>[^Eage2], which is approximately equal to 56.75 million non-overlapping 80-year human lives. The first microorganisms appeared between "at least 3770 and possibly 4290 million years..." ago[^early]. While the [history][timeline_of_life] and [emergence][abio] of life on Earth [began][life_began] is still the focus of major investigation, ribonucleic acid (RNA) is current believed to have been the original auto-self-replicating system utilized by early life to store and replicate genetic material; this hypothesis is called the [RNA World Hypothesis][rna_world], and posits that RNA preceded proteins and deoxyribonucleic acid (DNA)[^rnaW] in evolution. Moreover, the RNA world begot [ribonucleoproteins][wiki_RNP], which then lead to deoxyribonucleic acid (DNA) evolving. Presently, DNA, the other major nucleic acid, rather than RNA, is the platform for the genetic-material of all cells on Earth today[^cell_book]. 

This brings us to the question of what RNA and DNA actually are, and of how they relate to information in biology. Rather than answer this myself, I default to the writers on Wikipedia (as of 06/09/2022), who have done a much better job at providing a comprehensive definition of RNA and DNA than I could have: 

> __Ribonucleic acid ([RNA][wiki_rna])__ is a [polymeric][wiki_polymer] molecule essential in various biological roles in [coding][wiki_coding], [decoding][wiki_decoding], [regulation][wiki_regulation] and [expression][wiki_expression] of[genes][wiki_genes]. RNA and deoxyribonucleic acid ([DNA][wiki_DNA]) are [nucleic acids][wiki_nucleics]. Along with [lipids][wiki_lipids], [proteins][wiki_proteins], and [carbohydrates][wiki_carbs], nucleic acids constitute one of the four major [macromolecules][wiki_macros] essential for all known forms of [life][wiki_life]. Like DNA, RNA is assembled as a chain of [nucleotides][wiki_nucleos], but unlike DNA, RNA is found in nature as a single strand folded onto itself, rather than a paired double strand. Cellular organisms use messenger RNA ([mRNA][wiki_mRNA]) to convey genetic information (using the [nitrogenous][wiki_nitro_bases] bases of [guanine][wiki_gua], [uracil][wiki_ura], [adenine][wiki_ade], and [cytosine][wiki_cyto], denoted by the letters G, U, A, and C) that directs synthesis of specific proteins. Many [viruses][wiki_vir] encode their genetic information using an RNA [genome][wiki_geno]. 
> 
> [See <https://en.wikipedia.org/wiki/RNA>]

and 

> __Deoxyribonucleic acid (DNA)__ is a [polymer][wiki_polymer] composed of two [polynucleotide][wiki_polynu] chains that coil around each other to form a [double helix][wiki_doub] carrying [genetic][wiki_gentc] instructions for the development, functioning, growth and [reproduction][wiki_repo] of all known [organisms][wiki_org] and many [viruses][wiki_vir]. DNA and ribonucleic acid ([RNA][wiki_rna]) are [nucleic acids][wiki_nucleics]. Alongside [proteins][wiki_proteins], [lipids][wiki_lipids] and complex [carbohydrates][wiki_carbs] ([polysaccharides][wiki_polys]), nucleic acids are one of the four major types of [macromolecules][wiki_macro] that are essential for all known forms of [life][wiki_life]. 
> 
> [See <https://en.wikipedia.org/wiki/DNA>]

__RNA__ and __DNA__[^wiki_dna_img]

![](/assets/2022/for_digital_dna/images/rna_dna_diff.png)

The [central dogma of molecular biology][wiki_dogma] ensapsulates, from a broad lens, the interactions between DNA, RNA, and proteins in living organisms in terms of information transfer and storage. As originally stated by Francis Crick[^dogma]:

> The Central Dogma. This states that once "information" has passed into protein it cannot get out again. In more detail, the transfer of information from nucleic acid to nucleic acid, or from nucleic acid to protein may be possible, but transfer from protein to protein, or from protein to nucleic acid is impossible. Information means here the precise determination of sequence, either of bases in the nucleic acid or of amino acid residues in the protein. 

[wiki_half]: https://en.wikipedia.org/wiki/Half-life "https://en.wikipedia.org/wiki/Half-life"

[wiki_moa]: https://en.wikipedia.org/wiki/Moa "https://en.wikipedia.org/wiki/Moa"

RNA is much less structurally stable than DNA[^stability], which means that RNA degrades faster. The [half-life][wiki_half][^half_life] of DNA is much longer than that of RNA. For example, researchers looking a leg bones from [Moa][wiki_moa] found that DNA had a half-life of around 521 years. These bones were between 600 - 8000 years old and were preserved at a temperature of 13.1 degrees Celcius. Interestingly, even with an _"ideal preservation temperature of −5ºC, effectively every bond would be destroyed after a maximum of 6.8 million years"_.[^moa] Compare this with the half-life of mouse mRNA: around 7 hours (median), with the mRNA of a vast majority of genes having half-lives > 1 hour.[^mouse] DNA is much more robust a capsule for housing genetic information, and its dominion in this regard in all living cells makes sense.

[^half_life]: Given by the equation $N(t) = N_0 e^{-\lambda t}$. Here, $t$ denotes time, $N_0$ represents the starting amount of the substance in question, $\lambda \in \mathbb{R}_{>0}$ the decay rate of the substance, and $N(t)$ the amount of substance left after time $t$.  

[^stability]: _RNA is much less structurally stable and than DNA_: See <https://en.wikipedia.org/wiki/RNA_world#Comparison_of_DNA_and_RNA_structure>. Quote: "...the presence of a hydroxyl group at the 2'-position of the ribose sugar in RNA (illustration, right). [Source 21] This group makes the molecule less stable because, when not constrained in a double helix, the 2' hydroxyl can chemically attack the adjacent phosphodiester bond to cleave the phosphodiester backbone. The hydroxyl group also forces the ribose into the C3'-endo sugar conformation unlike the C2'-endo conformation of the deoxyribose sugar in DNA. This forces an RNA double helix to change from a B-DNA structure to one more closely resembling A-DNA."

[^mouse]: _Compare this with the half-life of mouse mRNA: around 7 hours_: Sharova, Lioudmila V., Alexei A. Sharov, Timur Nedorezov, Yulan Piao, Nabeebi Shaik, and Minoru SH Ko. "Database for mRNA half-life of 19 977 genes obtained by DNA microarray analysis of pluripotent and differentiating mouse embryonic stem cells." DNA research 16, no. 1 (2009): 45-58. See <https://academic.oup.com/dnaresearch/article/16/1/45/364974?login=true>. Quote: (abstract) "Median estimated half-life was 7.1 h and only <100 genes, including Prdm1, Myc, Gadd45 g, Foxa2, Hes5 and Trib1, showed half-life less than 1 h. In general, mRNA species with short half-life were enriched among genes with regulatory functions (transcription factors), whereas mRNA species with long half-life were enriched among genes related to metabolism and structure (extracellular matrix, cytoskeleton)."

[^moa]: _For example, researchers looking a leg bones from [Moa][wiki_moa] found that DNA had a half-life of around 521 years. These bones were between 600 - 8000 years old and were preserved at a temperature of 13.1 degrees Celcius[^moa]._: Kaplan, M. "DNA has a 521-year half-life [at 13.1 C]: genetic material can’t be recovered from dinosaurs–but it lasts longer than thought." Nature News 10 (2012). See <https://www.nature.com/articles/nature.2012.11555>. Quotes: (pp.1) "But palaeogeneticists led by Morten Allentoft at the University of Copenhagen and Michael Bunce at Murdoch University in Perth, Australia, examined 158 DNA-containing leg bones belonging to three species of extinct giant birds called moa. The bones, which were between 600 and 8,000 years old, had been recovered from three sites within 5 kilometres of each other, with nearly identical preservation conditions including a temperature of 13.1 ºC. The findings are published today in Proceedings of the Royal Society B1."; "By comparing the specimens' ages and degrees of DNA degradation, the researchers calculated that DNA has a half-life of 521 years. That means that after 521 years, half of the bonds between nucleotides in the backbone of a sample would have broken; after another 521 years half of the remaining bonds would have gone; and so on."; "The team predicts that even in a bone at an ideal preservation temperature of −5 ºC, effectively every bond would be destroyed after a maximum of 6.8 million years. The DNA would cease to be readable much earlier — perhaps after roughly 1.5 million years, when the remaining strands would be too short to give meaningful information."

That DNA has such a long half-life is quite extraordinary. Two fairly recent examples showcasing this feat of Nature that pierced the public's attention[^public] are Ötzi the iceman and the report of million year-old mammoth remains. Ötzi the iceman is a mummified human (25-40 year-olds and likely murdered) from the Late Neolithic (Copper Age) who was located on 09/19/1991 in the Tyrolean Öztaler Alps.[^back] Believed to be around 5.2k-5.3k years-old (3359 - 3105 BCE)[^old], Ötzi is one of the older mummies that have been retrieved; that DNA is so structurally sound over time can afford us amazing insight into humanity's and Otzi's past (e.g., Ötzi's last meal[^meal], or his gut microbiome[^biom]). The million year-old mammoths story refers to 3 mammoth (the oldest fossils being 1.2-1.1Ma) specimens of the Early-Middle Pleistocene from Siberia whose DNA was read by a team of researchers; the sequencing and recovery of DNA from these fossils pushed the limits of what people thought was achievable with DNA sequencing[^million_mam], as the previous oldest example NEED was at least 

While I am not sure how the distributions of lifeforms and cellular mechanics would be different in worlds where DNA was half, a third, etc... as robust as it is in this world, I am grateful, at least with regard to our understanding of the Earth's natural past, that DNA is the way it is. 

[^meal]: _Otzi's last meal_: Rollo, Franco, Massimo Ubaldi, Luca Ermini, and Isolina Marota. "Ötzi's last meals: DNA analysis of the intestinal content of the Neolithic glacier mummy from the Alps." Proceedings of the National Academy of Sciences 99, no. 20 (2002): 12594-12599. See <https://www.pnas.org/doi/pdf/10.1073/pnas.192184599>. 

[^biom]: _...his gut microbiome_: Lugli, Gabriele Andrea, Christian Milani, Leonardo Mancabelli, Francesca Turroni, Chiara Ferrario, Sabrina Duranti, Douwe van Sinderen, and Marco Ventura. "Ancient bacteria of the Ötzi’s microbiome: a genomic tale from the Copper Age." Microbiome 5, no. 1 (2017): 1-18. See <https://microbiomejournal.biomedcentral.com/articles/10.1186/s40168-016-0221-y>.

[wiki_hgen]: https://en.wikipedia.org/wiki/Human_genome/ "https://en.wikipedia.org/wiki/Human_genome/"

[wiki_base]: https://en.wikipedia.org/wiki/Base_pair "https://en.wikipedia.org/wiki/Base_pair"

The [human geneome][wiki_hgen] 


[^comp_gene]: Nurk, Sergey, Sergey Koren, Arang Rhie, Mikko Rautiainen, Andrey V. Bzikadze, Alla Mikheenko, Mitchell R. Vollger et al. "The complete sequence of a human genome." Science 376, no. 6588 (2022): 44-53. See <>. Quote: (pp.) ""

[^old]: _Believed to be around 5.2k-5.3k years-old (3359 - 3105 BCE)_: Seidler, Horst, Wolfram Bernhard, Maria Teschler-Nicola, Werner Platzer, Dieter Zur Nedden, Rainer Henn, Andreas Oberhauser, and Thorstein Sjøvold. "Some anthropological aspects of the prehistoric Tyrolean ice man." Science 258, no. 5081 (1992): 455-457. See [here](https://www.researchgate.net/profile/Seidler-Horst/publication/21743254_Some_Anthropological_Aspects_of_the_Prehistoric_Tyrolean_Ice_Man/links/59d89513aca272e6096691cc/Some-Anthropological-Aspects-of-the-Prehistoric-Tyrolean-Ice-Man.pdf). Quote: (pp.455) "Radiocarbon dating of the corpse conducted independently in Oxford and in Zurich have shown that the corpse is between 5200 and 5300 years old (2 [Bonani, G. "Bericht Ober das Erste Intematonak Symposium" Der Mann im Eis-Ein Fund aus der Steinzeit Tirols," Innsbruck, Austria, 3 to 5 June 1992, K." Ver6ffentlichungen der UniversitAt Innsbruck, vol. 187 (1992).])."

[^back]: _Ötzi the iceman is a mummified human (25-40 year-olds and likely murdered) from the Late Neolithic (Copper Age)..._: Williams, Adrian C., Howell GM Edwards, and Brian W. Barry. "The ‘Iceman’: molecular structure of 5200-year-old skin characterised by Raman spectroscopy and electron microscopy." Biochimica et Biophysica Acta (BBA)-Protein Structure and Molecular Enzymology 1246, no. 1 (1995): 98-105. See [here](https://www.researchgate.net/profile/Brian-Barry-7/publication/15386945_The_Iceman_Molecular_Structure_of_5200-Year_Old_Skin_Characterised_by_Raman_Spectroscopy_and_Electron_Microscopy/links/5b45be3a458515b4f662c652/The-Iceman-Molecular-Structure-of-5200-Year-Old-Skin-Characterised-by-Raman-Spectroscopy-and-Electron-Microscopy.pdf). Quote: (pp.98) "The discovery in September 1991 of a Late Neolithic man in a glacial field between Austria and Italy offered uniquely preserved archaeological samples [1]. Commonly known as the Iceman (or &i, having been found in the Tyrolean &ztaler Alps), the body is the oldest to be retrieved from an Alpine glacier and is one of the best preserved mummified humans ever discovered. Initially thought to date from the Early Bronze Age, Iceman is in fact unique in that he dates from the Copper Age (Chalcolithic) as verified by chemical analysis of the axe he carried at time of death." 

[^public]: _...pierced the public's attention..._: Example of news article for million year old mammoth: <https://www.cnn.com/2021/02/17/world/mammoth-oldest-dna-million-years-ago-scn/index.html>. Example of news article Otzi: <https://www.nationalgeographic.com/history/article/tzi-the-iceman-what-we-know-30-years-after-his-discovery> 

[wiki_otzi]: https://en.wikipedia.org/wiki/%C3%96tzi "https://en.wikipedia.org/wiki/%C3%96tzi"

[^million_mam]: _...the report of million year-old mammoth remains_: van der Valk, Tom, Patrícia Pečnerová, David Díez-del-Molino, Anders Bergström, Jonas Oppenheimer, Stefanie Hartmann, Georgios Xenikoudakis et al. "Million-year-old DNA sheds light on the genomic history of mammoths." Nature 591, no. 7849 (2021): 265-269. See <https://www.nature.com/articles/s41586-021-03224-9).>. Quote: (abstract; pp. 266 x 2) "Temporal genomic data hold great potential for studying evolutionary processes such as speciation. However, sampling across speciation events would, in many cases, require genomic time series that stretch well back into the Early Pleistocene subepoch. Although theoretical models suggest that DNA should survive on this timescale1, the oldest genomic data recovered so far are from a horse specimen dated to 780–560 thousand years ago. Here we report the recovery of genome-wide data from three mammoth specimens dating to the Early and Middle Pleistocene subepochs, two of which are more than one million years old."; "One of the specimens (which we refer to as ‘Krestovka’ on the basis of its find locality) is morphologically similar to the steppe mammoth (a species that was originally defined from the Middle Pleistocene of Europe (Supplementary Information section 1)), and was collected from Lower Olyorian deposits that have been dated to 1.2–1.1 Ma."; "We found that the DNA recovered from the Early and Middle Pleistocene specimens was considerably more fragmented and had higher levels of cytosine deamination than DNA from permafrost-preserved samples dating to the Late Pleistocene subepoch (Extended Data Figs. 3, 4, Supplementary Information section 4). To circumvent this, we used conservative filters and an iterative approach that was designed to minimize spurious mappings of short reads (Supplementary Information section 5). This approach allowed us to recover complete (over 37× coverage) mitogenomes from all three specimens, and 49 million, 884 million and 3,671 million base pairs of nuclear genomic data for the Krestovka, Adycha and Chukochya specimens, respectively (Supplementary Table 3)."

## Data and Storing It 

There is a lot of digital data around. The Internet comes to the forefront of my mind when I think about this — I imagine the constant and prodigious flow of emails, tweets, messages, posts, etc... inundating networks globally. My website is starting to run slower due to how many images I am including in my posts. 

The size of the Internet and how much digital data humans have generated are quantities of intrigue. In particular, 

The conclusion, at least after having learned a little about DNA, is obvious: biological data storage, with DNA as the prime candidate, has extraordinary potential in terms of changing the limits.

If you wanted to stored this 

<!-- Look at total # of people on the Internet and extrapolate several scenarios using drawings

https://ourworldindata.org/internet 

Qs:
Size of the Internet 
Amount of Data 
Read time
Write time 
Cost of reading
Google Trends 

-->
<!-- 
How much data is there? 
How large is the Internet?
How many internet users are there? 
What is Data Storage? 
<https://www.ibm.com/topics/data-storage>
What are problems with it? 
<DNA as a digital information storage device: hope or hype?>
### DNA Digital Data Storage 
What are the storage properties of DNA? 
How is DNA Digital Data Storage done? 
What are the issues and future potential of it?  -->

### DNA Digital Data Storage 


[^hype]: Panda, Darshan, Kutubuddin Ali Molla, Mirza Jainul Baig, Alaka Swain, Deeptirekha Behera, and Manaswini Dash. "DNA as a digital information storage device: hope or hype?." 3 Biotech 8, no. 5 (2018): 1-9. See <https://link.springer.com/article/10.1007/s13205-018-1246-7>. 

___Comparision of Data Storage Tools[^hype]___

![](/assets/2022/for_digital_dna/images/data_comp.png)

[^meth]: Meiser, Linda C., Philipp L. Antkowiak, Julian Koch, Weida D. Chen, A. Xavier Kohll, Wendelin J. Stark, Reinhard Heckel, and Robert N. Grass. "Reading and writing digital data in DNA." Nature Protocols 15, no. 1 (2020): 86-101.

___Method for DNA Digital Data Storage[^meth]___

![](/assets/2022/for_digital_dna/images/how_its_done.png)

> The complementary nature and ability to self-assemble during the formation of tertiary structure enables DNA strands to be folded arbitrarily into polygonal digital meshes (Benson et al. 2015), engineered into complex wireframe nanostructures (Zhang et al. 2015), and scaffolded to organ- ized biological molecules (Yang et al. 2015).
> 
> [See _DNA as a digital information storage device: hope or hype?_[^hype]]


<!-- AMMUNITION 

[^trends]: Akram, Fatima, Haider Ali, and Aiman Tahir Laghari. "Trends to store digital data in DNA: an overview." Molecular biology reports 45, no. 5 (2018): 1479-1490.

Every year the storage necessity is increasing by 50% [^trends] (Hakami HA, Chaczko Z, Kale A (2015) Review of big data storage based on DNA computing. In: Proceedings of the Asia- Pacific Conference on Computer-Aided System Engineering (APCASE’15), Quito Ecuador, pp 113–117)

DNA can store an unbelievable amount of enormous data just as Castillo has reported that the whole data present on internet can be recorded in a device that would be lesser than a cubic inch[^trends] (Castillo M (2014) From hard drives to flash drives to DNA drives. Am J Neuroradiol 35:1–2)

The amount of data that can be stored on DNA is 1 EB (EB or 109 GB) per cubic millimeter, it means that eighth order of the amount stored on tapes having a half-life of 500 years in harsh conditions[^trends] (Allentoft ME, Scofield RP, Oskam CL, Hale ML, Holdaway RN, Bunce M (2012) A molecular characterization of a newly discov- ered megafaunal fossil site in North Canterbury, South Island, New Zealand. J R Soc N Z 42:241–256)

Q: Google Trends interests, https://trends.google.com/trends/explore?date=all&q=%2Fm%2F0q3zpyk -->


<!-- 
DNA/RNA diff https://sciencenotes.org/dna-vs-rna-similarities-and-differences/
DNA half life: 
https://www.nature.com/articles/nature.2012.11555.pdf
mRNA half life 
https://watermark.silverchair.com/dsn030.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAswwggLIBgkqhkiG9w0BBwagggK5MIICtQIBADCCAq4GCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQML7j4o-S37Xdo4stVAgEQgIICf6hhVyBz-b1J3byoRsNCzRmayeSbwlbFzZmht3TjNWB_6u-wLW6CO9u8bgcgK5V5COpue7I8utdzgH1jwR0TvsrAl-AXEJXFbdeUvo8e53G58DZRHOgtq6AziA_l05OmLCJh1txozRSXYUVRLOzdeLhYCcGWocxkO09RzA7hvzgSI1McsCQ4srUoi9ABkXU4C6zjaRyKPcrcIYW2-7uremPTvZz-DB0bzKHUVDipRCGzeihIC1YbWqDAquL6TSGtvh5G215DqNCnhE23H7eaHS-nHwgYpacXbm3ikj8_EBhwMC5YGF7BK4vnR80UG34XVFnOKvHVXrcBvIFhVZ2IhSDw-zEqvPc7ye-GEIlTVRZrCoVJDKJleEZZbktIBapihTs0erQqiKnD8NYlUjGLNVgocALNx7XE4LSq36i3D_ukcjRT-NeiAHbeAcBraiUXGcA7VXkj73JKw3gbrujhrOiUwnTFpoZN6Mw_douZO8R0bSQ0FJ_w6M6yIrB_id4LDp_YHflfLP577-T-ZTirvK4yhQZE611MuBWcu2uUqZap1Cp90BmSlBhmZ8pcqUrQhF2woqcmwmrI6VnYJByUzaTwl7ulkNilE0ptnznz9TR_5EHlgn0UqPmK3qccUpRnJwJ1nE0l8urS4NwSryp-whQu7nKmXOnoendtEdbGWIcKwTfV_lk-x1qOLfrM-ssnxt8_Q2JBKrYlDfFoHqn5yc2ZwWM5HmPXFNN5jsqLBw9D3jnotgawQ-CIxqQxQ-eIr2he9Ytyhu7oFKkM-NldCZ_4W2v6iGpFkINAeXOgYa04dEhe1avId9slEyn9h03k4PQ7ytDCKe7PxaltuSDihw
http://book.bionumbers.org/how-fast-do-rnas-and-proteins-degrade/

DNA Information Storage Mechanisms in Expo

Reading and writing digital data in DNA (introduction)
Half life, discuss fossil examples 

Trends to store digital data in DNA: an overview
DNA Potential 

DNA as a digital information storage device: hope or hype?
The global data crunch 

Novel Modalities in DNA Data Storage
Current synthesis costs have been estimated to be approximately $3500 per megabyte of data [22–24], depending on the scale of synthesis conducted, with large-scale processes such as silicon chip deposition platforms having lowered costs per base compared with smaller-scale, column-based synthesis 


Look through all of this Molecular digital data storage using DNA
-->

<!-- ---

## [Usefulness?](#usefulness?)

### Data, Data, Data, etc...

### One of Several Options 

### Pros and Cons 

---

## [Trajectories](#trajectories) -->

---

## [Appendix](#appendix)

### [Fraction of The Landscape](#the-landscape)

To learn about DNA digital data storage, I began by searching "dna digital data storage" on FireFox, and reading the following:

- _DNA digital data storage_ Wikipedia page: <https://en.wikipedia.org/wiki/DNA_digital_data_storage>
- DNA Data Storage, Wyss Institute: <https://wyss.harvard.edu/technology/dna-data-storage/>
- DNA as a digital information storage device: hope or hype? <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5935598/>
- A primer on DNA data storage and its potential uses: <https://www.techtarget.com/searchstorage/feature/A-primer-on-DNA-data-storage-and-its-potential-uses>

Following this, I went through the first 10 pages of Google Scholar results for "DNA Digital Data Storage" without citations, and skimmed some results and read others. Listed below are some papers I've looked through, along with the extent I've looked through them. These are, for the most part, the sources I engaged with to develop my understanding of DNA digital data storage. 

- Dahlman, James E. "ALL THE WORLD’S DATA COULD FIT IN AN EGG." Scientific American 320, no. 6 (2019): 68-73. See <https://www.dahlmanlab.org/uploads/5/8/5/6/58561089/scientificamerican0619-68_1.pdf>. Extent: 3/9 - I read the piece, took some notes, but that's about it.
- Xu, Chengtao, Chao Zhao, Biao Ma, and Hong Liu. "Uncertainties in synthetic DNA-based data storage." Nucleic acids research 49, no. 10 (2021): 5451-5469. See <https://academic.oup.com/nar/article/49/10/5451/6219117?login=true>. 
- Ceze, Luis, Jeff Nivala, and Karin Strauss. "Molecular digital data storage using DNA." Nature Reviews Genetics 20, no. 8 (2019): 456-466. See <https://www.nature.com/articles/s41576-019-0125-3>.
- Meiser, Linda C., Philipp L. Antkowiak, Julian Koch, Weida D. Chen, A. Xavier Kohll, Wendelin J. Stark, Reinhard Heckel, and Robert N. Grass. "Reading and writing digital data in DNA." Nature Protocols 15, no. 1 (2020): 86-101. See <https://www.nature.com/articles/s41596-019-0244-5>.[^meth]
- Lim, Cheng Kai, Saurabh Nirantar, Wen Shan Yew, and Chueh Loo Poh. "Novel modalities in DNA data storage." Trends in Biotechnology 39, no. 10 (2021): 990-1003. See <https://www.sciencedirect.com/science/article/abs/pii/S0167779920303334>. 
- Akram, Fatima, Haider Ali, and Aiman Tahir Laghari. "Trends to store digital data in DNA: an overview." Molecular biology reports 45, no. 5 (2018): 1479-1490. See <https://link.springer.com/article/10.1007/s11033-018-4280-y>.

 <!-- - Idea: Encode/decode binary data into DNA, which has high storage potential (__Q__: how much?)
    - Problem: High cost (__Q__: how much?), slow encode/decode times (__Q__: how bad?) 
    - Event: 2019, 16 GB Wiki. En. stored in synthetic DNA. 
    - Event: 2021, able to write data into DNA at 18 Mbps.
    - Idea: Cell free vs. In vivo (__Q__: visualization?, explore these) = (Illumina dye sequencing, nanopores vs. CRISPR to make "molecular recorders")
    - Benchmark: 99.3% acc. in 2016 and 99.9999% acc. in 2022 for cell free mechanism -->

### [Other Visuals](#visuals)

___RNA World Hypothesis[^rnaW]___

![](/assets/2022/for_digital_dna/images/rna_world.png)

__DNA__[^gen_dna]

![](/assets/2022/for_digital_dna/images/just_dna.png)

[^gen_dna]: See <https://www.genome.gov/genetics-glossary/Deoxyribonucleic-Acid>

---

## [Notes](#notes)

### *Cover Photo*

The [cover photo](https://unsplash.com/photos/IyMaEo0f728) for this page was likely taken by [Martin Woortman](https://unsplash.com/@martfoto1). I found the photo on [Unsplash](https://unsplash.com/). To my knowledge, my use of this photo is permissible under Unsplash's [license](https://unsplash.com/license):
> Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service.

### *Footnotes*

<!-- 
MUSINGS ON DNA
Life on Earth 
RNA World 
RNA vs. DNA (longer)
DNA is dominant 
Facts on DNA (incl. human genome)

Use RNA world to break into solely discussing DNA


The Problem of Storage 
DNA Storage Potential


Some expectations 
DNA digital data storage 
pros 
cons 
bottlenecks  --> 

<!-- Oldest mummy How old will the oldest mummy be in  


https://duckduckgo.com/?t=ffab&q=oldest+human+mummy&atb=v225-1&ia=web-->