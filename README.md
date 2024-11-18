# Multilingual Speech-to-English Translation System

## Overview
The **Multilingual Speech-to-English Translation System** is an advanced application designed to translate spoken language into English in real-time or batch mode. It leverages cutting-edge machine learning models and web technologies to deliver accurate and efficient translations.

This project showcases how pre-trained language models can be fine-tuned for high performance in multilingual scenarios, making it suitable for applications in education, accessibility, and cross-cultural communication.

---

## Key Features
- **Speech-to-Text Conversion**: Converts speech in multiple languages into text.
- **Language Translation**: Translates detected text into English using fine-tuned Hugging Face models.
- **User-Friendly Interface**: Intuitive React-based interface for seamless user interaction.
- **Scalable API**: Powered by FAST API for robust backend operations.
- **Real-Time Processing**: Processes speech input with minimal latency.
- **Multilingual Support**: Supports a variety of languages and accents.

---

## Technologies Used
- **Backend**: Python, FAST API
- **Machine Learning**: Hugging Face Transformers (fine-tuned pre-trained models)
- **Frontend**: React, HTML, CSS, JavaScript
- **Additional Tools**: Audio processing libraries, RESTful APIs

---

## Project Architecture
1. **Audio Input**: Accepts audio via file upload or real-time recording.
2. **Speech Recognition**: Transforms speech into text using a speech-to-text engine.
3. **Text Translation**: Translates the recognized text into English.
4. **Output**: Displays or returns the English translation to the user.

---

## Setup and Installation

### 1. Clone the Repository
```bash
git clone https://github.com/mePriyansh/Multilingual-speech-to-English-translation-system.git
cd Multilingual-speech-to-English-translation-system
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the FastAPI server
```bash
uvicorn main:app --reload
```
### 4. Start the Frontend
```bash
npm install
npm start
```

