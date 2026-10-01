# TRACE

**Temporal Gradient Inversion for Private Trajectory Reconstruction in Embodied Reinforcement Learning**
(NeurIPS 2026)

Sudip Bhujel, Shanghao Shi, Ruiquan Huang, Ning Zhang, Yang Xiao
University of Kentucky · Washington University in St. Louis

[Project page](https://trace-gia.github.io/) · [Paper](https://arxiv.org/pdf/2609.30258) · [Code](https://github.com/sudip-bhujel/TRACE)

![TRACE overview](https://trace-gia.github.io/static/images/hero.png)

Embodied agents in distributed RL share per-step policy gradients instead of raw sensor data. TRACE shows those gradients are not private: it reconstructs the agent's observation-action trajectory from them at 3–4.5 ms per frame. It reaches 18.8 dB PSNR with near-perfect action recovery, outperforming prior single-frame attacks.