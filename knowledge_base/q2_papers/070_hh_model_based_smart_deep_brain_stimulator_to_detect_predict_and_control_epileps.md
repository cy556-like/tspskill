# HH model based smart deep brain stimulator to detect, predict and control epilepsy using machine learning algorithm

| Field | Value |
|-------|-------|
| ID | 70 |
| DOI | [`10.1016/j.jneumeth.2023.109825`](https://doi.org/10.1016/j.jneumeth.2023.109825) |
| Journal | Journal of Neuroscience Methods |
| CAS Quartile | Q2 |
| Year | 2023 |
| Authors | Nambi Narayanan S.; Subbian Sutha |
| Abstract source | semantic_scholar |

## Abstract

BACKGROUND
Epilepsy is the most common neurological disorder in the world. To control epilepsy, deep brain stimulation is one of the widely accepted treatment techniques. However, conventional deep brain stimulation technique provides continuous stimulation without optimizing the stimulation parameters, resulting in adverse side effects and unexpected death. Hence, understanding the dynamic behavior of brain neural networks at a cellular level is required for patient-specific epilepsy treatment. Considering the underlying mechanism of a single neuronal shift in the brain neural network, computational model-based techniques have a new face for healthcare, which aims to develop effective medical devices for preclinical investigations.


NEW METHOD
This paper discusses the design of a Smart Deep Brain Stimulator (SDBS) using the Hodgkin-Huxley (HH) conductance-based cellular model of brain neurons to automatically detect, predict and regulate epilepsy against patient-specific conditions. Epileptic activity is simulated as a spike train of action potential due to sodium and potassium channel conductance variations in the single-neuron HH model. The proposed SDBS consists of three components:- i) seizure detection using bagging and boosting-based ensemble machine learning classifiers, ii) channel conductance prediction using Long Short Term Memory-Recurrent Neural Network (LSTM-RNN) based Deep Neural Network (DNN) for updating model parameters of brain neuron, and iii) model-based intelligent control of epileptic seizure with Nonlinear Autoregressive Moving Average-L2 (NARMA-L2) Controller and Nonlinear Model Predictive Controller (NMPC).


RESULTS
For effective treatment, improving the overall accuracy and efficiency of SDBS is essential. For epilepsy detection, the ensemble bagging machine learning algorithm provides better accuracy of 92.7% compared to the ensemble boosting algorithm. LSTM-RNN deep neural network model with four layers predicts the variations in channel conductance with Root Mean Square Error (RMSE) of 0.00568 and 0.009081 for sodium and potassium channel conductance, respectively. From the closed-loop performances of SDBS with an intelligent control scheme, it is observed that SDBS with NMPC provides efficient and accurate stimulation with minimum energy consumption. From a stability point of view, SDBS with NMPC provides better stability than SDBS with NARMA-L2 Controller.


COMPARISON WITH EXISTING METHOD
The proposed SDBS is designed to generate accurate stimulation pulses for epilepsy patients with specific conditions depending on the neuronal activity of a single neuron. Moreover, it will also adapt to the dynamic condition of epilepsy patients. The existing deep brain stimulator continuously provides stimulation pulses without adapting to the patient's conditions.


CONCLUSION
The proposed SDBS could provide patient-specific treatment based on sodium/potassium channel conductance variations of brain neurons. It will help increase the use of deep brain stimulation techniques and reduce sudden death. Furthermore, the proposed technique will be extended to neural network models with larger neuronal populations to improve the practical feasibility.

## Why this paper is in the knowledge base

This paper is part of the curated knowledge base for the **tspskill** translation skill.
It was retrieved from **CrossRef** (real DOI, title, journal, authors) and, where the
publisher did not deposit an abstract, the abstract was fetched from **Semantic Scholar**.

It is published in a **Q2** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research. The abstract
above is the publisher's authoritative English version — when translating a Chinese passage
that discusses a similar topic, match the phrasing and terminology used here.
