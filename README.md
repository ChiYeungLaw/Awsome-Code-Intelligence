# Code Intelligence

💻 Welcome to the world of Code Intelligence!

Code Intelligence is an exciting field focused on automating code completion and generation. The ultimate objective is to develop intelligent models capable of generating code based on specific requirements. This repository serves as a comprehensive collection of the latest research and advancements in this domain.

## 🎆 Foundation Models for Code

- OctoPack: Instruction Tuning Code Large Language Models ([paper](https://arxiv.org/abs/2308.07124), [github](https://github.com/bigcode-project/octopack), *open-source* ⭕)
- PanGu-Coder2: Boosting Large Language Models for Code with Ranking Feedback ([paper](https://arxiv.org/abs/2307.14936), *close-source* ❌)
- CodeGen2.5: Small, but mighty ([github](https://github.com/salesforce/CodeGen/tree/main/codegen25?ref=blog.salesforceairesearch.com), [blog](https://blog.salesforceairesearch.com/codegen25/), *open-source* ⭕)
- Phi-1: Textbooks Are All You Need ([paper](https://arxiv.org/abs/2306.11644), 2023,  *close-source* ❌)
- 👑**WizardCoder**: Empowering Code Large Language Models with Evol-Instruct ([github](https://github.com/nlpxucan/WizardLM/tree/main/WizardCoder), [paper](https://arxiv.org/abs/2306.08568), 2023, *open-source* ⭕) 
- CodeT5+: Open Code Large Language Models for Code Understanding and Generation ([github](https://github.com/salesforce/CodeT5), [paper](https://arxiv.org/abs/2305.07922), 2023, *open-source* ⭕)
- **StarCoder**: May the source be with you! ([github](https://github.com/bigcode-project/starcoder), [paper](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view), 2023, *open-source* ⭕)
- CodeGen2: Lessons for Training LLMs on Programming and Natural Languages ([github](https://github.com/salesforce/CodeGen2), [paper](https://arxiv.org/abs/2305.02309), 2023, *open-source* ⭕)
- Replit-code-v1-3b ([github](https://github.com/replit/ReplitLM/tree/main/replit-code-v1-3b), [twitter](https://twitter.com/Replit/status/1651344184593506304), 2023, *open-source* ⭕)
- GPT4 ([paper](https://arxiv.org/abs/2303.08774), 2023, *close-source* ❌)
- SantaCoder: don't reach for the stars! ([github](https://huggingface.co/bigcode/santacoder), [paper](https://arxiv.org/abs/2301.03988), 2022, *open-source* ⭕)
- CodeGeeX: A Pre-Trained Model for Code Generation with Multilingual Evaluations on HumanEval-X ([github](https://github.com/THUDM/CodeGeeX#codegeex-a-multilingual-code-generation-model), [paper](https://arxiv.org/abs/2303.17568), 2022, *open-source* ⭕)
- CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis ([github](https://github.com/salesforce/CodeGen), [paper](https://arxiv.org/pdf/2203.13474.pdf), 2022, *open-source* ⭕)
- Codex: Evaluating Large Language Models Trained on Code (2021, *close-source* ❌)

## 🔨 Training Methods for Code LLMs

- Tuning Models of Code with Compiler-Generated Reinforcement Learning Feedback ([paper](https://arxiv.org/abs/2305.18341), 2023)
- CodeRL: Mastering Code Generation through Pretrained Models and Deep Reinforcement Learning ([github](https://github.com/salesforce/CodeRL), [paper](https://arxiv.org/abs/2207.01780), 2022)

## 🔧 Prompt Engineering for Code LLMs

- Demystifying GPT Self-Repair for Code Generation ([paper](https://arxiv.org/abs//2306.09896), 2023)
- Think Outside the Code: Brainstorming Boosts Large Language Models in Code Generation ([paper](https://arxiv.org/pdf/2305.10679.pdf), 2023)
- Teaching Large Language Models to Self-Debug ([paper](https://arxiv.org/abs/2304.05128), 2023)
- CodeT: Code Generation with Generated Tests ([github](https://github.com/microsoft/CodeT), [paper](https://arxiv.org/abs/2207.10397), 2022)

## 📋 Benchmarks

### Function-level Code Generation
- [APPS]() (Execution-Based)
- [HumanEval](https://github.com/openai/human-eval): Python Code Completion (Execution-Based)
- [MBPP](https://github.com/google-research/google-research/tree/master/mbpp): Python Code Completion (Execution-Based)
- [MultiPL-E](https://github.com/nuprl/MultiPL-E): Multi-language Code Completion (Execution-Based)
- [HumanEval-Plus](https://github.com/evalplus/evalplus): Same code problems as HumanEval, but contain much more test cases. (Execution-Based)
- [HumanEvalPack](https://github.com/bigcode-project/octopack) Extend HumanEval to Bugfix and Code Explain. (Execution-Based)
- [CodeXGLUE (Text-Code)](https://browse.arxiv.org/pdf/2102.04664.pdf) A Large Benchmark for Code Generation. (BLEU-Based)
- [Concode](https://browse.arxiv.org/pdf/1808.09588.pdf). Java Code Completion. (BLEU-Based)

### Class-level Code Generation

- [ClassEval](https://github.com/FudanSELab/ClassEval): Python Class-level Code Completion. (Execution-Based)

### Statement-level Code Generation
- [DS-1000](https://ds1000-code-gen.github.io/): Python data science code completion and insertion. (Execution-Based)
- [CoNaLA](https://conala-corpus.github.io/): Statement-level Python Code Generation. (BLEU-Based)

## 📑 Code-Related Data

- [bigcode/Stack](https://huggingface.co/datasets/bigcode/the-stack-dedup): The pre-training data of starcoder.
- [CodeAlpaca](https://github.com/sahil280114/codealpaca/tree/master): 20K instruction-following data generated by text-davinci-003.
- [LeetCode-Solution-Python](https://www.kaggle.com/datasets/erichartford/leetcode-solutions): Solutions and explanations for most of the leetcode problems.

## 📈 Leaderboard on HumanEval for Open-Source Models

| Model            | HumanEval Pass@1 |
|------------------|------------------|
| 🎃 **w/o SFT** 🎃                  |
| CodeGen-16B-Multi| 18.3             |
| CodeGen-16B-Mono | 29.3             |
| CodeGen2.5-7B-Multi| 28.4             |
| CodeGen2.5-7B-Mono| 33.4             |
| CodeGeeX-13B     | 22.9             |
| Replit-code-v1-3B| 17.1             |
| LLaMA-13B        | 15.8             |
| LLaMA-33B        | 21.7             |
| LLaMA-65B        | 23.7             |
| StarCoderBase-15B| 30.1             |
| StarCoder-15B    | 33.6             |
| 🎃 **w/ SFT** 🎃                   |
| InstructCodeT5+  | 35.0             |
| CodeGen2.5-7B-instruct | 36.2       |
| OctoCoder-15B    | 45.8             |
| WizardLM-30B  1.0| 37.8             |
| 👑 WizardCoder-15B  1.0 | **57.3**     |