# UnoCode
ELLM Startup Initiative 2025 - Public Heathcare
# MediBridge AI Chatbot – Multilingual Triage Assistant

**MediBridge MY** is an AI-powered, multilingual triage chatbot built to assist patients in Malaysia’s public healthcare system. It uses **Google Translate** and **OpenAI GPT** to interpret symptoms in **Malay, Tamil, Mandarin, Arabic, and English**, classifies the urgency of the condition, and returns a medical triage response.

---

## Features

-  Accepts inputs in multiple languages (Malay, Tamil, Mandarin, Arabic, English)
-  Translates symptoms to English using Google Translate API
-  Classifies triage urgency using OpenAI's GPT (gpt-3.5-turbo or gpt-4)
-  Returns an explanation for the classification
-  Easy to run locally with minimal setup

---

##  How It Works

1. User enters a symptom in their preferred language
2. Text is translated to English
3. Translated symptom is passed to GPT with a medical triage prompt
4. GPT returns:
   - Triage Level: Emergency / Urgent / Non-Urgent
   - Reason: Explanation for classification

---

##  Tech Stack

| Tool         | Purpose                          |
|--------------|----------------------------------|
| Python       | Core programming language        |
| OpenAI API   | Triage classification (LLM)      |
| Googletrans  | Translation to English           |
| dotenv       | Securely load API keys           |

---

##  Sample Output

Input: بطني بتوجعني
Translated: My stomach hurts me
Triage Level: Urgent
Reason: Abdominal pain could indicate infection or digestive distress. Prompt evaluation is advised.
