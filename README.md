# 🤖 Railway Ticket Generating Chatbot

A **voice-enabled chatbot** built using Python, Tkinter GUI, and Pandas, designed to simulate a railway ticket booking assistant. This project allows users to interact with a bot via text input, fetch train details from a dataset, and generate printable tickets — all in a friendly, conversational UI.

---

## 🧠 Features

- 🗣️ **Text-to-speech responses** using `pyttsx3`
- 📅 **Train data filtering** using a CSV file
- 🧾 **Auto ticket generation** (includes passenger info, train details, date)
- 🖨️ **Print simulation** with `tkinter.messagebox`
- 🎨 **Beautiful Tkinter-based UI** with background images and colorful messages
- 💬 Interactive conversation flow: name → source → destination → date → number of tickets → confirmation

---

## 🛠️ Tech Stack

- **Frontend:** Tkinter (Python GUI)
- **Backend:** Python
- **Data Handling:** Pandas
- **Voice & Speech:** pyttsx3, SpeechRecognition
- **Dataset:** `scraped.csv` (local CSV file containing train data)

---
## 📁 File Structure
Chatbot/
│
├── chatbot.py # Main Python GUI code (Tkinter + Logic)
├── scraped.csv # CSV dataset with train details
├── railway.jpg # Background image used in GUI
├── logo.jpg # Logo image for chatbot branding
└── README.md # Project documentation

## 👩‍💻 Author

**Komal Singh**
