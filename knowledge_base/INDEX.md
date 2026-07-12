# Knowledge Base Index

This directory contains the curated knowledge base for the **tspskill** translation skill.

## Source

Every paper in this knowledge base is a **real, retrievable publication**:

- **DOIs, titles, journal names, authors, years**: retrieved from the **CrossRef API**
  (`https://api.crossref.org`) using journal ISSN filtering.
- **Abstracts**: retrieved from CrossRef where deposited by the publisher; otherwise
  fetched from the **Semantic Scholar API** (`https://api.semanticscholar.org`).
- Each paper file records its `abstract_source` (crossref or semantic_scholar).

No paper in this knowledge base is fabricated. Every DOI resolves to a real publication
at `https://doi.org/<DOI>`.

## Summary

| Quartile | Count | Directory |
|----------|-------|-----------|
| Q1 (CAS Zone 1) | 26 | [`q1_papers/`](q1_papers/INDEX.md) |
| Q2 (CAS Zone 2) | 65 | [`q2_papers/`](q2_papers/INDEX.md) |
| **Total** | **91** | |

## Journal coverage

- Computers in Biology and Medicine (11 papers)
- Epilepsia (8 papers)
- IEEE Transactions on Biomedical Engineering (6 papers)
- Brain (5 papers)
- Nature Communications (5 papers)
- Frontiers in Neuroscience (5 papers)
- Journal of Neuroscience Methods (5 papers)
- Seizure: European Journal of Epilepsy (5 papers)
- IEEE Journal of Biomedical and Health Informatics (4 papers)
- Scientific Reports (4 papers)
- Sensors (4 papers)
- JAMA Neurology (3 papers)
- Artificial Intelligence in Medicine (3 papers)
- Diagnostics (3 papers)
- Epilepsy & Behavior (3 papers)
- IEEE Access (3 papers)
- Neural Networks (3 papers)
- Annals of Neurology (2 papers)
- npj Digital Medicine (2 papers)
- Clinical Neurophysiology (2 papers)
- STAR Protocols (1 papers)
- Expert Systems with Applications (1 papers)
- Knowledge-Based Systems (1 papers)
- Neurocomputing (1 papers)
- Seizure (1 papers)

## Topics covered

- Epileptic seizure detection (scalp EEG, intracranial EEG, stereo-EEG)
- Seizure prediction and forecasting
- Seizure onset zone localization
- Epilepsy type classification (focal, generalized, absence, etc.)
- Interictal epileptiform discharge detection
- Neonatal seizure detection
- ICU continuous EEG monitoring
- Postoperative seizure outcome prediction
- Multimodal EEG-MRI fusion for epilepsy
- Wearable and edge-AI seizure detection
- Antiseizure medication response prediction
- Epilepsy imaging (MRI, fMRI, PET)

## Deep learning architectures covered

- Convolutional Neural Networks (CNN, 1D-CNN, ResNet)
- Recurrent Neural Networks (LSTM, BiLSTM, GRU)
- Transformer and attention-based models (ViT, Informer)
- Graph Neural Networks (GCN, GAT, geometric deep learning)
- Generative models (GAN, VAE, diffusion)
- Self-supervised / contrastive / continual learning
- Foundation models for EEG
- Federated learning for multicentre data
- Domain adaptation and transfer learning

## How translators should use this knowledge base

1. **Domain terminology**: cross-check epilepsy and deep learning terms against the
   abstracts to ensure standard English usage.
2. **Academic phrasing**: study sentence structures in the abstracts to absorb
   conventional academic English patterns.
3. **Methodology description**: refer to papers using similar methods to render
   method descriptions accurately.
4. **Result reporting**: use the abstracts' phrasing of sensitivity, specificity,
   AUC, etc., as templates for translating result statements.
5. **Citation audit**: if your source text cites a paper, verify the citation
   against the DOI / authors / year recorded here.
