# AI-Generated Academic Text Detection

## Overview  
A supervised learning system to detect machine-generated academic essays using:
- Datasets (Kaggle LLM Detect (academic essays) + OpenAI GPT-2 (cross-domain))  
- Stylometric features (Logistic Regression/SVM)  
- Transformer models (BERT/RoBERTa)  
- Perplexity analysis with GPT-2

## Dataset References

This folder originally contained processed data from:

1. **Kaggle LLM Detect AI Text Dataset**  
   - Source: [Download here](https://www.kaggle.com/datasets/surajiha101/llm-detect-ai-generated-text-dataset)  
   - Files: `Training_Essay_Data.csv` (preprocessed)  
   - Citation:  
     ```bibtex
     @misc
     {
     thite2023llmdetect,
     author = {Thite, Suraj},
     title = {LLM Detect AI Generated Text Dataset},
     year = {2023},
     publisher = {Kaggle}
     }
     ```

2. **GPT-2 Output Dataset**  
   - Source: [GitHub](https://github.com/openai/gpt-2-output-dataset)  
   - Files: `webtext.test.jsonl`, `small-117M.test.jsonl`  
   - License: [MIT](https://github.com/openai/gpt-2-output-dataset/blob/master/LICENSE)

## Setup  
Clone this repository:  
   ```bash
   git clone https://github.com/Askahid66/ai-academic-text-detector.git
```

## Repository Structure
```
ai-academic-text-detector/
├── code/               # Python scripts and Colab notebooks
├── data/               # Dataset references (see data/README.md)
├── results/            # Model outputs and visualizations
├── README.md           # Project documentation
└── LICENSE             # MIT License file
```

## License  
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for full details.  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
