# 📄 Azure Document Intelligence Dashboard

A modern **Streamlit-based OCR dashboard** powered by **Azure Document Intelligence** that allows users to analyze uploaded documents or image URLs and extract text using Azure AI OCR.

---

## 🚀 Features

✅ Upload documents for OCR analysis  
✅ Analyze images using a direct image URL  
✅ Enter Azure API Key and Endpoint dynamically  
✅ Extract text from PDFs and images  
✅ Download extracted OCR text  
✅ Clean and modern Streamlit dashboard UI  
✅ Supports multiple document/image formats

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **Azure Document Intelligence**
- **Azure Cognitive Services**
- **Requests Library**

---

## 📂 Project Structure

```bash
azure-document-intelligence/
│── app.py
│── requirements.txt
│── README.md
│── venv/
```

---

## 📋 Supported File Formats

The application supports:

- PDF (`.pdf`)
- PNG (`.png`)
- JPG (`.jpg`)
- JPEG (`.jpeg`)
- BMP (`.bmp`)
- TIFF (`.tiff`)

---

## ⚙️ Prerequisites

Before running the project, you need:

### 1. Azure Document Intelligence Resource

Create a **Document Intelligence Resource** in Azure Portal.

Get:

- **API Key**
- **Endpoint URL**

You can find them here:

**Azure Portal → Document Intelligence Resource → Keys and Endpoint**

Example Endpoint:

```txt
https://your-resource.cognitiveservices.azure.com/
```

---

## 🔧 Installation

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd azure-document-intelligence
```

---

### Step 2: Create Virtual Environment

```bash
python -m venv venv
```

---

### Step 3: Activate Virtual Environment

### Windows PowerShell

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.\venv\Scripts\Activate.ps1
```

### Windows CMD

```cmd
venv\Scripts\activate.bat
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

### Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Run the Streamlit app:

```bash
streamlit run app.py
```

After running, Streamlit will open automatically in your browser.

Usually at:

```txt
http://localhost:8501
```

---

## 🖥️ How to Use

### Option 1: Upload Document

1. Enter your **Azure API Key**
2. Enter your **Azure Endpoint**
3. Upload a document or image
4. Click **Analyze Uploaded Document**
5. View extracted text
6. Download OCR result

---

### Option 2: Analyze Image URL

1. Enter Azure credentials
2. Paste an image URL
3. Click **Analyze Image URL**
4. View extracted text
5. Download OCR output

---

## 🧠 Azure Model Used

This project uses Azure's:

### `prebuilt-read`

The **Prebuilt Read Model** extracts text from:

- Printed documents
- PDFs
- Scanned documents
- Images
- Handwritten text (limited support)

---

## 📦 Required Dependencies

Install using:

```bash
pip install -r requirements.txt
```

Dependencies:

```txt
streamlit
azure-ai-documentintelligence
azure-core
requests
```

---

## 🔮 Future Improvements

- Document summarization
- Multi-language translation
- Text-to-speech conversion
- Table extraction
- Key-value pair extraction
- Export results as PDF/DOCX

---

## 👨‍💻 Author

**Utsav Kumar**

Built using **Azure AI + Streamlit** for intelligent document OCR and analysis.

---

## 📜 License

This project is licensed for educational and personal use.
