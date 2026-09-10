🤖 AI Meeting Minutes Generator

📌 Project No.: 14

👥 Group 5 — Group Members

1. 👩 Faiza Malik — 2507-1844
2. 👩 Sangkari Maniyarasu — 2503-0675
3. 👨 Ridhwan Mahamud Arpon — 2507-1809
4. 👨 Ahmed Estayak — 2507-1924

---

📋 Project Overview

The 🤖 AI Meeting Minutes Generator is an AI-powered system that generates meeting minutes from meeting audio. The system converts recorded meeting conversations into text and automatically analyzes the transcript to produce a concise meeting summary, important decisions, and actionable tasks.

🎯 Objectives

- 🎙️ Convert meeting audio to text using Speech-to-Text technology.
- 📝 Generate a concise and meaningful meeting summary.
- 💡 Identify important topics and decisions discussed during the meeting.
- ✅ Extract action items, responsible persons, and deadlines.

🛠️ Technologies Used

- 🐍 Python
- 🎤 OpenAI Whisper
- 🤖 OpenRouter AI
- 🌐 Streamlit

🔄 System Workflow

🎙️ Meeting Audio
⬇️
🎤 Whisper Speech-to-Text
⬇️
📄 Meeting Transcript
⬇️
🤖 OpenRouter AI
⬇️
📊 Meeting Summary + Action Items
⬇️
💻 Streamlit Application

✨ Features

1. 🎙️ Speech-to-Text

The system uses OpenAI Whisper to convert uploaded meeting audio into an accurate text transcript.

2. 📝 Meeting Summary

The AI analyzes the transcript and generates:

- 💬 Main topics discussed
- 📌 Important decisions
- 📋 Overall meeting summary

3. ✅ Action Items

The AI identifies and organizes:

- 📌 Task
- 👤 Person responsible
- 📅 Deadline

4. 💻 User Interface

Users can upload an MP3, WAV, or M4A meeting recording through the Streamlit interface and generate structured meeting minutes automatically.

🚀 How to Run

Install the required packages:

pip install -r requirements.txt

Then run the Streamlit application:

streamlit run app.py

🌐 The application will open in the browser, where users can upload their meeting recording and automatically generate professional meeting minutes.
