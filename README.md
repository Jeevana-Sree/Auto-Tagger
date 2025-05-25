# AutoTagger – NLP-Based Tag & Topic Extractor

AutoTagger is a lightweight, beginner-friendly Natural Language Processing (NLP) project that extracts meaningful tags and detects dominant topics from long-form articles.

It combines classical NLP techniques like TF-IDF, POS tagging, and LDA topic modeling to analyze real-world text (e.g., blogs, articles, papers) and provide semantic summaries.

---

## Features

- Tag extraction using TF-IDF (Term Frequency-Inverse Document Frequency)
- POS Filtering with spaCy to keep only relevant nouns and proper nouns
- LDA Topic Modeling using Gensim to uncover 2–3 core themes from a document
- Paragraph-based topic modeling for better granularity

---

## Sample Output

Top Tags (TF-IDF + POS):
```
['accuracy', 'ai', 'allocation', 'artificial', 'bias', 'care', 'compliance']
```

LDA Topics:
```
Topic 1: healthcare, data, learning, integration, challenges, diagnostics  
Topic 2: models, patient, using, integrated, care  
Topic 3: data, medical, human, researchers, processing
```

---

## How It Works

1. Load a long-form article (on AI, healthcare, etc.)
2. Clean the text using regex, stopword removal, and token filtering
3. Extract top tags using TfidfVectorizer and keep only noun-type tokens
4. Split text into paragraphs and apply LDA for topic clustering
5. Print and interpret top tags and topics

---

## Why This Project?

This project is ideal for:
- NLP beginners looking to understand classical text processing
- Interview and academic projects that require explainable output
- AI content analysis tasks in blogs, reports, and research summaries

---

## Skills Used

- Python NLP (spaCy, NLTK)
- Unsupervised Topic Modeling (LDA)
- Semantic Tagging with TF-IDF
- POS filtering and lemmatization
- Text preprocessing and interpretation


