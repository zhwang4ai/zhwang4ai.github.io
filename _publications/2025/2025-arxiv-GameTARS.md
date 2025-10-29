---
title:          "Game-TARS: Pretrained Foundation Models for Scalable Generalist Multimodal Game Agents"
date:           2025-10-29 00:01:00 +0800
selected:       true
pub:            "arXiv"
# pub_pre:        "Submitted to "
# pub_post:       'Workshop'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  We present Game-TARS, a generalist game agent trained with a unified, scalable action space anchored to human-aligned native keyboard–mouse inputs. Unlike API- or GUI-based approaches, this paradigm enables large-scale continual pre-training across heterogeneous domains, including OS, web, and simulation games. Game-TARS is pre-trained on over 500B tokens with diverse trajectories and multimodal data. Key techniques include a decaying continual loss to reduce causal confusion and an efficient Sparse-Thinking strategy that balances reasoning depth and inference cost. Experiments show that Game-TARS achieves about 2 times the success rate over the previous sota model on open-world Minecraft tasks, is close to the generality of fresh humans in unseen web 3d games, and outperforms GPT-5, Gemini-2.5-Pro, and Claude-4-Sonnet in FPS benchmarks. Scaling results on training-time and test-time confirm that the unified action space sustains improvements when scaled to cross-game and multimodal data. Our results demonstrate that simple, scalable action representations combined with large-scale pre-training provide a promising path toward generalist agents with broad problem-solving abilities.
cover:          /assets/images/covers/2510.23691.png
authors:
  - Bytedance Seed
links:
  Project: https://seed-tars.com/game-tars/
  Paper: https://arxiv.org/abs/2510.23691
  # Huggingface Models: https://huggingface.co/ByteDance-Seed/UI-TARS-1.5-7B
  # Code: https://github.com/CraftJarvis/GROOT
  # Twitter: https://twitter.com/jeasinema/status/1712526192665047493
  # Media: https://mp.weixin.qq.com/s/IqIRxFYDpCi3_Iy1FUg9DQ
---
