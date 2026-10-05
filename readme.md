# Transformer Java Code Generation

This project compares three Transformer models for Java source-code generation:

- DistilGPT2
- CodeGen-Multi 350M
- Qwen2.5-Coder 0.5B Instruct

The models are evaluated on three programming tasks with increasing difficulty.

## Files

- `notebook/` — Google Colab experiment
- `report/` — Experimental report in PDF format

## Evaluation

The generated programs are evaluated using:

- Java validity
- Compilation success
- Functional correctness
- Robustness
- Instruction following

## Environment

Google Colab  
Python  
Hugging Face Transformers  
Java