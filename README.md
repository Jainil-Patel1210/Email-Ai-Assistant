# 📧 AI Email Automation Assistant

This project is an LLM-powered email automation system that classifies incoming emails and generates appropriate responses using a generative AI model.

## 🚀 Features
- Email classification (leave request, salary query, job opening, policy feedback)
- Dynamic response generation using LLM
- Prompt-based workflow routing (similar to n8n pipelines)
- Built using LangChain and Google Gemini API

## 🧠 How it works
1. Input email is read from a file
2. LLM classifies the email type
3. Based on classification, a specific prompt template is selected
4. LLM generates a complete response

## 🛠️ Tech Stack
- Python
- LangChain
- Google Generative AI (Gemini)
- Prompt Engineering

## ▶️ How to Run

```bash
pip install -r requirements.txt

python take_home_assignment.py
Enter path to email file when prompted.


🔐 Setup

Create a .env file:

GOOGLE_API_KEY=your_actual_api_key
📌 Example

Input: Leave request email
Output: AI-generated HR response

💡 Key Concepts Demonstrated
LLM API integration
Prompt engineering
Workflow branching (similar to n8n)
End-to-end pipeline automation