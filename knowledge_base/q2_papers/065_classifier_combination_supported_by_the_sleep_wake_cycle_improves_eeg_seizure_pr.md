# Classifier Combination Supported by the Sleep-Wake Cycle Improves EEG Seizure Prediction Performance

| Field | Value |
|-------|-------|
| ID | 65 |
| DOI | [`10.1109/tbme.2024.3368304`](https://doi.org/10.1109/tbme.2024.3368304) |
| Journal | IEEE Transactions on Biomedical Engineering |
| CAS Quartile | Q2 |
| Year | 2024 |
| Authors | Oliveira Ana; Pinto Mauro F.; Lopes Fábio; Leal Adriana; Teixeira César A. |
| Abstract source | semantic_scholar |

## Abstract

Objective: Seizure prediction is a promising solution to improve the quality of life for drug-resistant patients, which concerns nearly 30% of patients with epilepsy. The present study aimed to ascertain the impact of incorporating sleep-wake information in seizure prediction. Methods: We developed five patient-specific prediction approaches that use vigilance state information differently: i) using it as an input feature, ii) building a pool of two classifiers, each with different weights to sleep/wake training samples, iii) building a pool of two classifiers, each with only sleep/wake samples, iv) changing the alarm-threshold concerning each sleep/wake state, and v) adjusting the alarm-threshold after a sleep-wake transition. We compared these approaches with a control method that did not integrate sleep-wake information. Our models were tested with data (43 seizures and 482 hours) acquired during presurgical monitoring of 17 patients from the EPILEPSIAE database. As EPILEPSIAE does not contain vigilance state annotations, we developed a sleep-wake classifier using 33 patients diagnosed with nocturnal frontal lobe epilepsy from the CAP Sleep database. Results: Although different patients may require different strategies, our best approach, the pool of weighted predictors, obtained 65% of patients performing above chance level with a surrogate analysis (against 41% in the control method). Conclusion: The inclusion of vigilance state information improves seizure prediction. Higher results and testing with long-term recordings from daily-life conditions are necessary to ensure clinical acceptance. Significance: As automated sleep-wake detection is possible, it would be feasible to incorporate these algorithms into future devices for seizure prediction.

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
