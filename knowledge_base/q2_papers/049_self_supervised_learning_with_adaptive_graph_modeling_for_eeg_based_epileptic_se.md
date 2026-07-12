# Self-Supervised Learning With Adaptive Graph Modeling for EEG-Based Epileptic Seizure Classification

| Field | Value |
|-------|-------|
| ID | 49 |
| DOI | [`10.1109/tbme.2025.3605790`](https://doi.org/10.1109/tbme.2025.3605790) |
| Journal | IEEE Transactions on Biomedical Engineering |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Hu Yue; Liu Jian; Zhang Wenli; Sui Yi; Meng Qingyue; Sun Rencheng |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Not available (paywall)** |

## Abstract

Objective: Epileptic seizure classification using EEG signals remains a significant challenge due to complex spatial-temporal dependencies, limited labeled data, and severe class imbalance. Methods: We propose a self-supervised learning framework, ASGPF (Adaptive Spatio-Graph Pretraining Framework), for EEG-based seizure classification. At its core is a novel Spatio-Graph Learning Cell (SGLC), which integrates a Graph Learning module to dynamically construct EEG topology, a Gated Graph Neural Network to extract spatial features across EEG channels, and a Gated Recurrent Unit to capture long-term temporal dependencies. ASGPF uses self-supervised sequence-to-sequence pretraining on unlabeled EEG to learn robust representations, enabling accurate seizure classification with a lightweight model that consists of the pretrained encoder and a simple prediction layer. Results: Extensive experiments on the TUSZ dataset demonstrate that our method significantly outperforms current state-of-the-art approaches, achieving weighted F1-scores of 83.8% for four-class and 73.5% for eight-class seizure classification tasks, respectively. Notably, with only 25% of labeled data, the proposed model achieves comparable performance to the best baseline trained on 75% of data, validating the effectiveness of ASGPF under data scarcity and class imbalance. Conclusion: ASGPF effectively learns discriminative EEG representations through adaptive spatial-temporal modeling and self-supervised pretraining, enabling accurate seizure classification with minimal labeled data. Significance: This work introduces a data-efficient EEG analysis framework for seizure classification, enabling accurate prediction with minimal labeled data and showing strong potential for clinical application in resource- and label-constrained environments.

## Full text

The full text of this paper is **not available in the knowledge base** because it is
published in a subscription-based journal and no open-access version could be
located via Unpaywall, PubMed Central, Europe PMC, or arXiv.

To access the full text:
1. Visit the publisher's page: https://doi.org/10.1109/tbme.2025.3605790
2. Use institutional access (university library, VPN, etc.)
3. Request the paper directly from the corresponding author.

The metadata (title, authors, journal, year, DOI) and abstract above are real
and were retrieved from CrossRef / Semantic Scholar. Only the full text is
unavailable due to copyright restrictions.

## Why this paper is in the knowledge base

This paper is part of the curated knowledge base for the **tspskill** translation skill.
It is published in a **Q2** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research.
