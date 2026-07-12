# GLEAM: A multimodal deep learning framework for chronic lower back pain detection using EEG and sEMG signals

| Field | Value |
|-------|-------|
| ID | 34 |
| DOI | [`10.1016/j.compbiomed.2025.109928`](https://doi.org/10.1016/j.compbiomed.2025.109928) |
| Journal | Computers in Biology and Medicine |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | De Sagnik; Mukherjee Prithwijit; Roy Anisha Halder |
| Abstract source | semantic_scholar |

## Abstract

Low Back Pain (LBP) is the most prevalent musculoskeletal condition worldwide and a leading cause of disability, significantly affecting mobility, work productivity, and overall quality of life. Due to its high prevalence and substantial economic burden, LBP presents a critical global public health challenge that demands innovative diagnostic and therapeutic solutions. This study introduces a novel deep-learning approach for diagnosing LBP intensity using electroencephalography (EEG) signals and surface electromyography (sEMG) signals from back muscles. A GAN-Convolution-Transformer-based model, named GLEAM (GAN-ConvoLution-sElf Attention-ETLSTM), is designed to classify LBP intensity into four categories: no LBP, mild LBP, moderate LBP, and intolerable LBP. A denoising GAN is central to the model's functionality, playing a pivotal role in enhancing the quality of EEG and sEMG signals by removing noise, resulting in cleaner and more accurate input data. Various features are extracted from the GAN-denoised EEG and sEMG signals, and the combined features from both EEG and sEMG are used for LBP detection. After the feature extraction, the CNN is employed to capture local temporal patterns within the data, allowing the model to focus on smaller, region-specific trends in the signals. Subsequently, the self-attention module identifies global correlations among these locally extracted features, enhancing the model's ability to recognize broader patterns. The proposed ETLSTM network performs the final classification, which achieves an impressive LBP detection accuracy of 98.95%. This research presents several innovative contributions: (i) the development of a novel denoising GAN for cleaning EEG and sEMG signals, (ii) the design and integration of a new ETLSTM architecture as a classifier within the GLEAM model, and (iii) the introduction of the GLEAM hybrid deep learning framework, which enables robust and reliable LBP intensity assessment.

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
