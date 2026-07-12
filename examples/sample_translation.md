# Sample Translation — Worked Example

This file demonstrates the tspskill translation workflow on a short Chinese
abstract, showing: (1) the source, (2) the analysis, (3) the English
translation, and (4) the translator notes.

---

## Source (Chinese)

> **基于一维卷积神经网络的长程脑电信号癫痫发作自动检测**
>
> **背景**：癫痫是一种常见的神经系统疾病，影响全球约1%的人口。长程脑电图监测是癫痫诊断的重要手段，但人工判读耗时费力，且存在主观差异。深度学习为脑电信号的自动分析提供了新的思路。
>
> **方法**：本研究纳入2018年1月至2022年12月期间在某三甲医院癫痫中心接受长程视频脑电监测的126例癫痫患者的脑电数据，共计8420小时的记录。脑电信号以256 Hz采样，按国际10-20系统放置19个通道。预处理包括50 Hz陷波滤波、0.5-50 Hz带通滤波以及逐通道z-score标准化。我们提出一种基于残差连接的一维卷积神经网络（1D-ResCNN），包含8个残差块，每块含两个卷积层。模型采用Adam优化器（学习率0.001），批大小64，训练100个epoch，使用焦点损失应对类别不平衡。采用留一被试交叉验证（LOSO）评估模型性能。
>
> **结果**：所提模型在测试集上的敏感度为94.3%（95% CI: 92.1%-96.5%），特异度为93.8%（95% CI: 91.6%-96.0%），平均AUC为0.962。发作平均检测延迟为4.7±2.1秒。与基线方法（传统CNN）相比，敏感度提升了3.5个百分点（p<0.001）。模型在外部验证队列（n=32）上敏感度仍保持在89.1%。
>
> **结论**：本研究提出的1D-ResCNN可实现对长程脑电信号的高效自动癫痫发作检测，在保持高敏感度的同时显著降低检测延迟，为癫痫的临床辅助诊断提供了有潜力的工具。

---

## Analysis

**Section type**: Structured abstract (Background / Methods / Results / Conclusions).

**Source register**: Formal academic Chinese, journal manuscript style.

**Quantitative content to preserve exactly**:
- 1% (prevalence)
- 2018年1月至2022年12月 (date range)
- 126例 (n patients)
- 8420小时 (recording duration)
- 256 Hz (sampling rate)
- 19个通道 (channel count)
- 50 Hz (notch filter)
- 0.5-50 Hz (band-pass)
- 8个残差块 (architecture)
- 学习率0.001 (learning rate)
- 批大小64 (batch size)
- 100个epoch (epoch count)
- 94.3% (sensitivity), 95% CI: 92.1%-96.5%
- 93.8% (specificity), 95% CI: 91.6%-96.0%
- 0.962 (AUC)
- 4.7±2.1秒 (detection latency)
- 3.5个百分点 (delta)
- p<0.001
- n=32 (external cohort size)
- 89.1% (external sensitivity)

**Technical terms requiring glossary consultation**:
- 长程脑电图监测 → long-term EEG monitoring
- 视频脑电监测 → video-EEG monitoring
- 国际10-20系统 → International 10-20 System
- 陷波滤波 → notch filtering
- 带通滤波 → band-pass filtering
- z-score标准化 → z-score normalization
- 残差连接 → residual connection
- 一维卷积神经网络 → 1D convolutional neural network (1D-CNN)
- 残差块 → residual block
- 卷积层 → convolutional layer
- Adam优化器 → Adam optimizer
- 学习率 → learning rate
- 批大小 → batch size
- epoch → epoch (do not translate)
- 焦点损失 → focal loss
- 类别不平衡 → class imbalance
- 留一被试交叉验证 → leave-one-subject-out (LOSO) cross-validation
- 敏感度 → sensitivity
- 特异度 → specificity
- 平均AUC → mean AUC
- 检测延迟 → detection latency
- 基线方法 → baseline approach
- 传统CNN → conventional CNN
- 外部验证队列 → external validation cohort

---

## Translation

**Automated seizure detection in long-term EEG signals using a one-dimensional convolutional neural network**

**Background**: Epilepsy is a common neurological disorder affecting approximately 1% of the global population. Long-term EEG monitoring is an important tool for epilepsy diagnosis; however, manual interpretation is time-consuming and subject to inter-rater variability. Deep learning has emerged as a promising approach for the automated analysis of EEG signals.

**Methods**: This study included EEG data from 126 patients with epilepsy who underwent long-term video-EEG monitoring at the epilepsy center of a tertiary hospital between January 2018 and December 2022, yielding a total of 8,420 hours of recordings. EEG signals were sampled at 256 Hz with 19 channels placed according to the International 10-20 System. Preprocessing comprised 50 Hz notch filtering, 0.5–50 Hz band-pass filtering, and per-channel z-score normalization. We propose a one-dimensional residual convolutional neural network (1D-ResCNN) comprising eight residual blocks, each containing two convolutional layers. The model was trained using the Adam optimizer (learning rate = 0.001) with a batch size of 64 for 100 epochs, employing focal loss to address class imbalance. Leave-one-subject-out (LOSO) cross-validation was used to evaluate model performance.

**Results**: The proposed model achieved a sensitivity of 94.3% (95% CI: 92.1%–96.5%) and a specificity of 93.8% (95% CI: 91.6%–96.0%) on the test set, with a mean AUC of 0.962. The mean detection latency was 4.7 ± 2.1 s. Compared with the baseline approach (a conventional CNN), the proposed model improved sensitivity by 3.5 percentage points (p < 0.001). Sensitivity remained at 89.1% on the external validation cohort (n = 32).

**Conclusions**: The proposed 1D-ResCNN enables efficient automated seizure detection in long-term EEG signals, achieving high sensitivity while substantially reducing detection latency. The approach offers a promising tool for computer-assisted epilepsy diagnosis in clinical practice.

**Keywords**: epilepsy; seizure detection; deep learning; convolutional neural network; electroencephalogram

---

## Translator notes

- **三甲医院** → "tertiary hospital": standard rendering; "Grade III Class A hospital" is overly literal and unfamiliar to international readers.
- **长程视频脑电监测** → "long-term video-EEG monitoring": the canonical term in epilepsy literature (cf. knowledge base entries from *Epilepsia* and *Seizure*).
- **国际10-20系统** → "International 10-20 System": note capitalization and hyphenation.
- **逐通道z-score标准化** → "per-channel z-score normalization": hyphenated compound modifier.
- **一维卷积神经网络** → "one-dimensional convolutional neural network (1D-CNN)": spelled out on first mention, abbreviation thereafter.
- **残差连接 / 残差块** → "residual connection / residual block": standard deep learning terminology.
- **焦点损失** → "focal loss": do not render as "focal loss function" — "focal loss" is the standard term.
- **类别不平衡** → "class imbalance": the conventional term; "category imbalance" is non-standard.
- **留一被试交叉验证** → "leave-one-subject-out (LOSO) cross-validation": canonical EEG research term.
- **传统CNN** → "conventional CNN": preferred over "traditional CNN" in academic writing.
- **检测延迟** → "detection latency": standard term in seizure detection literature.
- **百分点** → "percentage points": when describing a difference between percentages, "percentage points" (or "percentage-point") is correct; "percent" would be ambiguous.
- **辅助诊断** → "computer-assisted diagnosis": preferred rendering; "auxiliary diagnosis" is a calque.
- **临床辅助诊断** → "computer-assisted epilepsy diagnosis in clinical practice": expanded slightly for readability.
- **保持高敏感度的同时显著降低检测延迟** → "achieving high sensitivity while substantially reducing detection latency": restructured as a participial phrase for academic flow.

## Suggested alternatives

- The opening sentence of the Background could also be rendered as: *"Epilepsy is among the most prevalent neurological disorders, affecting approximately 1% of the global population."* This version is slightly more emphatic.
- The Methods paragraph sentence *"Preprocessing comprised 50 Hz notch filtering..."* could alternatively be rendered as: *"Preprocessing steps included 50 Hz notch filtering..."* — equivalent in meaning, slightly less formal.
- The Conclusions sentence *"The approach offers a promising tool for computer-assisted epilepsy diagnosis in clinical practice."* could alternatively be: *"The approach may serve as a promising decision-support tool for epilepsy diagnosis in clinical practice."* — slightly more hedged, which may be preferable for some target journals.
