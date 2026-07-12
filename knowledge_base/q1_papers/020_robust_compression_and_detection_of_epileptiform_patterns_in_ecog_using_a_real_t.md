# Robust compression and detection of epileptiform patterns in ECoG using a real-time spiking neural network hardware framework

| Field | Value |
|-------|-------|
| ID | 20 |
| DOI | [`10.1038/s41467-024-47495-y`](https://doi.org/10.1038/s41467-024-47495-y) |
| Journal | Nature Communications |
| CAS Quartile | Q1 |
| Year | 2024 |
| Authors | Costa Filippo; Schaft Eline V.; Huiskamp Geertjan; Aarnoutse Erik J.; van’t Klooster Maryse A.; Krayenbühl Niklaus; Ramantani Georgia; Zijlmans Maeike; Indiveri Giacomo; Sarnthein Johannes |
| Abstract source | crossref |

## Abstract

Abstract Interictal Epileptiform Discharges (IED) and High Frequency Oscillations (HFO) in intraoperative electrocorticography (ECoG) may guide the surgeon by delineating the epileptogenic zone. We designed a modular spiking neural network (SNN) in a mixed-signal neuromorphic device to process the ECoG in real-time. We exploit the variability of the inhomogeneous silicon neurons to achieve efficient sparse and decorrelated temporal signal encoding. We interface the full-custom SNN device to the BCI2000 real-time framework and configure the setup to detect HFO and IED co-occurring with HFO (IED-HFO). We validate the setup on pre-recorded data and obtain HFO rates that are concordant with a previously validated offline algorithm (Spearman’s ρ = 0.75, p = 1e-4), achieving the same postsurgical seizure freedom predictions for all patients. In a remote on-line analysis, intraoperative ECoG recorded in Utrecht was compressed and transferred to Zurich for SNN processing and successful IED-HFO detection in real-time. These results further demonstrate how automated remote real-time detection may enable the use of HFO in clinical practice.

## Why this paper is in the knowledge base

This paper is part of the curated knowledge base for the **tspskill** translation skill.
It was retrieved from **CrossRef** (real DOI, title, journal, authors) and, where the
publisher did not deposit an abstract, the abstract was fetched from **Semantic Scholar**.

It is published in a **Q1** SCI journal (CAS classification) and addresses
the intersection of **epilepsy** and **deep learning**, the two core topics this skill
is specialized to translate.

Translators should use this paper as a **reference for domain terminology, academic phrasing,
and standard expression patterns** in epilepsy-related deep learning research. The abstract
above is the publisher's authoritative English version — when translating a Chinese passage
that discusses a similar topic, match the phrasing and terminology used here.
