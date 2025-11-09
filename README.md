[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yusuf-Abol/Pathoscopy/blob/main/Pathoscopy.ipynb)


# Pathoscopy: Medical Knowledge Retrieval Chatbot

## Overview
Pathoscopy is a Retrieval-Augmented Generation (RAG) chatbot that answers medical questions using a curated corpus of medical abstracts. The chatbot provides source citations and can indicate when no relevant information is available.

## Features

- FAISS + Sentence Transformers for document retrieval
- microsoft/Phi-3-mini-4k-instruct for LLM responses
- Context-aware answers with source citations
- Google Colab
- Kaggle

## Example Interaction
**User:** What is Cardiogenic shock?  
**AI Response:** Cardiogenic shock occurs when there is insufficient circulation due to heart dysfunction after events like myocardial infarction.  
**Sources:** Source 3, Source 4
