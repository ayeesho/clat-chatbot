
# CLAT Chatbot Prototype 🤖

## 📘 Overview
This project is a simple rule-based/NLP-powered chatbot that answers common CLAT-related queries using spaCy.

## ⚙️ Technologies Used
- Python
- Jupyter Notebook
- spaCy (`en_core_web_md`)

## 🛠️ Setup Instructions

1. Clone the repository or download the ZIP:
```bash
git clone https://github.com/your-username/clat-chatbot.git
cd clat-chatbot
```

2. Install dependencies:
```bash
pip install spacy
python -m spacy download en_core_web_md
```

3. Open the notebook using Jupyter:
```bash
jupyter notebook clat_nlp_chatbot.ipynb
```

## 💬 Sample Queries
- What is the syllabus for CLAT 2025?
- How many questions in the English section?
- What was the cut-off for NLSIU Bangalore?

## 💡 Approach Summary
- A mini FAQ is stored as a list of Q&A pairs.
- User input is processed using spaCy and compared using vector similarity.
- The closest question is matched and the corresponding answer is returned.

## 🚀 Future Improvements
- Use sentence transformers for better accuracy.
- Add a Streamlit interface for web-based use.
