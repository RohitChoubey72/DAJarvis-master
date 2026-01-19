DAJarvis is a Python-based desktop assistant engineered to streamline daily workflows via voice commands. It handles tasks like web searches, application management, and system automation efficiently. Leveraging speech recognition libraries, this project provides a modular codebase for developers looking to build customized intelligent personal assistants.
<br>
# DAJarvis

**DAJarvis** is a desktop voice assistant designed to automate daily tasks and improve productivity through voice commands. Built with Python, it leverages Google's Speech API for accurate recognition and integrates SQL for efficient data management.

## 🚀 Features

* **Voice Interaction:** Seamless two-way communication using Speech-to-Text and Text-to-Speech engines.
* **Task Automation:** Executes system commands, opens applications, and performs web searches.
* **Data Management:** Uses an SQL backend to store user preferences, logs, or task history.
* **Modular Design:** Easy to extend with new commands and functionalities.

## 🛠️ Tech Stack

* **Programming Language:** [Python](https://www.python.org/)
* **Database:** SQL (e.g., SQLite/MySQL)
* **Speech Recognition:** [Google Speech API](https://pypi.org/project/SpeechRecognition/)
* **Text-to-Speech:** [pyttsx3](https://pypi.org/project/pyttsx3/) / gTTS

## ⚙️ Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/DAJarvis-master.git](https://github.com/your-username/DAJarvis-master.git)
    cd DAJarvis-master
    ```

2.  **Install required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *Common libraries likely needed:*
    * `SpeechRecognition`
    * `pyttsx3`
    * `pyaudio`
    * `mysql-connector-python` (or `sqlite3` built-in)

3.  **Database Setup:**
    * Ensure your SQL server is running (if using MySQL).
    * Update the database connection strings in the configuration file or main script.
    * Run the initial setup script to create necessary tables:
        ```bash
        python database_setup.py
        ```

## 🖥️ Usage

1.  Run the main assistant script:
    ```bash
    python main.py
    ```
2.  The assistant will start listening. Try commands like:
    * *"Open Google"*
    * *"What is the time?"*
    * *"Play music"*

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
