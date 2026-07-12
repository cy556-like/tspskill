# DCSENets: Interpretable deep learning for patient-independent seizure classification using enhanced EEG-based spectrogram visualization

| Field | Value |
|-------|-------|
| ID | 37 |
| DOI | [`10.1016/j.compbiomed.2024.109558`](https://doi.org/10.1016/j.compbiomed.2024.109558) |
| Journal | Computers in Biology and Medicine |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | Aboyeji Sunday Timothy; Ahmad Ijaz; Wang Xin; Chen Yan; Yao Chen; Li Guanglin; Tong Michael Chi Fai; Siu Alice K.Y.; Zhao Guoru; Chen Shixiong |
| Abstract source | semantic_scholar |

## Abstract

Neurologists often face challenges in identifying epileptic activities within multichannel EEG recordings, requiring extensive hours of analysis. Computer-aided diagnosis systems have been proposed to reduce manual inspection of EEG signals by neurologists. However, direct analysis of EEG signals is difficult due to their complex and dynamic nature, with variation across multiple patients. Therefore, researchers have proposed the short-time Fourier transform (STFT) to capture dynamic events indicative of seizures through time-varying frequency representation of EEG signals. However, tradeoffs between time and frequency resolution limited the spectrogram's interpretability and affected clinical deployment. Hence, this study proposes extracting high-resolution channels via a novel STFT spectrogram construction algorithm encompassing taper functions for seizure diagnosis. Initially, we extracted seizure and non-seizure segments from each channel of selected patients in the CHB-MIT dataset. Next, we systematically apply taper functions like Hann and Gaussian windows to minimize the edge effect during the construction of spectrogram images. Finally, we employ Dilated Convolutional Squeeze and Excitation Networks (DCSENets) through leave-one-patient-out cross-validation (LOPOCV) to perform patient-independent seizure classification. The proposed DCSENets achieve an average accuracy of 87.20±11.48% and 87.29±10.48% with Hann and Gaussian taper functions, respectively, and 86.85±11.56% without the taper function. Most patients with high performances indicate similarity in train-test sample distribution using the Kolmogorov-Smirnov test at 0.010.05. Furthermore, the Grad CAM deep visual explainer integration enhances the interpretability of the deep learning model's decision-making process. Consequently, neurologists are provided not only with enhanced visualized spectrograms but also a transparent model for improved seizure diagnosis.

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
