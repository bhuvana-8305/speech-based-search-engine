## 🔍 Speech-Based Search Engine

A simple Python application that allows users to perform web searches using voice commands. It utilizes speech recognition to capture queries and opens a browser window with search results using Google.

### 🧠 Features

* 🎤 Voice-activated search using microphone input
* 🌐 Opens search results directly in your default web browser
* 🔈 Text-to-speech feedback for user interaction

### 🛠️ Technologies Used

* [`speech_recognition`](https://pypi.org/project/SpeechRecognition/): Captures and interprets spoken language
* [`pyttsx3`](https://pypi.org/project/pyttsx3/): Provides text-to-speech responses
* `webbrowser`: Launches Google search results in the browser

### 📦 Installation

Install the necessary dependencies:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> ⚠️ Note: `pyaudio` can be tricky to install on some systems. For Windows, you may need to download a `.whl` file from [https://www.lfd.uci.edu/\~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio).

### 🚀 How to Run

```bash
python "speech based search engine.py"
```

### 💡 How It Works

1. Prompts the user to speak their search query.
2. Recognizes the speech using Google’s Speech API.
3. Opens the query in a browser using Google Search.
4. Gives voice feedback of the recognized query.

### 🧪 Example

```text
Listening...
Recognizing...
You said: weather in Paris
```

➡ Browser opens with: `https://www.google.com/search?q=weather+in+Paris`

### 📌 Requirements

* A working microphone
* Internet connection (for Google Speech Recognition)

### 📜 License

MIT License
