# HR Policy RAG Assistant 🤖

An AI-powered assistant that helps users find information from HR policy documents using **Retrieval-Augmented Generation (RAG)** and semantic search.

## 🚀 Live Demo

**[👉 Try the HR Policy RAG Assistant](https://4f578636cec29e62dd.gradio.live)**

*Note: This Gradio share link is temporary and may stop working when the hosting session ends.*

## 📌 Project Overview

HR policy documents can be lengthy and difficult to search manually. This project provides an interactive interface where users can ask questions and retrieve relevant information from HR policy documents.

The system uses text embeddings and similarity search to identify policy passages relevant to a user's query.

## ✨ Features

- 📄 Retrieve relevant information from HR policy documents.
- 🔍 Semantic search using text embeddings.
- 🧠 Find policy passages related to user questions.
- 💬 Interactive question-and-answer interface using Gradio.
- ⚡ Faster access to relevant policy information.

## 🛠️ Technologies Used

- **Python** — core programming language.
- **Sentence Transformers** — generates text embeddings.
- **FAISS** — performs similarity search over embeddings.
- **NumPy** — handles numerical arrays and vectors.
- **Gradio** — provides the interactive user interface.

## ⚙️ How It Works

1. Load the HR policy documents.
2. Convert the documents into smaller text chunks.
3. Generate embeddings for the text chunks.
4. Convert the user's question into an embedding.
5. Use FAISS to retrieve relevant text chunks.
6. Display the retrieved information to the user.

## 💻 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/hr-policy-rag-assistant.git
cd hr-policy-rag-assistant
```

Replace `YOUR_USERNAME` with your GitHub username.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

Open the `.ipynb` notebook in Google Colab or Jupyter Notebook and execute the cells in order.

## 📂 Project Structure

```text
hr-policy-rag-assistant/
├── hr-policy-rag-assistant.ipynb
├── README.md
└── requirements.txt
```

The notebook filename above is illustrative; use the actual filename in your repository.

## 🔮 Future Improvements

- Integrate an LLM to generate natural-language answers from retrieved passages.
- Display source references for answers.
- Support multiple HR policy documents and file formats.
- Improve retrieval accuracy and document handling.
- Deploy the application using a persistent hosting service.

## 🔐 Security

Do not commit API keys, `.env` files, confidential HR documents, or personal information to a public repository.

## 👩‍💻 Author

**Chinmitha**

