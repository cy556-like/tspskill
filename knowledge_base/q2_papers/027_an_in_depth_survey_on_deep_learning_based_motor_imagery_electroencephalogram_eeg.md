# An in-depth survey on Deep Learning-based Motor Imagery Electroencephalogram (EEG) classification

| Field | Value |
|-------|-------|
| ID | 27 |
| DOI | [`10.1016/j.artmed.2023.102738`](https://doi.org/10.1016/j.artmed.2023.102738) |
| Journal | Artificial Intelligence in Medicine |
| CAS Quartile | Q2 |
| Year | 2024 |
| Authors | Wang Xianheng; Liesaputra Veronica; Liu Zhaobin; Wang Yi; Huang Zhiyi |
| Abstract source | semantic_scholar |

## Abstract

Electroencephalogram (EEG)-based Brain-Computer Interfaces (BCIs) build a communication path between human brain and external devices. Among EEG-based BCI paradigms, the most commonly used one is motor imagery (MI). As a hot research topic, MI EEG-based BCI has largely contributed to medical fields and smart home industry. However, because of the low signal-to-noise ratio (SNR) and the non-stationary characteristic of EEG data, it is difficult to correctly classify different types of MI-EEG signals. Recently, the advances in Deep Learning (DL) significantly facilitate the development of MI EEG-based BCIs. In this paper, we provide a systematic survey of DL-based MI-EEG classification methods. Specifically, we first comprehensively discuss several important aspects of DL-based MI-EEG classification, covering input formulations, network architectures, public datasets, etc. Then, we summarize problems in model performance comparison and give guidelines to future studies for fair performance comparison. Next, we fairly evaluate the representative DL-based models using source code released by the authors and meticulously analyse the evaluation results. By performing ablation study on the network architecture, we found that (1) effective feature fusion is indispensable for multi-stream CNN-based models. (2) LSTM should be combined with spatial feature extraction techniques to obtain good classification performance. (3) the use of dropout contributes little to improving the model performance, and that (4) adding fully connected layers to the models significantly increases their parameters but it might not improve their performance. Finally, we raise several open issues in MI-EEG classification and provide possible future research directions.

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
