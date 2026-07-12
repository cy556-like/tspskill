# TasteNet: A novel deep learning approach for EEG-based basic taste perception recognition using CEEMDAN domain entropy features

| Field | Value |
|-------|-------|
| ID | 68 |
| DOI | [`10.1016/j.jneumeth.2025.110463`](https://doi.org/10.1016/j.jneumeth.2025.110463) |
| Journal | Journal of Neuroscience Methods |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | De Sagnik; Mukherjee Prithwijit; Roy Anisha Halder |
| Abstract source | semantic_scholar |

## Abstract

BACKGROUND
Taste perception is the process by which the gustatory system detects and interprets chemical stimuli from food and beverages, involving activation of taste receptors on the tongue. Analyzing taste perception is essential for understanding human sensory responses and diagnosing taste-related disorders.


NEW METHOD
This research focuses on developing a deep learning framework to effectively recognize basic taste stimuli from EEG signals. Initially, the recorded EEG signals undergo preprocessing to remove noise and artifacts. The CEEMDAN (complete ensemble empirical mode decomposition with adaptive noise) method is then applied to decompose the EEG signals into various frequency rhythms, referred to as intrinsic mode functions (IMFs). From the chosen IMFs, six distinct entropy features-sample, bubble, approximate, dispersion, slope, and permutation entropy-are extracted for further analysis. A novel deep learning model, TasteNet, is then developed, integrating a convolutional neural network (CNN) module, a multi-head attention module, and the Att-BiPLSTM (Attention-Bidirectional Potent Long Short-Term Memory) network.


RESULTS
The proposed architecture classifies the input data into six categories: no taste, sweet, sour, bitter, umami, and salty, achieving a remarkable accuracy of 97.52 ±0.48%.


COMPARISON WITH EXISTING METHODS
TasteNet outperforms existing taste perception classification methods, as demonstrated through extensive experiments.


CONCLUSION
This study presents TasteNet, a robust framework for precise taste perception recognition using EEG signals. Using CEEMDAN for effective signal decomposition and extracting key entropy features, the model captures intricate patterns in taste stimuli. The incorporation of multi-head attention module and the Att-BiPLSTM network further enhances the model's ability to identify various taste sensations accurately.

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
