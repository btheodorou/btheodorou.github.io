---
title: "MediSim: Multi-Granular Simulation for Enriching Longitudinal, Multi-Modal Electronic Health Records"
collection: publications
permalink: /publication/medisim
excerpt: 'The effectiveness of AI models across various domains hinges on diverse and comprehensive multi-modal training datasets. Yet, in healthcare, there is a stark shortage of linked high-quality multi-modal electronic health record (EHR) data, leading to less-than-optimal model performance in AI applications like phenotyping and mortality predictions. Current EHR data often have quality issues such as missing data modalities or exhibiting temporal gaps, resulting in a scarcity of high-quality, complete datasets. 

This paper presents an effective method called MediSim for enhancing EHR data using multiple modalities. MediSim uses a multi-granular, autoregressive architecture to simulate missing modalities and visits of medical codes to extend deficient EHRs. It is enhanced by an iterative, reinforcement learning-based training scheme that improves such simulation in low-data settings, and it furthermore introduces encoder-decoder model pairs to handle additional, complex modalities such as clinical notes and medical images that are not typically included in structured EHR representation. Using these contributions, MediSim is able to generate comprehensive, high-dimensional EHR data, which improves downstream predictive modeling tasks.'
date: 2024-10-10
venue: 'Preparing for Submission'
paperurl: 'http://academicpages.github.io/files/medisim.pdf'
citation: 'B Theodorou, D Cao, J Sun. MediSim: Multi-Granular Simulation for Enriching Longitudinal, Multi-Modal Electronic Health Records.'
---
This paper proposes a method to extend patient records both in terms of missing visits and missing modalities of medical codes, text, and images. Utilizes a self-supervised training regime to improve performance when only limited training data is available.

[Download paper here](http://academicpages.github.io/files/medisim.pdf)

Recommended citation: B Theodorou, D Cao, J Sun. MediSim: Multi-Granular Simulation for Enriching Longitudinal, Multi-Modal Electronic Health Records.