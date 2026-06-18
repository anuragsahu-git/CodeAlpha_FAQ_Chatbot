# CodeAlpha FAQ Chatbot

An intelligent FAQ chatbot developed as part of the CodeAlpha Artificial Intelligence Internship Program. This project uses Natural Language Processing (NLP) techniques to understand user queries and provide the most relevant answers from a predefined FAQ dataset.

The chatbot is designed to improve information retrieval by matching user questions with stored FAQs using TF-IDF vectorization and cosine similarity. It also includes voice interaction features to enhance the user experience.

---

## Project Overview

Finding accurate information quickly can be challenging when users have repetitive questions. This chatbot addresses that problem by automatically identifying the most relevant FAQ and returning the best possible answer in real time.

The application provides a clean and interactive interface built with Streamlit, making it easy for users to interact through both text and voice.

---

## Features

* NLP-based question understanding
* FAQ matching using TF-IDF vectorization
* Cosine similarity for accurate answer retrieval
* Interactive Streamlit web interface
* Voice-to-text support for user queries
* Text-to-speech functionality for chatbot responses
* Fast and responsive user experience
* Easy-to-maintain FAQ knowledge base

---

## Technologies Used

* Python
* Streamlit
* NLTK
* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity
* Speech Recognition
* Text-to-Speech (TTS)

---

## How It Works

1. The user enters a question through text or voice.
2. The query is cleaned and preprocessed using NLP techniques.
3. TF-IDF converts the text into numerical vectors.
4. Cosine similarity compares the query with stored FAQs.
5. The most relevant FAQ is identified.
6. The chatbot displays the corresponding answer.
7. Optionally, the answer can be spoken aloud using text-to-speech technology.

---

## System Workflow

```text
User Question
       ↓
Text Preprocessing
       ↓
TF-IDF Vectorization
       ↓
Cosine Similarity Matching
       ↓
Best FAQ Selection
       ↓
Chatbot Response
       ↓
Voice Output (Optional)
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/anuragsahu-git/CodeAlpha_FAQ_Chatbot.git
```

Navigate to the project folder:

```bash
cd CodeAlpha_FAQ_Chatbot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## Application Preview

Add screenshots of the chatbot interface here after deployment.

Example:

* Home Screen
* Chat Interface
* Voice Interaction Feature

---

## Internship Objective

The objective of this project is to demonstrate the practical application of Natural Language Processing techniques for building an intelligent FAQ assistant capable of understanding user queries and providing relevant responses efficiently.

---

## Author

**Anurag Sahu**

Artificial Intelligence Intern – CodeAlpha

GitHub: https://github.com/anuragsahu-git

---

## License

This project was developed for educational and internship purposes under the CodeAlpha Artificial Intelligence Internship Program.
