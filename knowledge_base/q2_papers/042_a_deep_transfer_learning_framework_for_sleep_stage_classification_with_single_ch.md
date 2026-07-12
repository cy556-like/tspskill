# A Deep Transfer Learning Framework for Sleep Stage Classification with Single-Channel EEG Signals

| Field | Value |
|-------|-------|
| ID | 42 |
| DOI | [`10.3390/s22228826`](https://doi.org/10.3390/s22228826) |
| Journal | Sensors |
| CAS Quartile | Q2 |
| Year | 2022 |
| Authors | ElMoaqet Hisham; Eid Mohammad; Ryalat Mutaz; Penzel Thomas |
| Abstract source | crossref |
| **Full-text PDF** | **Available: [`10-3390_s22228826.pdf`](../pdfs/10-3390_s22228826.pdf)** |

## Abstract

The polysomnogram (PSG) is the gold standard for evaluating sleep quality and disorders. Attempts to automate this process have been hampered by the complexity of the PSG signals and heterogeneity among subjects and recording hardwares. Most of the existing methods for automatic sleep stage scoring rely on hand-engineered features that require prior knowledge of sleep analysis. This paper presents an end-to-end deep transfer learning framework for automatic feature extraction and sleep stage scoring based on a single-channel EEG. The proposed framework was evaluated over the three primary signals recommended by the American Academy of Sleep Medicine (C4-M1, F4-M1, O2-M1) from two data sets that have different properties and are recorded with different hardware. Different Time–Frequency (TF) imaging approaches were evaluated to generate TF representations for the 30 s EEG sleep epochs, eliminating the need for complex EEG signal pre-processing or manual feature extraction. Several training and detection scenarios were investigated using transfer learning of convolutional neural networks (CNN) and combined with recurrent neural networks. Generating TF images from continuous wavelet transform along with a deep transfer architecture composed of a pre-trained GoogLeNet CNN followed by a bidirectional long short-term memory (BiLSTM) network showed the best scoring performance among all tested scenarios. Using 20-fold cross-validation applied on the C4-M1 channel, the proposed framework achieved an average per-class accuracy of 91.2%, sensitivity of 77%, specificity of 94.1%, and precision of 75.9%. Our results demonstrate that without changing the model architecture and the training algorithm, our model could be applied to different single-channel EEGs from different data sets. Most importantly, the proposed system receives a single EEG epoch as an input at a time and produces a single corresponding output label, making it suitable for real time monitoring outside sleep labs as well as to help sleep lab specialists arrive at a more accurate diagnoses.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-3390_s22228826.pdf` (located in [`../pdfs/`](../pdfs/)).

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
