# DistilCLIP-EEG: Enhancing Epileptic Seizure Detection Through Multi-modal Learning and Knowledge Distillation

| Field | Value |
|-------|-------|
| ID | 58 |
| DOI | [`10.1109/jbhi.2025.3603022`](https://doi.org/10.1109/jbhi.2025.3603022) |
| Journal | IEEE Journal of Biomedical and Health Informatics |
| CAS Quartile | Q2 |
| Year | 2025 |
| Authors | Wang Zexin; Shi Lin; Wu Haoyu; Luo Junru; Kong Xiangzeng; Qi Jun |
| Abstract source | semantic_scholar |

## Abstract

Epilepsy is a prevalent neurological disorder marked by sudden, brief episodes of excessive neuronal activity caused by abnormal electrical discharges, which may lead to some mental disorders. Most existing deep learning methods for epilepsy detection rely solely on unimodal EEG signals, neglecting the potential benefits of multimodal information. To address this, we propose a novel multimodal model, DistilCLIP-EEG, based on the CLIP framework, which integrates both EEG signals and text descriptions to capture comprehensive features of epileptic seizures. The model involves an EEG encoder based on the Conformer architecture as a text encoder, the proposed Learnable BERT (BERT-LP) as prompt learning within the encoders. Both operate in a shared latent space for effective cross-modal representation learning. To enhance efficiency and adaptability, we introduce a knowledge distillation method where the trained DistilCLIP-EEG serves as a teacher to guide a more compact student model to reduce training complexity and time. On the TUSZ, AUBMC, and CHB-MIT datasets, both the teacher and student models achieved accuracy rates exceeding 97%. Across all datasets, the F1-scores were consistently above 0.94, demonstrating the robustness and reliability of the proposed framework. Moreover, the student model's parameter count and model size are approximately 58.1% of those of the teacher model, significantly reducing model complexity and storage requirements while maintaining high performance. These results highlight the potential of our proposed model for EEG-based epilepsy detection and establish a solid foundation for deploying lightweight models in resource-constrained settings.

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
