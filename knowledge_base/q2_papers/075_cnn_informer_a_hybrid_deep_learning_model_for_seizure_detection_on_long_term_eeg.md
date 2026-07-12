# CNN-Informer: A hybrid deep learning model for seizure detection on long-term EEG

| Field | Value |
|-------|-------|
| ID | 75 |
| DOI | [`10.1016/j.neunet.2024.106855`](https://doi.org/10.1016/j.neunet.2024.106855) |
| Journal | Neural Networks |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | Li Chuanyu; Li Haotian; Dong Xingchen; Zhong Xiangwen; Cui Haozhou; Ji Dezan; He Landi; Liu Guoyang; Zhou Weidong |
| Abstract source | semantic_scholar |

## Abstract

Timely detecting epileptic seizures can significantly reduce accidental injuries of epilepsy patients and offer a novel intervention approach to improve their quality of life. Investigation on seizure detection based on deep learning models has achieved great success. However, there still remain challenging issues, such as the high computational complexity of the models and overfitting caused by the scarce availability of ictal electroencephalogram (EEG) signals for training. Therefore, we propose a novel end-to-end automatic seizure detection model named CNN-Informer, which leverages the capability of Convolutional Neural Network (CNN) to extract EEG local features of multi-channel EEGs, and the low computational complexity and memory usage ability of the Informer to capture the long-range dependencies. In view of the existence of various artifacts in long-term EEGs, we filter those raw EEGs using Discrete Wavelet Transform (DWT) before feeding them into the proposed CNN-Informer model for feature extraction and classification. Post-processing operations are further employed to achieve the final detection results. Our method is extensively evaluated on the CHB-MIT dataset and SH-SDU dataset with both segment-based and event-based criteria. The experimental outcomes demonstrate the superiority of the proposed CNN-Informer model and its strong generalization ability across two EEG datasets. In addition, the lightweight architecture of CNN-Informer makes it suitable for real-time implementation.

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
