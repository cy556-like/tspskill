# Development of a deep learning tool to detect drug-resistance epilepsy with EEG

| Field | Value |
|-------|-------|
| ID | 46 |
| DOI | [`10.1016/j.yebeh.2026.111028`](https://doi.org/10.1016/j.yebeh.2026.111028) |
| Journal | Epilepsy & Behavior |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Alanís-Bernal Manuel; Vélez-Rodríguez José Ramón; Campos-Fernández Daniel; Quintana Manuel; Abraira Laura; Fonseca Elena; López-Maza Samuel; Lallana Sofia; Garcés-Pellejero María; Bellido-Castillo Enric |
| Abstract source | semantic_scholar |

## Abstract

INTRODUCTION
Drug-resistant epilepsy affects about 30% of patients and is linked to poorer outcomes. Deep learning can extract complex patterns from EEG data and shows promise for identification of drug resistance (DRE). This study aimed to develop a convolutional neural network (CNN) to classify patients with epilepsy as drug-resistant or non-drug-resistant using surface EEG.


MATERIAL AND METHODS
We conducted a retrospective single-center study including patients with epilepsy recorded between 2020/01-2024/12. Each patient contributed one wake EEG (10-20; ≥30 min), preprocessed and labeled as drug-resistant or non-drug-resistant according to ILAE criteria. Patients with prior epilepsy surgery, progressive etiologies, or developmental and epileptic encephalopathies were excluded. Multiple CNN models were developed by an analyst blinded to all clinical data, using only the EEG images and their corresponding drug-resistance labels for training. Data were split into training-validation (80%) and independent test (20%) sets; tenfold cross-validation with bootstrap resampling optimized performance and avoid overfitting. The final model was evaluated on the test set for real-world applicability.


RESULTS
We included 180 patients (mean age 41.1 ± 17 years; 52.8% female), of whom 87 (48.3%) met DRE criteria. Median epilepsy onset was 19 years [IQR 10-35]. DRE patients had longer disease duration and more frequent focal epilepsy. The best model achieved 73.5% validation accuracy and, on the independent test set, 69.4% accuracy (sensitivity 68.4%, specificity 70.6%, F1-score 0.70, AUC-ROC 0.70 and AUPRC 0.66).


CONCLUSION
A deep learning model using only surface EEG data showed moderate performance, which could improve by adding neuroimaging and clinical information from larger datasets.

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
