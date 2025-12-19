# VoxLibris — Intelligent Reading Agent

This project implements an intelligent reading assistant using:
- LLaMA 3 + LoRA
- Reinforcement Learning with GRPO (Unsloth)
- Multi-agent architecture (ReaderAgent + AnalystAgent)
- Random Forest classifier for topic consistency
- Unsupervised clustering (K-Means)

## How to run
Open the notebook in Google Colab:
[Código](https://colab.research.google.com/drive/1TmSHh6PcziTosBI80E14hKW2VWg8ZDsb?usp=sharing)

## Project Structure
- Data Engineering: PDF extraction, embeddings, clustering
- Modeling: ReaderAgent + AnalystAgent
- Training: GRPO fine-tuning
- Quality: Metrics and reward evolution
- Deployment: Inference API

## Authors
Mário Vilares; Diogo Teixeira




