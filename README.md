# Mental-Health-chatbot
# Pandora: Mental Health Chatbot

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow 2.x](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Pandora is a therapeutic AI assistant designed to provide empathetic, conversational support for mental health‑related discussions. Built with TensorFlow and Keras, it uses a deep learning model to classify user input into one of over 100 predefined intents and returns an appropriate, compassionate response.

> **⚠️ Disclaimer:** This chatbot is **not a substitute for professional mental health care**. It is intended for general conversation and informational purposes only. If you are in crisis or need immediate help, please contact a qualified mental health professional or a crisis hotline in your area.

---

## ✨ Features

- **Intent classification** – Recognizes user statements about emotions, symptoms, general questions, and more.
- **Context‑aware responses** – Returns one of several possible responses per intent to keep conversations natural.
- **Educational facts** – Provides information about mental health conditions, treatments, and coping strategies.
- **Safe & non‑judgmental** – Designed to listen and respond without stigma.
- **Easy to extend** – Add new intents or responses by editing the `dataset.json` file and retraining.

---

## 📁 Dataset

The model is trained on [`dataset.json`](dataset.json), which contains over **200 intent categories**. Each intent includes:

- `tag` – a unique identifier (e.g., `greeting`, `sad`, `fact-1`)
- `patterns` – a list of example user messages
- `responses` – a list of possible bot replies

The dataset covers greetings, emotional states (sad, stressed, anxious, etc.), questions about mental health, therapy, medication, coping mechanisms, and many factual topics.

---

## 🔧 Requirements

Install the required Python packages:

```bash
pip install tensorflow numpy scikit-learn
