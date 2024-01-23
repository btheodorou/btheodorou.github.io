---
title: "SECONDGRAM: Self-Conditioned Diffusion with Gradiant Manipulation for Longitudinal MRI Imputation"
collection: publications
permalink: /publication/secondgram
excerpt: 'Magnetic Resonance Imaging (MRI) plays a critical role in modern medicine by aiding in the diagnosis and monitoring of various medical conditions. While individual MRI snapshots provide valuable insights, the longitudinal progression depicted in repeated MRI results often holds more significant diagnostic and prognostic value. However, a scarcity of longitudinal MRI datasets, comprising paired initial and follow-up scans, hinders the application of machine learning for crucial sequential tasks. We aim to address this gap by developing a model capable of generating absent follow-up imaging, enabling predictions of MRI developments over time, and enriching limited datasets through imputation. We propose SECONDGRAM, beginning with the state-of-the-art neural diffusion models and introducing two key contributions: Self-Conditioned Learning, to leverage much larger, unlinked datasets for training by conditioning MRI generations on their possibly noised selves, and Gradient Manipulation, to combat instability and overfitting in a low-data setting. We evaluate SECONDGRAM on the UK Biobank dataset and show that it not only models MRI patterns better than existing baselines but also achieves better downstream results by enhancing training datasets. Specifically, SECONDGRAM achieves a 20% improvement in mean Pearson correlation between the imputed and real follow-up images in a held-out test set, and up to a 10% improvement in downstream Stroke classification AUROC for models trained on its enriched datasets over naive approaches.'
date: 2023-01-10
venue: 'Preparing for Submission'
paperurl: 'http://academicpages.github.io/files/secondgram.pdf'
citation: 'B Theodorou, A Dadu, M Nalls, J Sun, F Faghri. SECONDGRAM: Self-Conditioned Diffusion with Gradiant Manipulation for Longitudinal MRI Imputation.'
---
This paper proposes a method to generatively impute follow-up MRI imaging results despite limited training data to enrich downstream machine learning datasets which have many individual imaging scans but few patients with follow-up scans usable on longitudinal tasks.

[Download paper here](http://academicpages.github.io/files/secondgram.pdf)

Recommended citation: B Theodorou, A Dadu, M Nalls, J Sun, F Faghri. SECONDGRAM: Self-Conditioned Diffusion with Gradiant Manipulation for Longitudinal MRI Imputation.