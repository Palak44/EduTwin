 # 🎓 EduTwin: LLM-Powered Digital Twin of University Students

## 🚀 Overview

EduTwin is an AI-powered system that creates a **Digital Twin of a student** using a dynamic **Live Learner Profile (LLP)**.
It leverages Large Language Models (LLMs) to simulate student behavior, diagnose weaknesses, predict performance, and generate personalized learning content.

---

## 💡 Problem Statement

Traditional education systems treat students uniformly, ignoring differences in:

* Learning pace
* Prior knowledge
* Study patterns
* Cognitive preferences

EduTwin solves this by building a **personalized AI twin** for each student.

---

## 🧠 Key Features

### 🔍 Weakness Diagnosis

Identifies weak topics using student performance and behavior data.

### 📘 Personalized Explanations

Generates tailored explanations based on student profile.

### 📊 Performance Prediction

Predicts future performance (High / Medium / Low).

### 📝 Exam Answer Simulation

Simulates how a student would answer an exam question.

### 📅 Study Plan Recommendations

Suggests personalized study strategies.

---

## 🏗️ Project Structure

```
EduTwin/
├── data/
│   └── generate_data.py
├── core/
│   ├── profile_builder.py
│   └── llp_updater.py
├── twin/
│   ├── prompt_engine.py
│   ├── weakness_diagnoser.py
│   ├── explainer.py
│   ├── predictor.py
│   ├── exam_simulator.py
│   └── twin_engine.py
├── ui/
│   ├── app.py
│   └── views/
│       ├── student_view.py
│       └── teacher_view.py
├── setup.py
└── requirements.txt
```

---

## ⚙️ Tech Stack

* **LLM**: Groq API
* **Backend**: Python
* **UI**: Streamlit
* **Data Generation**: Faker

---

## 📊 How It Works

1. **Data Ingestion**

   * Student grades, LMS activity, quizzes, self-reports

2. **Live Learner Profile (LLP)**

   * Structured representation of student

3. **LLM Reasoning Engine**

   * Uses LLP + prompts to generate insights

4. **Twin Capabilities**

   * Diagnosis, prediction, simulation, personalization

---

## 🛠️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Palak44/EduTwin.git
cd EduTwin
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate:

* Windows:

```bash
venv\Scripts\activate
```

* Mac/Linux:

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Application

```bash
streamlit run ui/app.py
```

---

## 📂 Data Generation

Generate synthetic student data:

```bash
python data/generate_data.py
```

---

## 👨‍🏫 Usage

### Student View

* View your learner profile
* Get personalized explanations
* Receive study recommendations

### Teacher View

* Analyze entire class
* Identify weak students
* Get insights and predictions

---

## 📈 Evaluation Metrics

| Capability         | Metric                |
| ------------------ | --------------------- |
| Weakness Diagnosis | Precision / Recall    |
| Prediction         | Accuracy / F1         |
| Explanation        | Human Rating          |
| Simulation         | Behavioral Similarity |

---

## 🔮 Future Enhancements

* 📅 Temporal tracking of student progress
* 🔁 Counterfactual analysis
* 🔐 Privacy-preserving modeling
* 👥 Student clustering

---

## 🤝 Team Collaboration

* Create feature branches
* Use pull requests
* Avoid pushing directly to `main`

---

## 🔐 Environment Variables

Create a `.env` file:

```
API_KEY=your_api_key_here
```

---

## 🙌 Acknowledgements

Inspired by research in:

* AI in Education
* Personalized Learning Systems
* LLM-based User Modeling

---



