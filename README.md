# Enhancing Question Generation with Novel Reward Functions: Evaluation and Comparison

## Overview
Improving the creation of questions by fine tuning a base LLM through Reinfocement Learning using new novel reward functions is the focus of "Enhancing Question Generation with Novel Reward Functions: Evaluation and Comparison." This study examines and compares these new approaches to see how well they work and what improvements they bring.
## Architecture:

- Pretrained SQUADv2 model
- PPO (Proximal Policy Optimization) instead of SCST (Self-Critical Sequence Training)

## Hyperparameters

- Batch Size: 512
- Total Batches: 50 out of 170
- Learning Rate: 5e-5
- Generation Kwargs: "min_new_tokens": 1, "max_new_tokens": 32

### Dataset : 
- https://pytorchnlp.readthedocs.io/en/latest/_modules/torchnlp/datasets/squad.html
### Reference Paper :
- https://dl.acm.org/doi/pdf/10.1145/3471158.3472240

<img width="774" alt="image" src="https://github.com/IMRO832000/CSE_574/assets/20886645/5e8c18ec-87e4-4059-9fd2-619bf6aed4bb">

<img width="787" alt="image" src="https://github.com/IMRO832000/CSE_574/assets/20886645/c13d90c6-3ece-4594-aaab-2bef1f044c29">

