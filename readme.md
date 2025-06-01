# EchoVal AI 

## 🔍 Overview

**EchoVal AI** is an intelligent, multi-agent system designed to automatically find the best online deals, estimate their value, and send real-time push notifications. It leverages a fine-tuned LLM (trained on 400K+ products), and is deployed on **Modal**. A simple **Gradio** UI enables easy interaction and testing.

---

## 🤖 Agents

1. **Scanner Agent**
   Scrapes deals from target URLs and extracts the top 5 promising offers.

2. **Specialist Agent (Pricer)**
   Uses a QLoRA fine-tuned LLM to predict prices and select the best-valued deal.

3. **Messaging Agent**
   Sends push notifications to your phone via **Pushover** with the selected deal.

4. **Planner Agent**
   Automates the entire process: scan → predict → notify, in a seamless flow.

---

## 🛠️ How to Run the Application

1. Activate your virtual environment:

   ```
   venv/Scripts/activate
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the application:

   ```
   python echoval.py
   ```


