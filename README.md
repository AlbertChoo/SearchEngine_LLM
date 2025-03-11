# 🔎 LangChain - Chat with Search

This project is a chatbot powered by **LangChain** and **Streamlit**, enhanced with real-time search capabilities using **ArXiv, Wikipedia, and DuckDuckGo**. Users can interact with an intelligent assistant that retrieves relevant information from multiple sources.

## 🚀 Features
- **Conversational AI** powered by LangChain.
- **Real-time search** with Wikipedia, ArXiv, and DuckDuckGo.
- **Groq API integration** for LLM-powered responses.
- **Interactive UI** built with Streamlit.
- **Persistent chat history** for smooth user experience.

## 🛠️ Installation
### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-repo/langchain-search-chat.git
cd langchain-search-chat
```

### 2️⃣ Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate    # For Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set up environment variables
Create a `.env` file and add your **Groq API Key**:
```
GROQ_API_KEY=your_api_key_here
```

## ▶️ Usage
Run the Streamlit app:
```bash
streamlit run app.py
```

## 📌 How It Works
1. **User Input**: Enter a query in the chat interface.
2. **Search Agent**: The chatbot uses ArXiv, Wikipedia, and DuckDuckGo to retrieve relevant information.
3. **Groq LLM Processing**: The chatbot generates an intelligent response using **Llama3-8B-8192**.
4. **Interactive Display**: The conversation history is maintained, and responses are displayed in a chat format.

## ⚡ Example
```plaintext
User: What is machine learning?
Bot: Machine learning is a branch of AI that allows systems to learn from data...
```

## 🏗️ Tech Stack
- **Python** 🐍
- **LangChain** 🔗
- **Streamlit** 🎈
- **Groq API** 🤖
- **ArXiv API** 📚
- **Wikipedia API** 🌍
- **DuckDuckGo Search** 🦆

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Feel free to fork this repository, submit issues, or contribute improvements. PRs are welcome!

## 📬 Contact
For any questions, reach out via GitHub Issues or email at `your-email@example.com`.

---
✅ Built with ❤️ using **LangChain** and **Streamlit**

