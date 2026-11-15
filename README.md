# 🛡️ ShadowAI Guard: Enterprise AI Security & Readiness Auditor

**ShadowAI Guard** is an automated AI Governance, Risk, and Compliance (GRC) auditing platform built for the **John Keells IT AI Readiness Challenge**. It enables enterprises to detect unauthorized Shadow AI data exposure and test internal LLM chatbots against adversarial prompt injection attacks before scaling AI adoption.

---

## 🚨 The Problem
As enterprises rapidly adopt Generative AI, two critical security vulnerabilities emerge:
1. **Shadow AI Data Leaks:** Employees upload sensitive corporate, financial, and customer data into unapproved public AI tools (e.g., ChatGPT, Claude, DeepSeek) without IT visibility.
2. **LLM Prompt Injection & Jailbreaks:** Customer-facing or internal AI assistants can be manipulated using adversarial prompts to bypass guardrails and leak confidential system secrets.

## 💡 The Solution
ShadowAI Guard provides a unified executive dashboard combining network telemetry analysis with automated red-teaming:
* **1️⃣ Shadow AI Network Log Scanner:** Parses enterprise network traffic logs (`CSV`) to flag unauthorized AI domain usage, identify high-risk data uploads, and pinpoint vulnerable departments.
* **2️⃣ Live LLM Red-Teaming Engine:** Powered by **Google Gemini (`gemini-2.5-flash`)**, it executes automated OWASP Top 10 prompt injection, authority impersonation, and obfuscation attacks to evaluate model resilience.
* **3️⃣ Executive AI Readiness Score (0–100):** Aggregates Data Exposure (40 pts), Model Resilience (40 pts), and Governance Controls (20 pts) into an actionable risk posture report for CISOs and leadership.

---

## 🛠️ Tech Stack
* **Frontend & Dashboard:** Streamlit
* **AI Red-Teaming Engine:** Google GenAI SDK (`google-genai`)
* **Data Processing:** Pandas
* **Environment Management:** Python-dotenv & Streamlit Secrets

---

## 🚀 Quick Start (Local Setup)

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/cyberThesha/ShadowAI-Guard.git](https://github.com/cyberThesha/ShadowAI-Guard.git)
   cd ShadowAI-Guard
