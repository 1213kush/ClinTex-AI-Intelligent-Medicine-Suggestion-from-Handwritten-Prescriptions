# 🤖 ClinTex AI – Intelligent Medicine Suggestion from Handwritten Prescriptions

ClinTex AI is an AI-powered healthcare tool that digitizes handwritten prescriptions and intelligently suggests alternative medicines. It combines modern OCR technology (like Microsoft’s TrOCR and Google Vision API) with a pharmaceutical database to extract, analyze, and recommend cost-effective and relevant alternatives — improving medication accessibility and prescription digitization in clinical settings.

---

## 🧠 Why ClinTex?

Handwritten prescriptions are often inconsistent, hard to read, and prone to human error. ClinTex AI solves this by automating the recognition of medicines using powerful deep learning-based OCR models and provides structured suggestions to patients or pharmacists.

---

## 🔍 Key Features

- 🔎 **OCR with TrOCR + Google Vision API**  
  Uses Microsoft's TrOCR model and integrates Google Vision API for higher accuracy in difficult or noisy handwritten text scenarios.

- 💊 **Smart Medicine Suggestions**  
  For each extracted medicine name, ClinTex suggests up to 5 similar or generic alternatives using fuzzy matching (RapidFuzz) and a pharmaceutical dataset.

- 📄 **PDF Report Generation**  
  Outputs structured suggestions in a clean, downloadable PDF format for easy sharing and offline reference.

- 🌐 **Gradio Web Interface**  
  A user-friendly drag-and-drop interface for uploading prescriptions and viewing results instantly — no technical knowledge required.

- 🧠 **Integrated Pharmaceutical Database**  
  Contains medicine names, compositions, manufacturers, and types to enable accurate and meaningful suggestions.

---

## 🚀 Tech Stack

- **OCR & NLP:**  
  - TrOCR (Hugging Face)  
  - Google Vision API (for enhanced OCR accuracy)  
  - RapidFuzz (for fuzzy string matching)

- **Frontend & Interaction:**  
  - Gradio (for user interface)

- **Report Generation:**  
  - ReportLab (for PDF exports)

- **Backend & Data Handling:**  
  - Python, Pandas  
  - MySQL (for large-scale pharmaceutical data)

---

## 📌 Use Cases

- Digital pharmacies and e-prescription apps  
- Hospitals automating handwritten prescriptions  
- Medical data entry and processing systems  
- Drug alternatives for cost-sensitive users

---

## 🧪 Future Improvements

- Integration with language models for context-aware suggestions  
- Real-time handwriting analysis on mobile devices  
- Multilingual prescription recognition support  
