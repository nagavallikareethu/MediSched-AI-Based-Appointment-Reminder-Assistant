# 🩺 MediSched: AI-Based Appointment & Reminder Assistant

**MediSched** is an intelligent healthcare assistant built using **n8n** that automates the process of managing medical appointments and sending personalized reminders to patients. By integrating Google Calendar, Cohere's AI, and Twilio SMS, it enables clinics and healthcare providers to deliver a seamless patient engagement experience.

---

## 🚀 Key Features

- 📅 **Smart Scheduling**  
  Integrates with Google Calendar to fetch real-time upcoming appointments.

- 🧠 **AI-Generated Reminders**  
  Uses Cohere's language model to generate friendly, context-aware reminder messages.

- 📲 **Automated SMS Notifications**  
  Sends personalized SMS reminders to patients using Twilio.

- 🔁 **Fully Automated Workflow**  
  Built using n8n for a no-code, easy-to-maintain automation pipeline.

---

## 📸 Project Workflow Overview



<img width="1737" height="828" alt="image" src="https://github.com/user-attachments/assets/d10a60b2-f773-4344-97a0-22ae944dda1d" />

---

## 🧰 Tools & Technologies

- **n8n** – Automation platform for workflow orchestration  
- **Google Calendar API** – Event scheduling integration  
- **Cohere API** – Natural language message generation  
- **Twilio API** – SMS sending service

---

## 🔐 API Key Setup

Before running the project, make sure to set up the required API credentials. Refer to the [API Setup Guide](./docs/API_keys_setup.md) for step-by-step instructions on:

- Google Calendar API
- Cohere API
- Twilio API

---

## ⚙️ How It Works

1. **Trigger**: The workflow starts on a schedule or webhook.
2. **Calendar Integration**: Fetches upcoming events from Google Calendar.
3. **AI Message Generation**: Uses Cohere API to craft personalized reminder text.
4. **SMS Delivery**: Sends the reminder via Twilio to the patient’s phone.

---

## 📝 Sample Output

![WhatsApp Image 2025-07-31 at 19 49 25_53bfdfa5](https://github.com/user-attachments/assets/d9fdab58-022b-415e-bf85-4c240164409e)
