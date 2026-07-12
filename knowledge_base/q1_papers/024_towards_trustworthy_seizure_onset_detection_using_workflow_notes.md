# Towards trustworthy seizure onset detection using workflow notes

| Field | Value |
|-------|-------|
| ID | 24 |
| DOI | [`10.1038/s41746-024-01008-9`](https://doi.org/10.1038/s41746-024-01008-9) |
| Journal | npj Digital Medicine |
| CAS Quartile | Q1 |
| Year | 2024 |
| Authors | Saab Khaled; Tang Siyi; Taha Mohamed; Lee-Messer Christopher; Ré Christopher; Rubin Daniel L. |
| Abstract source | crossref |

## Abstract

Abstract A major barrier to deploying healthcare AI is trustworthiness. One form of trustworthiness is a model’s robustness across subgroups: while models may exhibit expert-level performance on aggregate metrics, they often rely on non-causal features, leading to errors in hidden subgroups. To take a step closer towards trustworthy seizure onset detection from EEG, we propose to leverage annotations that are produced by healthcare personnel in routine clinical workflows—which we refer to as workflow notes—that include multiple event descriptions beyond seizures. Using workflow notes, we first show that by scaling training data to 68,920 EEG hours, seizure onset detection performance significantly improves by 12.3 AUROC (Area Under the Receiver Operating Characteristic) points compared to relying on smaller training sets with gold-standard labels. Second, we reveal that our binary seizure onset detection model underperforms on clinically relevant subgroups (e.g., up to a margin of 6.5 AUROC points between pediatrics and adults), while having significantly higher FPRs (False Positive Rates) on EEG clips showing non-epileptiform abnormalities (+19 FPR points). To improve model robustness to hidden subgroups, we train a multilabel model that classifies 26 attributes other than seizures (e.g., spikes and movement artifacts) and significantly improve overall performance (+5.9 AUROC points) while greatly improving performance among subgroups (up to +8.3 AUROC points) and decreasing false positives on non-epileptiform abnormalities (by 8 FPR points). Finally, we find that our multilabel model improves clinical utility (false positives per 24 EEG hours) by a factor of 2×.

## Why this paper is in the knowledge base

This paper is part of the curated knowledge base for the **tspskill** translation skill.
It was retrieved from **CrossRef** (real DOI, title, journal, authors) and, where the
publisher did not deposit an abstract, the abstract was fetched from **Semantic Scholar**.

It is published in a **Q1** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research. The abstract
above is the publisher's authoritative English version — when translating a Chinese passage
that discusses a similar topic, match the phrasing and terminology used here.
