# Machine-Learning-Assignments

This repository contains a single Jupyter Notebook implementing a full pipeline for **SemEval 2025 Task 9: The Food Hazard Detection Challenge**, covering:

- **ST1:** Text classification for food hazard prediction  
  - Predicts **hazard-category** and **product-category**
- **ST2:** Food hazard and product “vector” detection  
  - Predicts the exact **hazard** and **product**

The approach is based on fine-tuning **RoBERTa-base** with Hugging Face Transformers on the official SemEval data.

---

## Project Structure

- `SemEval 2025 Solution.ipynb`  
  End-to-end notebook that:
  1. Installs and imports dependencies  
  2. Loads and preprocesses the data  
  3. Trains RoBERTa models for ST1  
  4. Trains RoBERTa models for ST2  
  5. Generates a combined `submission.csv`  
  6. Compresses it into `submission.zip`

---
