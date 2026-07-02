---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from:
  - /Projects
  - /Projects/
---

## Predictive Future Tokens for Planning / JEPA World Model
**Leapmotor, 2026.05 - 2026.08. First author**

This project studies JEPA-style world modeling for autonomous driving. The goal is to adapt V-JEPA2.1 to multi-view driving scenes while preserving its general visual representations, then use predicted future latent tokens to improve trajectory scoring and planning.

* Fine-tuned the V-JEPA2.1 encoder with LoRA for autonomous-driving perception and temporal dynamics.
* Designed latent future prediction modules for road structure, dynamic agents, and ego-agent interactions.
* Integrated predicted future representations into a trajectory scorer for risk-aware candidate selection.

## Diffusion in Corridor for Safe Motion Planning
**HKUST(GZ), 2025.09 - 2026.03. First author**

This work addresses the tendency of unconstrained diffusion planners to violate drivable-area boundaries in narrow roads, sharp turns, and other highly constrained scenes.

* Built topological route corridors from lane graphs and extended them with predicted dynamic-agent occupancy.
* Developed corridor-guided diffusion with inpainting-style repair to regenerate invalid trajectory segments.
* Designed differentiable energy-field and forward-simulator guidance with LQR tracking to align planned references with executable trajectories.

## CoPlanner: Contingency-Aware Diffusion Planning
**HKUST(GZ), 2025.03 - 2025.09. First author**

CoPlanner is a generative joint prediction-and-planning framework for interactive autonomous driving under multimodal uncertainty.

* Introduced an inpainting mechanism that anchors short-term safe shared segments and generates diverse long-horizon contingency branches.
* Designed multi-scenario contingency scoring to balance safety, efficiency, and comfort across possible traffic futures.
* Evaluated the planner on nuPlan Val14/Test14, with strong closed-loop performance and reduced long-tail collision risk.

## LUNA-AD: Lightweight Uncertainty-Aware Decision-Making
**HKUST(GZ), 2025.06 - 2026.02. Co-author**

LUNA-AD explores confidence-aware language-model decision making for autonomous driving with low latency and limited memory overhead.

* Built a multi-agent confidence-aware workflow using action voting, confidence estimation, and summary aggregation.
* Distilled teacher reasoning from DeepSeek-V3 and DeepSeek-R1 into a lightweight Qwen3-1.7B student with 4-bit quantization and LoRA.
* Integrated RAG and reflection-driven lifelong learning with nuPlan closed-loop failure capture.

## VLA Model for Parking Scenarios
**Huawei 2012 Laboratories, 2025.09 - 2026.05. Project member**

This project builds an end-to-end vision-language-action model for parking scenarios, targeting interpretable decision reasoning and safe trajectory planning.

* Constructed instruction-tuning data from real driving trajectories and visual-question-answering tasks.
* Developed multi-task VLA models for multimodal scene understanding, decision reasoning, target-point generation, and trajectory planning.
* Supported staged model training, open-loop evaluation, and closed-loop simulation tests.

## Neural Operators for Stop-and-Go Traffic
**HKUST(GZ), 2023.05 - 2024.05. Co-author**

This research uses neural operators and physics-informed learning to accelerate boundary-control synthesis for macroscopic traffic-flow PDE systems.

* Approximated backstepping control kernels with neural operators and embedded them into analytic feedback controllers.
* Learned mappings from traffic-system parameters to closed-loop boundary controls without retraining for new initial conditions.
* Achieved approximately 300x computational acceleration over the backstepping baseline with small accuracy loss.

## Early Projects
### UAV Swarm Establishment and Factor Analysis
**Northwestern Polytechnical University / AVIC Shenyang Aircraft Design Institute, 2020.07 - 2021.05. Student leader**

Built an AirSim-based UAV simulation platform and developed sensitivity-analysis tools with PyQt5, multithreading, Python data processing, and C++ acceleration. The project produced a patent and follow-up research on Bayesian-network-based complex-system analysis.

### Collaborative Intelligent Control Based on Brain-Computer Interface
**National Key Discipline Laboratory of Neural Information Processing, 2018.07 - 2019.05. Project leader**

Developed a complete EEG-based closed-loop control system from signal acquisition and feature extraction to SVM/DNN recognition and vehicle control. The project received an excellent final evaluation in the national undergraduate innovation program.
