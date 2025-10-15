# DeepSeekCoder with Ollama in Jupyter Notebook

This document demonstrates how to set up and use [Ollama](https://ollama.com) with the `deepseek-coder` model and other models inside a Python Jupyter Notebook.

## Prerequisites

Make sure you have the following installed:

- Python 3.8 or higher
- [Ollama](https://ollama.com/download) (MacOS, Linux, or Windows)
- Jupyter Notebook or JupyterLab
- Git (For cloning this repo)

## 1. Install and Start Ollama

### Step 1: Download and install Ollama

Visit: [https://ollama.com/download](https://ollama.com/download) and install it for your OS.

### Step 2: Start the Ollama service

Once installed, open your terminal and run:

```bash
ollama run deepseek-coder:6.7b

```

Before working with any model, first open your terminal and run the following command.

```bash
ollama run model-name
```

> **Note:** This may take several minutes depending on your internet speed.

## 2. Execute files

### Step 1: Execute the CoT files 

CoT_CS1QA.ipynb <br>
CoT_CodeQA.ipynb

### Step 2: Execute the coreQA files 

coreQA_CS1QA.ipynb <br>
coreQA_CodeQA.ipynb