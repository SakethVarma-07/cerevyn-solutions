# 📄 Automated Document Processing Pipeline

## 🚀 Overview
This project extracts structured data from PDF/images using OCR and converts it into JSON format.

## 🔧 Features
- OCR-based text extraction
- Field extraction (Name, Amount, Date, Invoice ID)
- Data validation
- JSON output generation

## 🛠 Tech Stack
- Python
- Tesseract OCR
- OpenCV
- Pandas

## 📂 Project Structure
notebook/pipeline.ipynb
data/sample_invoice.pdf
output/output.json

## ▶️ How to Run
1. Open in Google Colab
2. Upload your PDF/image
3. Run all cells

## 📦 Output Example
```json
{
  "name": "John Doe",
  "amount": 1200.50,
  "date": "12/03/2025",
  "invoice_id": "INV12345",
  "status": "valid"
}
