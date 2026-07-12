# Automatic Seizure Classification Based on Domain-Invariant Deep Representation of EEG

| Field | Value |
|-------|-------|
| ID | 45 |
| DOI | [`10.3389/fnins.2021.760987`](https://doi.org/10.3389/fnins.2021.760987) |
| Journal | Frontiers in Neuroscience |
| CAS Quartile | Q2 |
| Year | 2021 |
| Authors | Cao Xincheng; Yao Bin; Chen Binqiang; Sun Weifang; Tan Guowei |
| Abstract source | crossref |
| **Full-text PDF** | **Available: [`10-3389_fnins-2021-760987.pdf`](../pdfs/10-3389_fnins-2021-760987.pdf)** |

## Abstract

Accurate identification of the type of seizure is very important for the treatment plan and drug prescription of epileptic patients. Artificial intelligence has shown considerable potential in the fields of automated EEG analysis and seizure classification. However, the highly personalized representation of epileptic seizures in EEG has led to many research results that are not satisfactory in clinical applications. In order to improve the clinical adaptability of the algorithm, this paper proposes an adversarial learning-driven domain-invariant deep feature representation method, which enables the hybrid deep networks (HDN) to reliably identify seizure types. In the train phase, we first use the labeled multi-lead EEG short samples to train squeeze-and-excitation networks (SENet) to extract short-term features, and then use the compressed samples to train the long short-term memory networks (LSTM) to extract long-time features and construct a classifier. In the inference phase, we first adjust the feature mapping of LSTM through the adversarial learning between LSTM and clustering subnet so that the EEG of the target patient and the EEG in the database obey the same distribution in the deep feature space. Finally, we use the adjusted classifier to identify the type of seizure. Experiments were carried out based on the TUH EEG Seizure Corpus and CHB-MIT seizure database. The experimental results show that the proposed domain adaptive deep feature representation improves the classification accuracy of the hybrid deep model in the target set by 5%. It is of great significance for the clinical application of EEG automatic analysis equipment.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-3389_fnins-2021-760987.pdf` (located in [`../pdfs/`](../pdfs/)).

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
