# Towards trustworthy seizure onset detection using workflow notes

| Field | Value |
|-------|-------|
| ID | 4 |
| DOI | [`10.1038/s41746-024-01008-9`](https://doi.org/10.1038/s41746-024-01008-9) |
| Journal | npj Digital Medicine |
| CAS Quartile | Q1 |
| Year | 2024 |
| Authors | Saab Khaled; Tang Siyi; Taha Mohamed; Lee-Messer Christopher; Ré Christopher; Rubin Daniel L. |
| Abstract source | crossref |
| **Full-text PDF** | **Available: [`10-1038_s41746-024-01008-9.pdf`](../pdfs/10-1038_s41746-024-01008-9.pdf)** |

## Abstract

Abstract A major barrier to deploying healthcare AI is trustworthiness. One form of trustworthiness is a model’s robustness across subgroups: while models may exhibit expert-level performance on aggregate metrics, they often rely on non-causal features, leading to errors in hidden subgroups. To take a step closer towards trustworthy seizure onset detection from EEG, we propose to leverage annotations that are produced by healthcare personnel in routine clinical workflows—which we refer to as workflow notes—that include multiple event descriptions beyond seizures. Using workflow notes, we first show that by scaling training data to 68,920 EEG hours, seizure onset detection performance significantly improves by 12.3 AUROC (Area Under the Receiver Operating Characteristic) points compared to relying on smaller training sets with gold-standard labels. Second, we reveal that our binary seizure onset detection model underperforms on clinically relevant subgroups (e.g., up to a margin of 6.5 AUROC points between pediatrics and adults), while having significantly higher FPRs (False Positive Rates) on EEG clips showing non-epileptiform abnormalities (+19 FPR points). To improve model robustness to hidden subgroups, we train a multilabel model that classifies 26 attributes other than seizures (e.g., spikes and movement artifacts) and significantly improve overall performance (+5.9 AUROC points) while greatly improving performance among subgroups (up to +8.3 AUROC points) and decreasing false positives on non-epileptiform abnormalities (by 8 FPR points). Finally, we find that our multilabel model improves clinical utility (false positives per 24 EEG hours) by a factor of 2×.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-1038_s41746-024-01008-9.pdf` (located in [`../pdfs/`](../pdfs/)).

The PDF was downloaded from an **open-access source** identified via the
[Unpaywall API](https://unpaywall.org/) (publisher OA, PubMed Central, Europe PMC,
or arXiv where the preprint matches the published version). The PDF has been
verified to match the expected paper by checking that the title and author
names appear in the extracted text.

Translators should **open and read the full PDF** when translating passages
that reference specific methodology, results, or discussion sections of this
paper. The full text provides the authoritative terminology and phrasing for
the methods and results sections, which abstracts alone cannot fully capture.

## Why this paper is in the knowledge base

This paper is part of the curated knowledge base for the **tspskill** translation skill.
It is published in a **Q1** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research.
