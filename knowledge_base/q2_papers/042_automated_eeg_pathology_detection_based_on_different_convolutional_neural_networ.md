# Automated EEG pathology detection based on different convolutional neural network models: Deep learning approach

| Field | Value |
|-------|-------|
| ID | 42 |
| DOI | [`10.1016/j.compbiomed.2021.104434`](https://doi.org/10.1016/j.compbiomed.2021.104434) |
| Journal | Computers in Biology and Medicine |
| CAS Quartile | Q2 |
| Year | 2021 |
| Authors | Bajpai Rishabh; Yuvaraj Rajamanickam; Prince A. Amalin |
| Abstract source | semantic_scholar |

## Abstract

The brain electrical activity, recorded and materialized as electroencephalogram (EEG) signals, is known to be very useful in the diagnosis of brain-related pathology. However, manual examination of these EEG signals has various limitations, including time-consuming inspections, the need for highly trained neurologists, and the subjectiveness of the evaluation. Thus, an automated EEG pathology detection system would be helpful to assist neurologists to enhance the treatment procedure by making a quicker diagnosis and reducing error due to the human element. This work proposes the application of a time-frequency spectrum to convert the EEG signals onto the image domain. The spectrum images are then applied to the Convolutional Neural Network (CNN) to learn robust features that can aid the automatic detection of pathology and normal EEG signals. Three popular CNN in the form of the DenseNet, Inception-ResNet v2, and SeizureNet were employed. The extracted deep-learned features from the spectrum images are then passed onto the support vector machine (SVM) classifier. The effectiveness of the proposed approach was assessed using the publicly available Temple University Hospital (TUH) abnormal EEG corpus dataset, which is demographically balanced. The proposed SeizureNet-SVM-based system achieved state-of-the-art performance: accuracy, sensitivity, and specificity of 96.65%, 90.48%, and 100%, respectively. The results show that the proposed framework may serve as a diagnostic tool to assist clinicians in the detection of EEG pathology for early treatment.

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
