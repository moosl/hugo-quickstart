---
title: 'Llama 2 Released for Commercial Use - What We Know So Far'
date: '2023-03-01'  
description: 'A look at the key details on Llama 2 from Meta AI including performance, usage permissions, model architecture and training methodology.'
image: 'https://pbs.twimg.com/media/F1VPb_IaAAEa4-b.jpg'
tags:
  - AI
  - Llama 2
  - Meta
  - Language Models
---

Llama 2 is finally released for commercial use! Here's a summary of what we know so far:

![Llama 2 announcement](https://pbs.twimg.com/media/F1VPb_IaAAEa4-b.jpg)

## Performance and Parameters

- Available in 7B, 13B and 70B parameter sizes 
- 40% more training data and 2x context length compared to Llama 1
- Pretrained on 2 trillion tokens with 4096 context length
- Outperforms other open-source LMs on benchmarks


![Llama 2 benchmarks](https://pbs.twimg.com/media/F1VPcWZaUAAC7T_.jpg)

![Llama 2 metrics](https://pbs.twimg.com/media/F1VPcwcaAAAiFqy.jpg)

## Usage and Restrictions

- Commercial use now permitted, unlike leaked version
- Apply to download directly from [Meta AI site](https://ai.meta.com/resources/models-and-libraries/llama-downloads/)
- Separate licensing needed for 700M+ DAU products 
- Cannot be used to improve other large LMs

![Llama 2 usage](https://pbs.twimg.com/media/F1VPdWSaQAAVIIh.jpg)

## Model Architecture

- Uses standard Transformer architecture
- Optimized with pre-normalization, SwiGLU activation, RoPE embeddings 
- Llama 2-Chat fine-tuned with supervised learning and reinforcement learning
- Available in 7B to 70B parameter sizes
- Trained only on public data 

## Training Methodology

**1. Pretraining**

- 2 trillion public tokens  
- Removed sites with personal info
- Standard Transformer + optimizations 

**2. Supervised Fine-Tuning** 

- 30,000 human annotated examples
- Optimized for answer not prompt labels

**3. Reinforcement Learning**

- Human preference data collected  
- Reward models scored responses
- Iterative tuning with rejection sampling, PPO

**4. Safety**

- Safe/helpful data collected
- Separate safety reward models   
- Enhanced safety via distillation 

**5. Evaluation** 

- 4K prompts rated for usefulness
- 2K prompts rated for safety, beat benchmarks

![Llama 2 training](https://pbs.twimg.com/media/F1VPedEaAAA-oPn.jpg)

Llama 2 provides powerful AI capabilities and benchmarks. Exciting to see open access to such large models!