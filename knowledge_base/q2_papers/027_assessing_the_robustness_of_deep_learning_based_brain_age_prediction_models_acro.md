# Assessing the Robustness of Deep Learning Based Brain Age Prediction Models Across Multiple EEG Datasets

| Field | Value |
|-------|-------|
| ID | 27 |
| DOI | [`10.1109/tbme.2025.3639477`](https://doi.org/10.1109/tbme.2025.3639477) |
| Journal | IEEE Transactions on Biomedical Engineering |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Tveitstøl Thomas; Tveter Mats; Hatlestad-Hall Christoffer; Hammer Hugo L.; Engemann Denis A.; Haraldsen Ira R.J. Hebold |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Available: [`10-1109_tbme-2025-3639477.pdf`](../pdfs/10-1109_tbme-2025-3639477.pdf)** |

## Abstract

The increasing availability of large electroencephalography (EEG) datasets enhances the potential clinical utility of deep learning (DL) for cognitive and pathological decoding. However, dataset shifts due to variations in the population and acquisition hardware can considerably degrade the model performance. We systematically investigated the generalisation of DL models to unseen datasets with different characteristics, using age as the target variable. Five datasets were used in two different experimental setups, including (1) leave-one-dataset-out (LODO) and (2) leave-one-dataset-in (LODI) cross validation. A comprehensive set of 1805 different hyperparameter configurations was tested, including variations in the DL architectures and data pre-processing. The performance varied across source/target dataset pair. Using LODO, we obtained Pearson’s r values of {0.63, 0.84, 0.75, 0.23, 0.10} and R2 values of {-0.01, 0.63, 0.41, −4.66, −70.98}. For LODI, the results varied in Pearson’s r from −0.11 to 0.84 and R2 values from −704.89 to 0.65, depending on the source and target dataset. Adjusting the model intercepts using the average age of the target dataset substantially improved some R2 scores. Our results show that DL models can learn age-related EEG patterns which generalise with strong correlations to datasets with broad age spans. The most important hyperparameter was to use the frequency range between 1 and 45Hz, rather than a single frequency band. The second most important hyperparameter effect depended on the experimental setup. Our findings highlight the challenges of dataset shifts in EEG-based DL models and establish a benchmark for future studies aiming to improve the robustness of DL models across diverse datasets.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-1109_tbme-2025-3639477.pdf` (located in [`../pdfs/`](../pdfs/)).

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
