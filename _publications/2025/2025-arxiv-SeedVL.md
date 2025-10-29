---
title:          "Seed1.5-VL Technical Report"
date:           2025-05-01 00:01:00 +0800
selected:       false
pub:            "Technical Report"
# pub_pre:        "Submitted to "
# pub_post:       'Workshop'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  We present Seed1.5-VL, a vision-language foundation model designed to advance general-purpose multimodal understanding and reasoning. Seed1.5-VL is composed with a 532M-parameter vision encoder and a Mixture-of-Experts (MoE) LLM of 20B active parameters. Despite its relatively compact architecture, it delivers strong performance across a wide spectrum of public VLM benchmarks and internal evaluation suites, achieving the state-of-the-art performance on 38 out of 60 public benchmarks. Moreover, in agent-centric tasks such as GUI control and gameplay, Seed1.5-VL outperforms leading multimodal systems, including OpenAI CUA and Claude 3.7. Beyond visual and video understanding, it also demonstrates strong reasoning abilities, making it particularly effective for multimodal reasoning challenges such as visual puzzles. We believe these capabilities will empower broader applications across diverse tasks. In this report, we mainly provide a comprehensive review of our experiences in building Seed1.5-VL across model design, data construction, and training at various stages, hoping that this report can inspire further research.
cover:          /assets/images/covers/Seed_15_VL.png
authors:
  - Bytedance Seed
links:
  Project: https://seed.bytedance.com/zh/tech/seed1_5_vl
  Paper: https://arxiv.org/abs/2505.07062
  API: https://www.volcengine.com/experience/ark?model=doubao-1-5-thinking-vision-pro-250428
  # Huggingface Models: https://huggingface.co/ByteDance-Seed/UI-TARS-1.5-7B
  # Code: https://github.com/CraftJarvis/GROOT
  # Twitter: https://twitter.com/jeasinema/status/1712526192665047493
  # Media: https://mp.weixin.qq.com/s/IqIRxFYDpCi3_Iy1FUg9DQ
---
