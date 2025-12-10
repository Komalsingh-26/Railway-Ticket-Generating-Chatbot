# 🤖 Railway Ticket Generating Chatbot

A **Python-based railway ticket booking chatbot** with a graphical user interface and voice-assisted interaction.  
This project simulates a real-world railway ticket booking assistant that helps users search trains, book tickets, and generate printable ticket confirmations through an interactive conversation.

---

## 🚀 Overview

The Railway Ticket Generating Chatbot is designed to demonstrate how **Python, data processing, and GUI development** can be combined to build an intelligent, user-friendly application.  
The chatbot guides users step-by-step through a ticket booking flow using **natural conversation**, backed by a real dataset.

---

## ✨ Key Features

- 🗣️ **Voice-enabled responses** using `pyttsx3`
- 💬 **Conversational chat-based interface** (Tkinter GUI)
- 📊 **Train data filtering** from a CSV dataset using Pandas
- 🧾 **Automatic ticket generation** with passenger & journey details
- 🖨️ **Print simulation** via system dialog boxes
- 🎨 **Attractive UI** with background image and branding
- 🔁 **State-based conversation flow** for realistic user interaction

---

## 🧠 Conversation Flow

1. User initiates booking request  
2. Bot asks for passenger name  
3. Source station  
4. Destination station  
5. Travel date  
6. Number of tickets  
7. Ticket generation & confirmation  
8. Print simulation  

---

## 🛠️ Tech Stack

### Programming Language
- Python 3.x

### GUI & UX
- Tkinter
- Pillow (PIL)

### Data Handling
- Pandas

### Voice & Speech
- pyttsx3 (Text-to-Speech)
- SpeechRecognition *(optional voice input)*

---

## 📂 Project Structure
Chatbot/
│
├── chatbot.py # Main chatbot application (GUI + logic)
├── scraped.csv # Dataset containing train details
├── railway.jpg # Background image for GUI
├── logo.jpg # Logo used in the chatbot UI
└── README.md # Project documentation


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Komalsingh-26/Railway-Ticket-Generating-Chatbot.git
cd Railway-Ticket-Generating-Chatbot

### 2️⃣ Install Required Dependencies
```bash
pip install pandas pyttsx3 pillow speechrecognition pyaudio
## ▶️ How to Run the Application

```bash
python chatbot.py
Make sure the following files are present in the **same folder**:

- `scraped.csv`
- `railway.jpg`
- `logo.jpg`

---

## 🧪 Dataset Information

The dataset **`scraped.csv`** includes:

- Train Name  
- Source Station (`SRC_station`)  
- Destination Station (`DESC_station`)  
- Travel Date (`start_date`)  

The chatbot filters this dataset based on user input to display matching trains.

---

## 🧠 How the Chatbot Works

- Uses **state-based conversation logic**  
- Filters train data using **Pandas**  
- GUI built entirely with **Tkinter**  
- Voice responses generated using **pyttsx3**  
- Automatically generates ticket text  
- Simulates printing using popup dialog boxes  

---
## 🎯 Learning Outcomes

This project demonstrates:

- GUI development with **Tkinter**
- Data handling & filtering using **Pandas**
- Voice-enabled application development in **Python**
- State-machine based chatbot logic
- Clean, modular, and maintainable code structure

---

## 👩‍💻 Author

**Komal Singh**  
B.Tech Computer Science Student  
Aspiring Software Developer | Python & Full Stack Enthusiast  

🔗 GitHub Profile: https://github.com/Komalsingh-26

---

## ⭐ Feedback & Contributions

If you like this project:

- ⭐ Star this repository
- 🍴 Fork it to experiment
- 🐞 Open issues for suggestions
- 🤝 Pull requests are welcome

> This project is built for learning and academic demonstration purposes.
