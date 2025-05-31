# 🤖 AI Agent Project

This project is a AI-powered application divided into three phases:

1. **Create AI Agent**
2. **Setup Backend with FastAPI**
3. **Setup Frontend with Streamlit**

It demonstrates a streamlined approach to building and deploying AI systems using Python, FastAPI, and Streamlit — all within a Conda environment.

---

## 📦 Features

- AI logic in Python
- REST API using FastAPI
- Interactive UI using Streamlit
- Cross-platform support via Conda

---

## ⚙️ Conda Environment Setup (Windows)

### Step 1: Create and activate a Conda environment

```bash
conda create --name myenv python=3.11
conda activate myenv
```

### Step 2: Install project dependencies

```bash
pip install -r requirements.txt
```

---

## 🚀 Project Phases & Commands

### 📘 Phase 1: Run the AI Agent

Start the AI agent logic:

```bash
python ai_agent.py
```

---

### 🌐 Phase 2: Start the Backend (FastAPI)

Run the backend server in a **separate terminal**:

```bash
python backend.py
```

> ⚠️ **Important:** The backend must remain running while the frontend interacts with it.

---

### 🎨 Phase 3: Launch the Frontend (Streamlit)

Run the Streamlit app:

```bash
python frontend.py
```

---

## 📌 Requirements

- Python 3.11 (via Conda)
- All required packages in `requirements.txt`

---

## 👤 Author

**Ayon Sen**  
[GitHub](https://github.com/AkagamiShnaks)  
[LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🛡️ Badges

![Python](https://img.shields.io/badge/Python-3.11-blue)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-green)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)

---

## 📈 Future Enhancements

- Add API documentation with Swagger or ReDoc
- Enhance AI capabilities (e.g. NLP, image processing)
- Improve frontend interactivity and UI design
