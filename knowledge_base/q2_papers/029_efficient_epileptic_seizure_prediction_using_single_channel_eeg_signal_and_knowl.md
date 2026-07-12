# Efficient epileptic seizure prediction using single channel EEG signal and knowledge distillation on deep neural networks

| Field | Value |
|-------|-------|
| ID | 29 |
| DOI | [`10.1038/s41598-026-58793-4`](https://doi.org/10.1038/s41598-026-58793-4) |
| Journal | Scientific Reports |
| CAS Quartile | Q2 |
| Year | 2026 |
| Authors | Nyamoradi Hana; Fathi Abdolhossein |
| Abstract source | semantic_scholar |
| **Full-text PDF** | **Available: [`10-1038_s41598-026-58793-4.pdf`](../pdfs/10-1038_s41598-026-58793-4.pdf)** |

## Abstract

Epilepsy is a common neurological disease, and in some patients, abnormal changes in brain activity typically begin before the onset of a seizure. Electroencephalography (EEG) is a practical method for recording electrical activity of brain and plays a crucial role in the diagnosis of epilepsy. Previous studies relied on multi-channel EEG signals and large deep neural networks, which require powerful hardware and reduce user convenience. In this study, teacher-student based knowledge distillation technique on deep neural networks is employed to find the best single EEG electrode to improve user convenience and decrease the network complexity. The teacher model employes Mel-spectrograms of all EEG electrodes as input of 3D convolutional layer of neural network. Subsequently, using response-based knowledge distillation techniques the information from 22 input electrodes of teacher model is transferred to the student model utilized one electrode. The proposed teacher and student models were evaluated on the CHB-MIT dataset, which contains scalp EEG signals recorded using 22 electrodes in a bipolar montage from 24 patients. The experimental results enabled us to identify two electrodes with superior performance (electrode no. 20 achieved accuracy of 84.49%, sensitivity of 86.85%, specificity of 82.58%, and an F1-score of 83.58%, while electrode no. 22 reached accuracy of 84.30%, sensitivity of 86.45%, specificity of 82.93%, and an F1-score of 83.35%). Both electrodes demonstrated the capability to predict seizure onset 30 min prior to its occurrence and have superior performance in terms of accuracy, sensitivity, specificity, and F1-score.

## Full text

The complete peer-reviewed full text of this paper is available as a PDF in the
knowledge base: `10-1038_s41598-026-58793-4.pdf` (located in [`../pdfs/`](../pdfs/)).

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
