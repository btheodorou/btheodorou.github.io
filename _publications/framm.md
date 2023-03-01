---
title: "FRAMM: Fair Ranking With Missing Modalities for Clinical Trial Site Selection"
collection: publications
permalink: /publication/framm
excerpt: 'Despite many efforts to address the disparities, the underrepresentation of gender, racial, and ethnic minorities in clinical trials remains a problem and undermines the efficacy of treatments on minorities. This paper focuses on the trial site selection task and proposes FRAMM, a deep reinforcement learning framework for fair trial site selection. We focus on addressing two real world challenges that affect fair trial sites selection: the data modalities are often not complete for many potential trial sites, and the site selection needs to simultaneously optimize for both enrollment and diversity since the problem is necessarily a trade-off between the two with the only possible way to increase diversity post-selection being through limiting enrollment via caps. To address the missing data challenge, FRAMM has a modality encoder with a masked cross-attention mechanism for handling missing data, bypassing data imputation and the need for complete data in training. To handle the need for making efficient trade-offs, FRAMM uses deep reinforcement learning with a specifically designed reward function that simultaneously optimizes for both enrollment and fairness. 

We evaluate FRAMM using 4,392 real-world  clinical trials ranging from 2016 to 2021 and show that FRAMM outperforms the leading baseline in enrollment-only settings while also achieving large gains in diversity. Specifically, it is able to produce a 9% improvement in diversity with similar enrollment levels over the leading baselines. That improved diversity is further manifested in achieving up to a 14% increase in Hispanic enrollment, 27% increase in Black enrollment, and 60% increase in Asian enrollment compared to selecting sites with an enrollment-only model.'
date: 2023-01-10
venue: 'Under Review at IJCAI 23'
paperurl: 'http://academicpages.github.io/files/framm.pdf'
citation: 'B Theodorou, D Cao, J Sun. FRAMM: Fair Ranking With Missing Modalities for Clinical Trial Site Selection.'
---
This paper proposes a RL ranking framework and model architecture to select a subset of sites from a proposed list with possibly missing modalities in order to simultaneously maximize both enrollment and diversity.

[Download paper here](http://academicpages.github.io/files/framm.pdf)

Recommended citation: B Theodorou, D Cao, J Sun. FRAMM: Fair Ranking With Missing Modalities for Clinical Trial Site Selection.