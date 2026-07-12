# EEG based multi-class seizure type classification using convolutional neural network and transfer learning

| Field | Value |
|-------|-------|
| ID | 76 |
| DOI | [`10.1016/j.neunet.2020.01.017`](https://doi.org/10.1016/j.neunet.2020.01.017) |
| Journal | Neural Networks |
| CAS Quartile | Q2 |
| Year | 2020 |
| Authors | Raghu S.; Sriraam Natarajan; Temel Yasin; Rao Shyam Vasudeva; Kubben Pieter L. |
| Abstract source | semantic_scholar |

## Abstract

Recognition of epileptic seizure type is essential for the neurosurgeon to understand the cortical connectivity of the brain. Though automated early recognition of seizures from normal electroencephalogram (EEG) was existing, no attempts have been made towards the classification of variants of seizures. Therefore, this study attempts to classify seven variants of seizures with non-seizure EEG through the application of convolutional neural networks (CNN) and transfer learning by making use of the Temple University Hospital EEG corpus. The objective of our study is to perform a multi-class classification of epileptic seizure type, which includes simple partial, complex partial, focal non-specific, generalized non-specific, absence, tonic, and tonic-clonic, and non-seizures. The 19 channels EEG time series was converted into a spectrogram stack before feeding as input to CNN. The following two different modalities were proposed using CNN: (1) Transfer learning using pretrained network, (2) Extract image features using pretrained network and classify using the support vector machine classifier. The following ten pretrained networks were used to identify the optimal network for the proposed study: Alexnet, Vgg16, Vgg19, Squeezenet, Googlenet, Inceptionv3, Densenet201, Resnet18, Resnet50, and Resnet101. The highest classification accuracy of 82.85% (using Googlenet) and 88.30% (using Inceptionv3) was achieved using transfer learning and extract image features approach respectively. Comparison results showed that CNN based approach outperformed conventional feature and clustering based approaches. It can be concluded that the EEG based classification of seizure type using CNN model could be used in pre-surgical evaluation for treating patients with epilepsy.

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
