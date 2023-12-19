# Extraction using OpenAI Functions and Langchain"


This templates is designed to extracts job information (company name, job 
title, salary range) from a job description. It uses OpenAI Functions and 
Langchain. It runs with agenta. 
[Agenta](https://github.com/agenta-ai/agenta) is an open-source LLMOps 
platform that allows you to 1) quickly experiment and compare 
configuration for LLM apps 2) evaluate prompts and workflows 3) deploy 
applications easily. 

## How to use
### 0. Prerequisites
-  Install the agenta CLI
```bash
pip install agenta-cli
```
- Either create an account in [agenta cloud](https://cloud.agenta.ai/) or 
[self-host agenta](/self-host/host-locally)

### 1. Clone the repository

```bash
git clone https://github.com/Agenta-AI/job_extractor_template
```

### 2. Initialize the project

```bash
agenta init
```

### 3. Setup your openAI API key
Create a .env file by copying the .env.example file and add your openAI 
API key to it.
```bash
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxx
```

### 4. Deploy the application to agenta

```bash
agenta variant serve app.py
```

### 5. Experiment with the prompts in a playground and evaluate different 
variants

