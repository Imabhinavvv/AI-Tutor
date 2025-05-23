# AI Conversational Data Science Tutor

![AI Tutor](https://cdn-icons-png.flaticon.com/512/2721/2721260.png)

## 📌 Overview
The **AI Conversational Data Science Tutor** is an interactive chatbot built using **Streamlit** and **Google Gemini AI** to assist users in learning data science. It supports real-time conversations, contextual tips, topic-based quizzes, and file uploads for analysis.

## 🚀 Features
- 💡 **Conversational AI**: Engage in real-time conversations about data science.
- 🌓 **Light/Dark Mode**: Toggle between themes for a better UI experience.
- 📚 **Topic Selection**: Choose from various data science topics for focused learning.
- 🧠 **Quiz Generator**: Generate topic-based multiple-choice quizzes.
- 📂 **File Upload Support**: Upload CSV or PDF files for insights and summarization.
- 🛠 **Python Code Execution**: Execute Python code using an interactive REPL tool.
- 🔍 **Contextual Tips**: Get AI-driven tips based on chat history.
- 📥 **Download Chat History**: Save conversations for later reference.

## 🛠️ Installation
### Prerequisites
- Python 3.8+
- `pip` installed

### Clone the Repository
```sh
git clone https://github.com/your-username/AI-Data-Science-Tutor.git
cd AI-Data-Science-Tutor
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Set Up API Key
1. Get an API key from [Google AI](https://ai.google.dev/)
2. Save it in a file: `genai.txt` inside the project directory.

### Run the Application
```sh
streamlit run app.py
```

## 🎨 Customization
You can modify the UI elements and themes inside `app.py`:
- Change colors in `set_theme(dark_mode)` function.
- Update the chatbot prompt and memory logic.

## 📂 Project Structure
```
AI-Data-Science-Tutor/
│── app.py             # Main Streamlit application
│── requirements.txt   # Dependencies
│── genai.txt          # API key file (Not included in the repository)
│── README.md          # Project documentation
```

## 🛠️ Tech Stack
- **Frontend**: Streamlit
- **AI Model**: Google Gemini AI
- **Backend**: Python, LangChain
- **Libraries**: Pandas, PyPDF2, Streamlit Extras

## 💡 Future Enhancements
- 🔍 Add vector database for better context retention.
- 📊 Integrate interactive visualizations.
- 🤖 Expand support for multiple AI models (OpenAI, Llama, etc.).
- 📅 Schedule AI-driven learning sessions.

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

## 📜 License
This project is licensed under the MIT License.

## 🎉 Acknowledgments
Thanks to **Google AI, LangChain, and Streamlit** for making this project possible!

---
### 🔗 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/your-profile/)  [![GitHub](https://img.shields.io/badge/GitHub-Repo-black)](https://github.com/your-username/)

