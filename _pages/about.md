---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me

I am a PhD candidate in Electrical and Computer Engineering at Northeastern University, advised by [Prof. Mahdi Imani](https://coe.northeastern.edu/people/imani-mahdi/). Before that, I completed my MSc in Electrical Engineering (Control) at [Sharif University of Technology](https://ee.sharif.edu/en/) under [Prof. Mohammad Saleh Tavazoei](https://sharif.edu/~tavazoei/).

I work on **reinforcement learning** and **stochastic control** for sequential decision-making under uncertainty, partial observability, and adversarial dynamics. My research combines classical control theory with modern deep RL to design policies with formal guarantees — equilibrium, contraction, exploitability — and validates them across three application domains: **cybersecurity** (network defense), **autonomous systems** (multi-agent traffic), and **computational biology** (gene regulatory network intervention). My current focus is **contextual representation learning** for robust RL under latent uncertainty.

# Publications

<ol>

<li><strong>Robust Contextual Reinforcement Learning under Partial Observability and Latent Uncertainty</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<em>Manuscript in preparation</em>, 2026.
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Develops a Transformer-based information-state embedding trained with a Soft-InfoNCE contrastive objective for robust RL under latent context uncertainty. Provides formal exploitability bounds quantifying the suboptimality of surrogate beliefs versus exact Bayesian beliefs.</em></p></details>
</li>

<li><strong>Belief-Based Reinforcement Learning for Asymmetric Partially Observable Zero-Sum Games</strong><br>
Seyed Hamid Hosseini, Armita Kazeminajafabadi, Amidu Kamara, Mahdi Imani<br>
<strong>(ACC-2026)</strong> American Control Conference. <a href="https://www.researchgate.net/profile/Seyed-Hamid-Hosseini/publication/401827974_Belief-Based_Reinforcement_Learning_for_Asymmetric_Partially_Observable_Zero-Sum_Games/links/69b20b39a5bf176ab54e8a0f/Belief-Based-Reinforcement-Learning-for-Asymmetric-Partially-Observable-Zero-Sum-Games.pdf">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Proves that local Bayesian beliefs are sufficient statistics for Nash play in asymmetric partially observable zero-sum games, and proposes a belief-conditioned actor–critic algorithm (CTDE). Validated on a 10-node network defense benchmark, where it approaches the full-information Nash bound under up to 50% miss-detection.</em></p></details>
</li>

<li><strong>Decentralized Reinforcement Learning for Asymmetric Gene Network Interventions</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<strong>IEEE/ACM Transactions on Computational Biology and Bioinformatics</strong>, 2025. <a href="https://ieeexplore.ieee.org/abstract/document/11250698">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Frames gene regulatory network intervention as an asymmetric two-player zero-sum game and develops a decentralized deep policy-gradient algorithm with provable robustness guarantees against the most adversarial cellular responses.</em></p></details>
</li>

<li><strong>Deep Reinforcement Learning for Intervention of Partially Observable Regulatory Networks</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<strong>(ACC-2025)</strong> American Control Conference — ★ <strong>Best Student Paper Award Finalist (1 of 6 finalists at ACC 2025)</strong>. <a href="https://ieeexplore.ieee.org/abstract/document/11107606/">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Designs a belief-state deep Q-network for sequential intervention in partially observable Boolean regulatory networks, with a proof of convergence to the dynamic-programming optimum as observation noise vanishes.</em></p></details>
</li>

<li><strong>Pareto-Optimal Interventions in Gene Regulatory Networks using Signal Temporal Logic</strong><br>
Seyed Hamid Hosseini, Derya Aksaray, Mahdi Imani<br>
<strong>(ACC-2025)</strong> American Control Conference. <a href="https://ieeexplore.ieee.org/abstract/document/11108118">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Uses Signal Temporal Logic to formalize multi-objective trade-offs in therapeutic intervention — worst-case efficacy, response time, intervention frequency, and long-term stability — and produces Pareto-optimal policy sets for downstream selection.</em></p></details>
</li>

<li><strong>Modeling Defensive Response of Cells to Therapies: Equilibrium Interventions for Regulatory Networks</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<strong>IEEE/ACM Transactions on Computational Biology and Bioinformatics</strong>, 2024. <a href="https://ieeexplore.ieee.org/abstract/document/10487852/">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Models cancer therapy as a two-player zero-sum game between the intervention and the cell's adaptive defensive response, and computes stochastic Nash-equilibrium intervention policies that outperform standard approaches on p53–MDM2 and melanoma networks.</em></p></details>
</li>

<li><strong>Dynamic Intervention in Gene Regulatory Networks: A Partially Observed Zero-Sum Markov Game</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<strong>(CCTA-2024)</strong> IEEE Conference on Control Technology and Applications. <a href="https://ieeexplore.ieee.org/abstract/document/10666558/">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Extends the zero-sum game framework to partial state observability via gene-expression measurements, combining MMSE state estimation with full-state Nash policies.</em></p></details>
</li>

<li><strong>An Optimal Bayesian Intervention Policy in Response to Unknown Dynamic Cell Stimuli</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<strong>Information Sciences</strong>, 2024. <a href="https://www.sciencedirect.com/science/article/pii/S0020025524003530">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Develops a Bayesian intervention policy that tracks the posterior over unknown cell responses and acts against a set of Nash policies, with empirical convergence to the optimal Nash policy on benchmark networks.</em></p></details>
</li>

<li><strong>Privacy-Preserved Federated Reinforcement Learning for Autonomy in Signalized Intersections</strong><br>
Negar Asadi, Seyed Hamid Hosseini, Mahdi Imani, Daniel P. Aldrich, Seyede Fatemeh Ghoreishi<br>
<strong>(ICTD-2024)</strong> ASCE International Conference on Transportation and Development. <a href="https://ascelibrary.org/doi/abs/10.1061/9780784485514.035">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Proposes a federated RL framework enabling connected autonomous vehicles to share intersection-driving knowledge across heterogeneous environments without revealing private data.</em></p></details>
</li>

<li><strong>Agent-based Time-Delay Margin in Consensus of Multi-Agent Systems by an Event-Triggered Control Method: Concept and Computation</strong><br>
Seyed Hamid Hosseini, Mohammad Saleh Tavazoei, Nikolay V. Kuznetsov<br>
<strong>Asian Journal of Control</strong>, 2023. <a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/asjc.2814">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Defines a per-agent notion of time-delay margin for event-triggered multi-agent consensus, proves Zeno-free behavior, and provides an algorithm for computing each agent's delay tolerance.</em></p></details>
</li>

<li><strong>Learning to Fight Against Cell Stimuli: A Game-Theoretic Perspective</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<strong>(CAI-2023)</strong> IEEE Conference on Artificial Intelligence. <a href="https://ieeexplore.ieee.org/abstract/document/10194997/">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Argues — analytically and via melanoma-network experiments — that ignoring the cell's adaptive response to therapy explains why current genomic interventions become ineffective over time.</em></p></details>
</li>

</ol>

# Awards and honors

**Finalist, Best Student Paper Award (1 of 6)** — American Control Conference (ACC), 2025.  
**Student Organization Leader of the Year** — Northeastern University, 2026.
