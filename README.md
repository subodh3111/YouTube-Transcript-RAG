# 📺 YouTube Transcript RAG (TubeSage)

**TubeSage** is a Retrieval-Augmented Generation (RAG) system that enables users to ask questions about YouTube videos based on their transcripts. It uses LangChain, FAISS, and Hugging Face models to extract, embed, retrieve, and generate responses intelligently — without relying on paid APIs.

---

## 🚀 Features

- 🎞️ Extracts video transcripts using `youtube-transcript-api`
- 🧠 Embeds and splits transcripts using `SentenceTransformers`
- 📂 Stores embeddings using FAISS vector database
- 🔍 Retrieves relevant chunks for user questions
- 💬 Uses Hugging Face models (like `Flan-T5`) for response generation
- 🆓 Fully open-source & free to run (no OpenAI API required)

---

## 🧠 Tech Stack

- [LangChain](https://github.com/langchain-ai/langchain)
- [FAISS](https://github.com/facebookresearch/faiss)
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)
- [Sentence Transformers](https://www.sbert.net/)
- [YouTube Transcript API](https://pypi.org/project/youtube-transcript-api/)
- Python 3.8+

---

## 📦 Installation

```bash
pip install youtube-transcript-api langchain-community langchain-openai \
            faiss-cpu tiktoken python-dotenv langchain-huggingface
