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


![image](https://github.com/user-attachments/assets/ef622387-ef70-4497-b6bf-95421bf354c9)

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

2. Install dependencies
pip install -r requirements.txt
3. Add your OpenAI API key
Create a .env file in the root directory:

OPENAI_API_KEY=your_openai_api_key_here
4. Run the Streamlit app
streamlit run app.py
📁 File Structure

├── app.py                # Main Streamlit application
├── .env                  # Environment variables (not tracked)
├── requirements.txt      # Required Python packages
├── Screenshot.png        # UI Preview Image
└── README.md             # You're here!

📬 Contact

Made by Aarush Prasad.
For feedback or collaboration, feel free to reach out!

📜 License

This project is licensed under the MIT License.
