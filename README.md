# ✨ Bangla Physics MCQ Solver

A streamlined and intelligent system built to tackle Bangla-medium Physics MCQs with precision.
Powered by Unsloth, Qwen3-14B, and LoRA optimization, this model delivers fast and accurate predictions by combining translation-aware reasoning with advanced large-language-model capabilities.

Whether the question is conceptual or numerical, the system extracts the most likely option (A/B/C/D) with exceptional reliability.

## 🚀 Overview
Artificial Intelligence is opening new possibilities for education in low-resource languages.  
This project develops an AI model that can understand and solve **Bengali Physics MCQs**, creating a benchmark for Bangla physics reasoning.

The pipeline includes translation, optimized model loading, clean prompting, and automatic submission file generation.

## ⚙️ Key Features
- ⚡ Fast inference using **Unsloth**
- 🧠 Strong reasoning with **Qwen3-14B (4-bit)**
- 🔧 **LoRA-enhanced** performance
- 📝 Clean MCQ prompt → single-letter output
- 📄 Auto-creates **Kaggle-ready submission CSV**

## 📂 Dataset Files
- `train.csv` — Labeled Bangla MCQs  
- `test.csv` — Unlabeled MCQs for prediction  
- `sample_submission.csv` — Required output structure  
- `test_data_translated_test.csv.csv` — English-translated test set  

## 🧠 How the Model Works
1. Loads Qwen3-14B with Unsloth acceleration  
2. Applies a structured MCQ-answering prompt  
3. Generates a single answer letter (A/B/C/D)  
4. Cleans outputs using regex  
5. Saves the final file:

```bash
translated_submission.csv
```

## 👥 Contributors
**Adnan Faisal**  and **Shiti Chowdhury**  
Department of Computer Science & Engineering  
Chittagong University of Engineering & Technology (CUET)
