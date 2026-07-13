---
name: tspskill
description: >
  Translate Chinese academic manuscripts (especially in epilepsy and deep learning
  research) into publication-ready English. Use this skill whenever the user wants
  to translate Chinese research papers, academic abstracts, methods sections,
  results sections, or conclusions into English suitable for submission to
  SCI-indexed journals (Q1/Q2). The skill should also trigger when the user
  mentions "论文翻译", "学术翻译", "中译英", "翻译成英文论文", "SCI 翻译",
  or asks to polish Chinese research writing for international submission.
  The skill is bilingual-aware: it preserves technical terminology, follows
  standard academic English conventions, and aligns phrasing with
  epilepsy + deep learning literature norms.
---

# TSPSkill — Academic Chinese-to-English Translation Skill

`tspskill` (**T**ranslate **S**cholarly **P**apers) is a specialized translation
skill that converts Chinese academic manuscripts — primarily in the fields of
**epilepsy research** and **deep learning applied to EEG / neuroimaging** —
into publication-ready English suitable for submission to SCI-indexed
journals (CAS Zone 1 / Zone 2).

This skill is for **translators and researchers** who need consistent,
terminology-accurate, academically natural English output. It is **not**
a casual translation tool; it enforces academic register, preserves
quantitative precision, and references a curated knowledge base of 70+
real epilepsy + deep learning papers from Q1/Q2 journals to anchor
terminology and phrasing choices.

## When to trigger

Trigger this skill whenever the user:

- Asks to translate a Chinese paper / abstract / methods section / conclusion
  into English for journal submission.
- Mentions "论文翻译", "学术翻译", "中译英", "翻译成英文", "SCI 翻译",
  "英文润色", "翻译并润色".
- Asks to "translate and polish" a Chinese research passage.
- Provides a Chinese paragraph that contains epilepsy, EEG, deep learning,
  CNN, LSTM, transformer, seizure, neural network terminology AND asks for
  English output.
- Asks for help matching academic English style of epilepsy + DL papers.

Do **not** trigger for casual conversational translation, UI localization,
or non-academic content.

## Knowledge base

This skill bundles a curated knowledge base under `knowledge_base/`:

- `knowledge_base/q1_papers/` — **26 real papers** from CAS Zone 1 journals
  (Epilepsia, Brain, Nature Communications, Annals of Neurology, JAMA Neurology,
  The Lancet Neurology, npj Digital Medicine, etc.) — **9 with full-text PDF**
- `knowledge_base/q2_papers/` — **65 real papers** from CAS Zone 2 journals
  (Computers in Biology and Medicine, Biomedical Signal Processing and Control,
  Journal of Neuroscience Methods, IEEE TBME, IEEE JBHI, Clinical Neurophysiology,
  Seizure, Epilepsy & Behavior, Frontiers in Neuroscience, Sensors, Scientific Reports,
  Neural Networks, Artificial Intelligence in Medicine, etc.) — **13 with full-text PDF**
- `knowledge_base/pdfs/` — **22 verified full-text PDFs**, downloaded
  from open-access sources via Unpaywall API. Each PDF was verified by extracting
  its text with pypdf and confirming: (1) title keyword recall ≥ 0.7, (2) at least
  one author surname appears in the PDF text, (3) DOI appears in the PDF text
  (19/22 papers — the remaining 3 have DOI only on later pages not extracted).

**Total: 91 real papers** (22 with full-text PDF + 69 with abstract only due to paywall).
All 91 DOIs have been verified to exist in CrossRef. Each paper has: real DOI
(resolves at https://doi.org/<DOI>), publisher-deposited title, journal name,
authors, year, and a real abstract sourced from CrossRef or Semantic Scholar.

Each paper is stored as a Markdown file with: title, journal, CAS quartile, year, DOI,
authors, abstract, abstract_source, and a `Full-text PDF` field showing whether the
PDF is available (with a relative link to `../pdfs/<filename>.pdf`) or paywalled.
The two `INDEX.md` files list all entries with hyperlinks and a PDF availability column.

**Translators must consult the knowledge base** before translating
passages that mention specific methods (e.g. "1D-CNN", "transformer encoder",
"GCN over electrode adjacency graphs") or specific clinical concepts
(e.g. "癫痫发作起始区", "间期癫痫样放电", "药物难治性癫痫"). When a paper has
a full-text PDF, **open and read the relevant section** (Methods / Results / Discussion)
rather than relying on the abstract alone — the full text provides authoritative
terminology and phrasing for technical sections that abstracts cannot fully capture.

## Translation workflow

### Step 1 — Analyze the source

Before translating, identify:

1. **Section type**: title / abstract / introduction / methods / results /
   discussion / conclusion / figure caption / table note.
2. **Source register**: formal academic Chinese (typical of journal manuscripts)
   vs. informal Chinese (thesis chapters, slide notes). The English output
   must always be formal academic.
3. **Quantitative content**: numbers, units, statistical metrics
   (sensitivity, specificity, AUC, p-values, confidence intervals). These
   must be preserved verbatim — never round, never convert units, never
   paraphrase statistics.
4. **Technical terms**: mark every epilepsy-specific and DL-specific term
   in the source. Cross-check each one against `templates/glossary.md` and
   the knowledge base abstracts before committing to an English rendering.

### Step 2 — Draft translation

Translate section-by-section. Follow these rules:

- **Sentence structure**: prefer Subject-Verb-Object English order. Restructure
  long Chinese sentences (which often chain comma-separated clauses) into
  shorter English sentences linked by transitional adverbs
  (Furthermore, Moreover, In addition, Consequently).
- **Voice**: use passive voice for methods ("EEG signals were recorded at
  256 Hz") and active voice for results and discussion ("We found that...").
- **Tense**: use past tense for completed methods and results; present tense
  for established facts and discussion of the literature.
- **Terminology**: use the canonical English term from the glossary. Do not
  translate technical terms literally (e.g. "卷积神经网络" → "convolutional
  neural network", never "convolution neural net").
- **Hedging**: academic English hedges claims. "证明" should usually become
  "demonstrate" or "suggest", not "prove". "导致" should usually become
  "was associated with" or "contributed to", not "caused".
- **Citations**: preserve reference markers (e.g. "[12]", "(Smith et al.,
  2023)") exactly as in the source. Do not invent or remove citations.

### Step 3 — Self-review

After drafting, perform a self-review pass:

1. **Readability check**: read each sentence aloud (mentally). If a sentence
   is longer than 25 words or contains more than two comma-separated clauses,
   split it.
2. **Terminology consistency**: verify that the same Chinese term is
   rendered with the same English term throughout the document.
3. **Article check**: English requires articles (a / an / the) where Chinese
   does not. Add them. Common error: "We trained model on dataset" →
   "We trained the model on the dataset".
4. **Quantitative fidelity**: re-verify every number, unit, and statistical
   metric against the source.
5. **Register check**: ensure no informal phrasing ("a lot of", "kind of",
  "really", "basically"). Replace with academic equivalents ("numerous",
  "somewhat", "substantially", "fundamentally").

### Step 4 — Output

Present the translation with:

1. The English translation as the primary output.
2. A brief "Translator notes" section listing any ambiguous source terms and
   the chosen English rendering, so the user can audit decisions.
3. Suggested alternative renderings for any sentence where multiple
   academically valid options exist.

## Section-specific guidance

### Title
- Concise, informative, ≤20 words ideally.
- Avoid "A study on...", "Research on..." — these are calques of Chinese
  "关于...的研究". Start directly with the content.
- If the source title contains a method and a task, place the task first:
  "Seizure detection using ..." rather than "Using ... for seizure detection".

### Abstract
- 200-300 words for most journals; check target journal limits.
- Standard structure: Background → Methods → Results → Conclusions.
- Use past tense for methods and results, present tense for background and
  conclusions.

### Methods
- Past tense, passive voice by default.
- Specify: dataset (name, size, sampling rate), preprocessing steps,
  architecture (layer counts, hyperparameters), training details
  (optimizer, learning rate, epochs), evaluation protocol
  (cross-validation folds, metrics).
- Preserve numerical precision exactly: "256 Hz" not "around 256 Hz".

### Results
- Past tense, active ("We found") or passive ("An AUC of 0.92 was achieved").
- Report metrics with the same precision as the source. If the source says
  "准确率 95.3%", render as "an accuracy of 95.3%" — not "approximately 95%"
  or "95.30%".
- Statistical notation: p < 0.001, 95% CI [0.85, 0.96], mean ± SD.

### Discussion / Conclusion
- Present tense for established findings; past tense for the present study's
  specific findings.
- Use hedged language for implications: "These findings suggest that..."
  rather than "This proves that...".

## Common pitfalls (epilepsy + deep learning specific)

| Chinese pitfall | Wrong English | Correct English |
|-----------------|---------------|-----------------|
| 癫痫发作 | epilepsy attack | epileptic seizure |
| 脑电图 | brain electrical diagram | electroencephalogram (EEG) |
| 难治性癫痫 | refractory epilepsy (acceptable) | drug-resistant epilepsy (preferred per ILAE 2010) |
| 发作间期 | inter-attack period | interictal period |
| 发作期 | attack period | ictal period |
| 发作前 | pre-attack | preictal |
| 癫痫样放电 | epilepsy-like discharge | epileptiform discharge |
| 棘波 | thorn wave | spike |
| 尖波 | sharp wave | sharp wave |
| 棘慢复合波 | thorn-slow complex wave | spike-and-wave complex |
| 局灶性癫痫 | focal epilepsy (acceptable) | focal epilepsy (ILAE preferred) |
| 全面性癫痫 | generalized epilepsy | generalized epilepsy |
| 卷积 | convolution (acceptable) | convolution |
| 池化 | pooling | pooling |
| 全连接层 | fully connected layer | fully connected layer / dense layer |
| 损失函数 | loss function | loss function |
| 反向传播 | back propagation | backpropagation (one word) |
| 训练集 | training set | training set / training split |
| 验证集 | validation set | validation set / development set |
| 测试集 | test set | test set / held-out test set |
| 过拟合 | over-fitting | overfitting (one word) |
| 欠拟合 | under-fitting | underfitting (one word) |
| 学习率 | learning rate | learning rate |
| 批大小 | batch size | batch size |
| 周期 | epoch | epoch |
| 注意力机制 | attention mechanism | attention mechanism |
| 自注意力 | self-attention | self-attention |
| 多头注意力 | multi-head attention | multi-head attention |
| 序列到序列 | seq2seq | sequence-to-sequence |
| 端到端 | end-to-end | end-to-end |
| 迁移学习 | transfer learning | transfer learning |
| 联邦学习 | federal learning | federated learning |
| 数据增强 | data enhancement | data augmentation |
| 特征提取 | feature extraction | feature extraction |
| 特征图 | feature map | feature map / feature activation map |
| 感受野 | receptive field | receptive field |
| 残差连接 | residual connection | residual connection / skip connection |
| 批归一化 | batch normalization | batch normalization (BatchNorm) |
| 丢弃 | discard | dropout (when referring to the regularization technique) |

## Output format

Always present translations in this format:

```
## Translation

<English text>

## Translator notes

- <Source term> → <English rendering>: <reason>
- <Source term> → <English rendering>: <reason>
- <Ambiguous sentence>: <chosen rendering> (alternative: <alternative>)

## Suggested alternatives

- Sentence 1: <alternative rendering>
- Sentence 2: <alternative rendering>
```

## Reference files

- [`templates/glossary.md`](templates/glossary.md) — full bilingual glossary
  of epilepsy and deep learning terminology.
- [`templates/academic_phrases.md`](templates/academic_phrases.md) —
  reusable academic English sentence patterns organized by section.
- [`templates/translation_template.md`](templates/translation_template.md) —
  a section-by-section template for translating a complete paper.
- [`examples/sample_translation.md`](examples/sample_translation.md) —
  a worked example showing Chinese source, English translation, and
  translator notes.
- [`knowledge_base/INDEX.md`](knowledge_base/INDEX.md) — index of the 73
  reference papers.

## Final reminder

The goal is **publication-ready English**. A successful translation should
read as if it had been written in English by a fluent researcher in
epilepsy + deep learning. If any sentence in your draft reads as
"translated", rewrite it. The knowledge base abstracts are the gold
standard for register and phrasing — when in doubt, match their style.
