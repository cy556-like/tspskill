# Rethinking Saliency Map: A Context-Aware Perturbation Method to Explain EEG-Based Deep Learning Model

| Field | Value |
|-------|-------|
| ID | 67 |
| DOI | [`10.1109/tbme.2022.3218116`](https://doi.org/10.1109/tbme.2022.3218116) |
| Journal | IEEE Transactions on Biomedical Engineering |
| CAS Quartile | Q2 |
| Year | 2023 |
| Authors | Wang Hanqi; Zhu Xiaoguang; Chen Tao; Li Chengfang; Song Liang |
| Abstract source | semantic_scholar |

## Abstract

Deep learning is widely used to decode the electroencephalogram (EEG) signal. However, there are few attempts to specifically study how to explain EEG-based deep learning models. In this paper, we review the related works that attempt to explain EEG-based models. And we find that the existing methods are not perfect enough to explain the EEG-based model due to the non-stationary nature, high inter-subject variability and dependency of EEG data. The characteristics of the EEG data require the explanation to incorporate the instance-level saliency identification and the context information of EEG data. Recently, mask perturbation is proposed to explain deep learning model. Inspired by the mask perturbation, we propose a new context-aware perturbation method to address these concerns. Our method not only extends the scope to the instance level but can capture the representative context information when estimating the saliency map. In addition, we point out another role of context information in explaining the EEG-based model. The context information can also help suppress the artifacts in the EEG-based deep learning model. In practice, some users might want a simple version of the explanation, which only indicates a few features as salient points. To further improve the usability of our method, we propose an optional area limitation strategy to restrict the highlighted region. In the experiment section, we select three representative EEG-based models and implement them on the emotional EEG dataset DEAP. The results of the experiments support the advantages of our method.

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
