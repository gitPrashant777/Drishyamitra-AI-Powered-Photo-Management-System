🚀 Drishyamitra
AI Powered Intelligent Photo Management System
<p align="center">

AI-driven platform that automatically organizes, searches, and shares photos using deep learning and conversational AI.

</p>
🌟 Overview

Drishyamitra is an AI-powered photo management system designed to transform the way people interact with their digital memories.

Traditional galleries require manual sorting and searching. Drishyamitra solves this by combining:

Deep Learning Face Recognition

Natural Language Search

Automated Photo Organization

Smart Photo Sharing

Users can simply type commands like:

Show me photos of Mom from Diwali 2023
Send John's pictures to WhatsApp

The AI processes the request and performs the action automatically.

✨ Key Features
🤖 AI Face Recognition

Automatically detects and identifies people in photos using advanced deep learning models.

🧠 Smart Photo Organization

Images are automatically grouped into intelligent folders such as:

Family

Trips

Events

Celebrations

Personal albums

💬 Conversational AI Chatbot

Interact with your photo library like chatting with an assistant.

Example queries:

Show photos of Priya from last month
Find pictures of Dad from my Goa trip
Email birthday photos to Mom
📤 Automated Photo Sharing

Instantly share photos through:

Gmail integration

WhatsApp Web API

🔐 Secure Data Handling

The system ensures:

Encrypted face embeddings

Token-based authentication

Secure API communication

🧠 AI Models Used

Drishyamitra integrates powerful computer vision models:

Model	Purpose
Facenet512	Face recognition
RetinaFace	Face detection
MTCNN	Multi-face detection

These models allow the system to identify individuals across thousands of photos accurately.

🏗 System Architecture
           React Frontend
                 │
                 │
           REST API Layer
             (Flask)
                 │
     ┌───────────┴───────────┐
     │                       │
 Face Recognition       NLP Chatbot
 (DeepFace Models)      (Groq API)
     │                       │
     └───────────┬───────────┘
                 │
             Database
       (SQLite / PostgreSQL)
                 │
       External Integrations
      Gmail API / WhatsApp API
⚙ Tech Stack
Frontend

React.js

JavaScript

CSS

Backend

Python

Flask

SQLAlchemy

Artificial Intelligence

DeepFace

Facenet512

RetinaFace

MTCNN

NLP

Groq API

Database

SQLite

PostgreSQL

Deployment

Docker

Nginx

AWS / DigitalOcean

📂 Project Structure
Drishyamitra
│
├── backend
│   ├── app.py
│   ├── face_recognition.py
│   ├── chatbot.py
│   ├── database.py
│   └── start_server.py
│
├── frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── package.json
│
├── models
│
├── requirements.txt
│
└── README.md
🚀 Installation Guide
1️⃣ Clone Repository
git clone https://github.com/YOUR_USERNAME/Drishyamitra.git
cd Drishyamitra
2️⃣ Backend Setup

Create virtual environment

python -m venv venv

Activate environment

Windows

venv\Scripts\activate

Linux / Mac

source venv/bin/activate

Install dependencies

pip install -r requirements.txt

Start server

python start_server.py

Backend will run on:

http://localhost:5000
3️⃣ Frontend Setup
cd frontend
npm install
npm start

Frontend runs at:

http://localhost:3000
🔑 Environment Variables

Create .env file:

GROQ_API_KEY=your_api_key
GMAIL_API_KEY=your_key
DATABASE_URL=postgresql://user:password@localhost/db
📊 Real World Applications
📸 Personal Photo Management

Automatically organize thousands of personal photos.

💍 Event Photography

Helps photographers automatically categorize photos of clients and guests.

🏢 Corporate Media Management

Allows teams to quickly retrieve images from large media libraries.

🔮 Future Improvements

📱 Mobile App Integration

🎥 Video Recognition

☁ Cloud Storage Integration

😊 Emotion Detection in Photos

📅 Automatic Event Detection

👨‍💻 Team
Name	Role
Ojasvi Rastogi	Team Lead
Prashant Kumar	Developer
Harshit Jain	Developer
Himanshi Verma	Developer
📽 Demo

🚧 Demo will be added soon.

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork it
📢 Share it
