# NLP Pipeline for Indian Languages (Hindi & Kannada)

This project implements an end-to-end Natural Language Processing (NLP) pipeline
tailored for morphologically rich Indian languages such as Hindi and Kannada.

Unlike standard English-centric NLP workflows, this project explores challenges
specific to Indic scripts, including agglutination, subword formation, and
cross-lingual entity recognition.

---

## Key Features

- Unicode normalization and script-specific text cleaning
- Custom implementation of:
  - Byte Pair Encoding (BPE)
  - WordPiece tokenization
- N-gram analysis for phrase-level patterns
- Morphological analysis using:
  - Stemming (rule-based)
  - Lemmatization (neural)
- Syntactic analysis using POS tagging (Hindi)
- Cross-lingual Named Entity Recognition (NER) using multilingual transformers

---

## Languages Covered
- Hindi (Devanagari)
- Kannada (Kannada script)

---

## Highlights

- Demonstrates why standard NLP pipelines fail for agglutinative languages
- Compares subword tokenization strategies on real Indic text
- Shows how multilingual transformer models bridge low-resource language gaps

---

## Tech Stack

- Python
- HuggingFace Transformers
- Stanza
- Indic NLP Library
- Snowball Stemmer
