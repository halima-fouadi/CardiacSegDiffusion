# CardiacSegDiffusion

This repository contains the implementation associated with the paper:

**"Supporting Transformer-based Cardiac MRI Segmentation with Text-to-Image Controllable Diffusion Pipelines"**

---

## Status

This repository is released for peer-review purposes.

The full implementation, trained models, and dataset will be made publicly available upon acceptance.

---

## Overview

We propose a controllable generative framework for cardiac MRI synthesis using:

- LoRA fine-tuned diffusion models for label generation
- ControlNet for image synthesis conditioned on segmentation maps
- SegFormer for downstream segmentation

---

## Implementation Details (Summary)

- Backbone: Stable Diffusion v1.5
- LoRA rank: 32 (attention layers)
- Resolution: 512×512
- Batch size: 1
- Scheduler: DDPM (1000 timesteps)
- CFG: 6.0 (LoRA), 3.0 (ControlNet)

---

## Repository Structure

CardiacSegDiffusion/
├── train_lora.py # (to be released)
├── train_controlnet.py # (to be released)
├── train_segformer.py # (to be released)
├── configs/ # (to be released)
├── prompts/ # (to be released)
├── utils/ # (to be released)
---

## Dataset

The synthetic dataset generated in this work will be released upon acceptance.

---

## Reproducibility

All experiments are conducted with:
- Seed: 42
- Resolution: 512×512
- Controlled diffusion parameters

---

##  Note

This repository is intentionally anonymized for the review process.
