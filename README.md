# distilbert-hate-speech-detection
This repository contains a neural NLP project focused on classifying social media content into three categories: Hate Speech, Offensive Language, or Neither. The project was developed as a final project for the **Large Language Models** course at the **University of Konstanz**. 

* **Language:** Python
* **Model:** DistilBERT (`distilbert-base-uncased`) - Fine-tuned for sequence classification.
* **Deep Learning Framework:** PyTorch & Hugging Face Transformers.
* **Data Processing:** Pandas, NumPy, Datasets (Hugging Face).
* **Evaluation:** Scikit-learn (Precision, Recall, F1-Score, Confusion Matrix).

Key Features:
The dataset used in this project was obtained from Kaggle's Hate Speech and Offensive Language Dataset, which consists of over 24,783 tweets. This dataset was chosen for its
explicit annotations, real-world applicability, and frequent use in hate speech research,providing a baseline for model comparison.

Key Focus: 
Analyzed the impact of **class imbalance** on model performance and implemented evaluation metrics including F1-score and Precision/Recall.
