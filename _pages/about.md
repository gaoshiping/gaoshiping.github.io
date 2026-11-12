---
permalink: /
title: "Shiping Gao"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD student in Computer Science and Engineering at the University of Michigan, advised by Prof. Silviu Pitis. My research interests include natural language processing, large language models, RLHF, reward hacking, fine-grained reward modeling, and LLM reasoning. During my PhD, I want to understand how language models learn from imperfect feedback and how to make their reasoning more reliable.

Before joining UMich, I completed an MEng in Computer Science and Technology at Sun Yat-Sen University, advised by Prof. Xiaojun Quan, and a BEng in Computer Science and Technology at Lanzhou University.

Research Focus
======

I'm currently studying what happens when a language model receives feedback on just one aspect of an answer. For example, when feedback rewards a more accurate answer, does training also change how much the model writes or how confidently it responds? I'm testing ways to improve the quality that the feedback addresses while preserving other aspects of the model's behavior.

My work studies how language models learn from preferences and feedback, with an emphasis on reward modeling, policy optimization, and reasoning. Recent projects include prefix-value learning for distribution-level optimization, token-level reward models, advantage-guided distillation for preference alignment, and edit-wise preference optimization for grammatical error correction.

Education
======

- **University of Michigan**, PhD in Computer Science and Engineering, Sep 2026 - Jun 2030 (Expected)
- **Sun Yat-Sen University**, MEng in Computer Science and Technology, Sep 2023 - Jun 2026
- **Lanzhou University**, BEng in Computer Science and Technology, Sep 2019 - Jul 2023

Publications
======

Also on [Google Scholar](https://scholar.google.com/citations?user=o4WHYTsAAAAJ). Click a title for details and BibTeX.

<div class="pub-list">{% for post in site.publications reversed %}
  {% include publication-item.html %}
{% endfor %}</div>

Academic Service
======

- **Reviewer:** NeurIPS 2026, EMNLP 2026, Applied Intelligence (Springer)
- **Teaching Assistant:** Artificial Neural Networks and Mathematical Principles of Reinforcement Learning, Sun Yat-Sen University (2025)

CV
======

A PDF version of my CV is available [here](/files/CV-Shiping-Gao.pdf) (updated Nov 2026). The web version is on the [CV](/cv/) page.

Contact
======

I can be reached at [shiping@umich.edu](mailto:shiping@umich.edu) or [rungao2001@outlook.com](mailto:rungao2001@outlook.com).
