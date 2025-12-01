# 🌾 MittiSense: AI-Powered Multi-Agent Agriculture Advisory System

**Created & Developed by Meet Chaudhari 🧡**

---

## 📌 Overview

MittiSense is a robust **multi-agent AI system** designed to deliver **safe, natural, and multilingual** agriculture advisory. It supports real farmers and agriculture learners by combining **10 specialized AI agents** capable of analyzing:

* Crop condition
* Weather
* Soil type
* Diseases & pests
* Nutrient deficiencies
* Organic fertilizer options
* Historical risks
* Yield expectations

Built using **Google Gemini 2.5 Flash**, the system produces a fully validated advisory that is accurate, organic, and farmer-friendly.

---

## 🌟 Key Features

### 1️⃣ Multi-Agent Architecture

MittiSense includes 10 powerful AI agents, demonstrating advanced specialization and workflow orchestration:

| Agent | Role |
| :--- | :--- |
| **Agent-1** | Core Advisory (soil + weather + crop + notes) |
| **Agent-2** | Disease & Pest Expert |
| **Agent-3** | **Final Reviewer & Safety Validator** |
| **Agent-4** | Short Summary Generator |
| **Agent-5** | Natural Fertilizer Advisory |
| **Agent-6** | Weather & Climate Advisor |
| **Agent-7** | Soil Health Advisor |
| **Agent-8** | Organic Nutrient Booster |
| **Agent-9** | Historical Pattern Analyzer |
| **Agent-10** | Yield Estimator |

### 2️⃣ Multilingual Support

The entire system works in:
* **English**
* **Hindi**
* **Hinglish**

Every agent responds strictly in the selected language.

### 3️⃣ Organic & Safe Guarantees (Guardrails)

MittiSense never recommends chemicals. All recommendations are:
* Natural
* Organic
* Soil-safe
* Crop-safe
* Human-safe

This system strictly enforces rules to prevent the use of chemical brand names and pesticide suggestions, and maintains a neutral, professional tone (never calls the user "farmer").

### 4️⃣ Real-Time Context Integration

* Weather summaries powered by Gemini
* Soil-type intelligence (Black, Red, Sandy, Alluvial, Loamy, Clay)

### 5️⃣ End-to-End Master Pipeline

A single orchestrator function runs the 3-agent core validation loop and utilizes all 10 agents to output a comprehensive report including:
* Core advisory
* Disease analysis
* Final polished advisory
* Organic nutrient plan
* Weather advisory
* Soil health report
* Historical warnings
* Yield estimation
* JSON report
* Short summary

---

## 🚀 Tech Stack

* **Python**
* **Google Gemini 2.5 Flash**
* Kaggle Notebook
* JSON
* Multi-Agent Prompting

---

## 📁 Project Structure

* **Main File:** `MittiSense.ipynb`
* **Output Files:** `mittisense_report.json`, `mittisense_report.txt`

---

## ⚙️ How It Works

1.  **User Inputs:** Crop, Location, Soil, Season, and Notes (symptoms).
2.  **Agent Activation:** The system activates all 10 agents.
3.  **Intelligence Gathering:** Each agent contributes independently with specialized intelligence (Soil, Weather reasoning, Disease prediction, Fertility needs, Early warnings, Yield expectation).
4.  **Final Output:** The final report is **Clean, Safe, Natural, Language-accurate, and Actionable.**

### 🧪 Example Usage

```python
pipeline = run_mittisense_pipeline(
    crop="Cotton",
    location="Surat, Gujarat",
    soil="Black Soil",
    season="Kharif",
    notes="Leaves have small white spots",
    language="english"
)
# The full, validated advisory is available in pipeline["final_advisory"]
```
---

## 🌱 Why This Project Matters

1. Millions of people in agriculture face challenges such as:

2. Lack of expert advisory

3. Misuse of chemicals

4. Unpredictable weather

5. Soil degradation

6. Low awareness of organic methods

7. Inaccessible disease detection

MittiSense helps by offering:

1. Free, safe, natural crop guidance

2. Weather-aware decisions

3. Soil-based recommendations

4. Pest/disease warnings

5. Multilingual accessibility

6. Organic nutrient plans

This project demonstrates how multi-agent AI systems can create real, positive impact in agriculture.

---

## 👨‍💻 Author

* **Meet Chaudhari**
* **Creator & Developer of MittiSense**
* **Google AI Intensive — Capstone Project**
* **Kaggle Public Notebook • GitHub Repository**
