# A deep hybrid CSAE-GRU framework with two-stage balancing for automatic epileptic seizure detection using EEG-derived features

| Field | Value |
|-------|-------|
| ID | 51 |
| DOI | [`10.3389/fnins.2025.1698960`](https://doi.org/10.3389/fnins.2025.1698960) |
| Journal | Frontiers in Neuroscience |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | Xiang Fei; Liu Mingyue; Chen Wenna; Zheng Shaojie; Zhang Jincan; Du Ganqin |
| Abstract source | crossref |

## Abstract

Introduction Epilepsy is a neurological disorder characterized by abnormal neuronal discharges in the brain, posing a persistent challenge in clinical diagnosis. This study presents a high-performance epileptic seizure detection framework that integrates advanced feature extraction and classification techniques using EEG signals. Methods We conduct experiments on the Bonn and CHB-MIT EEG datasets. The EEG signals are preprocessed through bandpass filtering and five-level Discrete Wavelet Transform (DWT) decomposition. From each sub-band, four representative features are systematically extracted. To mitigate severe class imbalance, we propose a two-stage balancing strategy: cluster centroid-based under-sampling initially reduces the interictal-to-ictal ratio to 2:1, followed by Borderline Synthetic Minority Oversampling Technique (BLSMOTE) in the feature space. A hybrid classification model that combines Convolutional Sparse Autoencoder (CSAE) with Gated Recurrent Unit (GRU) is proposed in the paper. The encoder weights from the pre-trained CSAE are transferred to the GRU-based classifier to enhance feature representation and model generalization. Results The proposed method achieves outstanding performance, with accuracy, sensitivity, specificity, precision, f1 score and AUC of 98.46, 98.27, 98.50, 98.36, 98.31, and 98.23% on the Bonn dataset, and 99.49, 99.21, 99.77, 99.49, 99.35, and 99.57% on the CHB-MIT dataset, respectively. These results validate the effectiveness of the proposed approach. Discussion This study introduces a novel framework combining cluster centroid-based under-sampling, BLSMOTE oversampling, and transfer learning via CSAE-GRU integration. The method offers a promising direction for reliable and clinically applicable automated epilepsy diagnosis.

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
