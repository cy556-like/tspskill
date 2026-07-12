# A novel deep learning model based on the ICA and Riemannian manifold for EEG-based emotion recognition

| Field | Value |
|-------|-------|
| ID | 71 |
| DOI | [`10.1016/j.jneumeth.2022.109642`](https://doi.org/10.1016/j.jneumeth.2022.109642) |
| Journal | Journal of Neuroscience Methods |
| CAS Quartile | Q2 |
| Year | 2022 |
| Authors | Wu Minchao; Hu Shiang; Wei Bing; Lv Zhao |
| Abstract source | semantic_scholar |

## Abstract

BACKGROUND
The EEG-based emotion recognition is one of the primary research orientations in the field of emotional intelligence and human-computer interaction (HCI).


NEW METHOD
We proposed a novel model, denoted as ICRM-LSTM, for EEG-based emotion recognition by combining the independent component analysis (ICA), the Riemannian manifold (RM), and the long short-term memory network (LSTM). The SEED and MAHNOB-HCI dataset were employed to verify the performance of the proposed model. Firstly, ICA was used to perform blind source separation (BSS) for the preprocessed EEG signals provided by the two datasets. Then, a series of the covariance matrices according to time order were extracted from the blind source signals, and the symmetric positive definiteness of covariance matrix allowed us to project them from RM space to Euclid space by logarithmic mapping. Finally, the transformed covariance matrices were taken as inputs of the LSTM network to perform the emotion recognition.


RESULTS
To validate the effect of the ICRM method on the performance of the proposed model, we designed three groups of comparative experiments. The average accuracy of the ICRM-LSTM model were 96.75% and 98.09% in SEED and MAHNOB-HCI, respectively. Then we compared our model with the models didn't perform the ICA or RM method, where we found that the proposed model had better performance. Furthermore, to verify the robustness, we added three groups of Gaussian noise with different signal-to-noise ratios (SNR) to the preprocessed EEG signals, and the proposed model achieved a good performance in both the two datasets.


COMPARISON WITH EXISTING METHOD
The performance of our model was superior to most of existing methods which also employed the SEED or MAHNOB-HCI dataset.


CONCLUSION
This paper demonstrated that the ICA and RM were helpful for EEG-based emotion recognition, and provided the evidence that the RM method could effectively alleviate the problem of the uncertain ordering of ICA.

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
