# 🧬 AI Health Analyzer — Genetic Risk & Lifestyle Predictor

A web-based AI Expert System that analyzes your daily lifestyle and health history to predict your risk for 6 major diseases, generate a personalized behaviour change plan, and find nearby clinics if your risk is critical.

---

## 🚀 Live Demo

🔗 [Click here to try the app](https://sensei017.github.io/ai-health-analyzer/ai-genetic-risk-predictor.html)

---

## 💡 What the App Does

You fill in a detailed 5-step form about your body, daily routine, habits, diet, and medical history. The AI Expert System then:

- Calculates your **BMI** and classifies your weight category
- Runs **36+ IF-THEN rules** from the Knowledge Base against your data
- Predicts your **risk percentage** for 6 major diseases
- Generates a **personalized behaviour change plan**
- Tells you **what to start doing** based on your top risk factors
- Shows **specific precautions** if you're already experiencing symptoms
- **Finds nearest hospitals and clinics** using your GPS location if risk is high

---

## ✨ Features

- 📏 **Live BMI Calculator** — real-time BMI with color-coded bar (Underweight / Normal / Overweight / Obese)
- 🤖 **AI Inference Engine** — forward chaining fires 36+ IF-THEN rules against patient data
- 📊 **6-Disease Risk Scoring** — Diabetes, Heart Disease, Hypertension, Obesity, Anxiety, Liver Disease
- 🔄 **Behaviour Change Plan** — 10 specific changes personalized to your exact lifestyle
- ✅ **Action Plan Generator** — Planning Agent creates 6 prioritized health goals
- 🚨 **Symptom Precautions** — specific medical advice if you're currently suffering
- 🏥 **GPS Clinic Finder** — locates nearest hospitals via Google Maps if risk is critical
- 📱 **Fully Responsive** — works on mobile, tablet, and desktop
- ⚡ **Zero Dependencies** — pure HTML, CSS, JavaScript — no frameworks needed

---

## 🧠 AI Concepts Used


Problem Solving & AI Techniques | Disease risk formulated as AI search problem — patient profile = initial state, diagnosis = goal state |
Knowledge Representation | Rule-based Knowledge Base with 36+ IF-THEN propositional logic rules across 6 disease categories |
Expert System & Planning | Full Expert System architecture — Knowledge Base + Inference Engine + Planning Agent |

---

## 🏃 How to Run

### Option 1 — Open directly
Just download the file and open it in any browser. No installation needed.

### Option 2 — Run with VS Code Live Server
1. Clone this repository
```bash
   git clone https://github.com/Sensei017/ai-health-analyzer.git
```
2. Open the folder in VS Code
3. Right-click `ai-genetic-risk-predictor.html`
4. Click **Open with Live Server**

---

## 🗂️ Project Structure
```
ai-health-analyzer/
└── ai-genetic-risk-predictor.html   ← entire app in one file
```

---

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Browser Geolocation API
- Google Maps (for clinic finder)

---

## 📌 Subject Info

- **Subject:** Artificial Intelligence (AI)
- **Test:** FT3 — Application Development Project
- **Units Covered:** Unit 1 · Unit 4 · Unit 5
