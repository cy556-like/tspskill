# A Multi-View Deep Learning Framework for EEG Seizure Detection

| Field | Value |
|-------|-------|
| ID | 61 |
| DOI | [`10.1109/jbhi.2018.2871678`](https://doi.org/10.1109/jbhi.2018.2871678) |
| Journal | IEEE Journal of Biomedical and Health Informatics |
| CAS Quartile | Q2 |
| Year | 2019 |
| Authors | Yuan Ye; Xun Guangxu; Jia Kebin; Zhang Aidong |
| Abstract source | semantic_scholar |

## Abstract

The recent advances in pervasive sensing technologies have enabled us to monitor and analyze the multi-channel electroencephalogram (EEG) signals of epilepsy patients to prevent serious outcomes caused by epileptic seizures. To avoid manual visual inspection from long-term EEG readings, automatic EEG seizure detection has garnered increasing attention among researchers. In this paper, we present a unified multi-view deep learning framework to capture brain abnormalities associated with seizures based on multi-channel scalp EEG signals. The proposed approach is an end-to-end model that is able to jointly learn multi-view features from both unsupervised multi-channel EEG reconstruction and supervised seizure detection via spectrogram representation. We construct a new autoencoder-based multi-view learning model by incorporating both inter and intra correlations of EEG channels to unleash the power of multi-channel information. By adding a channel-wise competition mechanism in the training phase, we propose a channel-aware seizure detection module to guide our multi-view structure to focus on important and relevant EEG channels. To validate the effectiveness of the proposed framework, extensive experiments against nine baselines, including both traditional handcrafted feature extraction and conventional deep learning methods, are carried out on a benchmark scalp EEG dataset. Experimental results show that the proposed model is able to achieve higher average accuracy and f1-score at 94.37% and 85.34%, respectively, using 5-fold subject-independent cross validation, demonstrating a powerful and effective method in the task of EEG seizure detection.

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
