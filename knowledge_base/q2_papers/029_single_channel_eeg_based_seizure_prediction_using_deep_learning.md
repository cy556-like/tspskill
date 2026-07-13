# Single-channel EEG-based seizure prediction using deep learning

| Field | Value |
|-------|-------|
| ID | 29 |
| DOI | [`10.1038/s41598-026-44670-7`](https://doi.org/10.1038/s41598-026-44670-7) |
| Journal | Scientific Reports |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Jang Dabin; Jung Ki-Young; Jeon Young-Gyu; Kim Tae-Joon; Lee Sang Kun; Min Kyeong-Yuk |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Available: [`10-1038_s41598-026-44670-7.pdf`](../pdfs/10-1038_s41598-026-44670-7.pdf)** |

## Abstract

Reliable seizure prediction can improve patient safety by enabling timely protective actions, yet most high-performing approaches depend on multichannel EEG, limiting feasibility in wearable and low-power environments. This study developed an ultralight deep learning model for seizure prediction using only single-channel EEG and evaluated its clinical applicability under predefined, clinically actionable criteria: a seizure prediction horizon (SPH) of 2 minutes and a seizure occurrence period (SOP) of 30 minutes. A 37,985-parameter MobileNet-derived architecture was designed to process STFT spectrograms and validated using patient-specific leave-one-out cross-validation on the SNUH and CHB-MIT datasets. Performance was assessed using segment-based accuracy and false positive rate (FPR), along with event-based sensitivity computed under SPH–SOP constraints. The model demonstrated strong and consistent performance across both datasets. In the SNUH cohort, it achieved 85.97% accuracy, an FPR of 0.130, and 94.93% sensitivity, successfully predicting 95.08% of seizures within the SOP window. In the CHB-MIT dataset, it reached 90.72% accuracy, an FPR of 0.092, and 97.92% sensitivity. These findings provide the first evidence that single-channel EEG can support reliable seizure prediction within clinically meaningful early-warning windows. The proposed lightweight model delivers multichannel-comparable performance while drastically reducing computational demand, demonstrating strong potential for real-time deployment in wearable and patient-centered epilepsy management systems.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-1038_s41598-026-44670-7.pdf` (located in [`../pdfs/`](../pdfs/)).

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
It is published in a **Q2** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research.
