# Hugging Face & LLM Experiments Repository

This repository contains hands-on experiments with **Hugging Face models, local LLM inference, and OpenRouter-hosted large language models**.  
The goal is to explore, evaluate, and understand different NLP tasks and LLM behaviors through practical notebooks.

---

##  Repository Structure

###  HuggingFace
Experiments using Hugging Face models for standard NLP tasks and local inference.

####  Local
Contains notebooks for running LLMs **locally**.
- `Tiny_Llama.ipynb` – Local inference with TinyLlama model

####  Natural Language Processing
Task-wise notebooks demonstrating core NLP capabilities:

- **Feature Extraction** – Generating embeddings and representations
- **Fill Mask** – Masked language modeling
- **Question Answering** – Extractive QA models
- **Sentence Similarity** – Semantic similarity using embeddings
- **Summarization** – Abstractive text summarization
- **Table Question-Answering** – QA over tabular data
- **Text Classification** – Sentiment and topic classification
- **Text Generation** – Language generation models
- **Token Classification** – Named Entity Recognition (NER)
- **Translation** – Machine translation tasks
- **Zero Shot Classification** – Label-free text classification

---

###  OpenRouter
Experiments with **state-of-the-art LLMs accessed via OpenRouter APIs**, focusing on instruction-following, reasoning, and agentic behavior.

Notebooks include:
- `AllenAI_Olmo_3_32B_Think.ipynb`
- `Amazon_Nova_2_Lite_v1.ipynb`
- `arcee-ai_trinity-mini.ipynb`
- `Google_Gemma_3n_2B.ipynb`
- `Meta_Llama_3.3_70B_Instruct.ipynb`
- `Mistral_Devstral_2_2512.ipynb`
- `nemotron-nano-12b-v2-v1.ipynb`
- `nex_agi_deepseek_v3.1_nex_n1.ipynb`
- `nvidia_nemotron_3_nano_30b_a3b.ipynb`
- `openai_gpt-oss-120b.ipynb`
- `Qwen_Qwen3_Coder_480B_A35B.ipynb`
- `TNG_R1T_Chimera.ipynb`

These notebooks explore:
- Instruction-following
- Reasoning and chain-of-thought behavior
- Agentic coding models
- Model comparison across providers

---

## Purpose of This Repository
- Learn and experiment with modern NLP tasks
- Evaluate open-source and hosted LLMs
- Understand deployment differences (local vs API)
- Build intuition around model strengths and limitations

---

## Tools & Libraries
- Python
- Hugging Face Transformers
- Hugging Face Hub
- OpenRouter APIs
- PyTorch
- Sentence-Transformers

---

## Who Is This For?
- Students learning NLP and LLMs
- Beginners exploring Hugging Face models
- Developers comparing modern LLMs
- Anyone interested in practical LLM evaluation

---

## Notes
- Some large models are accessed via APIs due to hardware constraints
- Local execution depends on system resources (CPU/GPU)

---

## Summary
This repository serves as a **practical playground for NLP and LLM evaluation**, covering everything from classic NLP pipelines to modern agentic large language models.
