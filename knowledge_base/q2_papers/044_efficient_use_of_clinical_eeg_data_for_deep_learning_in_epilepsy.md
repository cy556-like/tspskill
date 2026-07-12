# Efficient use of clinical EEG data for deep learning in epilepsy

| Field | Value |
|-------|-------|
| ID | 44 |
| DOI | [`10.1016/j.clinph.2021.01.035`](https://doi.org/10.1016/j.clinph.2021.01.035) |
| Journal | Clinical Neurophysiology |
| CAS Quartile | Q2 |
| Year | 2021 |
| Authors | da Silva Lourenço Catarina; Tjepkema-Cloostermans Marleen C.; van Putten Michel J.A.M. |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Available: [`10-1016_j-clinph-2021-01-035.pdf`](../pdfs/10-1016_j-clinph-2021-01-035.pdf)** |

## Abstract

OBJECTIVE
Automating detection of Interictal Epileptiform Discharges (IEDs) in electroencephalogram (EEG) recordings can reduce the time spent on visual analysis for the diagnosis of epilepsy. Deep learning has shown potential for this purpose, but the scarceness of expert annotated data creates a bottleneck in the process.


METHODS
We used EEGs from 50 patients with focal epilepsy, 49 patients with generalized epilepsy (IEDs were visually labeled by experts) and 67 controls. The data was filtered, downsampled and cut into two second epochs. We increased the number of input samples containing IEDs through temporal shifting and using different montages. A VGG C convolutional neural network was trained to detect IEDs.


RESULTS
Using the dataset with more samples, we reduced the false positive rate from 2.11 to 0.73 detections per minute at the intersection of sensitivity and specificity. Sensitivity increased from 63% to 96% at 99% specificity. The model became less sensitive to the position of the IED in the epoch and montage.


CONCLUSIONS
Temporal shifting and use of different EEG montages improves performance of deep neural networks in IED detection.


SIGNIFICANCE
Dataset augmentation can reduce the need for expert annotation, facilitating the training of neural networks, potentially leading to a fundamental shift in EEG analysis.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-1016_j-clinph-2021-01-035.pdf` (located in [`../pdfs/`](../pdfs/)).

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
