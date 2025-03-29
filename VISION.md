# smolLM-cookbook: Vision & Roadmap

This document outlines the vision, goals, and planned roadmap for the `smolLM-cookbook` project. It serves as a guiding reference for development.

## Goals

This project aims to:

1.  Provide clear, practical examples and learning materials for developing Large Language Models (LLMs) from the ground* up.
2.  Serve as a concise reference and cookbook for common LLM development tasks and techniques.

## Roadmap (Progressive Releases)

The project will evolve through manageable, progressive releases:

*   **v0.1: Foundational GPT (PyTorch)**
    *   Implement a basic GPT model in PyTorch.
    *   Train on a simple dataset (e.g., Shakespeare).
    *   Focus: Environment setup, core implementation correctness, basic training loop.

*   **v0.2: Framework Integration & Configuration**
    *   Refactor the code using PyTorch Lightning.
    *   Implement configuration management (e.g., Hydra/YAML) for hyperparameters, model architecture, etc.

*   **v0.3: Performance Optimization**
    *   Implement basic optimization techniques to improve training/inference speed.

*   **v0.4: Scaling Utilities & Estimation**
    *   Add utilities or documentation related to LLM scaling laws (e.g., Chinchilla).
    *   Include tools/guides for estimating training resources (compute, time, cost) and potential performance.

*   **v0.5: Monitoring & Logging**
    *   Integrate experiment tracking and logging (e.g., Weights & Biases).

*   **v0.6: Meaningful Dataset**
    *   Select and integrate a more meaningful, yet still manageable, dataset.

*   **v0.7: Distributed Training**
    *   Implement distributed training capabilities (e.g., across 2 GPUs using DDP).

*   **v1.0: SOTA Demonstration**
    *   Train a model targeting State-of-the-Art (SOTA) performance for the chosen dataset within a specific resource class.
    *   Demonstrate effective application of research techniques.

## Future Directions

Beyond v1.0, potential avenues include:

*   Experimenting with newer architectures, larger datasets, and advanced training regimes.
*   Exploring Parameter-Efficient Fine-Tuning (PEFT) techniques.
*   Investigating Reinforcement Learning from Human Feedback (RLHF).
*   Potentially branching into Vision-Language Models (VLMs).

This roadmap is a living document and subject to refinement as the project progresses.
