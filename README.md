CodeAlpha Artificial Intelligence Internship Projects

This repository contains the three AI tasks completed during the CodeAlpha Artificial Intelligence Internship, implemented in Python using Google Colab.
Each task demonstrates different areas of AI — NLP, Chatbot systems, and Music Generation using Deep Learning.


Table of Contents:
1. Task 1 — Language Translation Tool
2. Task 2 — Chatbot for FAQs
3. Task 3 — Music Generation Using Lakh MIDI Dataset
4. Project Requirements
5. Results & Outputs
6. Future Enhancements
7. References


🗣️ Task 1 — Language Translation Tool

📘 Objective

To build an AI-powered text translation system that allows users to input text in one language and translate it into another language using NLP models or Google Translate API.

🧠 Technologies Used

•Python
•googletrans library (Google Translate unofficial API)
•ipywidgets for GUI
•gTTS (Google Text-to-Speech) for voice output


⚙️ Implementation

•User inputs text and selects source/target languages.
•The system translates text using the Google Translate API.
•Optional: Converts translated text to speech and allows copying.


🧩 Features

•Auto language detection
•Translation between 100+ languages
•Audio playback using text-to-speech
•GUI built with ipywidgets in Colab


📄 Example Output

Input: Hello, how are you?
Translated (English → French): Bonjour, comment ça va ?



🤖 Task 2 — Chatbot for FAQs

📘 Objective

To develop a rule-based and NLP-powered chatbot that can answer Frequently Asked Questions (FAQs) using semantic matching and text processing.

🧠 Technologies Used

•Python
•pandas, scikit-learn (TF-IDF & Cosine Similarity)
•sentence-transformers (optional: semantic embeddings)
•nltk for text preprocessing


⚙️ Implementation

•FAQ dataset stored in CSV format (question, answer).
•Texts are cleaned and vectorized using TF-IDF or embeddings.
•Cosine similarity identifies the most relevant answer.
•The bot continuously interacts with users until they exit.


🧩 Features

•Responds to questions semantically similar to stored FAQs
•Learns from additional FAQs dynamically
•Supports fallback response for unmatched queries


📄 Example Conversation

You: How can I reset my password?
Bot: Use the 'Forgot Password' link on the login page and follow the instructions.



🎶 Task 3 — Music Generation Using Lakh MIDI Dataset

📘 Objective

To train an LSTM-based neural network to generate new musical compositions using the Lakh MIDI Dataset (Clean).

🧠 Technologies Used

•TensorFlow / Keras
•music21 and pretty_midi for MIDI processing
•numpy, tqdm, matplotlib
•Dataset: Lakh MIDI Clean


⚙️ Implementation Steps

1. Dataset Loading — unzip and parse MIDI files.
2. Preprocessing — convert notes/chords/rests into token sequences.
3. Model Training — LSTM learns the next note prediction.
4. Music Generation — model predicts new sequences, which are converted back to MIDI format.



🧩 Features

•Generates original musical sequences
•Supports variable sequence length and vocabulary size
•Uses embeddings + stacked LSTM layers for sequential learning


📄 Example Output

Input Seed: 40-note sequence

Output: generated_from_lakh.mid (AI-generated music file)



⚙️ Project Requirements

•Python:3.10+
•TensorFlow:2.12.0
•scikit-learn:latest
•music21:latest
•gTTS:latest
•googletrans:4.0.0-rc1
•sentence-transformers:latest


🔮 Future Enhancements

•Language Translation: Integrate with official Google Cloud or Microsoft Translator APIs for enterprise accuracy.
•Chatbot: Deploy using Flask or Streamlit for a web-based user interface.
•Music Generation: Fine-tune with Transformers (Music Transformer, MuseNet) for higher-quality compositions.



📚 References

•Googletrans Library
•Scikit-learn Documentation
•Lakh MIDI Dataset
•TensorFlow Keras LSTM Guide
•Music21 Documentation



🏁 Author

Siddesh B. Demse

Artificial Intelligence & Data Science (AIDS)
SPPU | CodeAlpha AI Internship (2025)
