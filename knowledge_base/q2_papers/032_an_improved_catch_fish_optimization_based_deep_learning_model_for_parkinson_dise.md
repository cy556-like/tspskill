# An improved catch fish optimization based deep learning model for Parkinson disease classification using EEG signal

| Field | Value |
|-------|-------|
| ID | 32 |
| DOI | [`10.1016/j.compbiomed.2026.111812`](https://doi.org/10.1016/j.compbiomed.2026.111812) |
| Journal | Computers in Biology and Medicine |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Pravitha V. Devan; Ramesh S.C.; Sreelekshmi P.G.; Keerthanadevi R. |
| Abstract source | semantic_scholar |

## Abstract

Accurate and objective identification of Parkinson's Disease (PD) from Electroencephalogram (EEG) signals is important because EEG responses are complex, non-stationary, and difficult to evaluate manually. This work proposes an Improved Catch Fish Optimization (ICFO)-based encoder-decoder deep learning framework for PD classification using EEG signals. Initially, EEG signals are pre-processed using a bandpass filter to remove unwanted noise and retain the significant frequency range. Then, Tunable-Q Wavelet Transform (TQWT) is employed to decompose the EEG signals into informative sub-bands. The extracted signal components are classified using an encoder-decoder-based Multi-Head Attention Bidirectional Long Short-Term Memory network (MA-BiLSTM), while ICFO is used to optimize the major hyperparameters of the model. The proposed method was evaluated using two publicly available EEG datasets, namely the San Diego dataset and the Iowa dataset. The proposed MA-BiLSTM-ICFO model achieved an accuracy of 99.2%, recall of 99.9%, precision of 99.2%, F-score of 99.2%, and AUC of 98.975% on the San Diego dataset. For the Iowa dataset, the model achieved an accuracy of 99.7%, recall of 99.9%, precision of 99.3%, F-score of 98.9%, and AUC of 98.973%. The ablation and comparative analyses confirm that the integration of TQWT, multi-head attention, BiLSTM, and ICFO improves classification performance compared with existing models. These results demonstrate that the proposed framework can provide reliable automated support for EEG-based PD classification.

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
