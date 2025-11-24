# Native Language Identification of Indian English Speakers Using HuBERT

This project builds a system that identifies the **native language (mother tongue)** of Indian English speakers based on their speech accents. The model uses **HuBERT (Hidden-Unit BERT)** embeddings along with pitch and duration features to analyze pronunciation patterns influenced by the speaker’s native language.

---

## 🔍 Project Summary

- Extracts embeddings from **HuBERT Layer 6 and Layers 9–12**
- Adds **pitch** and **duration** to improve classification
- Uses **MLP classifier** for training and prediction
- Compares multiple HuBERT layers to find the best-performing feature level

---

## 📁 Dataset & Model Files

Large dataset and feature files are stored externally in Google Drive.

📌 You **do NOT need to download** them manually —  
the notebook automatically downloads required cached `.npz` files using stored Google Drive file IDs.

---

## 🚀 How to Use

1. Open the notebook: `NLI_FINAL_NOTEBOOK.ipynb`
2. Ensure dependencies are installed:

```bash
pip install -r requirements.txt
