# Enhancing Question Generation with Novel Reward Functions: Evaluation and Comparison

## Overview

## Architecture:

- Pretrained SQUADv2 model
- PPO (Proximal Policy Optimization) instead of SCST (Self-Critical Sequence Training)

## Hyperparameters

- Batch Size: 512
- Total Batches: 50 out of 170
- Learning Rate: 5e-5
- Generation Kwargs: "min_new_tokens": 1, "max_new_tokens": 32


