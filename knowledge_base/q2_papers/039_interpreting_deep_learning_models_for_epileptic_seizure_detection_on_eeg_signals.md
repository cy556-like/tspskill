# Interpreting deep learning models for epileptic seizure detection on EEG signals

| Field | Value |
|-------|-------|
| ID | 39 |
| DOI | [`10.1016/j.artmed.2021.102084`](https://doi.org/10.1016/j.artmed.2021.102084) |
| Journal | Artificial Intelligence in Medicine |
| CAS Quartile | Q2 |
| Year | 2021 |
| Authors | Gabeff Valentin; Teijeiro Tomas; Zapater Marina; Cammoun Leila; Rheims Sylvain; Ryvlin Philippe; Atienza David |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Available: [`10-1016_j-artmed-2021-102084.pdf`](../pdfs/10-1016_j-artmed-2021-102084.pdf)** |

## Abstract

While Deep Learning (DL) is often considered the state-of-the art for Artificial Intel-ligence-based medical decision support, it remains sparsely implemented in clinical practice and poorly trusted by clinicians due to insufficient interpretability of neural network models. We have approached this issue in the context of online detection of epileptic seizures by developing a DL model from EEG signals, and associating certain properties of the model behavior with the expert medical knowledge. This has conditioned the preparation of the input signals, the network architecture, and the post-processing of the output in line with the domain knowledge. Specifically, we focused the discussion on three main aspects: (1) how to aggregate the classification results on signal segments provided by the DL model into a larger time scale, at the seizure-level; (2) what are the relevant frequency patterns learned in the first convolutional layer of different models, and their relation with the delta, theta, alpha, beta and gamma frequency bands on which the visual interpretation of EEG is based; and (3) the identification of the signal waveforms with larger contribution towards the ictal class, according to the activation differences highlighted using the DeepLIFT method. Results show that the kernel size in the first layer determines the interpretability of the extracted features and the sensitivity of the trained models, even though the final performance is very similar after post-processing. Also, we found that amplitude is the main feature leading to an ictal prediction, suggesting that a larger patient population would be required to learn more complex frequency patterns. Still, our methodology was successfully able to generalize patient inter-variability for the majority of the studied population with a classification F1-score of 0.873 and detecting 90% of the seizures.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-1016_j-artmed-2021-102084.pdf` (located in [`../pdfs/`](../pdfs/)).

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
