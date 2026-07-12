# Dynamic learning framework for epileptic seizure prediction using sparsity based EEG Reconstruction with Optimized CNN classifier

| Field | Value |
|-------|-------|
| ID | 49 |
| DOI | [`10.1016/j.eswa.2020.114533`](https://doi.org/10.1016/j.eswa.2020.114533) |
| Journal | Expert Systems with Applications |
| CAS Quartile | Q2 |
| Year | 2021 |
| Authors | Priya Prathaban Banu; Balasubramanian Ramachandran |
| Abstract source | semantic_scholar |

## Abstract

Abstract The World Health Organization (WHO) recently stated that epilepsy affects nearly 65 million people of the world population. Early forecast of the oncoming seizures is of paramount importance in saving the life of epileptic patients. This paper demonstrates a phase transition-based seizure prediction approach from multi-channel scalp electroencephalogram (EEG) recordings. The primary focus of this work is to discriminate the seizure and seizure-free EEG signals by learning the dynamics of preictal, interictal and ictal period. We propose an adaptive optimization approach using non-linear conjugate gradient technique in conjunction with Sparsity based EEG Reconstruction (SER) and three-dimensional Optimized Convolutional Neural Network (3D OCNN) classifier, based on Fletcher Reeves (FR) algorithm. Sparsity based artifact removal approach along with a 3D OCNN classifier, classifies the various states of seizures. FR algorithm is deployed with the deep neural network architecture to accelerate the convergence rate and to reduce the complexity of the proposed non-linear model. The Principle Component Analysis (PCA) algorithm replacing the Singular Value Decomposition (SVD) in the K-SVD algorithm, further reduces the time and complexity of the pre-processing stage. We further propose a Phase Transition based Kullback-Leibler divergence (PTB-KL) predictor for obtaining the Optimal Seizure Prediction Horizon (OSPH). The proposed model is evaluated using three diverse databases such as CHB-MIT, NINC and SRM respectively. Empirical results on the three EEG databases of 300 recordings outperforms the state-of-art approaches with an accuracy score of 0.98, sensitivity score of 0.99 and False Prediction Rate (FPR) of 0.07 FP/h. Statistical assessment of the proposed predictor gains an OSPH of about 1.1 h prior to the seizure onset. Experimental results prove that the phase transition-based seizure prediction approach is a promising one for accurate real-time prediction of epilepsy using scalp EEG data.

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
