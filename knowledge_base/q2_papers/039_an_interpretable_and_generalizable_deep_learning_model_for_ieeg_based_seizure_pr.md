# An interpretable and generalizable deep learning model for iEEG-based seizure prediction using prototype learning and contrastive learning

| Field | Value |
|-------|-------|
| ID | 39 |
| DOI | [`10.1016/j.compbiomed.2024.109257`](https://doi.org/10.1016/j.compbiomed.2024.109257) |
| Journal | Computers in Biology and Medicine |
| CAS Quartile | Q2 |
| Year | 2024 |
| Authors | Gao Yikai; Liu Aiping; Cui Heng; Qian Ruobing; Chen Xun |
| Abstract source | semantic_scholar |

## Abstract

Epileptic seizure prediction plays a crucial role in enhancing the quality of life for individuals with epilepsy. Over recent years, a multitude of deep learning-based approaches have emerged to tackle this challenging task, leading to significant advancements. However, the 'black-box' nature of deep learning models and the considerable interpatient variability significantly impede their interpretability and generalization, thereby severely hampering their efficacy in real-world clinical applications. To address these issues, our study aims to establish an interpretable and generalizable seizure prediction model that meets the demands of clinical diagnosis. Our method extends self-interpretable prototype learning networks into a novel domain adaptation framework designed specifically for cross-patient seizure prediction. The proposed framework enables patient-level interpretability by tracing the origins of significant prototypes. For instance, it could provide information about the seizure type of the patient to which the prototype belongs. This surpasses the existing sample-level interpretability, which is limited to individual patient samples. To further improve the model's generalization capability, we introduce a contrastive semantic alignment loss constraint to the embedding space, enhancing the robustness of the learned prototypes. We evaluate our proposed model using the Freiburg intracranial electroencephalography (iEEG) dataset, which consists of 20 patients and a total of 82 seizures. The experimental results demonstrated a high sensitivity of 79.0%, a low false prediction rate of 0.183, and a high area under the receiver operating characteristic curve (AUC) value of 0.804, achieving state-of-the-art performance with self-interpretable evidence in contrast to the current cross-patient seizure prediction methods. Our study represents a significant step forward in developing an interpretable and generalizable model for seizure prediction, thereby facilitating the application of deep learning models in clinical diagnosis.

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
