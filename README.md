Language Translator

---

```markdown
# 🌐 Language Translator App (Text, Speech, and PDF)

This project is a powerful multilingual **Language Translator** built using **Python** and **Tkinter**, integrating **Natural Language Processing (NLP)** tools like **Google Translate API**, **Speech Recognition**, **Text-to-Speech (gTTS)**, and **PDF parsing**. It allows users to translate between multiple Indian languages using text input, speech recognition, and even directly from PDF documents.

## 🚀 Features

- 🔤 Text Translation: Translate text from English to Indian languages like Hindi, Tamil, Telugu, Gujarati, Marathi, and more.
- 🎙️ Speech-to-Text and Translation: Recognizes spoken language, detects its language, translates it, and plays the audio in the target language.
- 📄 PDF Translation: Extracts and translates text from PDF files into Indian languages.
- 🔊 Text-to-Speech (TTS): Converts translated text to speech for audio playback.
- 📦 GUI built with Tkinter for a clean, user-friendly experience.

## 🛠️ Tech Stack / Libraries Used

- Python (Core programming language)
- Tkinter (For GUI)
- googletrans (For translating text)
- speech_recognition (To capture and recognize voice)
- gTTS (Google Text-to-Speech) (To convert text into speech)
- PyPDF2 (To read text from PDF files)
- langdetect (To auto-detect spoken language)
- pygame (To play audio)

## 📦 Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/language-translator-app.git
   cd language-translator-app
   ```

2. Install required libraries
   ```bash
   pip install tkinter googletrans==4.0.0-rc1 PyPDF2 gTTS pygame speechrecognition langdetect translate
   ```

> 💡 *Ensure your device has a microphone and audio output enabled for full functionality.*

## ▶️ How to Use

### 1. Text Translator
- Enter text in English.
- Select the target Indian language.
- Click “Translate” to get the translated output in a text box.

### 2. Speech Translator
- Click “Start Speech Recognition.”
- Speak a sentence.
- The app will detect the language, translate it to English, and speak it out loud.

### 3. PDF Translator
- Upload a PDF using the "Upload PDF" button.
- Select your target language.
- The extracted text will be translated and displayed in the text area.

 

## 📌 Future Enhancements
- Add support for more languages.
- Improve accuracy using AI models like transformers (e.g., BERT or MarianMT).
- Integrate OCR for scanned PDF/image translation.
- Provide support for offline translation using on-device models.

## 👨‍💻 Author

Created by Venkata Sarma –  https://github.com/VenkataSarma/Language_Translator

 
---
