# 🩸 Blood-Report-Analyzer
AI-powered web app that extracts health parameters from blood test reports (PDF/images), analyzes them against medical reference ranges, and provides actionable insights and personalized health suggestions.

## 🚀 Features
- Upload scanned or PDF blood reports
- OCR-based data extraction (Tesseract / PyMuPDF)
- Reference range comparison & abnormality detection
- GPT-generated health insights and recommendations
- Simple web UI (Streamlit / Gradio)

## 🔧 Tech Stack
- OCR: Tesseract / PyMuPDF
- Data Analysis: Pandas
- LLM: OpenAI GPT-3.5 / Claude / Mixtral (OpenRouter)
- Frontend: Streamlit / Gradio
- Deployment: Streamlit Cloud / Render / Vercel

## 📁 Folder Structure
- `app/`: Core logic for OCR, data analysis, insights
- `web/`: Frontend UI components
- `examples/`: Sample reports for testing
- `main.py`: Entry point

## 📦 Setup Instructions

```bash
git clone https://github.com/your-username/blood-report-analyzer-ai.git
cd blood-report-analyzer-ai
pip install -r requirements.txt
python main.py
```
