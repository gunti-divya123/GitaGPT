# 📖 GitaGPT – AI-Powered Bhagavad Gita Assistant

🧘 Explore the wisdom of the Bhagavad Gita through an intelligent chatbot that provides thoughtful guidance, self-reflection, and context-aware conversations.

##  Demo Video

🔗 [Click here to watch the GitaGPT demo video](https://drive.google.com/file/d/1MThcY_Ok7jIbBLl1tfDeY8AurlMMwyHL/view?usp=sharing)



---

# 🕉️ GitaGPT – Inner Peace Edition

An AI-powered spiritual assistant that combines the timeless wisdom of the **Bhagavad Gita** with **Artificial Intelligence** to provide thoughtful guidance, self-reflection, and meaningful conversations.

---

# 📖 About the Project

In today's busy lifestyle, people often seek guidance, motivation, and peace of mind. **GitaGPT** is designed to bridge the gap between ancient spiritual wisdom and modern AI technology.

Instead of giving simple answers, the application understands the user's query, retrieves the most relevant Bhagavad Gita verse, and generates meaningful responses that encourage self-reflection and personal growth.

The project is built using a **Retrieval-Augmented Generation (RAG)** architecture to ensure that every response is based on authentic teachings from the Bhagavad Gita.

---

# ✨ Key Features

🤖 **AI-Powered Chatbot**  
Interact with an intelligent chatbot through a simple and user-friendly Streamlit interface.

📚 **Bhagavad Gita Knowledge Base**  
Retrieves relevant verses from a curated dataset containing **110+ important Bhagavad Gita verses**.

🧠 **Context-Aware Responses**  
Uses **Gemma 2B** with Retrieval-Augmented Generation (RAG) to provide meaningful and philosophical responses.

🌐 **Multilingual Support**  
Displays verses in **English, Sanskrit, and Telugu** for better understanding.

⚡ **Semantic Search**  
Uses **TensorFlow Universal Sentence Encoder** and **ChromaDB** for accurate verse retrieval.

❤️ **Empathetic Guidance**  
Designed to provide calm, motivational, and spiritually meaningful conversations.

💻 **Runs Locally**  
Works completely on your local machine using open-source technologies.

---

# 🛠️ Tech Stack

### 💻 Frontend
- Streamlit

### 🐍 Programming Language
- Python

### 🤖 Large Language Model
- Gemma 2B (via Ollama)

### 🧠 Embedding Model
- TensorFlow
- Universal Sentence Encoder (TensorFlow Hub)

### 🗄️ Vector Database
- ChromaDB

### ⚙️ Architecture
- Retrieval-Augmented Generation (RAG)

---

# 🔄 Project Workflow

1️⃣ User enters a question through the chatbot.

2️⃣ The query is converted into vector embeddings using the Universal Sentence Encoder.

3️⃣ ChromaDB searches the knowledge base for the most relevant Bhagavad Gita verse.

4️⃣ The retrieved verse is combined with the user's question.

5️⃣ Gemma 2B generates a meaningful response based on the retrieved verse.

6️⃣ The chatbot displays the response along with the relevant scripture.

---

# 🚀 Getting Started

## 📌 Prerequisites

- Python 3.9+
- Ollama
- Git

---

## ⚙️ Installation

### 📥 Clone the Repository

```bash
git clone https://github.com/your-username/GitaGPT.git

cd GitaGPT
```

### 🐍 Create Virtual Environment

```bash
python -m venv gita
```

### ▶️ Activate Virtual Environment

Windows

```bash
gita\Scripts\activate
```

Linux/macOS

```bash
source gita/bin/activate
```

### 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

### 🤖 Download Gemma Model

```bash
ollama pull gemma:2b
```

### ▶️ Run the Application

```bash
streamlit run app.py
```

Open your browser and visit:

```
http://localhost:8501
```

---

# 📈 Future Enhancements

🚀 Full Telugu User Interface

📖 Support for all **700 Bhagavad Gita verses**

🎤 Voice-to-Text Interaction

🌍 Additional Indian Language Support

📊 User Feedback & Rating System

📱 Mobile-Friendly Interface

☁️ Cloud Deployment

⚡ Performance Optimization

---

# 🤝 Contributing

We welcome contributions from developers, researchers, and Bhagavad Gita enthusiasts.

You can contribute by:

✅ Adding more Bhagavad Gita verses

✅ Improving English and Telugu translations

✅ Writing better verse commentaries

✅ Supporting additional regional languages

✅ Improving semantic search

✅ Optimizing application performance

✅ Reporting bugs and issues

✅ Enhancing project documentation

Every contribution helps improve the project and makes spiritual guidance more accessible to everyone.

---

# 🙏 Acknowledgements

Special thanks to:

📖 **Swami Sivananda** for the public-domain English translation of the Bhagavad Gita.

🌸 Contributors of traditional Telugu translations.

💙 **Streamlit**

🧠 **TensorFlow & TensorFlow Hub**

🤖 **Ollama**

🗄️ **ChromaDB**

🌍 The Open-Source AI Community

---

# ⭐ If you like this project, don't forget to give it a Star!
