# Real-Time AI Chatbot with Streaming

A **real-time AI-powered chat application** built as part of a Frontend Developer assignment. The project demonstrates **streaming AI responses**, **WebSocket-based real-time communication**, and clean **React + TypeScript** state management. The focus is on **core functionality, real-time UX, and clarity**, aligned strictly with the assignment requirements.

---

## 🚀 Features Implemented (Checklist)

* [x] Real-time chat interface
* [x] User & AI message distinction
* [x] Auto-scroll to latest message
* [x] Message timestamps
* [x] Responsive (mobile-friendly) UI
* [x] WebSocket connection setup
* [x] Connection status indicator
* [x] Streaming AI responses (chunk-by-chunk)
* [x] Typing indicator during AI response
* [x] Input disabled while AI is responding
* [x] Basic error handling
* [x] AI-powered responses using OpenAI
* [x] Optional web search using Tavily API

---

## 🧠 Tech Stack & Libraries Used

### Frontend

* React 18
* TypeScript
* Tailwind CSS

### Backend / Real-Time

* Node.js
* WebSockets
* Express

### AI & APIs

* OpenAI API (streaming responses)
* GetStream (real-time chat infrastructure)
* Tavily API (web search integration)

---

## ⚙️ Setup Instructions (Step-by-Step)

### 1️⃣ Clone the Repository

```bash
git clone <your-repository-url>
cd nodejs-ai-assistant
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the project root using the following template:

```env
# GetStream credentials - Replace with your actual values from Stream Dashboard
STREAM_API_KEY=zsqss3u6cefq
STREAM_API_SECRET=yqj9sz36cb3kjq964jg9gbnkte4dv753rtgpjyys4sg585gzbc4mavku6fwznvkd

# AI API keys
OPENAI_API_KEY=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
TAVILY_API_KEY=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
```

⚠️ **Important:** Do not commit `.env` files. Use `.env.example` for GitHub.

---

## ▶️ Commands to Run the Project

### Start Development Server

```bash
npm run dev
```

The backend server will start at:

```
http://localhost:3000
```

---

## ⏱️ Time Spent on the Assignment

**Approximately 6–8 hours**

* Project setup & configuration
* WebSocket & streaming logic
* AI integration
* UI development & state management
* Testing & debugging

---

## 🎥 Demo Video

📺 **Live Demo & Code Walkthrough:**
👉 [https://www.veed.io/view/8c5596c7-62a6-422f-8cc4-e208858b2369](https://www.veed.io/view/8c5596c7-62a6-422f-8cc4-e208858b2369)

---

Built for the **Frontend Developer – Real-Time AI Chatbot Assignment** 🚀
