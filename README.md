# NLP Chatbot — Conversational AI Using Deep Learning

## Project Overview

This project develops a conversational chatbot using Natural Language Processing (NLP) and deep learning techniques. The aim is to generate responses to user messages and investigate how neural network architectures can support conversational AI.

The project was developed using Python and PyTorch as part of my MSc Artificial Intelligence studies at De Montfort University.

## Technologies Used

- Python
- PyTorch
- Hugging Face Datasets
- Natural Language Processing (NLP)
- Recurrent Neural Networks (GRU/LSTM)
- Sequence-to-Sequence (Seq2Seq) Learning
- Attention Mechanisms
- NLTK
- NumPy, pandas, Matplotlib and Seaborn

## Dataset

The implementation uses the DialogSum dataset from Hugging Face to construct conversational input–response pairs.

Text preprocessing includes normalisation, tokenisation, vocabulary construction, padding and conversion into numerical sequences.

A small demonstration dataset is available as a fallback when the main dataset cannot be loaded.

## Model Development

The project includes:

1. **Dataset Preparation:** Load and preprocess conversational text.
2. **Vocabulary Construction:** Convert words into numerical representations.
3. **Seq2Seq Architecture:** Implement an encoder–decoder chatbot with attention.
4. **Model Training:** Use the Adam optimiser, teacher forcing and gradient clipping.
5. **Model Evaluation:** Analyse training and validation losses, BLEU scores and perplexity.
6. **Attention Visualisation:** Examine how the model attends to input words when generating responses.
7. **Model Comparison:** Implement an MLP-based chatbot baseline for comparison.

## Project Files

- `NLP-Chatbot-GitHub-Safe.ipynb` — Main notebook containing the chatbot implementation, training, evaluation and visualisation code.

## How to Run

1. Download or clone this repository.
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Install the required Python libraries.
4. Run the notebook cells in order.
5. Download the conversational dataset and train the chatbot.
6. Run the chatbot demonstration after training.

Some dataset-loading operations may require Hugging Face authentication. Access tokens should be provided securely and must not be stored directly in the notebook.

## Author

**Ahsan Khalid**

MSc Artificial Intelligence  
De Montfort University, United Kingdom

GitHub: https://github.com/ahsankhalid52-ai-dev# nlp-chatbot
Natural Language Processing chatbot developed using Python and deep learning techniques for conversational AI
