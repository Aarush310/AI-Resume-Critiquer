# AI-Resume-Critiquer
AI Resume Critiquer is a **Streamlit-powered web app** that allows users to upload their resumes in PDF or TXT format and receive **instant AI-generated feedback** tailored to a specific job role.

## 🚀 Features

- 🧠 **AI-Powered Feedback** – Uses OpenAI's GPT model to provide personalized suggestions on:
  - Content clarity
  - Skills presentation
  - Experience highlights
  - Tailored recommendations for your selected job role
- 📂 **Upload Support** – Accepts PDF and TXT resume files.
- 👨‍💼 **Job Role Dropdown** – Select from a list of common job roles or enter your own.
- ⚙️ **Built with Streamlit** – Fast, interactive UI and easy deployment.

---

## 🖼️ Preview

![App Screenshot](./Screenshot%202025-06-25%20at%2011.00.27%E2%80%AFAM.png)

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) – For UI and frontend interaction
- [OpenAI GPT-4o-mini](https://platform.openai.com/) – For generating resume critiques
- [PyPDF2](https://pypi.org/project/PyPDF2/) – To extract text from PDF files
- [dotenv](https://pypi.org/project/python-dotenv/) – For loading API keys securely

---

## 🔧 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/ai-resume-critiquer.git
cd ai-resume-critiquer
