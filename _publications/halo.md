---
title: "Synthesize Extremely High-dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model"
collection: publications
permalink: /publication/halo
excerpt: 'Synthetic electronic health records (EHRs) that are both realistic and privacy-preserving offer alternatives to real EHRs for machine learning (ML) and statistical analysis. However, generating high-fidelity EHR data in its original, high-dimensional form poses challenges for existing methods. 
We propose Hierarchical Autoregressive Language mOdel (HALO) for generating longitudinal, high-dimensional EHR, which preserve the statistical properties of real EHRs and can train accurate ML models without privacy concerns. HALO generates a probability density function over medical codes, clinical visits, and patient records, allowing for generating realistic EHR data without requiring variable selection or aggregation. Extensive experiments demonstrated that HALO can generate high-fidelity data with high-dimensional disease code probabilities closely mirroring (above 0.9 $R^2$ correlation) real EHR data. HALO also enhances the accuracy of predictive modeling and enables downstream ML models to attain similar accuracy as models trained on genuine data. 

We conducted extensive experiments and demonstrate that HALO can generate high-fidelity EHR data with high-dimensional disease code probabilities (d ~ 10,000), disease code co-occurrence probabilities within a visit (d ~ 1,000,000), and conditional probabilities across consecutive visits (d ~ 5,000,000) and achieve above 0.9 $R^2$ correlation in comparison to real EHR data.
In comparison to the leading baseline, HALO improves predictive modeling by over 17% in its predictive accuracy and perplexity on a hold-off test set of real EHR data. This performance then enables downstream ML models trained on its synthetic data to achieve comparable accuracy to models trained on real data (0.938 area under the ROC curve with HALO data vs. 0.943 with real data). 
Finally, using a combination of real and synthetic data enhances the accuracy of ML models beyond that achieved by using only real EHR data.'
date: 2023-03-01
venue: 'Nature Communications'
paperurl: 'https://www.nature.com/articles/s41467-023-41093-0'
citation: 'B Theodorou, D Cao, J Sun. Synthesize High-Dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model.'
---
This paper proposes an architecture to simulate patient records with full dimensionality for the first time while maintaining full autoregressive dependencies to capture complex patterns.

[Download paper here](https://www.nature.com/articles/s41467-023-41093-0)

Recommended citation: B Theodorou, D Cao, J Sun. Synthesize High-Dimensional Longitudinal Electronic Health Records via Hierarchical Autoregressive Language Model.