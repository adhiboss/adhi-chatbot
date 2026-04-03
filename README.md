# 🤖 Adhi Chatbot — Rasa-Based AI Assistant

## 🚀 Overview

**Adhi Chatbot** is a conversational AI assistant built using the Rasa framework. It is designed to handle common student queries such as fees, timetable, and general academic information through natural language interaction.

This project demonstrates core concepts of **NLU (Natural Language Understanding)** and **dialogue management**, along with practical debugging and system setup.

---

## 🎯 Features

* 🧠 Intent recognition (fees, timetable, basic queries)
* 💬 Conversational responses using Rasa Core
* ⚙️ YAML-based configuration and training
* 🖥️ CLI-based chatbot interaction (`rasa shell`)
* 🔧 Modular architecture (domain, data, actions)

---

## 🛠️ Tech Stack

* **Framework:** Rasa
* **Language:** Python 3.10
* **Configuration:** YAML
* **Environment:** Linux (Ubuntu)

---

## 📁 Project Structure

```
adhi-chatbot/
 ├── actions/            # Custom action scripts
 ├── data/               # Training data (NLU + stories)
 ├── models/             # Trained models
 ├── domain.yml          # Intents, entities, responses
 ├── config.yml          # Pipeline & policies
 ├── credentials.yml     # Channel configs
 ├── endpoints.yml       # Action server config
 └── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```
git clone https://github.com/YOUR-USERNAME/adhi-chatbot.git
cd adhi-chatbot
```

### 2️⃣ Create Virtual Environment

```
python3.10 -m venv rasa-env
source rasa-env/bin/activate
```

### 3️⃣ Install Dependencies

```
pip install rasa
```

---

## ▶️ Run the Chatbot

### Train Model

```
rasa train
```

### Start Chatbot

```
rasa shell
```

---

## 🔁 Development Workflow

1. Update training data (`data/`)
2. Modify responses (`domain.yml`)
3. Retrain model → `rasa train`
4. Test → `rasa shell`

---

## ⚠️ Challenges Faced

* ❌ Rasa command not found → Fixed via virtual environment
* ❌ Python 3.12 incompatibility → Downgraded to 3.10
* ❌ YAML duplicate key errors → Restructured domain file
* ❌ Virtual environment issues → Installed python3.10-venv

---

## 🚀 Future Enhancements

* 📊 Add more intents (attendance, exams, faculty)
* 🧩 Integrate database (SQLite/MySQL)
* 🌐 Build web-based chat interface
* ☁️ Deploy chatbot online
* 🤖 Add advanced NLP models / APIs

---

## 📌 Key Learning Outcomes

* Understanding of Rasa architecture (NLU + Core)
* YAML structuring and debugging
* Model training lifecycle
* Real-world chatbot development workflow

---

## 👨‍💻 Author

**Adhi Gowda**

* 🔗 GitHub: https://github.com/YOUR-USERNAME
* 🔗 Portfolio: https://adhigowda.me

---

## ⭐ Contribution

Feel free to fork this repository and improve the chatbot with new features or integrations.

---

## 📜 License

This project is open-source and available under the MIT License.
