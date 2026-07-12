# Automated spectrographic seizure detection using convolutional neural networks

| Field | Value |
|-------|-------|
| ID | 91 |
| DOI | [`10.1016/j.seizure.2019.07.009`](https://doi.org/10.1016/j.seizure.2019.07.009) |
| Journal | Seizure |
| CAS Quartile | Q2 |
| Year | 2019 |
| Authors | Yan Peter Z.; Wang Fei; Kwok Nathaniel; Allen Baxter B.; Keros Sotirios; Grinspan Zachary |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Not available (paywall)** |

## Abstract

PURPOSE
Non-convulsive seizures are common in critically ill patients, and delays in diagnosis contribute to increased morbidity and mortality. Many intensive care units employ continuous EEG (cEEG) for seizure monitoring. Although cEEG is continuously recorded, it is often reviewed intermittently, which may delay seizure diagnosis and treatment. This may be mitigated with automated seizure detection. In this study, we develop and evaluate convolutional neural networks (CNN) to automate seizure detection on EEG spectrograms.


METHODS
Adult EEGs (12 patients, 12 EEGs, 33 seizures) from New-York Presbyterian Hospital (NYP) and pediatric EEGs (22 patients, 130 EEGs, 177 seizures) from Children's Hospital Boston (CHB) were converted into spectrograms. To simulate a telemetry display, seizure and non-seizure events on spectrograms were sequentially sampled as images across a detection window (26,380 total images). Four CNN models of increasing complexity (number of layers) were trained, cross-validated, and tested on CHB and NYP spectrographic images. All CNNs were based on the VGG-net architecture, with adjustments to alleviate overfitting.


RESULTS
For spectrographically visible seizures, two CNN models (containing 4 and 7 convolution layers) achieved >90% seizure detection sensitivity and specificity on the CHB test set and >90% sensitivity and 75-80% specificity on the NYP test set. The one CNN model (10 convolution layers) did not converge during training; while another CNN (2 convolution layers) performed poorly (60% sensitivity and 32% specificity) on the NYP test set.


CONCLUSIONS
Seizure detection on EEG spectrograms with CNN models is feasible with sensitivity and specificity potentially suitable for clinical use.

## Full text

The full text of this paper is **not available in the knowledge base** because it is
published in a subscription-based journal and no open-access version could be
located via Unpaywall, PubMed Central, Europe PMC, or arXiv.

To access the full text:
1. Visit the publisher's page: https://doi.org/10.1016/j.seizure.2019.07.009
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
