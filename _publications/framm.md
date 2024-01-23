---
title: "FRAMM: Fair Ranking With Missing Modalities for Clinical Trial Site Selection"
collection: publications
permalink: /publication/framm
excerpt: 'The underrepresentation of gender, racial, and ethnic minorities in clinical trials is a problem undermining the efficacy of treatments on minorities and preventing precise estimates of the effects within these subgroups. 
We propose FRAMM, a deep reinforcement learning framework for fair trial site selection to help address this problem. We focus on two real-world challenges: the data modalities used to guide selection are often incomplete for many potential trial sites, and the site selection needs to simultaneously optimize for both enrollment and diversity.
To address the missing data challenge, FRAMM has a modality encoder with a masked cross-attention mechanism for bypassing missing data. To make efficient trade-offs, FRAMM uses deep reinforcement learning with a reward function designed to simultaneously optimize for both enrollment and fairness. 
We evaluate FRAMM using real-world historical clinical trials and show that it outperforms the leading baseline in enrollment-only settings while also greatly improving diversity. 
Specifically, it is able to produce a 9% improvement in diversity with similar enrollment levels over the leading baselines. That improved diversity is further manifested in achieving up to a 14% increase in Hispanic enrollment, 27% increase in Black enrollment, and 60% increase in Asian enrollment compared to selecting sites with an enrollment-only model.'
date: 2023-01-10
venue: 'Under Review at Patterns'
paperurl: 'http://academicpages.github.io/files/framm.pdf'
citation: 'B Theodorou, D Cao, J Sun. FRAMM: Fair Ranking With Missing Modalities for Clinical Trial Site Selection.'
---
This paper proposes a RL ranking framework and model architecture to select a subset of sites from a proposed list with possibly missing modalities in order to simultaneously maximize both enrollment and diversity.

[Download paper here](http://academicpages.github.io/files/framm.pdf)

Recommended citation: B Theodorou, D Cao, J Sun. FRAMM: Fair Ranking With Missing Modalities for Clinical Trial Site Selection.