---
title: "MediSim: Multi-Granular Simulation for Enriching Longitudinal, Multi-Modal Electronic Health Records"
collection: publications
permalink: /publication/medisim
excerpt: 'High-quality and complete electronic health record (EHR) data is crucial for healthcare analysis and prediction. However, current EHR data often suffer from quality issues such as temporal gaps and missing modalities, making high-quality complete data scarce. While some remedies exist, such as imputing missing information or predicting future medical codes, they often fail due to limited training data. To date, no method effectively addresses multiple EHR data quality issues simultaneously.

In this paper, we introduce a new approach called MediSim, which is an iterative, self-supervised method that improves EHR data quality using a multi-granular autoregressive data generation architecture. It can enrich and simulate high-dimensional data with thousands of medical codes from all modalities, including unstructured and complex ones like clinical notes and medical images. This method generates augmented data with comprehensive records and adequate temporal history, enhancing downstream predictive modeling tasks.

We extensively tested MediSim against top EHR generation and code prediction methods. It consistently outperformed baseline approaches, securing up to 390% F1 score improvement (from 0.095 to 0.479) in longitudinal prediction and 74% (from 0.333 to 0.582) in same-visit code modality prediction. Moreover, we show the value of the data enrichment task itself, showing that using models such as MediSim to augment real EHRs boosted downstream predictive tasks, delivering a 65% F1 Score improvement (from 0.316 to 0.522) over limited-length data from temporal extension and an 7% enhancement (from F1 Score of 0.244 to 0.262) over limited-modality data from code modality completion. Finally, we showcase our ability to effectively handle additional, more complex modalities such as clinical note text and X-ray imaging through a series of sample conditional generations.'
date: 2023-01-10
venue: 'Under Review at IJCAI 23'
paperurl: 'http://academicpages.github.io/files/medisim.pdf'
citation: 'B Theodorou, D Cao, J Sun. MediSim: Multi-Granular Simulation for Enriching Longitudinal, Multi-Modal Electronic Health Records.'
---
This paper proposes a method to extend patient records both in terms of missing visits and missing modalities of medical codes, text, and images. Utilizes a self-supervised training regime to improve performance when only limited training data is available.

[Download paper here](http://academicpages.github.io/files/medisim.pdf)

Recommended citation: B Theodorou, D Cao, J Sun. MediSim: Multi-Granular Simulation for Enriching Longitudinal, Multi-Modal Electronic Health Records.