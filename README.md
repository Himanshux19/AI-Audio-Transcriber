# 🎧 Audio to Text Transcriber

AI-powered **audio-to-text transcription web application** that converts speech into text using a **React frontend** and **Spring Boot backend**. Users can upload audio files and receive accurate text transcriptions powered by AI speech recognition APIs.


# 🚀 Features

* Upload audio files for transcription
* Convert speech to text using AI
* Modern responsive UI
* Full-stack architecture (React + Spring Boot)
* Loading indicator while processing audio
* REST API integration
* Clean and responsive user interface


# 🏗️ Project Architecture

```
Client (React)
      │
      ▼
Spring Boot REST API
      │
      ▼
AI Speech-to-Text API
      │
      ▼
Transcription Result
```

# 🛠️ Tech Stack

### Frontend

* React
* Axios
* CSS
* Vite

### Backend

* Spring Boot
* Java
* REST API
* Maven

### AI Integration

* Speech-to-Text API (Whisper / Groq / OpenAI)

---

# 📂 Project Structure

```
ai-audio-transcriber
│
├── Audio-Transcriber           # Spring Boot Backend
│   ├── src
│   ├── pom.xml
│
├── audio-transcriber-frontend  # React Frontend
│   ├── src
│   ├── package.json
│
└── README.md
```


# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-audio-transcriber.git
cd ai-audio-transcriber
```

---

## 2️⃣ Backend Setup (Spring Boot)

Navigate to backend folder:

```bash
cd Audio-Transcriber
```

Run the backend server:

```bash
./mvnw spring-boot:run
```

Backend runs on:

```
http://localhost:8080
```

---

## 3️⃣ Frontend Setup (React)

Navigate to frontend folder:

```bash
cd audio-transcriber-frontend
```

Install dependencies:

```bash
npm install
```

Run the frontend:

```bash
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

# 🔐 Environment Variables

API keys are **not included in this repository** for security.

Create a `.env` file and add:

```
OPENAI_API_KEY=your_api_key_here
```

or

```
GROQ_API_KEY=your_api_key_here
```

---

# 📸 Demo

Upload an audio file → AI processes the speech → Text transcription appears instantly.

---

# 💡 Future Improvements

* Real-time microphone transcription
* Download transcript feature
* Copy-to-clipboard button
* Multi-language support
* Drag-and-drop audio upload

---

# 👨‍💻 Author

**Himanshu Singh**
