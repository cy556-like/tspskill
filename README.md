# tspskill — Academic Chinese-to-English Translation Skill

**T**ranslate **S**cholarly **P**apers — a specialized translation skill for converting Chinese academic manuscripts (especially in epilepsy and deep learning research) into publication-ready English suitable for SCI-indexed journal submission.

## What this skill does

- Translates Chinese research papers, abstracts, methods sections, results, and conclusions into academic English.
- Preserves technical terminology in **epilepsy** and **deep learning** with strict consistency.
- Aligns phrasing with conventions of Q1/Q2 SCI journals (CAS Zone 1/2).
- Anchors terminology and academic register to a curated knowledge base of **73 real papers** (22 Q1 + 51 Q2) from the epilepsy + deep learning literature.

## Knowledge base coverage

| Quartile | Count | Sample journals |
|----------|-------|-----------------|
| Q1 (CAS Zone 1) | 22 | Nature Communications, Brain, Epilepsia, Lancet Neurology, JAMA Neurology, Nature Machine Intelligence, npj Digital Medicine, Nature Biomedical Engineering, Patterns |
| Q2 (CAS Zone 2) | 51 | Computers in Biology and Medicine, Biomedical Signal Processing and Control, Journal of Neuroscience Methods, IEEE TBME, IEEE JBHI, Clinical Neurophysiology, Seizure, Epilepsy & Behavior, Frontiers in Neuroscience, Sensors, Neurocomputing, Expert Systems with Applications |
| **Total** | **73** | |

### Topics covered

- Seizure detection (scalp EEG, intracranial EEG, sEEG)
- Seizure prediction and forecasting
- Seizure onset zone localization
- Epilepsy type classification (focal, generalized, absence, etc.)
- Interictal epileptiform discharge detection
- Neonatal seizure detection
- ICU continuous EEG monitoring
- Postoperative seizure outcome prediction
- Multimodal EEG-MRI fusion
- Wearable and edge-AI seizure detection

### Deep learning architectures covered

- CNN (1D-CNN, ResNet)
- RNN (LSTM, BiLSTM, GRU)
- Transformer and attention models
- Graph neural networks (GCN, GAT)
- Generative models (GAN, VAE, diffusion)
- Self-supervised / contrastive learning
- Foundation models for EEG
- Federated learning

## Repository structure

```
tspskill/
├── SKILL.md                              # Main skill file (trigger + workflow)
├── README.md                             # This file
├── knowledge_base/
│   ├── INDEX.md                          # KB summary
│   ├── q1_papers/
│   │   ├── INDEX.md                      # Q1 paper index
│   │   └── 001_*.md ... 022_*.md         # 22 Q1 paper files
│   └── q2_papers/
│       ├── INDEX.md                      # Q2 paper index
│       └── 001_*.md ... 051_*.md         # 51 Q2 paper files
├── templates/
│   ├── glossary.md                       # Bilingual glossary (epilepsy + DL)
│   ├── academic_phrases.md               # Reusable sentence patterns
│   └── translation_template.md           # Section-by-section template
└── examples/
    └── sample_translation.md             # Worked example
```

## How to use

1. **Trigger the skill** by asking the assistant to translate a Chinese academic passage (mention "论文翻译", "学术翻译", "中译英", "SCI 翻译", or "translate to academic English").
2. **Provide the source text** — a paragraph, a section, or a full abstract.
3. **Optionally specify** the target journal or section type (abstract / methods / results / discussion).
4. The skill will:
   - Identify section type and source register
   - Look up relevant knowledge base papers for terminology
   - Draft a publication-ready English translation
   - Provide translator notes for any ambiguous decisions
   - Offer alternative renderings where multiple options are valid

## Quality standards enforced

- ✅ All epilepsy terminology follows ILAE 2010/2017 classification
- ✅ All deep learning terminology follows standard conventions
- ✅ Quantitative content (numbers, units, statistics) preserved verbatim
- ✅ Sentence length ≤ 25 words on average
- ✅ No informal phrasing
- ✅ Hedging applied to claims in discussion
- ✅ Articles (a/an/the) added where Chinese omits them
- ✅ Tense and voice consistent within each section

## Source of knowledge base papers

- A subset of entries were obtained via automated web search across academic databases (ScienceDirect, IEEE Xplore, Nature, MDPI, Frontiers, Springer, Wiley, PLOS, Cell Press).
- A subset were curated from widely-cited publications in the epilepsy + deep learning field.
- Each paper file records its source ("web_search" or "curated").
- Quartile classification is based on commonly known CAS journal rankings; users should verify specific entries against the latest CAS classification list before relying on them for grant or evaluation purposes.

## License

MIT License — see LICENSE file.

## Contributing

Pull requests welcome. To add a paper to the knowledge base:
1. Create a new Markdown file under `knowledge_base/q1_papers/` or `knowledge_base/q2_papers/` following the existing format.
2. Update the corresponding `INDEX.md`.
3. Verify the journal's CAS quartile in the latest classification.

## Citation

If this skill contributes to your work, please cite the repository:

```
tspskill: Academic Chinese-to-English translation skill for epilepsy and
deep learning research. GitHub repository, 2024.
```
