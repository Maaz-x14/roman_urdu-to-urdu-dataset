# Roman Urdu → Urdu Transliteration Dataset

## 📌 Overview
This repository contains a curated dataset of **1923 parallel sentence pairs** in Roman Urdu and Urdu script.  
It is designed for **fine‑tuning transliteration models** (e.g., m2m100) to adapt from classical/formal Roman Urdu to modern, everyday usage (WhatsApp/social media style).

## ✨ Features
- **Cleaned & Preprocessed:** All pairs manually reviewed for alignment and consistency.  
- **Focus on Transliteration:** Preserves Roman Urdu pronunciation in Urdu script (not translation).  
- **Modern Vocabulary Coverage:** Includes everyday terms like *call, message, login, ticket, cloud storage*.  
- **Spelling Variations:** Captures informal Roman Urdu spellings for better domain adaptation.  
- **Size:** 1923 pairs.

## 🔧 Usage
You can use this dataset for:
- Fine‑tuning existing transliteration models.  
- Benchmarking transliteration accuracy on informal Roman Urdu.  
- Augmenting larger datasets with modern spelling variations.  

**Example (Roman Urdu → Urdu):**  
Roman: `missed call aayi thi teri`  
Urdu: `مسڈ کال آئی تھی تیری`

## 🗂 Structure
- `final_transliteration_dataset.csv` → Roman Urdu & Urdu pairs.  
- Columns:  
  - `roman_urdu` → Input text in Roman Urdu  
  - `urdu` → Target text in Urdu script  

## 🚀 Motivation
Existing datasets (e.g., Roman‑Urdu‑Parl) are large but mostly formal.  
This dataset fills the gap by focusing on **informal, everyday Roman Urdu** used in chats and social media.

## 📜 License
Open for research and educational use. Please cite if used in publications.

---
**Maintainer:** Maaz
