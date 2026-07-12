# Augmenting Common Spatial Patterns to deep learning networks for improved alcoholism detection using EEG signals

| Field | Value |
|-------|-------|
| ID | 36 |
| DOI | [`10.1016/j.compbiomed.2025.110359`](https://doi.org/10.1016/j.compbiomed.2025.110359) |
| Journal | Computers in Biology and Medicine |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | Neeraj; Singhal Vatsal; Mathew Jimson; Behera Ranjan Kumar |
| Abstract source | semantic_scholar |

## Abstract

One of the main risk factors for numerous health problems is excessive drinking. Alcoholism is a severe disorder that can affect a person's thinking and cognitive abilities. Early detection of alcoholism can help the subject regain control over their drinking habits and help them recover faster. The diagnosis of alcoholism is challenging, primarily when standard diagnostic tests rely on blood tests and questionnaires that are subjective to the patient and the examiner. This poses the need for fast, reliable, automatic, and preferably non-invasive ways to detect alcoholism. A non-invasive method to capture the electrical activity of the brain is the electroencephalogram (EEG). It can help detect alcohol use disorders in a subject. To our knowledge, no previous work in the literature proposes a mechanism to detect alcoholism using an EEG signal using a deep learning model that considers the spatio-temporal nature of EEG signals. Two works in the literature using a deep learning architecture are Fayyaz et al. (2019) and Farsi et al. (2021). However, both use a simple deep learning architecture and ignore the spatio-temporal nature of multichannel EEG signals. This paper suggests a new hybrid architecture called CSP-CNN-LSTM-ATTN. To obtain nonlinear and nonstationary spatio-temporal features from EEG signals that can accurately classify them as either alcoholic or control (not alcoholic). Our method integrates Common spatial patterns (CSP) for feature extraction, convolutional neural networks (CNN) for spatial representation, long-short-term memory (LSTM) for temporal learning, and attention networks (ATTN) for feature weighting, enhancing classification performance. Experiments on the publicly available UCI EEG dataset demonstrate that our model achieves state-of-the-art results, outperforming existing methods with an accuracy of 98.60%, F1-score 98.59, recall 98.24, precision 98.95, MCC 97.20, and AUC 99.64. The source code for this study is available at Github repository https://github.com/n28neeraj/Alcoholism-Detectio.

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
