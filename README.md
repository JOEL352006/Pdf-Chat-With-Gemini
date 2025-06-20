# Pdf-Chat-With-Gemini




PDF Question Answering Chatbot using Google Gemini API
A simple, fully functional PDF Q/A Chatbot built using Google Gemini 1.5 API, Streamlit, and Google Colab, allowing users to upload a PDF and ask questions strictly based on its content.

🚀 Features
✅ Upload any PDF via web UI
✅ Chat with the PDF — ask questions based only on its content
✅ Uses Google Gemini 1.5 Flash model (v1 API)
✅ Handles large PDFs via per-page chunking
✅ Works in Google Colab + Streamlit with public link
✅ Error-handling for rate limits, API exceptions
✅ Lightweight, easy to modify

🔧 Technologies Used
Python 3.11+

Google Gemini 1.5 API (v1)

Streamlit (Web Interface)

PyMuPDF (PDF Text Extraction)

PyNgrok / LocalTunnel (for Colab Public URL)
🔑 Setting up Google Gemini API Key
1) Visit Google AI Studio.
2)Generate an API Key.
3)Replace in app.py:
GOOGLE_API_KEY = "YOUR_GEMINI_API_KEY"


