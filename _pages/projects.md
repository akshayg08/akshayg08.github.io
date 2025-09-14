---
permalink: /projects/
title: "Projects"
excerpt: "Projects"
author_profile: true
---

<h2>Needle: A PyTorch-like training framework</h2>
<p>
  Built a deep learning framework in C++ and Python, supporting tensor operations including convolution, broadcasting, and transpose for training neural networks. Optimized training on NVIDIA GPUs with custom CUDA kernels for reduction, matrix multiplication, and other critical operations. Designed computation graph execution with backpropagation via topological sort, implementing efficient forward and backward passes for numerous operations. Extended capabilities with gradient checkpointing and <b>FP16 mixed-precision training</b>, significantly improving memory efficiency.
</p>

<h2>Synthetic Data Generation for Off-Policy Preference Optimization</h2>
<p>
  Generated a synthetic preference dataset using a model pool for fine-tuning vision language models to improve abductive reasoning capabilities. Used CLIP for scoring model generations to determine preference ordering, then fine-tuned PaliGemma-3B on the preference data using <b>Direct Preference Optimization</b>. [<a href="https://huggingface.co/datasets/akshayg08/sherlock_preference_dataset">Dataset</a>] [<a href="https://github.com/akshayg08/paligemma_dpo/blob/main/loss_utils.py">Code</a>]
</p>

<h2>MinBERT</h2>
<p>
Implemented the BERT architecture from scratch, including positional embeddings and multi-head attention mechanisms, and trained it for sentiment classification tasks. Built a custom AdamW optimizer to enable efficient training and fine-tuning of the language model using PyTorch and Hugging Face libraries. [<a href="https://github.com/akshayg08/bert_classifier">Code</a>]
</p>

<h2>Hybrid Machine Translation</h2>
<p>
  A Machine Translation model that utilizes the strengths of both Statistical and Neural MT. The neural sequence-to-sequence archtitecture is enhanced by the phrase-table constructed using Phrase-Based SMT. The generated unknown tokens are replaced with the translations of the aligned source phrases. [<a href="https://github.com/akshayg08/Hybrid-Machine-Translation">Github</a>]
</p>

