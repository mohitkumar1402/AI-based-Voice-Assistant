*******************************************************************
By :Mohit KUMAR LNCTS
*******************************************************************

# AI Voice Assistant 🔊🤖

An AI-powered voice assistant built using Python that performs a wide range of daily tasks through voice commands. Designed for convenience and productivity, this assistant can greet users, play music, tell the time and date, search Google or Wikipedia, manage to-do lists, send WhatsApp messages or emails, and even interact with ChatGPT using the OpenAI API.

## 🎯 Features
- Voice-activated interaction
- Personalized greeting on startup
- Play music on command
- Report current time and date
- Search topics on Google or Wikipedia
- Add tasks to a to-do list
- Send WhatsApp messages
- Send emails through voice commands
- ChatGPT integration for AI-powered answers




## 🛠️ Technologies Used
- **Python**
- **SpeechRecognition**, **pyttsx3**, **pyaudio**
- **Google Search API**, **Wikipedia API**
- **Twilio** (for WhatsApp)
- **SMTP** (for sending emails)
- **OpenAI API** (for ChatGPT integration





## 🚀 Getting Started

1.	Unzip .rar file. Open the folder in vs code.

2.	Create Your Virtual Environment.
Command: python -m venv env_jarvis

3.	Activate the environment 
Command: .\env_jarvis\Scripts\activate

4.	Install the requirements.txt
Command : pip install -r  requirements.txt

5.	In user_config.py
	1.	Enter the gmail app password (this is not the gmail login password. You have to generate app password  to send emails from python. 
	Follow following steps: https://itsupport.umd.edu/itsupport?id=kb_article_view&sysparm_article=KB0015112
	2.	Enter the openai key
6.	Enter the required email and phone number in main.py. (Follow the video for more details)

7.	Run the code
Command : python main.py




