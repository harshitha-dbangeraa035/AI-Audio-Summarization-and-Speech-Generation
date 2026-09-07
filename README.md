# 🎙️ AI Audio Summarization and Speech Generation

An AI-powered n8n workflow that converts audio recordings into concise meeting notes and generates a spoken audio summary.

## 🚀 Features

- 🎤 Accepts an audio URL
- 📝 Converts speech to text using Groq Whisper
- 🤖 Summarizes the transcript using Google Gemini
- ✅ Identifies key points, action items, and decisions
- 🔊 Converts the summary into speech using Murf AI
- 🎧 Generates a downloadable final audio file

## 🔄 Workflow

Audio URL
↓
Download Input Audio
↓
Groq Whisper Transcription
↓
Gemini Meeting Summarizer
↓
Murf Voice Generation
↓
Download Final Audio

## 🛠️ Technologies

- n8n
- Groq Whisper
- Google Gemini
- Murf AI
- REST APIs
- Natural Language Processing
- AI-powered summarization
- Text-to-Speech

## 💡 Use Cases

- Meeting recordings
- Lecture recordings
- Interviews
- Podcasts
- Team discussions
- Educational content

## ⚙️ Setup

1. Import the workflow JSON into n8n.
2. Configure Groq credentials.
3. Configure Google Gemini credentials.
4. Configure Murf AI credentials.
5. Provide a direct audio URL.
6. Execute the workflow.

## 🔐 Security

API keys and credentials are not included in this repository.

Users must configure their own API credentials in n8n.

## 📌 Workflow Result

The workflow produces:

- Audio transcription
- AI-generated meeting notes
- Action items
- Decisions
- Voice-generated summary

## 👩‍💻 Author

Harshitha D Bangera
