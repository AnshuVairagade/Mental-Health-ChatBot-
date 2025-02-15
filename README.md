# 🌟 Mental Health Chatbot

## 📝 Project Description

MindMate_Bot is an AI-driven mental health chatbot designed to provide empathetic and evidence-based responses to user queries. It leverages advanced natural language processing (NLP) and retrieval-augmented generation (RAG) techniques to deliver accurate and context-aware answers. The chatbot is built using the **LangChain** framework, **HuggingFace embeddings**, and the **Groq API** for high-performance LLM inference.

## ✨ Features

- 🖥️ Conversational AI: Empathetic and context-aware responses using the Llama-3.3-70b model.
- 🧠 Vector Database: Store and retrieve embeddings using Chroma DB.
- 🔄 Custom Prompting: Tailored prompts for mental health-related queries.
- 🎨 Interactive Chat Interface: Real-time interaction with the chatbot.

## 🛠️ Tech Stack

** 🔰Frameworks:** LangChain
** 🔰LLM:** Groq API (Llama-3.3-70b)
** 🔰Embeddings:** HuggingFace (sentence-transformers/all-MiniLM-L6-v2)
** 🔰Vector Database:** Chroma DB
** 🔰Document Loader:** PyPDFLoader
** 🔰Text Splitting:** RecursiveCharacterTextSplitter
** 🔰Programming Language:** Python

## 📂 Project Structure
- MindMate_Bot/  
- ├── main.py                  # Main script to run the chatbot  
- ├── data/                   # Directory containing PDF documents  
- ├── chroma_db/              # Persisted Chroma vector database  
- ├── README.md               # Project documentation  
- └── requirements.txt        # Python dependencies  



### 🏆 Key Achievements
- Developed a mental health chatbot using a knowledge base built from 50+ research paper PDFs.
- Optimized Llama-3.3-70B-Versatile for 30% more accurate, domain-specific responses by restricting it to the vector database.
- Utilized sentence transformers and pypdf for PDF extraction with 512 embeddings, maintaining a 50-character overlap for
context retention.

### 📸 Screenshots

- Domain knoweldge prompt 
![Screenshot 2025-02-15 224643](https://github.com/user-attachments/assets/74969b58-a1c8-474b-80fe-5a6581ab32bd)


- Global Knowlege promt
![Screenshot 2025-02-15 224705](https://github.com/user-attachments/assets/ade06047-8037-4574-ba0e-e88c3a44ae83)


## 🤝 Contributing
- Contributions are welcome! If you'd like to contribute:
- Fork the repository.
- Create a new branch (git checkout -b feature/YourFeatureName).
- Commit your changes (git commit -m 'Add some feature').
- Push to the branch (git push origin feature/YourFeatureName).
- Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

