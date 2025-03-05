---
title: A Deep-learning Anomaly-detection Method to Identify Gamma-Ray Bursts in the
  Ratemeters of the AGILE Anticoincidence System
authors:
- N. Parmiggiani
- A. Bulgarelli
- A. Ursi
- \textbfA. \textbfMacaluso
- A. Di Piano
- V. Fioretti
- A. Aboudan
- L. Baroncelli
- A. Addis
- M. Tavani
- C. Pittori
date: '2023-03-01'
publishDate: '2025-03-05T14:29:06.088372Z'
publication_types:
- article-journal
publication: '*The Astrophysical Journal*'
doi: 10.3847/1538-4357/acba0a
abstract: Astro-rivelatore Gamma a Immagini Leggero (AGILE) is a space mission launched
  in 2007 to study X-ray and gamma-ray astronomy. The AGILE team developed real-time
  analysis pipelines to detect transient phenomena such as gamma-ray bursts (GRBs)
  and react to external science alerts received by other facilities. The AGILE anticoincidence
  system (ACS) comprises five panels surrounding the AGILE detectors to reject background-charged
  particles. It can also detect hard X-ray photons in the energy range 50–200 keV.
  The ACS data acquisition produces a time series for each panel. The time series
  are merged into a single multivariate time series (MTS). We present a new deep-learning
  model for the detection of GRBs in the ACS data using an anomaly detection technique.
  The model is implemented with a convolutional neural network autoencoder architecture
  trained in an unsupervised manner, using a data set of MTSs randomly extracted from
  the AGILE ACS data. The reconstruction error of the autoencoder is used as the anomaly
  score to classify the MTS. We calculated the associated p-value distribution, using
  more than 107 background-only MTSs, to define the statistical significance of the
  detections. We evaluate the trained model with a list of GRBs reported by the GRBWeb
  catalog. The results confirm the model’s capabilities to detect GRBs in the ACS
  data. We will implement this method in the AGILE real-time analysis pipeline.
tags:
- 2023 ml
---
