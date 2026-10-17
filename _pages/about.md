---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me

I recently defended my PhD in Electrical and Computer Engineering at Northeastern University, advised by [Prof. Mahdi Imani](https://coe.northeastern.edu/people/imani-mahdi/), and will receive the degree in December 2026. Before that, I completed my MSc in Electrical Engineering (Control) at [Sharif University of Technology](https://ee.sharif.edu/en/) under [Prof. Mohammad Saleh Tavazoei](https://sharif.edu/~tavazoei/), where I also earned my BSc in Electrical Engineering.

I work on **reinforcement learning** for sequential decision-making under uncertainty, partial observability, and adversarial dynamics. I develop belief-state and contextual RL methods, including actor-critic and policy-gradient algorithms with centralized training and decentralized execution (CTDE), deep Q-networks over belief spaces, Bayes-adaptive RL with unknown structure, and Transformer-based contrastive representation learning, grounded in **partially observable stochastic games** with formal **Nash-equilibrium**, contraction, and exploitability guarantees. I validate these methods across **cybersecurity**, **autonomous systems**, **computational biology**, and **protein engineering**.

In fall 2026, I am a Research Intern at [Manus Bio](https://www.manus.bio), where I develop offline reinforcement learning for protein engineering: framing directed evolution as sequential decision-making over sequence space, and combining experimental measurements with protein language model (ESM-2) scores to propose experimental candidates.

# Selected Publications

<ol>

<li><strong>Exploitability Bounds for Learned Information States in Zero-Sum Games with Latent Context</strong><br>
Seyed Hamid Hosseini, Seyede Fatemeh Ghoreishi, Mohsen Imani, Mahdi Imani<br>
<em>AAAI Conference on Artificial Intelligence</em>, 2027 (under review).<br>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline"> Summary</summary><p style="margin-top:0.5em"><em>Studies zero-sum partially observable stochastic games in which a latent context, hidden from the defender, shapes the dynamics, sensing, reward, and the adversary's admissible responses. Shows that defending against an oracle adversary suffices, and bounds the exploitability of a defense built on a learned history representation by its one-step reward and prediction errors, with matching lower bounds. A robust-Bellman pseudometric over contexts guides contrastive training of a nested Transformer-recurrent context-state encoder, evaluated on four benchmarks including the CAGE-2 cyber-defense simulator.</em></p></details>
</li>

<li><strong>Exploitability Bound for Belief-Based Defenses in Partially Observable Zero-Sum Games with Latent Objectives</strong><br>
Seyed Hamid Hosseini, Seyede Fatemeh Ghoreishi, Mohsen Imani, Mahdi Imani<br>
<em>International Conference on Autonomous Agents and Multiagent Systems (AAMAS)</em>, 2027 (under review).<br>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline"> Summary</summary><p style="margin-top:0.5em"><em>Studies zero-sum partially observable stochastic games in which the adversary's reward is drawn per episode from a finite set of models, known to the adversary and hidden from the defender. Shows that the joint posterior over state and reward model is the defender's exact information state, and bounds the exploitability of a defense that filters with a single learned adversary model by its filter and policy errors, with a matching lower bound. The likelihood model, defender, and centralized critic are trained jointly; on a Bayesian attack graph and a pursuit-evasion game, the learned defense is the least exploitable deployable defender.</em></p></details>
</li>

<li><strong>Bayes-Adaptive Reinforcement Learning in Binary Factored MDPs with Unknown Structure</strong><br>
Seyed Hamid Hosseini, Fatemeh Zarei, Bahram Shafai, Mahdi Imani<br>
<em>65th IEEE Conference on Decision and Control (CDC)</em>, 2026.<br> <a href="https://www.researchgate.net/profile/Seyed-Hamid-Hosseini/publication/412084881_Bayes-Adaptive_Reinforcement_Learning_in_Binary_Factored_MDPs_with_Unknown_Structure/links/6a7a20a27b52ad375d60d9d5/Bayes-Adaptive-Reinforcement-Learning-in-Binary-Factored-MDPs-with-Unknown-Structure.pdf">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Bayes-adaptive RL for binary factored MDPs learning structure and transition probabilities online. Beta-Bernoulli conjugacy gives closed-form posterior updates, no sampling. The intractable Bayesian information state is compressed to state, structure beliefs, and predictive probabilities, proven sufficient for one-step prediction and bounded against Bayes-optimal. A DQN acts on the compressed space.</em></p></details>
</li>

<li><strong>Belief-Based Reinforcement Learning for Asymmetric Partially Observable Zero-Sum Games</strong><br>
Seyed Hamid Hosseini, Armita Kazeminajafabadi, Amidu Kamara, Mahdi Imani<br>
<em>American Control Conference</em>, 2026.<br> <a href="https://www.researchgate.net/profile/Seyed-Hamid-Hosseini/publication/401827974_Belief-Based_Reinforcement_Learning_for_Asymmetric_Partially_Observable_Zero-Sum_Games/links/69b20b39a5bf176ab54e8a0f/Belief-Based-Reinforcement-Learning-for-Asymmetric-Partially-Observable-Zero-Sum-Games.pdf">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Proves that local Bayesian beliefs are sufficient statistics for Nash play in asymmetric partially observable zero-sum games, and proposes a belief-conditioned actor-critic algorithm (CTDE). Validated on a 10-node network defense benchmark, where it approaches the full-information Nash bound under up to 50% miss-detection.</em></p></details>
</li>

<li><strong>Decentralized Reinforcement Learning for Asymmetric Gene Network Interventions</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<em>IEEE/ACM Transactions on Computational Biology and Bioinformatics</em>, 2025.<br> <a href="https://ieeexplore.ieee.org/abstract/document/11250698">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Frames gene regulatory network intervention as an asymmetric two-player zero-sum game and develops a decentralized deep policy-gradient algorithm with provable robustness guarantees against the most adversarial cellular responses.</em></p></details>
</li>

<li><strong>Deep Reinforcement Learning for Intervention of Partially Observable Regulatory Networks</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<em>American Control Conference</em>, 2025, ★ <strong>Best Student Paper Award Finalist</strong>.<br><a href="https://ieeexplore.ieee.org/abstract/document/11107606/">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Designs a belief-state deep Q-network for sequential intervention in partially observable Boolean regulatory networks, with a proof of convergence to the dynamic-programming optimum as observation noise vanishes.</em></p></details>
</li>

<li><strong>An Optimal Bayesian Intervention Policy in Response to Unknown Dynamic Cell Stimuli</strong><br>
Seyed Hamid Hosseini, Mahdi Imani<br>
<em>Information Sciences</em>, 2024.<br> <a href="https://www.sciencedirect.com/science/article/pii/S0020025524003530">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Develops a Bayesian intervention policy that tracks the posterior over unknown cell responses and acts against a set of Nash policies, with empirical convergence to the optimal Nash policy on benchmark networks.</em></p></details>
</li>

<li><strong>Privacy-Preserved Federated Reinforcement Learning for Autonomy in Signalized Intersections</strong><br>
Negar Asadi, Seyed Hamid Hosseini, Mahdi Imani, Daniel P. Aldrich, Seyede Fatemeh Ghoreishi<br>
<em>ASCE International Conference on Transportation and Development</em>, 2024.<br> <a href="https://ascelibrary.org/doi/abs/10.1061/9780784485514.035">Full Version</a>
<details style="display:inline"><summary style="cursor:pointer; color:#0078ff; display:inline">| Summary</summary><p style="margin-top:0.5em"><em>Proposes a federated RL framework enabling connected autonomous vehicles to share intersection-driving knowledge across heterogeneous environments without revealing private data.</em></p></details>
</li>

</ol>

[See all papers →](/papers/)

# Awards and honors

**Finalist, Best Student Paper Award (1 of 6)**, American Control Conference (ACC), 2025.  
**Student Organization Leader of the Year (ISAN)**, Northeastern University, 2026.
