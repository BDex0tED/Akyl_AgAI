# 🧠 Akyl_AgAI

Multilingual AI-powered learning assistant.

Akyl_AgAI is an educational platform built with Gemini AI to help students learn more effectively. Unlike traditional chatbots, AkylAIday requires no complex prompts — just choose what you need.

---

## Features

- 💬 Gemini-powered AI (via free token)  
- 🌍 Multilingual UI: Kyrgyz, Russian, English  
- 🎓 Smart learning modes:
  - **Concept explanation**
  - **Exam preparation**
  - **Practice questions & answers**  
- 🧠 Three answer detail levels: short, medium, full  
- 🧑‍🏫 Friendly UI with button-based input  
- 🔄 Tracks user input → generates questions → evaluates answers  

---

## Tech Stack

**Backend**  
- Java 17 + Spring Boot  
- Gemini AI API integration  
- RESTful endpoints  
- PostgreSQL   
- Secure free-token access system  

**Frontend**  
- React + Vite  
- Axios  
- Dynamic mode & answer type selection UI

---

## Run Locally

Clone the project:
```bash
git clone https://github.com/BDex0tED/Akyl_AgAI.git
```
Run Frontend=>
```bash
cd Akylagai_frontend
npm i
npm run dev
```
Run Backend=>
```bash
cd Akylagai_backend
./mvnw spring-boot:run or just run via intelij/vscode
```
In Akylagai_backend/src/main/resources/application.properties change stuff which is written in there.
Peace :)
