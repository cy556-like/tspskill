# Translation Template — Section-by-Section

This template provides a structural skeleton for translating a complete
academic paper from Chinese to English. Translators should fill in the
content while following the conventions described in `SKILL.md` and
using terminology from `glossary.md`.

## Front matter

```
Title: <English title — concise, ≤20 words, no "A study on...">

Authors: <as provided in source>

Affiliations: <as provided in source>

Corresponding author: <name, email>

Word count: <count>

Number of figures: <count>

Number of tables: <count>

Conflict of interest: <as declared>

Funding: <as declared>

Acknowledgments: <as declared>
```

## Abstract (200-300 words)

```
Background: <2-3 sentences establishing the clinical/scientific problem
and the gap the study addresses.>

Methods: <3-4 sentences describing the dataset, model architecture,
training procedure, and evaluation protocol.>

Results: <3-4 sentences reporting the primary quantitative findings,
with specific metrics (sensitivity, specificity, AUC, etc.).>

Conclusions: <1-2 sentences stating the study's contribution and
its implications.>

Keywords: epilepsy; deep learning; <3-5 specific keywords separated
by semicolons, following MeSH terms where applicable>
```

## 1. Introduction (4-6 paragraphs)

```
Paragraph 1 — Background:
  Establish the clinical burden of epilepsy and the importance of the
  specific problem being addressed. Cite recent epidemiology.

Paragraph 2 — Existing approaches:
  Summarize the current state of the art, both classical and deep
  learning-based. Identify what has been achieved.

Paragraph 3 — Gap statement:
  Articulate the specific limitation or open question this study
  addresses. Be concrete; avoid generic "however, challenges remain".

Paragraph 4 — Contribution:
  State the contributions of the present study. Use a numbered list
  if there are multiple contributions.

Paragraph 5 (optional) — Paper organization:
  "The remainder of this paper is organized as follows. Section 2
  describes ... Section 3 presents ... Section 4 discusses ..."
  (Common in engineering-oriented journals; less common in clinical
  journals — check the target journal's convention.)
```

## 2. Methods (variable length, often 1500-3000 words)

### 2.1 Dataset
```
- Source and ethics (IRB approval, informed consent)
- Cohort description (n patients, demographics, epilepsy types,
  inclusion/exclusion criteria)
- Recording protocol (modality, channels, sampling rate, duration,
  reference)
- Annotation procedure (expert reviewers, consensus process)
```

### 2.2 Preprocessing
```
- Filtering (notch, band-pass; specify cutoffs and filter order)
- Re-referencing
- Artifact handling (automated, manual, or both)
- Segmentation (epoch length, overlap)
- Normalization
```

### 2.3 Feature representation (if applicable)
```
- Time-domain features
- Frequency-domain features (PSD, band power)
- Time-frequency features (STFT, wavelet, spectrogram)
- Spatial features (connectivity, graph)
```

### 2.4 Model architecture
```
- Input shape
- Layer-by-layer description (type, kernel size, number of filters,
  activation, normalization, pooling)
- Output layer and activation
- Total parameter count
```

### 2.5 Training
```
- Optimizer and hyperparameters
- Loss function
- Batch size, number of epochs
- Regularization (dropout, weight decay, data augmentation)
- Learning rate schedule
- Hardware specification
```

### 2.6 Evaluation protocol
```
- Cross-validation scheme (k-fold, LOSO, etc.)
- Train/validation/test split ratios
- Evaluation metrics
- Statistical testing for comparisons
```

## 3. Results

### 3.1 Cohort characteristics
- Demographic table
- Seizure-type distribution
- Recording duration statistics

### 3.2 Main results
- Primary metric (sensitivity, AUC, etc.) with confidence intervals
- Per-class performance
- Confusion matrix

### 3.3 Comparison with baselines
- Tabular comparison
- Statistical significance

### 3.4 Ablation studies
- Effect of each component

### 3.5 Generalization
- External cohort performance
- Cross-domain / cross-patient performance

## 4. Discussion (4-6 paragraphs)

```
Paragraph 1 — Summary of key findings:
  Restate the principal results with their quantitative magnitudes.

Paragraph 2 — Comparison with prior work:
  Position the findings within the existing literature. Use the
  knowledge base abstracts to anchor phrasing.

Paragraph 3 — Mechanistic interpretation:
  Explain WHY the method works (or doesn't). Reference attention
  maps, feature visualizations, or architectural properties.

Paragraph 4 — Clinical implications:
  Discuss how the findings translate (or fail to translate) to
  clinical practice. Be measured; hedge appropriately.

Paragraph 5 — Limitations:
  Enumerate limitations honestly. Common ones: single-center cohort,
  retrospective design, limited external validation, computational
  cost, interpretability concerns.

Paragraph 6 — Future work:
  Suggest concrete next steps. Avoid generic "more research is needed".
```

## 5. Conclusions (1 paragraph, 100-200 words)

```
- Restate the contribution (one sentence)
- State the principal finding (one sentence)
- State the implication (one sentence)
- Optionally: state the next step for validation
```

## 6. Figures and tables

For each figure:
- Caption is a complete sentence (or two) above or below the figure
- Panel labels: (A), (B), (C) — each panel must be described
- Statistical annotations: use standard notation (* p<0.05, ** p<0.01, *** p<0.001)

For each table:
- Title above the table, not a sentence but a noun phrase
- Footnotes below using lowercase letters as superscripts
- All abbreviations spelled out in footnote

## 7. References

- Preserve the citation style of the source (Vancouver, APA, etc.)
- Verify that all citations in the text appear in the reference list and vice versa
- For Chinese-language references, retain the original Chinese title in pinyin
  with an English translation in brackets, per journal guidelines

## Self-review checklist

Before submitting the translation, verify:

- [ ] All technical terms match the glossary
- [ ] All numbers, units, and statistical metrics are preserved exactly
- [ ] All citation markers [n] or (Author, year) preserved
- [ ] All figure/table cross-references work
- [ ] Sentence length ≤ 25 words on average
- [ ] No informal phrasing (see "Phrases to AVOID" in academic_phrases.md)
- [ ] Articles (a/an/the) added where Chinese omits them
- [ ] Tense consistent within each section
- [ ] Voice consistent (passive for methods, active for results preferred)
- [ ] Hedging applied to claims in discussion
- [ ] Translator notes appended for any ambiguous decisions
