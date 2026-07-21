# 🧠 AI Mental Health Chatbot

An AI-powered mental health companion designed to help college students manage stress, exam pressure, and everyday emotional challenges.

## ✨ Features

* 💬 **AI Chatbot** – Talk about your feelings and receive supportive responses.
* 🫁 **Breathing Exercise** – Guided breathing exercises to help reduce stress.
* 💡 **Daily Tips** – Get simple and practical wellness tips.
* 📚 **Exam Mode** – Helpful study and focus suggestions during exam preparation.
* ✨ **Motivation** – Receive motivational messages and positive reminders.
* 📊 **Mood Detection** – Automatically detects moods such as:

  * 😊 Happy
  * 😔 Sad
  * 😰 Stressed
  * 😐 Neutral
* 📝 **Mood Log** – Keeps track of recent moods during the session.
* 📄 **Export Chat** – Download your chatbot conversation as a text file.

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **Groq API**
* **LLaMA 3.1 8B Instant**
* **Python Datetime**
* **Python Random**

## 📁 Project Structure

```text
AI-Mental-Health-Chatbot/
│
├── app.py
├── README.md
└── .streamlit/
    └── secrets.toml
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Folder

```bash
cd AI-Mental-Health-Chatbot
```

### 3. Install Required Libraries

```bash
pip install streamlit groq
```

### 4. Add Your Groq API Key

Create a folder named `.streamlit` in the project directory.

Inside it, create a file named:

```text
secrets.toml
```

Add your API key:

```toml
GROQ_API_KEY = "your_api_key_here"
```

⚠️ **Important:** Never upload your API key publicly to GitHub.

## ▶️ Run the Application

Run the following command in Terminal:

```bash
streamlit run app.py
```

The application will open in your browser.

## 🎯 Purpose

This project aims to provide students with an accessible AI-based wellness companion that can help them:

* Manage daily stress
* Deal with exam pressure
* Track their mood
* Practice simple breathing exercises
* Receive motivation and wellness tips

## ⚠️ Disclaimer

This chatbot is designed for general emotional support and wellness assistance only. It is **not a replacement for a qualified mental health professional, doctor, or emergency service**.

If someone is experiencing a mental health emergency, they should contact a qualified professional or appropriate emergency service.

## 👨‍💻 Developed By

**YASH PRATAP SINGH**

---

⭐ If you find this project useful, consider giving it a star on GitHub!
