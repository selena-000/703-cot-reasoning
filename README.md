# Chain-of-Thought Prompt Quantity & LLM Reasoning Performance (COMPSCI703)

This repository contains the experimental code for my COMPSCI703 Individual Research Project at the University of Auckland.  
The study investigates how the number of Chain-of-Thought (CoT) examples in prompts affects the reasoning performance of large language models (LLMs) on commonsense tasks, specifically using the Social IQA dataset.

## 🧪 Project Summary

- **Research Question:**  
  How does the number of CoT examples (1-shot, 3-shot, 5-shot) affect LLMs' reasoning accuracy and output length on Social IQA?

- **Models Tested:**  
  `gpt-4.1-mini` (replace this if you used more models)

- **Metrics:**  
  - Accuracy (prediction correctness vs. gold labels)  
  - Reasoning length (word count of model output)

- **Dataset:**  
  [Social IQA](https://leaderboard.allenai.org/socialiqa/submissions/get-started) (used a subset of 100 dev examples)

## 📁 Files

| File Name               | Description |
|------------------------|-------------|
| `703research.ipynb`    | Main notebook containing prompt generation, API interaction, and results collection |
| `requirements.txt`     | (optional) Python dependencies if you want to run locally |
| `README.md`            | This file |

## 🚀 How to Run the Notebook

1. Open [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive (if dataset is stored there)
3. Install dependencies (e.g., `openai`, `pandas`)
4. **Set your OpenAI API key** safely:
   ```python
   import os
   os.environ["OPENAI_API_KEY"] = "your-key-here"
   ```

  Or, if you're running this notebook privately (e.g., personal test),  you can directly set the key inline like this:

  ```python
  openai.api_key = "..."  # Replace with your actual key
  ```

