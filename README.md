# Python Code Generation Using LLM (Llama 3)

## Overview
This project uses a local LLM (Llama 3) to generate Python solutions for selected problems from the HumanEval dataset.  
The generated solutions are evaluated by comparing them with reference solutions using a similarity score.
## Key Points
- **Model:** Llama 3 (local, via Ollama)  
- **Tasks:** 10 problems from HumanEval dataset  
- **Evaluation:** Similarity score using Python's `difflib`  

## Results
- All generated solutions achieved a similarity score of **1.0** with the reference solutions.  
- Shows that Llama 3 successfully replicates the expected Python solutions for the selected tasks.

## References
- [HumanEval Dataset on Kaggle](https://www.kaggle.com/datasets/thedevastator/openai-humaneval-code-gen/data)
