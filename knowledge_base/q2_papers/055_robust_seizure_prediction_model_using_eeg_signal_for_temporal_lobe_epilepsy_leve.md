# Robust Seizure Prediction Model Using EEG Signal for Temporal Lobe Epilepsy Leveraging Deep Learning and Continual Learning

| Field | Value |
|-------|-------|
| ID | 55 |
| DOI | [`10.1109/access.2025.3595578`](https://doi.org/10.1109/access.2025.3595578) |
| Journal | IEEE Access |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | Sahoo Bikash Chandra; Mishra Shruti; Satapathy Sandeep Kumar; Kumar Sachin |
| Abstract source | semantic_scholar |

## Abstract

Epilepsy is characterized by abnormal electrical activity in the brain that affects millions worldwide and poses significant challenges to patients and healthcare providers. Seizure prediction has emerged as a pivotal area of research in epilepsy management aiming to mitigate the unpredictability of seizures and enhance patient quality of life. This research focuses on leveraging memory-based learning approaches including transfer learning and recurrent neural networks (RNNs) for seizure prediction. The dataset comprises time-domain signals embedded with noise necessitating preprocessing techniques such as filtering for optimal utilization. By employing deep learning methodologies, the work seeks to classify seizure in temporal lobe epilepsy from the EEG signals to improve seizure prediction accuracy. With deep learning ability to capture temporal dependencies in sequential data, they offer promising avenues for modeling the temporal dynamics of epileptic seizures. Among the performed architecture and their merits when compared to other, “Googlenet” proved to be the best architecture for training the model by achieving the accuracy of 97.5%. Through continual learning strategies, the model’s training process adapts dynamically enabling it to incorporate new information while retaining knowledge from previous tasks. We used “Elastic Weight Consolidation (EWC)” as the continual learning technique which enforces adaptability and robustness of the trained model. With a custom learning rate scheduler that adjust the learning rate during the training based on the current epoch in the EWC technique we enhanced the accuracy to 98.7% which is pretty much promising result. The model improved by 1.2% over the baseline GoogLeNet (97.5%) to reach an accuracy of 98.7% by including Elastic Weight Consolidation (EWC) for continuous learning. When paired with a customized learning rate scheduler, EWC accelerates convergence and improves model adaptability by eliminating catastrophic forgetting.

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
