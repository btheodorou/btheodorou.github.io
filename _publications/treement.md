---
title: "TREEMENT: Intepretable Patient-Trial Matching via Personalized Dynamic Tree-Based Memory Network"
collection: publications
permalink: /publication/treement
excerpt: 'Clinical trials are critical for drug development but often suffer from expensive and inefficient patient recruitment. In recent years, machine learning models have been proposed for speeding up patient recruitment via automatically matching patients with clinical trials based on longitudinal patient electronic health records (EHRs) and eligibility criteria of trials. However, they either depend on trial-specific expert rules that cannot be generalized or perform matching more generally with a black-box model where the lack of interpretability makes the model results difficult to be adopted.

To provide accurate and interpretable patient trial matching, we introduce a personalized dynamic tree-based memory network, TREEMENT. It utilizes hierarchical clinical ontologies to expand the personalized patient representation learned from sequential EHR data, and then uses an attentional beam-search query learned from eligibility criteria embedding to offer a granular level of alignment for improved performance and interpretability. We evaluate TREEMENT against existing models on real-world datasets and show that TREEMENT outperforms the top baseline by 7% in terms of error reduction in criteria-level matching and achieves state-of-the-art results at the trial-level too. Furthermore, we show TREEMENT offers good interpretability to make the model results easier for adoption.'
date: 2023-01-10
venue: 'ACM BCB'
paperurl: 'http://academicpages.github.io/files/treement.pdf'
citation: 'B Theodorou, D Cao, J Sun. TREEMENT: Intepretable Patient-Trial Matching via Personalized Dynamic Tree-Based Memory Network.'
---
This paper proposes a novel tree-based memory network to label a patient’s eligibility for a given clinical trial based on the eligibility criteria and their structure electronic health record. The network uses granular attention to provide extremely specific interpretability as is necessary for real-world use on an extremely sensitive task

[Download paper here](http://academicpages.github.io/files/treement.pdf)

Recommended citation: B Theodorou, D Cao, J Sun. TREEMENT: Intepretable Patient-Trial Matching via Personalized Dynamic Tree-Based Memory Network.