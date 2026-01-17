# 🧠 Low-Cost Smart Board – SIH 2023 Final Project

An AI-powered Smart Classroom Assistant designed and built by Team Tech Trojans for the Smart India Hackathon 2023 – Hardware Edition (Finals).

A self-contained, plug-and-play smart board system powered by Raspberry Pi, integrating voice intelligence, gesture control, smart notes, and classroom automation — all under ₹20,000.

🚫 No laptops
🚫 No external USB cables
🚫 No cloud dependency

Just plug in, power up, and go smart.

## 🎯 Project Highlights

🔌 Fully embedded Raspberry Pi–based system

🎤 Real-time voice monitoring with Speech-to-Text & decibel alerts

✋ Gesture-based slide control (touch-free)

📝 Smart note-taking, QR sharing & Text-to-Speech

📦 Standalone design – no laptops, no cloud

💰 Total cost < ₹20,000

🛠️ Elegant & portable custom enclosure

## ✨ Features
🎤 Voice Intelligence

Real-time Speech-to-Text transcription

Decibel level monitoring

Auto email alerts to HOD/Tutor on excessive noise

Live transcription & noise visualization via React UI

## ✋ Gesture-Based Slide Control

Hand tracking using OpenCV + cvzone

Navigate slides (Next / Previous) using simple gestures

Zero physical interaction required

## 📅 Smart Class Scheduler

Automatic hourly bell alerts

End-of-class detection with popup & TTS reminders

Fully config-driven schedule

## 📚 Text-to-Speech Assistant

Converts any text/note into natural speech

Instant playback using pyttsx3

Controlled via React interface

## 📝 Smart Notes

Rich-text note creation & editing

Save / load notes locally (.txt)

Ideal for class notes & instructions

## 📦 QR Code Generator

Generate QR codes for:

PPTs

Google Drive links

Built using segno

Students scan & instantly access materials

## ✅ Attendance System (Extendable)

Face-based attendance logging via webcam

Modular attendance.py for future upgrades

## 🛠️ Hardware Stack
Component	Description
💻 Raspberry Pi 4	Primary compute unit
📷 USB Camera	Gesture & voice capture
🔊 Speaker	Alerts & TTS
🖥️ HDMI Display	Smart board output
🪛 Custom Enclosure	Portable acrylic casing
⚡ Power Supply	Fully standalone
💻 Software Stack
Layer	Technology
UI / UX	React.js, Material UI, CSS
Backend API	Python Flask
AI / ML	OpenCV, speech_recognition, pyttsx3, cvzone
QR & Notes	segno, tkinter
Alerts	Brevo SMTP, Email, TTS
🚀 Setup & Installation
🧠 Backend (Flask + Python)
cd backend/
pip install -r requirements.txt
python app.py

## 🖼️ Frontend (React UI)
cd frontend/
npm install
npm start

## 🔐 Optional .env (Email Alerts)
EMAIL_USERNAME=your_email@gmail.com
EMAIL_PASSWORD=your_brevo_smtp_key
FLASK_SERVER_URL=http://127.0.0.1:5000

## 💰 Cost Breakdown
Item	Approx. Cost (₹) <br>
Raspberry Pi 4B	₹7,000 <br>
USB Camera & Mic	₹1,000 <br>
Speaker & Display	₹3,000 <br>
Acrylic Enclosure	₹1,000<br>
Misc. Electronics	₹1,000<br>
Development & Software	₹7,000 (DIY)<br>
Total	< ₹20,000
## 📊 Success Metrics
Metric	Value <br>
STT Accuracy	~91% (classroom noise)  <br>
Gesture Response Delay	< 0.4 sec<br>
Email Alert Latency	< 2 sec<br>
QR Code Generation	~1 sec<br>
TTS Response	Instant<br>
## 🏆 Submission Details
Category	Description
Hackathon	Smart India Hackathon 2023
Track	Hardware Edition – Finals
PS ID & Ministry	SIH1430 / Ministry of Education, India
Team	Tech Trojans
College	SKCET, Coimbatore
## 💡 Future Enhancements

Offline face-based attendance

Integration with school ERP systems

Analytics dashboard for HODs

Mobile companion application
