# Research_socratic

A code repository accompanying the research paper **“Advancing Bloom’s Cognitive Levels through Socratic Dialogue: A DPO-
Based Multi-Agent AI Framework for K-12 Learners”**.

This repository contains:

- **Dataset curation**  
  - Scripts and notebooks used to extract and curate 734 Socratic dialogue pairs from the Class 7 NCERT Science textbook *Curiosity*  
  - Hosted as `mudit23/class7-socratic-dpo` on Hugging Face

- **Model fine-tuning**  
  - Implementation of Direct Preference Optimization (DPO) with LoRA adapters on Qwen 2.5 (7B)  
  - Training scripts and hyperparameter configurations  
  - Final model published as `mudit23/Socratic-Qwen2.5-7B-v2`

- **Multi-agent framework**  
  - Three agents in Python:  
    - **Master Agent** (orchestrates dialogue flow)  
    - **Socratic Agent** (generates probing questions)  
    - **Motivator Agent** (monitors engagement and interjects encouragement)  
  - Notebook detailing system architecture and interaction protocols

- **Results & Evaluation**  
  - Metrics (preference alignment accuracy, DPO loss curves) logged via Weights & Biases  
  - Sample transcripts demonstrating Socratic behavior

- **Citation**  
  ```bibtex
  @misc{jain2025socraticdpo,
    title  = {Advancing Bloom’s Cognitive Levels through Socratic Dialogue: A DPO- Based Multi-Agent AI Framework for K-12 Learners},
    author = {Jain, Mudit},
    year   = {2025},
    howpublished = {\url{https://github.com/m-u-d-i-t/Research_socratic}}
  }
