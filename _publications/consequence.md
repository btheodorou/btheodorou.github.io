---
title: "ConSequence: Synthesizing Logically Constrained Sequences for Electronic Health Record Generation"
collection: publications
permalink: /publication/consequence
excerpt: 'Generative models can produce synthetic patient records for analytical tasks when real data is unavailable or limited. However, current methods struggle with adhering to domain-specific knowledge and removing invalid data. We present ConSequence, an effective approach to integrating domain knowledge into sequential generative neural network outputs. Our rule-based formulation includes temporal aggregation and antecedent evaluation modules, ensured by an efficient matrix multiplication formulation, to satisfy hard and soft logical constraints across time steps. Existing constraint methods often fail to guarantee constraint satisfaction, lack the ability to handle temporal constraints, and hinder the learning and computational efficiency of the model. In contrast, our approach efficiently handles all types of constraints with guaranteed logical coherence. We demonstrate ConSequence's effectiveness in generating electronic health records, outperforming competitors in achieving complete temporal and spatial constraint satisfaction without compromising runtime performance or generative quality. Specifically, ConSequence successfully prevents all rule violations while improving the model quality in reducing its test perplexity by 5% and incurring less than a 13% slowdown in generation speed compared to an unconstrained model.'
date: 2024-02-24
venue: 'AAAI 24'
paperurl: 'https://arxiv.org/abs/2312.05964'
citation: 'B Theodorou, S Jain, C Xiao, J Sun. ConSequence: Synthesizing Logically Constrained Sequences for Electronic Health Record Generation.'
---
This paper proposes a logical constraint enforcement method which prevents rule violations in generated outputs while efficiently handling both static and temporal constraints.

[Download paper here](https://arxiv.org/abs/2312.05964)

Recommended citation: B Theodorou, S Jain, C Xiao, J Sun. ConSequence: Synthesizing Logically Constrained Sequences for Electronic Health Record Generation. 