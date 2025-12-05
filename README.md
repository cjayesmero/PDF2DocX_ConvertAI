# 📄 AI-Powered PDF to DOCX Converter

A robust, AI-driven tool that extracts text from PDF documents and converts them into clean, unformatted DOCX files using Google's Gemini AI models.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NeelPatra/PDF-to-DOCX-Gemini/blob/main/PDF2DocX_ConvertAI.ipynb)

## 🌟 Features

![User Interface](images/screenshot.png)

- **AI-Powered Extraction:** Uses Google's advanced Gemini Flash models (1.5/2.0) for high-accuracy OCR.
- **Smart Cleaning:** Automatically removes repetitive headers, footers, and page numbers.
- **Formatting Removal:** Flattens complex PDF layouts into a linear Word document.
- **Rate Limit Handling:** Manages Free Tier API limits.
- **Privacy Focused:** API keys are input securely and never stored.
- **Interactive UI:** Uses ipywidgets for configuration.

## 🚀 Quick Start

### ✅ Prerequisites
- Google account for Gemini API Key.
- Python 3.

### 📥 Installation
```
git clone https://github.com/YOUR_USERNAME/PDF-to-DOCX-Gemini.git
cd PDF-to-DOCX-Gemini
pip install -r requirements.txt
```

### 👨🏻‍💻 Usage
1. Open the notebook:
```
jupyter notebook PDF2DocX_ConvertAI.ipynb
```
2. Run initialization cells.
3. Open configuration form.
4. Paste API key.
5. Load models.
6. Upload PDF.
7. Run conversion.

## 🛠️ Tech Stack
- **Core Logic:** Python 3  
- **AI Model:** Google Gemini  
- **Document Handling:** python-docx  
- **Interface:** ipywidgets  

## 🤝 Contributing
Pull requests and issues are accepted.

## 📄 License
MIT License.
