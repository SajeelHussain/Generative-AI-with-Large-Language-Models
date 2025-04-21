# Generative AI with Large Language Models

This repository contains hands-on labs and resources for working with generative AI, focusing on dialogue summarization using large language models (LLMs) and fine-tuning techniques. The materials are designed to help you understand prompt engineering, model evaluation, and advanced fine-tuning methods with state-of-the-art models from Hugging Face.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Files in this Repository](#files-in-this-repository)
- [Getting Started](#getting-started)
- [Lab 1: Summarize Dialogue](#lab-1-summarize-dialogue)
- [Lab 2: Fine-Tune a Generative AI Model](#lab-2-fine-tune-a-generative-ai-model)
- [Dataset and Results](#dataset-and-results)
- [Requirements](#requirements)
- [License](#license)

---

## Project Overview
This project demonstrates how to use and fine-tune large language models (LLMs) for the task of dialogue summarization. You will:
- Explore prompt engineering (zero-shot, one-shot, few-shot)
- Fine-tune a model using the FLAN-T5 architecture
- Evaluate model performance using human and automated metrics (e.g., ROUGE)
- Compare full fine-tuning with Parameter Efficient Fine-Tuning (PEFT)

---

## Files in this Repository
- `1_summarize_dialogue.ipynb`: Lab notebook for summarizing dialogue with generative AI, including prompt engineering techniques.
- `Fine_tune_generative_ai_model.ipynb`: Lab notebook for fine-tuning a Hugging Face LLM (FLAN-T5) on a dialogue summarization task, including PEFT.
- `dialogue-summary-training-results.csv`: Example dataset and results for dialogue summarization, including human, original, instruction-tuned, and PEFT model summaries.
- `Project.png`: (Optional) Project illustration or diagram.
- `.gitignore`: Standard Python and Jupyter ignore rules.

---

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Generative-AI-with-Large-Language-Models.git
   cd Generative-AI-with-Large-Language-Models
   ```
2. Open the notebooks (`.ipynb` files) in JupyterLab or Google Colab.
3. Follow the instructions in each notebook to run the code and experiments.

---

## Lab 1: Summarize Dialogue
- Learn prompt engineering for dialogue summarization
- Compare zero-shot, one-shot, and few-shot inference
- Experiment with Hugging Face models and prompt templates

## Lab 2: Fine-Tune a Generative AI Model
- Load and preprocess dialogue-summary datasets
- Fine-tune FLAN-T5 for improved summarization
- Evaluate with ROUGE and human metrics
- Try Parameter Efficient Fine-Tuning (PEFT) for efficient adaptation

---

## Dataset and Results
- `dialogue-summary-training-results.csv` contains sample dialogue summaries:
  - Human-written
  - Original model
  - Instruction-tuned model
  - PEFT model

---

## Requirements
- Python 3.8+
- Jupyter Notebook or Google Colab
- Key libraries: `transformers`, `datasets`, `torch`, `tensorflow`, `pandas`, `scikit-learn`, `rouge-score`
- See notebook cells for specific installation commands

---

## License
This project is for educational purposes. Please refer to individual files and notebooks for any additional licensing or usage notes.
