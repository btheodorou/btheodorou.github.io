---
title: "Synthesize Extremely High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model"
collection: publications
permalink: /publication/halo
excerpt: 'Synthetic electronic health records (EHRs) that are both realistic and preserve privacy can serve as an alternative to real EHRs for machine learning (ML) modeling and statistical analysis. 
However, generating high-fidelity and granular electronic health record (EHR) data in its original, highly-dimensional form poses challenges for existing methods due to the complexities inherent in high-dimensional data. 
In this paper, we propose Hierarchical Autoregressive Language mOdel (HALO) for generating longitudinal high-dimensional EHR, which preserve the statistical properties of real EHR and can be used to train accurate ML models without privacy concerns. Our HALO method, designed as a hierarchical autoregressive model,  generates a probability density function of medical codes, clinical visits, and patient records, allowing for the generation of realistic EHR data in its original, unaggregated form without the need for variable selection or aggregation. Additionally, our model also produces high-quality continuous variables in a longitudinal and probabilistic manner.
%We evaluate HALO in its probabilistic modeling, the realism of its generated synthetic dataset, and the utility for supporting machine learning tasks such as rare disease detection and phenotyping. 

We conducted extensive experiments and demonstrate that HALO   can generate high-fidelity EHR data with high-dimensional disease code probabilities ($d\approx10,000$), disease code co-occurrence probabilities within a visit ($d\approx1,000,000$), and conditional probabilities across consecutive visits ($d\approx5,000,000$) and achieve above 0.9 $R^2$ correlation in comparison to real EHR data.
In comparison to the leading baseline, HALO improves predictive modeling by over 17% in its predictive accuracy and perplexity on a hold-off test set of real EHR data. This performance then enables downstream ML models trained on its synthetic data to achieve comparable accuracy to models trained on real data (0.938 area under the ROC curve with HALO data vs. 0.943 with real data). 
Finally, using a combination of real and synthetic data enhances the accuracy of ML models beyond that achieved by using only real EHR data.'
date: 2023-03-01
venue: 'Preparing for Submission'
paperurl: 'http://academicpages.github.io/files/halo.pdf'
citation: 'B Theodorou, D Cao, J Sun. Synthesize Extremely High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model.'
---
This paper proposes an architecture to simulate patient records with full dimensionality for the first time while maintaining full autoregressive dependencies to capture complex patterns.

[Download paper here](http://academicpages.github.io/files/halo.pdf)

Recommended citation: B Theodorou, D Cao, J Sun. Synthesize Extremely High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model.