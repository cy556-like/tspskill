# Development and validation of machine learning models for prediction of seizure outcome after pediatric epilepsy surgery

| Field | Value |
|-------|-------|
| ID | 13 |
| DOI | [`10.1111/epi.17320`](https://doi.org/10.1111/epi.17320) |
| Journal | Epilepsia |
| CAS Quartile | Q1 |
| Year | 2022 |
| Authors | Yossofzai Omar; Fallah Aria; Maniquis Cassia; Wang Shelly; Ragheb John; Weil Alexander G.; Brunette‐Clement Tristan; Andrade Andrea; Ibrahim George M.; Mitsakakis Nicholas |
| Abstract source | crossref |

## Abstract

Abstract Objective There is substantial variability in reported seizure outcome following pediatric epilepsy surgery, and lack of individualized predictive tools that could evaluate the probability of seizure freedom postsurgery. The aim of this study was to develop and validate a supervised machine learning (ML) model for predicting seizure freedom after pediatric epilepsy surgery. Methods This is a multicenter retrospective study of children who underwent epilepsy surgery at five pediatric epilepsy centers in North America. Clinical information, diagnostic investigations, and surgical characteristics were collected, and used as features to predict seizure‐free outcome 1 year after surgery. The dataset was split randomly into 80% training and 20% testing data. Thirty‐five combinations of five feature sets with seven ML classifiers were assessed on the training cohort using 10‐fold cross‐validation for model development. The performance of the optimal combination of ML classifier and feature set was evaluated in the testing cohort, and compared with logistic regression, a classical statistical approach. Results Of the 801 patients included, 61.3% were seizure‐free 1 year postsurgery. During model development, the best combination was XGBoost ML algorithm with five features from the univariate feature set, including number of antiseizure medications, magnetic resonance imaging lesion, age at seizure onset, video‐electroencephalography concordance, and surgery type, with a mean area under the curve (AUC) of .73 (95% confidence interval [CI] = .69–.77). The combination of XGBoost and univariate feature set was then evaluated on the testing cohort and achieved an AUC of .74 (95% CI = .66–.82; sensitivity = .87, 95% CI = .81–.94; specificity = .58, 95% CI = .47–.71). The XGBoost model outperformed the logistic regression model (AUC = .72, 95% CI = .63–.80; sensitivity = .72, 95% CI = .63–.82; specificity = .66, 95% CI = .53–.77) in the testing cohort ( p = .005). Significance This study identified important features and validated an ML algorithm, XGBoost, for predicting the probability of seizure freedom after pediatric epilepsy surgery. Improved prognostication of epilepsy surgery is critical for presurgical counseling and will inform treatment decisions.

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
