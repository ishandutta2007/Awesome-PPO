<div align="center">
  <img src="assets/banner.svg" alt="Awesome PPO Banner" width="800" />

  # Awesome PPO 🚀

  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

  **A curated list of Proximal Policy Optimization (PPO) variants, implementations, and real-world applications.**
</div>

---

## 📖 Table of Contents
- [1. Foundational Variants](#1-foundational-variants)
- [2. Specialized Algorithmic Variants](#2-specialized-algorithmic-variants)
- [3. Real-World Applications & Examples](#3-real-world-applications--examples)
- [4. Successors & Related Alternatives](#4-successors--related-alternatives)
- [📈 Star History](#-star-history)

---

## 1. Foundational Variants 🏗️

| Variant | Description | Year | Original Paper | Details |
| :--- | :--- | :--- | :--- | :--- |
| **PPO-Clip** | The industry default variant (popularized by OpenAI). | 2017 | [arXiv:1707.06347](https://arxiv.org/abs/1707.06347) | [🔗 Read More](docs/variants/ppo-clip.md) |
| **PPO-Penalty** | Conceptually closer to TRPO with adaptive KL penalty. | 2017 | [arXiv:1707.06347](https://arxiv.org/abs/1707.06347) | [🔗 Read More](docs/variants/ppo-penalty.md) |

## 2. Specialized Algorithmic Variants 🧪

| Variant | Description | Year | Original Paper | Details |
| :--- | :--- | :--- | :--- | :--- |
| **Dual-Clip PPO** | Adds a secondary clipping for extreme value spikes. | 2019 | [arXiv:1912.09729](https://arxiv.org/abs/1912.09729) | [🔗 Read More](docs/variants/dual-clip-ppo.md) |
| **PPOS (PPO Smoothed)** | Utilizes functional, smooth clipping. | 2020 | [arXiv:2012.02439](https://arxiv.org/abs/2012.02439) | [🔗 Read More](docs/variants/ppos.md) |
| **Async PPO** | Parallelized data collection across multiple workers. | 2017 | [arXiv:1707.02286](https://arxiv.org/abs/1707.02286) | [🔗 Read More](docs/variants/async-ppo.md) |

## 3. Real-World Applications & Examples 🌍

| Application | Description | Year | Reference | Details |
| :--- | :--- | :--- | :--- | :--- |
| **LLM Alignment (RLHF)** | Standard algorithm for aligning LLMs with human feedback. | 2022 | [arXiv:2203.02155](https://arxiv.org/abs/2203.02155) | [🔗 Read More](docs/applications/llm-alignment.md) |
| **Robotics and Control** | Heavily used in robotic locomotion and navigation. | 2018 | [arXiv:1808.00177](https://arxiv.org/abs/1808.00177) | [🔗 Read More](docs/applications/robotics.md) |
| **Game Playing** | Mastered complex environments like Dota 2. | 2019 | [arXiv:1912.06680](https://arxiv.org/abs/1912.06680) | [🔗 Read More](docs/applications/game-playing.md) |
| **Finance and Trading** | Optimization engine for automated trading agents. | 2020 | [arXiv:2011.03907](https://arxiv.org/abs/2011.03907) | [🔗 Read More](docs/applications/finance.md) |

## 4. Successors & Related Alternatives ⏭️

| Algorithm | Description | Year | Original Paper | Details |
| :--- | :--- | :--- | :--- | :--- |
| **GRPO** | Evolution utilized in advanced LLM post-training. | 2024 | [arXiv:2402.03300](https://arxiv.org/abs/2402.03300) | [🔗 Read More](docs/variants/grpo.md) |
| **TRPO** | PPO's predecessor using complex second-order optimization. | 2015 | [arXiv:1502.05477](https://arxiv.org/abs/1502.05477) | [🔗 Read More](docs/variants/trpo.md) |

---

## 📈 Star History

<div align="center">
   <a href="https://www.star-history.com/#ishandutta2007/Awesome-PPO&type=date&legend=bottom-right">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-PPO&type=date&theme=dark&legend=bottom-right" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-PPO&type=date&legend=bottom-right" />
      <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-PPO&type=date&legend=bottom-right" />
    </picture>
   </a>
</div>

---

<div align="center">
  Built with ❤️ by <a href="https://github.com/ishandutta2007">Ishan Dutta</a>
</div>
