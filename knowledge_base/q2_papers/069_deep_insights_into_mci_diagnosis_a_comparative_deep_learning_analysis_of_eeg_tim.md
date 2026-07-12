# Deep insights into MCI diagnosis: A comparative deep learning analysis of EEG time series

| Field | Value |
|-------|-------|
| ID | 69 |
| DOI | [`10.1016/j.jneumeth.2024.110057`](https://doi.org/10.1016/j.jneumeth.2024.110057) |
| Journal | Journal of Neuroscience Methods |
| CAS Quartile | Q2 |
| Year | 2024 |
| Authors | Şeker Mesut; Özerdem Mehmet Siraç |
| Abstract source | semantic_scholar |

## Abstract

BACKGROUND
Individuals in the early stages of Alzheimer's Disease (AD) are typically diagnosed with Mild Cognitive Impairment (MCI). MCI represents a transitional phase between normal cognitive function and AD. Electroencephalography (EEG) records carry valuable insights into cerebral cortex brain activities to analyze neuronal degeneration. To enhance the precision of dementia diagnosis, automatic and intelligent methods are required for the analysis and processing of EEG signals.


NEW METHODS
This paper aims to address the challenges associated with MCI diagnosis by leveraging EEG signals and deep learning techniques. The analysis in this study focuses on processing the information embedded within the sequence of raw EEG time series data. EEG recordings are collected from 10 Healthy Controls (HC) and 10 MCI participants using 19 electrodes during a 30min eyes-closed session. EEG time series are transformed into 2 separate formats of input tensors and applied to deep neural network architectures. Convolutional Neural Network (CNN) and ResNet from scratch are performed with 2D time series with different segment lengths. Furthermore, EEGNet and DeepConvNet architectures are utilized for 1D time series.


RESULTS
ResNet demonstrates superior effectiveness in detecting MCI when compared to CNN architecture. Complete discrimination is achieved using EEGNet and DeepConvNet for noisy segments.


COMPARISON WITH EXISTING METHODS
ResNet has yielded a 3% higher accuracy rate compared to CNN. None of the architectures in the literature have achieved 100% accuracy except proposed EEGNet and DeepConvnet.


CONCLUSION
Deep learning architectures hold great promise in enhancing the accuracy of early MCI detection.

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
