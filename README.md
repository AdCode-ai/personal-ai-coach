# 🏋️ Personal AI Coach

> A personal AI coach that uses health, activity and training data to provide personalized daily workout recommendations.

🚧 **Status: Early development — MVP planned for December 2026**

---

## 🎯 Vision

Personal AI Coach is designed to answer a single question every morning:

> **"What should I do today?"**

It removes daily decision fatigue by combining:
- 💤 **Sleep & Recovery** (Duration, HRV, fatigue)
- 🏃 **Recent Activities** (Acute load from the last 48-72h)
- 🏋️ **Training History** (Past sessions, volume, muscle groups)
- 🎯 **Goals & Constraints** (Available time, gear, targets)
- 💬 **User Feedback** (Perceived exertion, soreness)

The goal is to evolve from a daily recommender into a comprehensive AI companion for **training, recovery and nutrition**.

---

## 🚀 MVP: Daily Recommendation Engine

The initial release focuses on a single, reliable loop:

```text
Physiological & Training Data
              │
              ▼
   Deterministic Guardrails
   (Safety limits, target duration & intensity)
              │
              ▼
    LLM Contextual Engine
    (Exercise selection & session structure)
              │
              ▼
    Personalized Workout + Clear "Why"
              │
              ▼
    User Feedback & Log 

```

---
## 🛠️ Tech Stack

- **Backend**: Python 3.12+, FastAPI, Pydantic v2

- **Database**: PostgreSQL 16

- **Environment**: Docker, Docker Compose

- **Quality**: Pytest

- **AI**: LLM API with Strict Structured Outputs (JSON Schema) & MCP in the future

---

## ⚡ Quick Start

# 1. Clone repo
git clone [https://github.com/AdCode-ai/personal-ai-coach.git]
cd personal-ai-coach

# 2. Setup venv
python3 -m venv .venv
source .venv/bin/activate

# 3. Start database


# 4. Run API
