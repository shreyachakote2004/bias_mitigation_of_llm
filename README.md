# Bias Mitigation in Large Language Models (LLMs)

## Overview
This repository focuses on various techniques to mitigate biases in Large Language Models (LLMs), ensuring fair and unbiased AI-generated responses. The project implements multiple strategies, including:

- **DPO (Direct Preference Optimization) Bias Mitigation**
- **Evaluation of Model Bias**
- **LoRA (Low-Rank Adaptation) Bias Mitigation**
- **MEMIT (Mass-Editing Memory in Transformers) Bias Mitigation**
- **REPE (Retrieval-Augmented Prompt Engineering) Bias Mitigation**

## Features
- **Bias Evaluation**: Metrics and tools to measure bias in LLMs before and after mitigation.
- **DPO Mitigation**: Fine-tuning LLMs with preference-based training to reduce biases.
- **LoRA Adaptation**: Lightweight fine-tuning for targeted bias correction.
- **MEMIT Editing**: Controlling and modifying memory to mitigate biases in model responses.
- **REPE Techniques**: Improving prompting strategies to counteract model biases.

## Installation
```bash
# Clone the repository

```

## Usage
### 1. Evaluating Bias
Run bias evaluation scripts to analyze model fairness:
```bash
python evaluate_bias.py --model model_name
```

### 2. DPO Bias Mitigation
Fine-tune a model using Direct Preference Optimization:
```bash
python dpo_mitigation.py --model model_name --dataset dataset_path
```

### 3. LoRA-Based Bias Mitigation
```bash
python lora_mitigation.py --model model_name --lora_weights lora_path
```

### 4. MEMIT Bias Correction
```bash
python memit_mitigation.py --model model_name --edit_target target_bias
```

### 5. REPE Bias Mitigation
```bash
python repe_mitigation.py --model model_name --prompt_strategy strategy_type
```

## Results and Benchmarking
After mitigation, the bias evaluation script can be run again to compare results.

```bash
python evaluate_bias.py --model model_name --after_mitigation
```

