---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Contact
======

- Email: [shiping@umich.edu](mailto:shiping@umich.edu), [rungao2001@outlook.com](mailto:rungao2001@outlook.com)
- Research interests: NLP, LLMs, RLHF, reward hacking, fine-grained reward modeling, and LLM reasoning

Education
======

- **University of Michigan**, Ann Arbor, MI, USA<br>
  PhD student in Computer Science and Engineering, advised by Prof. Silviu Pitis<br>
  Aug 2026 - Jun 2030 (Expected)

- **Sun Yat-Sen University**, Guangzhou, China<br>
  MPhil in Computer Science and Technology, GPA: 89.84/100<br>
  Sep 2023 - Jun 2026

- **Lanzhou University**, Lanzhou, China<br>
  BEng in Computer Science and Technology, GPA: 90.17/100, ranking: 8/232 (top 3.5%)<br>
  Sep 2019 - Jul 2023

Honors
======

- Outstanding Graduate and Outstanding Graduation Thesis, 2023 (top 10%)
- Hui-Chun Chin & Tsung-Dao Lee Undergraduate Endowment (CURE), 2022
- First Prize Scholarship, 2021 (top 5%)

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Research Experience
======

**Unleashing Implicit Rewards: Prefix-Value Learning for Distribution-Level Optimization**<br>
Internship, University of California, Davis; supervised by Prof. Lifu Huang<br>
Jul 2025 - Dec 2025

- Developed IPVRM, a prefix-level implicit reward model with value-function-style supervision on every prefix.
- Integrated distribution-level temporal-difference advantages into reinforcement learning for dense credit assignment.

**Discriminative Policy Optimization for Token-Level Reward Models**<br>
Research team member, Sun Yat-Sen University; supervised by Prof. Xiaojun Quan<br>
Oct 2024 - Jan 2025

- Designed Q-RM, a token-level reward model that learns without fine-grained annotations.
- Integrated Q-RM into PPO and REINFORCE and improved reasoning-task performance and convergence.

**Advantage-Guided Distillation for Preference Alignment in Small Language Models**<br>
Principal investigator, Sun Yat-Sen University; supervised by Prof. Xiaojun Quan<br>
Jul 2024 - Oct 2024

- Designed DCKD, ADPA, and ADPA+ for transferring preference-alignment knowledge to small language models.
- Improved alignment on MT-Bench, AlpacaEval, and the Open LLM Leaderboard with reduced sample complexity.

**Edit-Wise Preference Optimization for Grammatical Error Correction**<br>
Research team member, Sun Yat-Sen University; supervised by Prof. Xiaojun Quan<br>
Jul 2024 - Sep 2024

- Proposed EPO, emphasizing edit spans and pivot tokens for grammatical error correction.
- Developed annotation-free preference data construction using negative sentences with large edit distances.

**Chinese Text Correction System Based on Deep Learning**<br>
Outstanding undergraduate thesis, Lanzhou University; supervised by Prof. Binbin Yong<br>
Dec 2022 - May 2023

- Designed a Chinese text correction system covering spelling, grammar, and semantic errors.
- Proposed AutoCscError for realistic pseudo-data generation and augmentation.

**A Novel Dynamic Interpolation Method Based on Temporal and Spatial Correlations**<br>
Research team member, Lanzhou University; supervised by Prof. Zhili Zhao<br>
May 2021 - Oct 2021

- Proposed a dynamic spatiotemporal interpolation method for environmental and meteorological monitoring.

Teaching
======

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Technical Skills
======

- **Languages:** Python, C++, Java, Bash, LaTeX, SQL
- **Frameworks and libraries:** Transformers, Ray, VeRL, LLaMA-Factory, Datasets, Accelerate, DeepSpeed, vLLM
- **Tools and platforms:** Git, Docker, Weights & Biases, SwanLab, TensorBoard, Slurm, CUDA
