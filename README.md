# NLP Pipeline Demo

A Streamlit app that walks through a full NLP pipeline on user-entered text:

1. Sentence Tokenization
2. Word Tokenization
3. Stemming
4. Lemmatization
5. Stopword Removal
6. POS Tagging
7. Named Entity Recognition (NER)
8. Chunking

## Setup

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## Run

```bash
streamlit run app.py
```

Then open the local URL Streamlit prints (usually http://localhost:8501).
