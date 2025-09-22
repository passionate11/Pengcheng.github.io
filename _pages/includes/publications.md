# 📝 Publications 

> You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=VA9mUOsAAAAJ). \* marks the corresponding author.

<!-- PamramMute_nips -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/paper/parammute_nips25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# ParamMute: Suppressing Knowledge-Critical FFNs for Faithful Retrieval-Augmented Generation

`Pengcheng Huang`, Zhenghao Liu*, Yukun Yan, Xiaoyuan Yi, Hao Chen, Zhiyuan Liu, Maosong Sun, Tong Xiao, Ge Yu, Chenyan Xiong

[**📄PDF**](https://arxiv.org/pdf/2502.15543)

- This work presents ParamMute, a novel framework for enhancing the faithfulness of Retrieval-Augmented Generation. By identifying and suppressing unfaithfulness-associated feed-forward networks (FFNs), and incorporating a knowledge preference adaptation module, ParamMute effectively steers language models to better leverage retrieved evidence, paving the way for more reliable and trustworthy RAG systems.
</div>
</div>

<!-- rag_survey -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AI Open 2025</div><img src='images/paper/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Knowledge Intensive Agents

Zhenghao Liu*, `Pengcheng Huang`, Zhipeng Xu, Xinze Li, Shuliang Liu, Chunyi Peng, Haidong Xin, Yukun Yan, Shuo Wang, Xu Han, Zhiyuan Liu, Maosong Sun, Yu Gu, Ge Yu

[**📄PDF**](https://papers.ssrn.com/sol3/Delivery.cfm/81afde5f-fbd1-4635-b582-7ac104b3322a-MECA.pdf?abstractid=5459034&mirid=1)

- This work provides a comprehensive overview of Retrieval-Augmented Generation from an agentic perspective, categorizing knowledge-intensive agents into acquisition and utilization roles, and highlighting future directions for joint optimization in multi-agent RAG systems.
</div>
</div>


<!-- PC_sampler_aaai -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='images/paper/Pc_sampler_aaai26.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Pc-sampler: Position-aware calibration of decoding bias in masked diffusion models

`Pengcheng Huang`, Shuhao Liu, Zhenghao Liu*, Yukun Yan, Shuo Wang, Zulong Chen, Tong Xiao

[**📄PDF**](https://arxiv.org/abs/2508.13021)

- This work discovered that mainstream uncertainty‑based decoding in Masked Diffusion Models suffers from both a lack of global trajectory control and a strong early bias toward trivial tokens, and PC‑Sampler remedies this by using a position‑aware pathway planner together with a confidence calibration mechanism to boost informativeness, delivering over 10% gains on average while significantly narrowing the performance gap with autoregressive models.
</div>
</div>

<!-- Expandr_EMNLP_oral -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Oral</div><img src='images/paper/expandr_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# ExpandR: Teaching Dense Retrievers Beyond Queries with LLM Guidance

Sijia Yao, `Pengcheng Huang`, Zhenghao Liu*, Yu Gu, Yukun Yan, Shi Yu, Ge Yu


[**📄PDF**](https://arxiv.org/abs/2502.17057)

- This work introduces ExpandR, a unified framework that jointly trains a large language model (LLM) and a dense retriever by having the LLM generate rich query expansions and optimizing both expansion generation (via Direct Preference Optimization with combined rewards for retrieval utility and consistency) and retriever ranking performance at the same time, resulting in >5% boost over strong baselines on retrieval benchmarks.
</div>
</div>


<!-- ClueAnchor_EMNLP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/paper/clueanchor_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# ClueAnchor: Clue-Anchored Knowledge Reasoning Exploration and Optimization for Retrieval-Augmented Generation

Hao Chen, Yukun Yan, Sen Mei, Wanxiang Che, Zhenghao Liu, Qi Shi, Xinze Li, Yuchun Fan, `Pengcheng Huang`, Qiushi Xiong, Zhiyuan Liu, Maosong Sun

[**📄PDF**](https://arxiv.org/abs/2505.24388)

- This work discovered that RAG systems often under‐utilize retrieved documents because critical evidence (“clues”) is implicit, dispersed, or obscured by noise, and ClueAnchor addresses this by first extracting key clues from the retrieved content, generating multiple reasoning paths under different knowledge configurations (internal, external, and clue‑anchored), and then using reward‑based preference optimization to select the most effective path — yielding much better reasoning completeness and robustness.
</div>
</div>


<!-- positionid_EMNLP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/paper/position_id_emnlp25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Position IDs Matter: An Enhanced Position Layout for Efficient Context Compression in Large Language Models

Runsong Zhao, Xin Liu, Xinyu Liu, `Pengcheng Huang`, Chunyang Xiao, Tong Xiao*, Jingbo Zhu

[**📄PDF**](https://arxiv.org/abs/2409.14364)

- This work identifies that existing LLM context‑compression methods like ICAE suffer from suboptimal position identifier layouts for compressed tokens and that the auto‑encoding loss alone insufficiently promotes memorization; it then proposes spreading position identifiers uniformly across input and introducing a “compression loss” focused purely on memorization, enabling much higher compression ratios (up to ~15× vs 4×) while retaining reconstruction and downstream performance.
</div>
</div>

<!-- Forgetting_curve_EMNLP -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/paper/forget_emnlp24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Forgetting curve: A reliable method for evaluating memorization capability for long-context models

Xinyu Liu, Runsong Zhao, `Pengcheng Huang`, Chunyang Xiao, Bei Li, Jingang Wang, Tong Xiao*, Jingbo Zhu

[**📄PDF**](https://arxiv.org/abs/2410.04727)

- This work discovered that existing methods for measuring memorization in long‑context models (e.g. via perplexity or “needle in a haystack” tasks) are unreliable—being overly sensitive to prompts, corpora, or downstream tasks—and proposes the Forgetting Curve, a prompt‑free, robust metric based on comparing copy accuracy vs. LM accuracy over prefixes to more faithfully capture a model’s memory over long contexts, revealing that many claimed context extension techniques may not truly improve memorization for very long inputs.
</div>
</div>


<!-- TAR_CCL -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCL 2025</div><img src='images/paper/tar_ccl24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

# Translate-and-Revise: Boosting Large Language Models for Constrained Translation

`Pengcheng Huang`, Yongyu Mu, Yuzhang Wu, Bei Li, Chunyang Xiao, Tong Xiao*, Jingbo Zhu

[**📄PDF**](https://aclanthology.org/2024.ccl-1.82/)

- This work discovers that large language models (LLMs) prompted for constrained translation often ignore or violate specified lexical or structural constraints—partly because they’re overly confident and let their own fluency priorities override constraint satisfaction—and Translate‑and‑Revise remedies this by adding a revision process that prompts the model to identify unmet constraints and correct its output, yielding ~15% improvement in constraint translation accuracy and surpassing NMT baselines.
</div>
</div>