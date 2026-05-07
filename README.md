## 🤖 MindMate – AI Mental Wellness Companion for Students
### 📘 Overview

MindMate is an assessment-driven mental wellness companion designed to support students facing stress, anxiety, and emotional overload. 

The platform combines a custom Attention-Enhanced Bi-LSTM model, a Flask-based web application, and SQLite-backed persistence to deliver context-aware emotional support through a structured end-to-end workflow. 

The system is built to understand Hinglish student conversations, generate supportive responses, and route high-risk cases appropriately.

### 🧩 Problem Statement

Many students experience emotional distress but hesitate to seek formal counselling due to stigma, limited availability, or lack of immediate support. Generic chat systems often fail to understand informal or mixed-language student communication, especially Hinglish text. MindMate addresses this gap by combining structured assessment, emotion classification, risk analysis, and supportive AI responses in a student-friendly web application.

---

### 🚀 Key Features
#### 1. Assessment-Driven Support Flow

Begins with a structured wellness assessment to capture emotional state, support needs, and risk-related context before chat-based interaction.

#### 2. Hinglish Emotion Classification

Uses an Attention-Enhanced Bi-LSTM model trained on Hinglish student conversations to classify emotions such as Happy, Sad, Critical, Out of Context, and Chitchat.

#### 3. Strong Model Performance

The core model was trained on 19,000+ labeled samples and achieved approximately 87–91% emotion classification accuracy across the refined versions of the system.

#### 4. Safety-Oriented Risk Analysis

Adds a risk layer to detect higher-risk conversations and support safer routing instead of relying only on open-ended generation.

#### 5. Context-Aware AI Responses

Generates supportive replies using a hybrid flow, where the trained model handles classification and Groq API helps make responses more natural and student-friendly.

#### 6. Full Web App Integration

The system includes a multi-page frontend for assessment, support selection, AI chat, specialist discovery, booking, and dashboards, all connected through a Flask backend.

#### 7. Database Persistence

Uses SQLite to store registered users and support application data, making the system more complete than a standalone model demo.

---

### ⚙️ Workflow Architecture
1. User registers or logs in through the web app
2. Completes the wellness assessment
3. Submits a message or concern through the AI chat interface
4. Input is cleaned and processed by the backend
5. Bi-LSTM with Attention predicts the emotion class
6. Risk analysis determines the severity level
7. Groq API helps refine response phrasing when needed
8. Response is returned through Flask with emotion and risk context
9. User Data is stored in SQLite for persistence and future use

---

### 🛠️ Tech Stack
1. Python
2. Flask
3. HTML,CSS
4. JavaScript
5. SQLite
6. TensorFlow / Keras
7. Bi-LSTM
8. Attention Mechanism
9. Groq API
10. NLP for Hinglish conversations

---

### 💼 Use Cases
1. Student mental wellness support
2. Emotion classification for informal Hinglish text
3. Early risk detection and escalation
4. Digital counselling assistance
5. Safe AI-based student interaction platforms

---

### 📚 Learning Outcomes
1. Built and refined a Machine Learning model using Bi-LSTM with Attention Mechanism for emotion classification
2. Worked with Hinglish NLP and student-style conversational data
3. Designed a safety-oriented conversational AI flow
4. Integrated Flask backend with frontend and SQLite
5. Connected ML inference with a real web application
6. Improved the system through multiple model versions and testing cycles

---

### 🔮 Future Scope
1. Expand and improve the Hinglish dataset
2. Add more emotional categories and finer-grained risk detection
3. Strengthen chatbot-to-assessment linkage
4. Store richer chat and assessment history
5. Implement specialist side workflows and secure live consultation
6. Add stronger privacy, security, and cloud deployment support
7. Build repeated-risk detection and mood-tracking analytics
