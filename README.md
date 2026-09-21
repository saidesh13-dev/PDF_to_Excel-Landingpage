# 📊 PDF Bank Statement to Excel Converter

A lightweight, secure, and automated Python web application that extracts raw financial data from PDF bank statements and structures it into beautifully formatted Excel (`.xlsx`) spreadsheets. Built specifically to eliminate the headache of manual data entry for freelancers, small business owners, and bookkeepers.

---

## ✨ Features

- **Automated Text Extraction:** Uses advanced PDF parsing libraries to accurately extract transaction histories, dates, descriptions, and balanced balances.
- **Smart Formatting:** Outputs data directly into clean Excel spreadsheets with proper data types (numbers formatted as currency, dates formatted uniformly).
- **Privacy-First Design:** Zero server storage. Financial data is parsed entirely in memory and permanently wiped immediately after processing.
- **Responsive Interface:** A minimal, clean UI built with Streamlit for seamless cross-platform file uploads.

---

## 🛠️ Tech Stack

- **Backend Logic:** Python 3
- **Data Parsing:** `pdfplumber` / `pypdf` (or your specific text extraction engine)
- **Data Structuring:** `pandas`
- **File Output:** `openpyxl` (Excel Spreadsheet Engine)
- **Web Frontend:** `streamlit`
- **Hosting Platform:** Render

---

## 🚀 Local Installation & Setup

Want to run this project locally on your machine via VS Code? Follow these quick steps:

### 1. Clone the Repository
```bash
git clone https://github.com
cd YOUR_REPO_NAME
```

### 2. Set Up a Virtual Environment (Recommended)
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
streamlit run app.py
```
Your default browser will automatically open a local window at `http://localhost:8501`.

---

## 🔒 Security & Privacy Notice

We treat financial data with the absolute highest level of sensitivity. 
- The application processes the PDF files instantly in temporary memory.
- No files are written to hard drives or persistent cloud servers during processing.
- No database connections exist, making it mathematically impossible for historical statement data to leak.

---

## 💰 Monetization & Support

This tool is intentionally kept 100% free to support small businesses and independent creators. If this script saved you hours of manual spreadsheet bookkeeping, consider supporting its infrastructure costs:

- [☕ Buy Me A Coffee](https://buymeacoffee.com)

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
