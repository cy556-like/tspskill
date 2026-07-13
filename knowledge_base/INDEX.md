# Knowledge Base Index

This directory contains the curated knowledge base for the **tspskill** translation skill.

## What's included

| Type | Count | Source |
|------|-------|--------|
| Papers with **full-text PDF** | 22 | Downloaded from open-access sources via Unpaywall API |
| Papers with abstract only | 69 | Paywalled — abstract retrieved from CrossRef / Semantic Scholar |
| **Total papers** | **91** | — |

## Source

Every paper in this knowledge base is a **real, retrievable publication**:

- **DOIs, titles, journal names, authors, years**: retrieved from the **CrossRef API**
  (`https://api.crossref.org`) using journal ISSN filtering.
- **Abstracts**: retrieved from CrossRef where deposited by the publisher; otherwise
  fetched from the **Semantic Scholar API** (`https://api.semanticscholar.org`).
- **Full-text PDFs** (where available): downloaded from open-access sources
  identified via the **Unpaywall API** (`https://api.unpaywall.org`). Each PDF
  was verified by extracting its text and confirming the title keywords and
  author surnames appear.

**No paper in this knowledge base is fabricated.** Every DOI resolves to a real
publication at `https://doi.org/<DOI>`.

## Summary by quartile

| Quartile | Total | With PDF full text | Directory |
|----------|-------|--------------------|-----------|
| Q1 (CAS Zone 1) | 26 | 9 | [`q1_papers/`](q1_papers/INDEX.md) |
| Q2 (CAS Zone 2) | 65 | 13 | [`q2_papers/`](q2_papers/INDEX.md) |
| **Total** | **91** | **22** | — |

## Directory structure

```
knowledge_base/
├── INDEX.md                  # This file
├── pdfs/                     # 22 verified full-text PDFs
│   ├── 10-1038_s41467-..._.pdf
│   ├── 10-3389_fnins-..._.pdf
│   └── ...
├── q1_papers/                # 26 Q1 paper metadata files + INDEX.md
│   ├── INDEX.md
│   ├── 001_*.md
│   └── ...
└── q2_papers/                # 65 Q2 paper metadata files + INDEX.md
    ├── INDEX.md
    ├── 001_*.md
    └── ...
```

## Journal coverage

- Computers in Biology and Medicine (11 papers, 0 with PDF)
- Epilepsia (8 papers, 1 with PDF)
- IEEE Transactions on Biomedical Engineering (6 papers, 1 with PDF)
- Brain (5 papers, 1 with PDF)
- Nature Communications (5 papers, 5 with PDF)
- Frontiers in Neuroscience (5 papers, 5 with PDF)
- Seizure: European Journal of Epilepsy (5 papers, 0 with PDF)
- Journal of Neuroscience Methods (5 papers, 0 with PDF)
- Scientific Reports (4 papers, 4 with PDF)
- IEEE Journal of Biomedical and Health Informatics (4 papers, 2 with PDF)
- Sensors (4 papers, 0 with PDF)
- JAMA Neurology (3 papers, 0 with PDF)
- Artificial Intelligence in Medicine (3 papers, 1 with PDF)
- Epilepsy & Behavior (3 papers, 0 with PDF)
- Neural Networks (3 papers, 0 with PDF)
- IEEE Access (3 papers, 0 with PDF)
- Diagnostics (3 papers, 0 with PDF)
- npj Digital Medicine (2 papers, 2 with PDF)
- Annals of Neurology (2 papers, 0 with PDF)
- Clinical Neurophysiology (2 papers, 0 with PDF)
- STAR Protocols (1 papers, 0 with PDF)
- Neurocomputing (1 papers, 0 with PDF)
- Expert Systems with Applications (1 papers, 0 with PDF)
- Knowledge-Based Systems (1 papers, 0 with PDF)
- Seizure (1 papers, 0 with PDF)

## Why only 22 PDFs out of 91?

The remaining 69 papers are published in subscription-based
journals (Elsevier ScienceDirect, Wiley Online Library, IEEE Xplore paywall, etc.).
Their full texts are protected by publisher copyright and cannot be legally
redistributed. We attempted to find open-access versions via:

1. **Unpaywall API** — checks publisher OA, hybrid OA, green OA (institutional repositories), bronze OA
2. **EuropePMC** — checks PubMed Central open-access subset
3. **Semantic Scholar openAccessPdf** — checks S2's verified OA PDF links
4. **Publisher direct PDF URLs** — for known OA publishers (Nature, Frontiers, MDPI, PLOS)

For 69 papers, none of these sources had a legally downloadable
full-text version. The metadata and abstract are still included because they are
sufficient for terminology anchoring and phrasing reference during translation.

If you have institutional access to a paywalled paper, you can manually add its
PDF to the `pdfs/` folder using the naming convention `<doi-with-slashes-and-dots-replaced>.pdf`
and update the corresponding metadata file to reflect that the PDF is now available.

## Topics covered

- Epileptic seizure detection (scalp EEG, intracranial EEG, stereo-EEG)
- Seizure prediction and forecasting
- Seizure onset zone localization
- Epilepsy type classification (focal, generalized, absence, etc.)
- Interictal epileptiform discharge detection
- ICU continuous EEG monitoring
- Postoperative seizure outcome prediction
- Multimodal EEG-MRI fusion for epilepsy
- Wearable and edge-AI seizure detection
- Antiseizure medication response prediction
- Post-stroke epilepsy prediction
- Epilepsy biotype identification via machine learning
- Brain age prediction and classification

## Deep learning architectures covered

- Convolutional Neural Networks (CNN, 1D-CNN, ResNet, depthwise separable)
- Recurrent Neural Networks (LSTM, BiLSTM, GRU)
- Transformer and attention-based models (ViT, Informer, DistilCLIP-EEG)
- Graph Neural Networks (GCN, GAT, geometric deep learning)
- Generative models (GAN, VAE, diffusion)
- Self-supervised / contrastive / continual learning
- Foundation models for EEG
- Federated learning for multicentre data
- Domain adaptation and transfer learning
- Multi-view and multi-modal fusion
- Biomimetic deep learning networks

## How translators should use this knowledge base

1. **Domain terminology**: cross-check epilepsy and deep learning terms against the
   abstracts and PDFs to ensure standard English usage.
2. **Academic phrasing**: study sentence structures in the abstracts and full texts
   to absorb conventional academic English patterns.
3. **Methodology description**: refer to papers using similar methods to render
   method descriptions accurately. The full-text PDFs are especially valuable here.
4. **Result reporting**: use the papers' phrasing of sensitivity, specificity,
   AUC, etc., as templates for translating result statements.
5. **Citation audit**: if your source text cites a paper, verify the citation
   against the DOI / authors / year recorded here.
