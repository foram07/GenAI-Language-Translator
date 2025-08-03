# 🌐 Language Translator Notebook**

### 📘 Overview

This Jupyter Notebook demonstrates a simple yet powerful multilingual translation pipeline using pre-trained models. It enables users to translate text from one language to another directly within Python, making it ideal for educational purposes, language learning, or integrating translation into data pipelines.


### 🎯 Key Features

* 🔄 Bidirectional Translation: Translate text between multiple languages.
* 🤖 Pretrained Model: Uses Hugging Face's transformers library and a language translation model (e.g., Helsinki-NLP/opus-mt).
* 🧠 Easy-to-Use Functions: Accepts source and target languages along with input text for quick translations.
* ✅ Supports 40+ Languages (depending on the model used).



### 🛠️ Technologies Used

1. Python 3.x
2. Transformers – For using pre-trained language models.
3. Torch – As the backend framework for model execution.
4. langcodes – For mapping language names to ISO language codes.



### 📁 Notebook Sections

* Environment Setup: Install and import necessary libraries.
* Language Mapping: A dictionary to map language names to their ISO codes.
* Translation Function: Load the translation model dynamically based on the language pair. Use the model pipeline for performing translations.



### **Example Translations**

Includes multiple input-output examples to demonstrate translations between languages such as English, Hindi, French, and Spanish.



### 🚀 How to Use

* Clone or download this notebook.
* Open the .ipynb file using Jupyter Notebook or JupyterLab.
* Run the setup cell to install dependencies (if not already installed).
* Use the translate() function:



`translate("Hello, how are you?", source_lang="English", target_lang="Hindi")`



### 📌 Notes

* This translation tool is designed for short to medium text. For long documents, consider batching or using more robust APIs.
* Pre-trained models are downloaded at runtime (first use), so internet access is required initially.
* Model performance may vary across languages — it's based on the opus-mt model family.
