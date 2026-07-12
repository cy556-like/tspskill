# A unified framework for EEG seizure detection using universum-integrated generalized eigenvalues proximal support vector machine

| Field | Value |
|-------|-------|
| ID | 74 |
| DOI | [`10.1016/j.neunet.2025.108520`](https://doi.org/10.1016/j.neunet.2025.108520) |
| Journal | Neural Networks |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Kumar Yogesh; Ahire Vrushank; Ganaie Mudasir |
| Abstract source | semantic_scholar |

## Abstract

The paper presents novel Universum-enhanced classifiers: the Universum Generalized Eigenvalue Proximal Support Vector Machine (U-GEPSVM) and the Improved U-GEPSVM (IU-GEPSVM) for EEG signal classification. Using the computational efficiency of generalized eigenvalue decomposition and the generalization benefits of Universum learning, the proposed models address critical challenges in EEG analysis: non-stationarity, low signal-to-noise ratio, and limited labeled data. U-GEPSVM extends the GEPSVM framework by incorporating Universum constraints through a ratio-based objective function, while IU-GEPSVM enhances stability through a weighted difference-based formulation that provides independent control over class separation and Universum alignment. The models are evaluated on the Bonn University EEG dataset across two binary classification tasks: (O vs S)-healthy (eyes closed) vs seizure, and (Z vs S)-healthy (eyes open) vs seizure. IU-GEPSVM achieves peak accuracies of 85% (O vs S) and 80% (Z vs S), with mean accuracies of 81.29% and 77.57% respectively, outperforming baseline methods. Rigorous statistical validation confirms these improvements: Friedman tests reveal significant overall differences, pairwise Wilcoxon signed-rank tests with Bonferroni correction establish IU-GEPSVM's superiority over all baselines, and win-tie-loss analysis demonstrates practical significance. Overall, integrating interictal Universum data yields an efficient and reliable solution for neurological diagnosis.

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
