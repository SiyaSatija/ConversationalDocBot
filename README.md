# 🚀 Conversational-DOCBOT

Conversational-DOCBOT is an **interactive Retrieval-Augmented Generation (RAG) application** that enables users to **upload PDFs and chat with them** using **Streamlit**. It integrates **Gemini Vision** for image analysis, **ChromaDB** for vector storage, and **Groq's LLaMA 3.3** model for AI-powered responses.

---

## 🔥 Features

✅ **PDF Processing** – Extracts **text** and **images** from PDFs  
✅ **Image Analysis** – Uses **Gemini Vision** to analyze images, tables, and graphs  
✅ **Vector Storage** – Stores extracted data in **ChromaDB** for efficient retrieval  
✅ **Conversational AI** – Enables **chat-based interactions** with PDFs  
✅ **Streamlit UI** – Simple and interactive **web interface**  

---

## 🛠️ Tech Stack

- **Python, Streamlit**
- **LangChain, ChromaDB, Hugging Face Embeddings**
- **Gemini Vision** for image insights
- **LLaMA 3.3 70B (via Groq)** for response generation
- **PyMuPDF (Fitz)** for PDF text/image extraction

---

## 🚀 How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/SiyaSatija/ConversationalDocBot.git
cd Conversational-DOCBOT
```

### 2️⃣ Create and activate a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
pip install langchain-community
```

### 4️⃣ Set up environment variables (`.env` file)
Create a `.env` file in the project root:
```
GEMINI_API_KEY=your_gemini_api_key
GROQ_API_KEY=your_groq_api_key
HF_TOKEN=your_huggingface_token
```

Get your free API keys from:
- **Gemini** → [aistudio.google.com](https://aistudio.google.com)
- **Groq** → [console.groq.com](https://console.groq.com)
- **HuggingFace** → [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)

### 5️⃣ Run the Streamlit app
```bash
streamlit run complete.py
```

---

## 📌 Usage

1️⃣ **Upload a PDF**  
2️⃣ **Extract text & images** automatically  
3️⃣ **Analyze images** using **Gemini Vision**  
4️⃣ **Store extracted data** in **ChromaDB**  
5️⃣ **Chat with your document** using an AI-powered interface  
6️⃣ **Receive accurate, context-aware responses**  

---

## ⚠️ Notes

- The `chroma_db/` folder is not included in the repo — it is generated automatically when you upload a PDF.
- Do **not** commit your `.env` file — it contains sensitive API keys.
- On first run, the HuggingFace embedding model (`all-MiniLM-L6-v2`, ~90MB) will be downloaded and cached automatically.

---

## 🎯 Future Improvements

📊 **Advanced Data Visualization** for extracted insights  
🤖 **Multi-LLM Support** for diverse responses  
💬 **Chat history** to maintain conversation context across queries  

---

🛠 **Built for seamless document understanding and AI-powered insights.** 🚀✨
