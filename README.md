# Heracles: Bridging Precise Tracking and Generative Synthesis for General Humanoid Control

**Project Page**: [https://Heracles-Humanoid-Control.github.io](https://Heracles-Humanoid-Control.github.io)

Heracles is a state-conditioned diffusion middleware that bridges precise motion tracking and generative synthesis for general-purpose humanoid control. Rather than relying on rigid tracking paradigms, Heracles operates as an intermediary layer between high-level reference motions and low-level physics trackers — preserving zero-shot tracking fidelity under nominal conditions while seamlessly synthesizing anthropomorphic recovery trajectories under severe perturbations.

## Key Features

- **Generative Control Middleware**: A state-conditioned flow matching model that dynamically modulates reference commands based on real-time physical feasibility.
- **Enhanced Physics Tracker**: An improved general-purpose tracking policy with iFSQ-based motion tokenization and adaptive motion sampling.
- **Robust Anthropomorphic Recovery**: Emergent human-like recovery behaviors under extreme out-of-distribution perturbations, validated on physical humanoid robots.

## Citation

```bibtex
@misc{heracles2026,
  title         = {Heracles: Bridging Precise Tracking and Generative Synthesis for General Humanoid Control},
  author        = {Qiang Zhang and Zelin Tao and Zeran Su and Peiran Liu and Jingkai Sun and Wenqiang Que and Jiahao Ma and Jialin Yu and Gang Han and Wen Zhao and Zhiyuan Xu and Yijie Guo and Jian Tang},
  year          = {2026},
  archivePrefix = {arXiv},
  primaryClass  = {cs.RO}
}
```
