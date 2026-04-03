# 🎙️ Meeting AI Assistant

An AI-powered application that converts meeting audio into structured insights including transcription and summarization.

---

## 🚀 Live Demo
🔗 Streamlit App: https://meeting-ai-assistant-new-gzy5ukfe9u3uparciqxadc.streamlit.app/

---

## 📊 Project Presentation
📌 PPT: https://docs.google.com/presentation/d/1vr13XWp1fBr88XfcO2k1A6Xv_-zFDEo5ddqq4OmWKb8/edit?usp=sharing

---

## 📑 Project Report
📄 Report: https://docs.google.com/document/d/1g3fMAFtLE1ERATU8lF_Tcp-wr0idN4lIWqiWQzs1OWk/edit?usp=sharing

---

## ✨ Features

- 🎤 Speech-to-Text using Vosk
- 📝 Automatic Meeting Transcription
- 👥 Speaker-aware formatting (basic diarization)
- ✨ AI-based Meeting Summarization
- 📂 Upload audio files for processing
- 📊 Real-time processing status updates

---

## 🏗️ Tech Stack

- **Frontend:** Streamlit  
- **Backend:** Python (Threaded pipeline)  
- **Speech Recognition:** Vosk  
- **NLP Model:** Hugging Face Transformers (GPT-2)  
- **Audio Processing:** SoundDevice, SoundFile  

---

## ⚙️ How It Works

1. Upload a `.wav` audio file
2. Audio is processed through pipeline:
   - Transcription (Vosk)
   - (Optional) Diarization
   - Summarization (Transformers)
3. Results displayed in UI:
   - Transcript
   - Diarized Output
   - Summary

---

