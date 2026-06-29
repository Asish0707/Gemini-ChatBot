# 🤖 Gemini Chatbot

A Streamlit-based AI chatbot powered by Google's Gemini API. This application provides an interactive chat interface where users can communicate with Gemini and receive intelligent responses in real time.

---

## 🚀 Features

* Interactive chatbot interface
* Powered by Google Gemini AI
* Real-time conversational responses
* Simple and clean Streamlit UI
* Secure API key management using `.env`
* Maintains chat history during a session

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Google Generative AI (Gemini)
* Python Dotenv

---

## 📂 Project Structure

```text
Gemini-ChatBot/
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
├── README.md
└── LICENSE
```

---

## ⚙️ Getting Started

### Prerequisites

* Python 3.10+
* Google Gemini API Key
* Streamlit

### Installation

#### 1. Clone the Repository

```bash
git clone https://github.com/Asish0707/Gemini-ChatBot.git
cd Gemini-ChatBot
```

#### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

#### 3. Create a `.env` File

Create a file named `.env` in the project root and add:

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

#### 4. Run the Application

```bash
python -m streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

## 💡 Usage

1. Launch the application.
2. Enter your question or prompt in the chat box.
3. Press Enter.
4. Receive AI-generated responses from Gemini.
5. Continue the conversation naturally.

---

## 🔒 Security

Never upload your API key to GitHub.

Make sure `.gitignore` contains:

```gitignore
.env
```

---

## 📸 Screenshot

Add a screenshot of your chatbot here:

```md
![Gemini Chatbot](screenshot.png)
```

---

## 🚀 Future Improvements

* PDF Chat Support
* Voice Assistant Integration
* Chat Export Feature
* Multiple Gemini Model Selection
* Dark Mode Support
* Chat History Persistence

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/YourFeature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature/YourFeature
```

5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License.

---

## 👨‍💻 Author

**Asish**

GitHub: https://github.com/Asish0707
