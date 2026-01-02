# sms-spam-classification-bert
High-precision SMS Spam detection system using BERT. Achieved 98.2% accuracy through fine-tuning with PyTorch and Transformers.

## 📚 About Data
More than 5500 real text labeled examples. Dataset created by Tiago A. Almeida and José M. Gómez Hidalgo available [here](https://archive.ics.uci.edu/dataset/228/sms+spam+collection).

## 🎯 Key Features
* **Data Visualization:** Several charts show relevant data features.
* **Transformer-based:** Leverages `bert-base-cased` for deep contextual understanding.
* **Optimized Training:** Implements a **Linear Learning Rate Scheduler** with a peak LR of 2e-5, decaying to zero to ensure stable convergence and prevent overfitting.
* **High Performance:** Reached **98.2% accuracy** on the test set.
* **Ready for Production:** Model weights are hosted on Hugging Face for easy integration.

## 📊 Results
The model shows exceptional performance across all metrics:

| Metric | Score |
| :--- | :---: |
| **Accuracy** | **0.98** |
| **Precision (Spam)** | **0.99** |
| **Recall (Spam)** | **0.92** |
| **F1-Score (Spam)** | **0.93** |



## 🚀 Model Hosting
Due to GitHub's file size limitations, the trained model weights are hosted on the **Hugging Face Hub**. 

You can access the model here: [https://huggingface.co/mrcsgh/bert-sms-spam-classifier]
 
