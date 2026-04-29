# Enhancing-Search-Intent-Understanding-for-Hinglish-Queries-using-Hybrid-NLP-Techniques
This project focuses on improving search engine understanding of Hinglish queries (a mix of Hindi and English written in Roman script). Traditional search systems struggle with such queries due to spelling variations, informal grammar, and code-mixing.

The system uses Hybrid NLP + Machine Learning techniques to accurately process, analyze, and classify user intent, resulting in more relevant and meaningful search results.

**Problem Statement**

Most search engines are optimized for English and fail to interpret Hinglish queries like:

"job chahiye near me"
"achha laptop under 50000"

This leads to:

1. Poor search accuracy
2. Misclassification of intent
3. Bad user experience

**Solution**

This project builds a Hinglish-aware NLP pipeline that:

Understands mixed-language queries
Normalizes spelling variations
Extracts the semantic meaning
Classifies user intent accurately

**Features**
🔍 Language Detection (Hindi / English / Hinglish)
✍️ Query Normalization using Hinglish lexicon & transliteration
🧠 Semantic Embeddings using transformer-based models
📊 Query Clustering (K-Means / similarity-based grouping)
🎯 Intent Classification
Informational
Navigational
Transactional
📈 Performance Evaluation
Accuracy
F1-score
NMI
ARI


**System Architecture**

The system follows a pipeline-based architecture:

User Query
   ↓
Preprocessing
   ↓
Language Detection
   ↓
Normalization (Lexicon + Transliteration)
   ↓
Embedding Generation (Transformers)
   ↓
Clustering + Classification
   ↓
Output (Intent + Insights)

**Tech Stack
💻 Programming Language
Python
📚 Libraries & Tools
Pandas
NumPy
Scikit-learn
Sentence Transformers
Matplotlib
