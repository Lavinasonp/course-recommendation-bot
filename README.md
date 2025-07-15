# course-recommendation-bot
"A GenAI-powered chatbot that recommends courses using real-time search and summarization."
# 🤖 Course Recommendation Bot using Gen AI + RAG

This project builds an intelligent chatbot that recommends the **best online courses** based on your interests. It uses **generative AI** (summarization and semantic search) and **Retrieval-Augmented Generation (RAG)** to fetch and recommend learning paths.

---

## 🚀 Project Overview

- **Input:** User's interest (e.g., "data science", "UI design", "finance")
- **Output:** Top 3 summarized, AI-ranked course suggestions
- **Tech Used:** Hugging Face Transformers, Sentence Transformers, DuckDuckGo Search, Google Colab
- **Goal:** Help learners find the most relevant and updated courses using GenAI.

---

## 🧠 How It Works

1. User types a learning topic (e.g., "Python for data analysis").
2. The bot searches the internet (Coursera, edX, Udemy) using DuckDuckGo.
3. It summarizes top results using **BART** model from Hugging Face.
4. It ranks summaries using **sentence embeddings** and cosine similarity.
5. Finally, it recommends the **Top 3 courses** with brief AI-generated summaries.

---

## 📁 Files

- `course_bot_colab.ipynb`: Main Google Colab notebook
- `requirements.txt`: Install dependencies if running locally
- `README.md`: Project documentation

---

## ⚙️ Requirements

- Google Colab or Jupyter Notebook  
- Internet connection for model access (Hugging Face)

---

## 🛠️ Installation & Usage

1. Open the notebook in [Google Colab](https://colab.research.google.com/).
2. Install dependencies (first cell).
3. Run all cells step-by-step.
4. Type your learning topic when prompted.
5. Get summarized course recommendations with links!

---

## ✨ Example Output

| User Input             | Top Recommended Courses                       |
|------------------------|-----------------------------------------------|
| `data science`         | Summary 1: Learn DS with Python on Coursera...<br>Summary 2: Harvard's Data Science series... |
| `graphic design`       | Summary 1: UI/UX basics from Google on edX...<br>Summary 2: Adobe suite tutorials on Udemy... |

---

## 💡 Use Cases

- Smart educational advisors
- Career planning tools
- College/university recommendation chatbots
- Personal learning assistants

---

## 📜 License

This project is open-source and free to use for **educational and non-commercial** purposes.

---

## 🙌 Acknowledgements

- [Hugging Face Transformers](https://huggingface.co)
- [Sentence Transformers](https://www.sbert.net/)
- [DuckDuckGo Search API](https://pypi.org/project/duckduckgo-search/)
- [Google Colab](https://colab.research.google.com/)
