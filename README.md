# Finnish Sentiment Classifier with spaCy and Programmatic Labeling

This repository contains a single Google Colab notebook that demonstrates a complete, modern NLP workflow for sentiment analysis on Finnish text.

The project showcases two key techniques:
1.  **Programmatic Labeling:** Using a large language model (Google's Gemini API) to create high-quality training labels from raw text.
2.  **Custom Model Training:** Using the generated insights to train a high-performance, custom `spaCy` classifier with a transformer backend (`TurkuNLP/bert-base-finnish-cased-v1`).

---
## 🎯 Project Goals

* Demonstrate an end-to-end text classification pipeline in a single, reproducible notebook.
* Validate the accuracy of LLM-based programmatic labeling.
* Train a custom `spaCy` model on Finnish text and evaluate its performance.

---
## 📊 Results Summary

* **Gemini Labeling Accuracy:** The programmatic labeling achieved **~94% accuracy** when validated against a human-labeled ground truth.
* **Final spaCy Model F1-Score:** `[0.85]`

---
## 🚀 How to Run

1.  Open the `Finnish-Sentiment-Classifier.ipynb` notebook in Google Colab.
2.  Add your `GOOGLE_API_KEY` to the Colab Secrets Manager (the 🔑 icon on the left).
3.  Run the cells in order from top to bottom. The notebook will install all required dependencies.
