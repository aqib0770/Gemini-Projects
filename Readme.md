# Gemini AI Applications Suite

This repository contains a collection of applications that leverage Google's Gemini AI models for various document and image processing tasks.

## 🚀 Projects

### 1. Chat with PDF
A Streamlit application that allows users to have conversations with PDF documents using Gemini AI.

**Features:**
- Upload multiple PDF documents
- Extract and process text from PDFs
- Create vector embeddings for efficient text search
- Ask questions about the PDF content
- Get detailed AI-powered responses

### 2. Invoice Extractor
A multi-language invoice processing application that uses Gemini's vision capabilities.

**Features:**
- Upload invoice images (JPG, JPEG, PNG)
- Extract invoice information using AI
- Support for multiple languages
- Interactive Q&A about invoice contents

### 3. Vision Analysis
A general-purpose image analysis application powered by Gemini AI.

**Features:**
- Upload images (JPG, JPEG, PNG)
- Add custom prompts for specific analysis
- Get AI-generated descriptions and insights
- Interactive user interface

## 🛠️ Setup & Installation

1. **Clone the repository**
```bash
git clone https://github.com/aqib0770/Gemini-Projects.git
cd Gemini-Projects
```

2. **Install required dependencies**
```bash
pip install -r requirements.txt
```

3. **Obtain API Key**
- Sign up for a Gemini API key at [Google AI Studio](https://aistudio.google.com/app/apikey)
- Enable the Gemini API in your project



4. **Environment Setup**
- Create a `.env` file in the root directory
- Add your Gemini API key:
```
GEMINI_API_KEY=your_api_key_here
```


## 🚀 Usage

### Chat with PDF
```bash
streamlit run chatWithPdf.py
```
1. Upload PDF files using the sidebar
2. Click "Submit and process" to analyze the documents
3. Ask questions in the text area
4. Get AI-powered responses based on the PDF content

### Invoice Extractor
```bash
streamlit run InvoiceExtractor.py
```
1. Upload an invoice image
2. (Optional) Add specific prompts
3. Click "Tell me about the invoice" to get analysis

### Vision Analysis
```bash
streamlit run vision.py
```
1. Upload any image
2. (Optional) Add custom prompts
3. Click "Tell me about the image" for AI analysis

## 🔐 Security Notes
- Never commit your `.env` file
- Keep your API keys secure
- Use appropriate file permissions

