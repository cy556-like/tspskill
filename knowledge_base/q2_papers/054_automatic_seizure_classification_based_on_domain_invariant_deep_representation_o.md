# Automatic Seizure Classification Based on Domain-Invariant Deep Representation of EEG

| Field | Value |
|-------|-------|
| ID | 54 |
| DOI | [`10.3389/fnins.2021.760987`](https://doi.org/10.3389/fnins.2021.760987) |
| Journal | Frontiers in Neuroscience |
| CAS Quartile | Q2 |
| Year | 2021 |
| Authors | Cao Xincheng; Yao Bin; Chen Binqiang; Sun Weifang; Tan Guowei |
| Abstract source | crossref |

## Abstract

Accurate identification of the type of seizure is very important for the treatment plan and drug prescription of epileptic patients. Artificial intelligence has shown considerable potential in the fields of automated EEG analysis and seizure classification. However, the highly personalized representation of epileptic seizures in EEG has led to many research results that are not satisfactory in clinical applications. In order to improve the clinical adaptability of the algorithm, this paper proposes an adversarial learning-driven domain-invariant deep feature representation method, which enables the hybrid deep networks (HDN) to reliably identify seizure types. In the train phase, we first use the labeled multi-lead EEG short samples to train squeeze-and-excitation networks (SENet) to extract short-term features, and then use the compressed samples to train the long short-term memory networks (LSTM) to extract long-time features and construct a classifier. In the inference phase, we first adjust the feature mapping of LSTM through the adversarial learning between LSTM and clustering subnet so that the EEG of the target patient and the EEG in the database obey the same distribution in the deep feature space. Finally, we use the adjusted classifier to identify the type of seizure. Experiments were carried out based on the TUH EEG Seizure Corpus and CHB-MIT seizure database. The experimental results show that the proposed domain adaptive deep feature representation improves the classification accuracy of the hybrid deep model in the target set by 5%. It is of great significance for the clinical application of EEG automatic analysis equipment.

## Why this paper is in the knowledge base

This paper is part of the curated knowledge base for the **tspskill** translation skill.
It was retrieved from **CrossRef** (real DOI, title, journal, authors) and, where the
publisher did not deposit an abstract, the abstract was fetched from **Semantic Scholar**.

It is published in a **Q2** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research. The abstract
above is the publisher's authoritative English version — when translating a Chinese passage
that discusses a similar topic, match the phrasing and terminology used here.
