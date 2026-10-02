# TRACE

**Temporal Gradient Inversion for Private Trajectory Reconstruction in Embodied Reinforcement Learning**
(NeurIPS 2026)

[Sudip Bhujel](https://sudipbhujel.com.np)<sup>1</sup>, [Shanghao Shi](https://shishishi123.github.io/)<sup>2</sup>, [Ruiquan Huang](https://ruiquan5514.github.io/)<sup>1</sup>, [Ning Zhang](https://engineering.washu.edu/faculty/Ning-Zhang.html)<sup>2</sup>, [Yang Xiao](https://yang-sec.github.io/yang/index.html)<sup>1</sup>

<sup>1</sup> University of Kentucky &nbsp;&nbsp; <sup>2</sup> Washington University in St. Louis

[Project page](https://trace-rl.github.io/) · [Paper](https://arxiv.org/pdf/2609.30258) · [Code](https://github.com/sudip-bhujel/TRACE)

![TRACE overview](https://trace-rl.github.io/static/images/hero.png)

Embodied agents in distributed RL share per-step policy gradients instead of raw sensor data. TRACE shows those gradients are not private: it reconstructs the agent's observation-action trajectory from them at 3–4.5 ms per frame. It reaches 18.8 dB PSNR with near-perfect action recovery, outperforming prior single-frame attacks.