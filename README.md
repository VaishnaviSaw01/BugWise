# 🐞 BugWise – AI-Powered Code Debugger

## 📌 Overview

BugWise is an AI-powered code debugging platform that supports multi-language code execution with real-time feedback and intelligent explanations.

The system integrates execution and AI analysis APIs to help users understand errors, optimize code, and improve programming logic efficiently.

---

## 🚀 Features

- 💻 Multi-language code execution  
- ⚡ Real-time program output  
- 🧠 AI-generated code explanations  
- 🔍 Error detection and debugging assistance  
- 🌐 Web-based interactive interface  
- 📦 Modular API integration  

---

## 🏗️ System Architecture

1. User writes code in the browser editor  
2. Code is sent to Judge0 API for execution  
3. Execution output or error is returned  
4. Code is sent to Gemini API for explanation  
5. AI-generated feedback is displayed to the user  

---

## 🧰 Tech Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript  

### APIs Integrated
- Judge0 API (Code Execution Engine)  
- Google Gemini API (AI Code Explanation)  

### Tools
- Git  
- Postman  

---

## 🔄 How It Works
User Code → Judge0 API → Execution Result →
Gemini API → Explanation & Suggestions → Display to User

---

## 🧠 Supported Capabilities

- Compile & execute multiple programming languages  
- Identify syntax and runtime errors  
- Generate AI-based explanation of code logic  
- Suggest improvements and optimizations  

---

## 🔒 Limitations

- Execution time depends on external API response  
- AI explanations rely on API accuracy  
- No offline execution support  

---

## 📈 Future Enhancements

- User authentication & history tracking  
- Code complexity analysis  
- Performance benchmarking  
- Dark mode UI  
- Custom AI fine-tuning for debugging  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/bugwise.git
cd bugwise
```
### 2️⃣ Configure API Keys
```
Create a .env file and add:

JUDGE0_API_KEY=your_key_here
GEMINI_API_KEY=your_key_here
```

### 3️⃣ Run the Application
```
Open index.html in your browser
(or run using a local development server)
```

## 👩‍💻 Author

Vaishnavi Saw

AI & Full-Stack Enthusiast
