---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024–Present
  * HKUST NLP Group; advisor: Prof. Junxian He
* B.Eng., Shanghai Jiao Tong University, 2020–2024 (graduated June 2024)

Research Experience
======
* February 2025 – Present: Research Intern, MINIMAX
* June 2024 – September 2024: Research Intern, Tencent WXG
  * Advisor: Zifei Shan
* June 2023 – December 2023: Research Intern, Shanghai AI Lab
  * Advisor: Prof. Yu Cheng

Research Interests
======
* Natural language processing and machine learning
* LLM reasoning and reinforcement learning
* Hallucination in vision-language models (VLMs)
* LLM truthfulness and interpretability

Honors and Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Publications
======
  <ul>{% assign cv_pubs = site.publications | sort: "order" %}{% for post in cv_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
