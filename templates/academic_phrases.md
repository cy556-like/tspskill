# Academic English Phrases — Reusable Patterns

This file collects sentence patterns commonly used in epilepsy + deep learning
academic papers, organized by section. Translators should adapt these patterns
to the specific content of the source text rather than translating literally.

## Title patterns

- "<Task> using <method> with <data>"
  Example: *Seizure detection using a 1D-CNN with intracranial EEG*
- "<Method>-based <task> in <cohort / data modality>"
  Example: *Transformer-based seizure detection in long-term scalp EEG*
- "Deep learning for <task>: a <study type>"
  Example: *Deep learning for seizure prediction: a multicentre retrospective study*
- "Automated <task> using <method>"
  Example: *Automated epileptiform discharge detection using a residual network*

## Abstract patterns

### Background
- "<Disease> affects approximately <number> people worldwide."
- "Despite advances in <field>, <problem> remains challenging."
- "Automated <task> could <potential benefit>."
- "Existing approaches to <task> are limited by <limitation>."

### Methods
- "We developed a <method> for <task>."
- "The model was trained on <dataset> (<n> recordings from <n> patients)."
- "We evaluated performance using <n>-fold cross-validation."
- "EEG signals were preprocessed by <steps>."
- "The architecture consisted of <component description>."
- "Training was performed with the <optimizer> optimizer (learning rate = <lr>) for <epochs> epochs."

### Results
- "The model achieved a sensitivity of <x>% (95% CI [<lo>, <hi>]) and a specificity of <y>%."
- "Performance was highest on <subset / class>, with an AUC of <z>."
- "Compared with the <baseline> baseline, our approach improved <metric> by <delta>."
- "We observed no significant performance degradation when generalizing to <new setting>."

### Conclusions
- "These findings suggest that <method> can <capability>."
- "The proposed approach offers a promising avenue for <application>."
- "Further prospective validation in <setting> is warranted."
- "Code and pretrained models are publicly available at <url>."

## Introduction patterns

### Opening sentence
- "<Disease> is one of the most common <specialty> conditions worldwide, affecting approximately <n> million people."
- "Epilepsy, characterized by recurrent unprovoked seizures, affects approximately 1% of the global population."
- "Deep learning has emerged as a powerful tool for <task> in <field>."

### Gap statement
- "However, <existing limitation> remains a major challenge."
- "Despite the success of <prior approach>, several limitations persist: <list>."
- "Most existing studies have focused on <single-center / small cohort>, leaving generalizability unclear."
- "Little is known about <open question>."

### Contribution statement
- "In this study, we propose <method> for <task>."
- "Our contributions are threefold: (1) ..., (2) ..., (3) ..."
- "We make the following contributions: ..."
- "To the best of our knowledge, this is the first study to <innovation>."

## Methods patterns

### Dataset
- "We used the publicly available <dataset name> dataset, which contains <description>."
- "EEG recordings were obtained from <n> patients with epilepsy (mean age ± SD = <x> ± <y> years; <m> female) who underwent <monitoring type> at <institution> between <year> and <year>."
- "The study was approved by the institutional review board of <institution>, and informed consent was obtained from all participants (or waived due to retrospective design)."
- "Recordings were sampled at <rate> Hz with <n> channels following the International 10-20 System."

### Preprocessing
- "EEG signals were re-referenced to <reference>."
- "A <notch / band-pass> filter (cutoffs: <freqs> Hz) was applied to remove <artifact type>."
- "Continuous recordings were segmented into <duration>-s epochs with <overlap> overlap."
- "Signals were normalized to zero mean and unit variance per channel."

### Architecture
- "The proposed model consists of <n> convolutional blocks followed by <n> fully connected layers."
- "Each convolutional block comprises a convolutional layer (kernel size = <k>, stride = <s>, filters = <f>), a batch normalization layer, a ReLU activation, and a max-pooling layer."
- "We used a transformer encoder with <n> layers, <n> attention heads, and an embedding dimension of <d>."
- "The graph convolutional network operates over an electrode adjacency graph constructed using <method>."

### Training
- "Models were trained using the Adam optimizer (initial learning rate = <lr>, weight decay = <wd>) with a batch size of <b> for <e> epochs."
- "We used early stopping with patience = <p> on the validation loss."
- "The learning rate was reduced by a factor of 0.5 when validation loss plateaued for <p> epochs."
- "To address class imbalance, we used focal loss with γ = <g>."
- "Training was performed on a single NVIDIA <GPU model> GPU."

### Evaluation
- "We evaluated model performance using <n>-fold cross-validation at the patient level."
- "Performance was quantified using sensitivity, specificity, precision, F1 score, and AUC."
- "Statistical comparisons between models used the Wilcoxon signed-rank test with Bonferroni correction."

## Results patterns

### Quantitative reporting
- "The proposed model achieved a sensitivity of <x>% (<CI>) and a specificity of <y>% (<CI>) on the held-out test set."
- "The mean AUC across <n> folds was <z> (SD = <s>)."
- "Performance metrics are summarized in Table <n>."
- "The confusion matrix (Figure <n>) shows that the model confused <class A> with <class B> in <k>% of cases."

### Comparisons
- "Our approach outperformed the <baseline> baseline by <delta> percentage points in sensitivity (p < 0.001)."
- "Compared with <baseline>, our method reduced the false alarm rate by <factor>×."
- "No statistically significant difference was observed between <method A> and <method B> (p = <value>)."

### Ablation
- "Removing the attention module decreased AUC by <delta>, indicating its contribution to model performance."
- "Replacing the transformer encoder with an LSTM reduced sensitivity by <delta>."

### Generalization
- "When evaluated on the external held-out cohort, the model maintained a sensitivity of <x>%."
- "Performance on pediatric recordings was comparable to that on adult recordings (<x>% vs. <y>%, p = <value>)."

## Discussion patterns

### Summary of findings
- "In this study, we developed <method> and demonstrated its efficacy for <task>."
- "Our results show that <method> achieves <performance level>, which is competitive with <prior state of the art>."

### Comparison with prior work
- "Our findings are consistent with those of <prior study>, which reported <similar finding>."
- "In contrast to <prior study>, we observed <different finding>, which may be explained by <explanation>."

### Mechanistic explanation
- "The superior performance of <method> may be attributed to <property>."
- "The attention maps (Figure <n>) suggest that the model focuses on <EEG pattern>, consistent with clinical interpretation."

### Limitations
- "This study has several limitations. First, <limitation 1>. Second, <limitation 2>. Finally, <limitation 3>."
- "The retrospective design and single-center cohort limit generalizability."
- "Although we validated on an external cohort, prospective evaluation in <setting> is needed."

### Future work
- "Future work should focus on <direction>."
- "Prospective multicentre studies are needed to confirm these findings."
- "Integration with <other modality> may further improve performance."

## Conclusion patterns

- "In conclusion, we propose <method> for <task>, demonstrating that <key finding>."
- "Our findings suggest that <method> offers a promising approach to <problem>."
- "With further prospective validation, this approach could <clinical application>."

## Figure / table captions

### Figure
- "Figure <n>. <Overview of figure content>. (A) <panel A description>. (B) <panel B description>. (C) <panel C description>."
- "Figure <n>. Architecture of the proposed model. The input consists of <description>; the output is <description>."
- "Figure <n>. Representative EEG segments. (A) Interictal. (B) Preictal. (C) Ictal."

### Table
- "Table <n>. Demographic and clinical characteristics of the study cohort."
- "Table <n>. Performance comparison between the proposed model and baseline approaches."
- "Values are presented as mean ± standard deviation unless otherwise indicated."

## Hedging phrases (essential for academic English)

- "These findings suggest that..."
- "It is plausible that..."
- "One possible explanation is that..."
- "Our results are consistent with..."
- "This may be attributable to..."
- "Although preliminary, these results indicate..."
- "Further studies are warranted to..."

## Phrases to AVOID (and their academic replacements)

| Avoid | Use instead |
|-------|-------------|
| a lot of | numerous, substantial, considerable |
| kind of | somewhat, partially |
| really | substantially, markedly |
| basically | fundamentally, essentially |
| get | obtain, achieve, acquire |
| show | demonstrate, illustrate, reveal |
| big | substantial, considerable, marked |
| small | modest, slight, marginal |
| good | favorable, satisfactory |
| bad | unfavorable, suboptimal |
| find | identify, observe, detect |
| use | employ, utilize, apply |
| make | construct, develop, generate |
| prove | demonstrate, suggest, indicate |
| cause | contribute to, be associated with |
| very important | critical, essential, pivotal |
| more and more | increasingly |
| in recent years | in recent years, recently, over the past decade |
| as everyone knows | (delete; do not assert common knowledge) |
