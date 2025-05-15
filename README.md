# 🧠 AI-Driven Early Detection of Autism in Toddlers Using Multimodal Data

This project is a proof-of-concept pipeline for the **early detection of Autism Spectrum Disorder (ASD) in toddlers**, utilizing AI and non-invasive, multimodal data. It focuses on identifying early behavioral signs through structured clinical inputs, image analysis, and NLP-driven textual trait extraction.

---

## 📌 Project Overview

Early diagnosis of ASD is crucial for timely intervention. This project leverages machine learning and deep learning techniques to analyze:

* **Structured clinical and behavioral data**
* **Visual data** (images showing behavioral cues)
* **Textual data** (clinical context, symptom traits)

The goal is to automate and improve the autism screening process by identifying subtle early signs observable in toddlers.

---

## ✅ Implemented Components

### 1. **🧾 Feature Identification (Structured Data)**

* **Goal:** Identify clinical and behavioral features indicative of autism.
* **Method:**

  * Uses standardized screening data (e.g., Q-CHAT, A1–A10 binary indicators).
  * Extracts key behaviors like reduced eye contact, repetitive actions, delayed response.
* **Code:** `Code.ipynb`, `Code-Copy1.ipynb`

---

### 2. **🖼️ Repetitive Behavior Detection (Image Data)**

* **Goal:** Detect repetitive motor behaviors (e.g., hand flapping, rocking).
* **Method:**

  * A CNN model is trained on labeled images of autistic vs. non-autistic toddlers.
  * Architecture includes convolutional, pooling, batch normalization, and dropout layers.
* **Code:** `CNN_model.ipynb`

---

### 3. **📚 Social Reciprocity Assessment (Textual Data)**

* **Goal:** Analyze deficits in social interaction using clinical text.
* **Method:**

  * A BERT-based NLP model performs question-answering on medical descriptions.
  * Extracts indicators like poor eye contact, non-responsiveness to name, etc.
* **Code:** `NLP.ipynb`

---


## 📂 File Descriptions

| File               | Description                                                             |
| ------------------ | ----------------------------------------------------------------------- |
| `Code.ipynb`       | Structured data processing and ML modeling using ASD screening datasets |
| `Code-Copy1.ipynb` | Alternative implementation for structured feature analysis              |
| `CNN_model.ipynb`  | CNN model for image-based repetitive behavior detection                 |
| `NLP.ipynb`        | BERT-based NLP pipeline for ASD trait extraction from text              |

---

## 🚀 How to Run

1. **Structured Data Analysis:**

   * Run `Code.ipynb` or `Code-Copy1.ipynb` to train ML classifiers on behavioral datasets.

2. **Image-Based Detection:**

   * Open `CNN_model.ipynb` and run the training pipeline for image classification.

3. **Textual Trait Extraction:**

   * Use `NLP.ipynb` to extract ASD traits using a QA-based NLP model.



