---
permalink: /
title: "Murong Ma | Code Agents, Data Curation, and XAI"
excerpt: "Computer Science Ph.D. student at NUS developing data and post-training methods for reliable code agents."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="simple-academic" markdown="1">

## About Me

I am a Computer Science Ph.D. student at the [National University of Singapore](https://www.comp.nus.edu.sg/), supervised by [Prof. Jin Song Dong](https://www.comp.nus.edu.sg/~dongjs/) and [Prof. Yun Lin](http://linyun.info/). I develop **data and post-training methods for reliable code agents** and am currently a research intern at Microsoft Research Asia (MSRA).

My work spans supervised fine-tuning trajectory construction and curation, reinforcement learning for software-engineering agents, and data-centric methods for accurate and trustworthy AI. I am currently open to research and industry opportunities.

## Research Interests

- **Code Agent Post-Training:** constructing and curating high-quality supervised fine-tuning trajectories and developing reinforcement-learning methods for code agents.
- **Data Curation:** selecting, refining, and evaluating training data and agent trajectories to improve model capability and reliability.
- **Explainable AI (XAI):** developing actionable explanations that help people understand model behavior and make informed decisions.

## Education

<div class="education-list">
  <div class="education-item">
    <div><strong>Ph.D. in Computer Science</strong><br>National University of Singapore</div>
    <time>Aug 2023 — Present</time>
  </div>
  <div class="education-item">
    <div><strong>M.S. in Computer Science</strong><br>National University of Singapore · Artificial Intelligence specialization</div>
    <time>2021 — 2023</time>
  </div>
  <div class="education-item">
    <div><strong>B.E. in Computer Science and Technology</strong><br>Beijing University of Posts and Telecommunications</div>
    <time>2016 — 2020</time>
  </div>
</div>

## Experience

<div class="experience-list">
  <article class="experience-item">
    <header>
      <div>
        <p class="experience-item__organization"><a href="https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/">Microsoft Research Asia</a></p>
        <h3>Research Intern</h3>
      </div>
      <time datetime="2026-07-26">26 July 2026 — Present</time>
    </header>
    <p class="experience-item__intro">Working with <a href="https://www.microsoft.com/en-us/research/people/yegong/">Dr. Yeyun Gong</a> on code-agent post-training across four workstreams:</p>
    <ul>
      <li><strong>Repository-level mid-training — collaborator:</strong> contributed to a pipeline that uses verified pull requests as training signals for repository-level code editing, including the data and evaluation work reported in our <a href="https://arxiv.org/abs/2602.07457">ICML 2026 paper</a>.</li>
      <li><strong>Process-supervised SFT trajectories — lead:</strong> led the trajectory-construction and curation work for <a href="https://arxiv.org/abs/2605.21996">P2T</a>, using golden patches as privileged process supervision to recover effective, efficient agent trajectories; improved Pass@1 on SWE-bench Verified by up to 10.8 points while reducing per-instance inference cost by approximately 15%.</li>
      <li><strong>Dense rewards for long-horizon agentic RL:</strong> developing an evidence-driven process reward model (PRM) that extracts and verifies task-relevant evidence from intermediate agent trajectories, providing process-level feedback to mitigate sparse terminal rewards.</li>
      <li><strong>Hard-trajectory bootstrapping for RL:</strong> extending P2T from SFT to reinforcement learning to construct valid training trajectories for difficult instances where successful single-pass rollouts remain rare even under repeated sampling.</li>
    </ul>
    <p class="experience-item__scope"><strong>Evaluation scope:</strong> SWE-bench, NL2Repo, and other benchmarks requiring long-horizon repository reasoning and complex code generation.</p>
  </article>

  <article class="experience-item">
    <header>
      <div>
        <p class="experience-item__organization">ShowLab · National University of Singapore</p>
        <h3>Research Assistant</h3>
      </div>
      <time>Aug 2021 — Sep 2022</time>
    </header>
    <ul>
      <li>Completed the M.S. thesis <a href="https://dl.comp.nus.edu.sg/bitstreams/4ccc07df-ed54-4af8-bf40-063694aeda83/download"><em>Subject-Adaptive Speech-Driven 3D Facial Animation</em></a>, focusing on 3D avatar generation and speech-driven animation.</li>
      <li>Built a high-resolution face video dataset—a 4K variant of VoxCeleb—for face generation, talking-head synthesis, and cross-modal research.</li>
      <li>Helped organize the <a href="https://ego4d-data.org/docs/challenge/">Ego4D Challenge 2022</a> as a point of contact for the <a href="https://eval.ai/web/challenges/challenge-page/1624/overview">Talking to Me Challenge</a>.</li>
    </ul>
  </article>

  <article class="experience-item">
    <header>
      <div>
        <p class="experience-item__organization">SMIIP Lab · Data Science Research Center · Duke Kunshan University</p>
        <h3>Research Intern</h3>
      </div>
      <time>Jun 2020 — Feb 2021<br>Jul 2019 — Sep 2019</time>
    </header>
    <ul>
      <li>Conducted research in speech recognition, bilingual query-by-example spoken-term detection, keyword spotting, and multimodal speech-driven facial animation.</li>
      <li>Helped organize the <a href="https://github.com/lenovo-voice/THE-2020-PERSONALIZED-VOICE-TRIGGER-CHALLENGE-BASELINE-SYSTEM">2020 Personalized Voice Trigger Challenge</a>; the team placed second in the Interspeech 2021 Auto-KWS Challenge.</li>
    </ul>
  </article>

</div>

## Publications

### Recent and Selected

1. [**From Patches to Trajectories: Privileged Process Supervision for Software-Engineering Agents**](https://arxiv.org/abs/2605.21996)<br>
   **Murong Ma**, Tianyu Chen, Yun Lin, Shuai Lu, Qinglin Zhu, Yeyun Gong, Zhiyong Huang, Peng Cheng, Yan Lu, and Jin Song Dong. *arXiv preprint arXiv:2605.21996*, 2026.

2. [**Pull Requests as a Training Signal for Repo-Level Code Editing**](https://arxiv.org/abs/2602.07457)<br>
   Qinglin Zhu, Tianyu Chen, Shuai Lu, Lei Ji, Runcong Zhao, **Murong Ma**, Xiangxiang Dai, Yulan He, Lin Gui, Peng Cheng, and Yeyun Gong. In *International Conference on Machine Learning (ICML)*, 2026.

3. [**TrainRef: Curating Data with Label Distribution and Minimal Reference for Accurate Prediction and Reliable Confidence**](https://openreview.net/forum?id=jSs8CDsF0A)<br>
   **Murong Ma**, Ruofan Liu, Yun Lin, Zhiyong Huang, and Jin Song Dong. In *The Fourteenth International Conference on Learning Representations (ICLR)*, 2026.

4. [**Few-Shot Precise Event Spotting via Unified Multi-Entity Graph and Distillation**](https://doi.org/10.1609/aaai.v40i9.37681)<br>
   Zhaoyu Liu, Kan Jiang, **Murong Ma**, Zhe Hou, Yun Lin, and Jin Song Dong. *Proceedings of the AAAI Conference on Artificial Intelligence*, 40(9):7422–7430, 2026.

5. [**F<sup>3</sup>Set: Towards Analyzing Fast, Frequent, and Fine-grained Events from Videos**](https://proceedings.iclr.cc/paper_files/paper/2025/hash/1c8e2cd11daf2d0a8c68663d504a841d-Abstract-Conference.html)<br>
   Zhaoyu Liu, Kan Jiang, **Murong Ma**, Zhe Hou, Yun Lin, and Jin Song Dong. In *International Conference on Learning Representations (ICLR)*, pp. 10566–10580, 2025.

6. [**Revisiting the Conflict-Resolving Problem from a Semantic Perspective**](https://doi.org/10.1145/3691620.3694993)<br>
   Jinhao Dong, Jun Sun, Yun Lin, Yedi Zhang, **Murong Ma**, Jin Song Dong, and Dan Hao. In *Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering (ASE)*, pp. 141–152, 2024.

### Earlier Work

1. [**Novel View Synthesis for High-fidelity Headshot Scenes**](https://arxiv.org/abs/2205.15595)<br>
   Satoshi Tsutsui, Weijia Mao, Sijing Lin, Yunyi Zhu, **Murong Ma**, and Mike Zheng Shou. *arXiv preprint arXiv:2205.15595*, 2022.

2. [**Acoustic Word Embedding System for Code-Switching Query-by-Example Spoken Term Detection**](https://doi.org/10.1109/ISCSLP49672.2021.9362056)<br>
   **Murong Ma**, Haiwei Wu, Xuyang Wang, Lin Yang, Junjie Wang, and Ming Li. In *2021 12th International Symposium on Chinese Spoken Language Processing (ISCSLP)*, pp. 1–5, 2021.

3. [**The DKU System Description for the Interspeech 2021 Auto-KWS Challenge**](https://arxiv.org/abs/2104.04993)<br>
   Yechen Wang, Yan Jia, **Murong Ma**, Zexin Cai, and Ming Li. *arXiv preprint arXiv:2104.04993*, 2021.

4. [**Training Wake Word Detection with Synthesized Speech Data on Confusion Words**](https://arxiv.org/abs/2011.01460)<br>
   Yan Jia, Zexin Cai, **Murong Ma**, Zeqing Zhao, Xuyang Wang, Junjie Wang, and Ming Li. *arXiv preprint arXiv:2011.01460*, 2020.

## Technical Expertise

<div class="technical-stack">
  <div class="technical-stack__row">
    <h3>Code-Agent Post-Training</h3>
    <p>Supervised fine-tuning (SFT), trajectory generation and filtering, process-supervised data curation, and agentic reinforcement learning</p>
  </div>
  <div class="technical-stack__row">
    <h3>Training & RL Infrastructure</h3>
    <p>PyTorch, slime, Megatron-LM</p>
  </div>
  <div class="technical-stack__row">
    <h3>Inference & Rollouts</h3>
    <p>vLLM, SGLang, high-throughput model serving, and rollout generation</p>
  </div>
  <div class="technical-stack__row">
    <h3>Evaluation & Verification</h3>
    <p>SWE-bench Verified and Lite, NL2Repo, repository-level code editing, test-based verification, Pass@1, and inference-cost analysis</p>
  </div>
  <div class="technical-stack__row">
    <h3>Programming & Systems</h3>
    <p>Python, C++, C, Linux, Git</p>
  </div>
</div>

## Selected Honors

- NUS Research Scholarship
- Excellent Bachelor Thesis, Beijing University of Posts and Telecommunications (top 10 among 630 students)
- Second-Class Scholarship (top 30 among 320 students)

## Open to Opportunities

<div class="opportunity-note" markdown="1">
I am interested in **Research Scientist, Applied Scientist, and Research Engineer** opportunities related to code agents, LLM post-training, data curation, and trustworthy AI. For opportunities or research collaborations, please [email me](mailto:murongma@u.nus.edu) or view my [CV](/cv/).
</div>

</div>
