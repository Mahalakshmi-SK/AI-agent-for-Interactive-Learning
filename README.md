# AI Agent for Interactive Learning

## 📌 Project Overview

The **AI Agent for Interactive Learning** is an intelligent tutoring system designed to provide structured, interactive, and personalized learning experiences. The agent explains topics, conducts quizzes, evaluates user responses, provides feedback, and tracks learning progress in a conversational manner. The goal of this project is to simulate a human-like tutor using AI and help learners understand concepts more effectively.

---

## 🎯 Key Features

* 📖 Topic-wise concept explanation using AI
* ❓ Automatic quiz generation after each topic
* ✅ Answer evaluation with detailed explanations
* 🔄 Interactive conversation flow (learn → quiz → feedback → next topic)
* 📊 Score and progress tracking
* 🧠 Session-based memory to avoid re-explaining topics
* 🌐 Web-based interface for easy access

---

## 🛠️ Technologies Used

* **Programming Language:** Python
* **Framework:** Flask
* **Frontend:** HTML, CSS, JavaScript (Tailwind CSS)
* **AI / LLM:** Groq API (LLaMA / Mixtral models)
* **Data Handling:** JSON
* **Version Control:** Git & GitHub

---

## 🧩 Project Architecture

* `app.py` – Main Flask application
* `chatbot.py` – Core conversation flow controller
* `managers/` – Modular logic for courses, explanations, quizzes, and scoring
* `data.json` – Structured course and topic data
* `score.json` – User quiz score tracking
* `templates/` – Frontend HTML files
* `static/` – CSS and JavaScript assets

---

## 🔄 Workflow

1. User selects a course
2. AI explains the selected topic
3. User is asked whether they want a quiz
4. Quiz is generated dynamically
5. User answers are evaluated by AI
6. Feedback and score are provided
7. User proceeds to the next topic

This flow repeats consistently for all topics.

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required dependencies
3. Set up the Groq API key
4. Run the Flask application
5. Open the app in a web browser

---

## 💡 Use Cases

* AI-powered tutoring systems
* E-learning platforms
* Personalized learning assistants
* Interview and exam preparation tools

---

## 📈 Future Enhancements

* User authentication and dashboards
* Certificate generation
* Multi-language support
* Advanced analytics and learning recommendations
* Voice-based interaction

---

## 👩‍💻 Author

**Mahalakshmi S K**
B.Tech – Information Science and Engineering
AI/ML Intern | Aspiring AI Engineer

---


## ⭐ Acknowledgements

* Groq API for LLM support
* Flask open-source community
* Online AI research and learning resources

---

⭐ If you find this project useful, please consider giving it a star!
