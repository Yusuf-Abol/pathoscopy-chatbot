[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yusuf-Abol/pathoscopy-chatbot/blob/main/sandbox/pathoscopy.ipynb)



# PathoScopy: Medical Knowledge Retrieval Chatbot

## Overview

> PathoScopy is a medical question-answering chatbot built using a Retrieval-Augmented Generation (RAG) approach. It retrieves  relevant medical text passages from a curated corpus and generates responses grounded in the provided context. The project focuses on cardiovascular conditions, including cardiogenic shock and related disorders.

## Key Features

* Retrieves contextually relevant passages from a local corpus.
* Generates cited responses using the **microsoft/Phi-3-mini-4k-instruct** model.
* Displays sources used for each response.
* Handles unknown or missing information gracefully.
* Implemented and tested in Google Colab.

## Technologies Used

| Component            | Description                      |
| -------------------- | -------------------------------- |
| Language Model       | microsoft/Phi-3-mini-4k-instruct |
| Retriever            | FAISS Vector Store               |
| Embeddings           | Sentence-Transformers            |
| Environment          | Google Colab & Kaggle            |
| Programming Language | Python                           |

## Example Interaction

```
=== PathoScopy AI Chatbot Ready! ===
User: What is cardiogenic shock?

PathoScopy: Cardiogenic shock occurs when there is severe dysfunction of the heart muscle leading to insufficient perfusion of organs due to decreased pump action by the heart. It often follows events such as myocardial infarction and is associated with high mortality if not treated promptly.

Sources:
- Source 1: Multicenter registry of angioplasty therapy of cardiogenic shock: initial and long-term survival.
- Source 2: Usefulness of blood lactate as a predictor of shock development in acute myocardial infarction.
```

## Project Structure

```
PathoScopy/
├── README.md               # Project documentation
└── Sandbox/
    └── PathoScopy.ipynb   # Main notebook &  RAGs chatbot
```

## How to Run

1. Open `PathoScopy.ipynb` in [Google Colab](https://colab.research.google.com/).
2. Upload your dataset of medical abstracts or papers.
3. Run all cells to initialize the chatbot.
4. Interact with the chatbot in the notebook terminal.

Example:

```
User: What causes cardiogenic shock?
User: Can cardiogenic shock occur without a heart attack?
User: exit
```

## Future Improvements

* Add a web-based interface using Streamlit or Gradio.
* Expand the dataset to include other medical specialties.
* Integrate live PubMed API access for updated sources.

