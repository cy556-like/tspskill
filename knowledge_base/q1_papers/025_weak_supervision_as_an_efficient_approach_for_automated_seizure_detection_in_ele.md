# Weak supervision as an efficient approach for automated seizure detection in electroencephalography

| Field | Value |
|-------|-------|
| ID | 25 |
| DOI | [`10.1038/s41746-020-0264-0`](https://doi.org/10.1038/s41746-020-0264-0) |
| Journal | npj Digital Medicine |
| CAS Quartile | Q1 |
| Year | 2020 |
| Authors | Saab Khaled; Dunnmon Jared; Ré Christopher; Rubin Daniel; Lee-Messer Christopher |
| Abstract source | crossref |

## Abstract

Abstract Automated seizure detection from electroencephalography (EEG) would improve the quality of patient care while reducing medical costs, but achieving reliably high performance across patients has proven difficult. Convolutional Neural Networks (CNNs) show promise in addressing this problem, but they are limited by a lack of large labeled training datasets. We propose using imperfect but plentiful archived annotations to train CNNs for automated, real-time EEG seizure detection across patients. While these weak annotations indicate possible seizures with precision scores as low as 0.37, they are commonly produced in large volumes within existing clinical workflows by a mixed group of technicians, fellows, students, and board-certified epileptologists. We find that CNNs trained using such weak annotations achieve Area Under the Receiver Operating Characteristic curve (AUROC) values of 0.93 and 0.94 for pediatric and adult seizure onset detection, respectively. Compared to currently deployed clinical software, our model provides a 31% increase (18 points) in F1-score for pediatric patients and a 17% increase (11 points) for adult patients. These results demonstrate that weak annotations, which are sustainably collected via existing clinical workflows, can be leveraged to produce clinically useful seizure detection models.

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
