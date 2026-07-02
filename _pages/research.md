---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research centers on preference alignment, reward modeling, reinforcement learning from feedback, and reasoning in large language models.

Unleashing Implicit Rewards: Prefix-Value Learning for Distribution-Level Optimization
======

**Internship, University of California, Davis**  
Supervised by Prof. Lifu Huang  
Jul 2025 - Dec 2025

- Developed an Implicit Prefix-Value Reward Model (IPVRM) with value-function-style supervision on every prefix, reducing the training-inference inconsistency of prior implicit process reward models.
- Preserved the efficiency of implicit reward models while improving erroneous-step detection on math reasoning tasks, enabling a 0.6B model to reach performance comparable to 7B process reward models.
- Incorporated distribution-level temporal-difference advantages into reinforcement learning for dense credit assignment over unsampled tokens.

Discriminative Policy Optimization for Token-Level Reward Models
======

**Research Team Member, Sun Yat-Sen University**  
Supervised by Prof. Xiaojun Quan  
Oct 2024 - Jan 2025

- Designed Q-RM, a token-level reward model that learns without fine-grained annotations by decoupling reward modeling from language modeling through a discriminative policy.
- Derived a token-level Q-function from a discriminative perspective and integrated Q-RM into PPO and REINFORCE.
- Improved Pass@1 by 4-6 points on GSM8K and MATH, with substantially faster convergence than outcome and step-level reward model baselines.

Advantage-Guided Distillation for Preference Alignment in Small Language Models
======

**Principal Investigator, Sun Yat-Sen University**  
Supervised by Prof. Xiaojun Quan  
Jul 2024 - Oct 2024

- Designed Dual-Constrained Knowledge Distillation (DCKD), applying KL constraints to both preferred and dispreferred responses.
- Introduced Advantage-Guided Distillation for Preference Alignment (ADPA), using log-probability margins between aligned and unaligned teacher LLMs as distribution-level preference signals.
- Developed ADPA+, combining DCKD initialization with ADPA for improved training stability and alignment performance.

Edit-Wise Preference Optimization for Grammatical Error Correction
======

**Research Team Member, Sun Yat-Sen University**  
Supervised by Prof. Xiaojun Quan  
Jul 2024 - Sep 2024

- Proposed Edit-Wise Preference Optimization (EPO), emphasizing edit spans and pivot tokens to guide grammatical corrections and reduce error accumulation.
- Built an annotation-free preference data construction method using negative samples with large edit distances.
- Achieved strong single-model performance on English and Chinese grammatical error correction benchmarks while mitigating overcorrection.

Chinese Text Correction System Based on Deep Learning
======

**Outstanding Undergraduate Thesis, Lanzhou University**  
Supervised by Prof. Binbin Yong  
Dec 2022 - May 2023

- Designed a Chinese text correction system covering spelling, grammar, and semantic errors.
- Proposed AutoCscError, a pseudo-data generation and augmentation method that predicts likely human spelling errors using shape and phonetic similarity enhanced by IDS encoding.
- Improved zero-shot and fine-tuned performance across multiple benchmarks by producing more realistic pseudo-data.

A Novel Dynamic Interpolation Method Based on Temporal and Spatial Correlations
======

**Research Team Member, Lanzhou University**  
Supervised by Prof. Zhili Zhao  
May 2021 - Oct 2021

- Proposed a dynamic spatiotemporal interpolation method for environmental and meteorological monitoring.
- Adaptively weighted temporal and spatial correlations to improve missing-data recovery.
