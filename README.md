# 🚀 AI Interview Preparation System

An AI-powered interview preparation platform built using **Streamlit**, **Google Gemini AI**, and **Machine Learning**. The system helps students assess technical skills, identify weak areas, generate personalized learning roadmaps, create interview questions, and track interview readiness.

---

## 📌 Features

### 👤 Student Profile
- Store student information
- Select preferred job role
- Choose academic branch and year

### 📊 Skill Assessment
- Self-evaluate technical skills (0–100)
- Topics covered:
  - Arrays
  - Linked List
  - Stack
  - Queue
  - DBMS
  - Operating System

### 📈 Dashboard Analytics
- Average score calculation
- Weak and strong topic detection
- Visual performance charts
- Skill analysis summary

### 🛣️ AI Learning Roadmap
- Personalized 4-week learning plan
- Focus on weak topics
- Resource recommendations
- Interview preparation strategies

### 💡 AI Interview Question Generator
- Powered by Google Gemini AI
- Supports multiple job roles:
  - Frontend Developer
  - Backend Developer
  - Full Stack Developer
  - Data Analyst
  - ML Engineer
- Difficulty levels:
  - Easy
  - Medium
  - Hard

### 🎯 Progress Tracker
- Current vs Target score tracking
- Interview readiness prediction
- Machine Learning-based evaluation

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Streamlit | Web Application Framework |
| Pandas | Data Processing |
| Matplotlib | Data Visualization |
| Scikit-learn | Machine Learning |
| Google Gemini AI | AI Content Generation |

---

## 📂 Project Structure

```text
AI-Interview-Preparation-System/
│
├── app.py
├── requirements.txt
├── README.md
├──.gitignore
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/demohit37-jpg/AI-Interview-Preparation-System.git
cd AI-Interview-Preparation-System
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Required Packages

Create a **requirements.txt** file with:
streamlit
pandas
matplotlib
scikit-learn
google-generativeai
```

---

## 🔑 Gemini API Setup

Replace the API key placeholder in `app.py`:

```python
GEMINI_API_KEY = "YOUR_API_KEY"
```

Recommended approach:

```python
import os

GEMINI_API_KEY = os.getenv("GEMINI_API_KEY")
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```
## 🔄 Application Workflow

1. Create Student Profile
2. Complete Skill Assessment
3. View Dashboard Analytics
4. Generate AI Learning Roadmap
5. Practice AI Interview Questions
6. Track Progress & Readiness

---

## 🤖 Machine Learning Model

The system uses a **Decision Tree Classifier** to predict interview readiness based on average assessment scores.

| Score Range | Readiness Level |
|------------|----------------|
| 0 – 35 | Low |
| 36 – 55 | Medium |
| 56 – 75 | Good |
| 76 – 100 | Excellent |
---

## 🚀 Future Enhancements

- Pofile Analysis
- Mock Interview Simulation
- Performance History Tracking
- Gamification & Leaderboards

---

## 🎯 Expected Outcomes

- Improved interview readiness
- Personalized learning guidance
- Better technical preparation
- Enhanced confidence in placements
- Data-driven skill improvement

---

## 👨‍💻 Author

**Mohit De**
 Project – AI Interview Preparation System
Feel free to use, modify, and distribute it for educational purposes.
