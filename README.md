# n8n-automation-workflows-collection

📌 Workflows Included
🤖 AI Mentor Chatbot (Telegram)

Description:
A Telegram-based AI Mentor chatbot that guides students through structured, mentor-like conversations to resolve technical doubts.

Key Features:

Telegram-triggered conversational workflow

AI Agent powered by LangChain and Gemini

Context-aware responses using session-based memory

Beginner-friendly, step-by-step explanations

Use Cases:
AI teaching assistant, student doubt-solving bot, guided learning mentor

🎓 Certificate Eligibility & Email Automation

Description:
An automated workflow that evaluates student performance from Google Sheets and sends personalized email notifications for Bronze, Silver, or Gold certificate eligibility.

Key Features:

Auto-trigger on new Google Sheet entries

Rule-based eligibility validation

Tiered certificate logic (Bronze/Silver/Gold)

Automated Gmail notifications for eligible and non-eligible students

Use Cases:
EdTech platforms, bootcamps, certification programs, academic evaluation systems

🛠 Tech Stack

Automation: n8n

AI / LLMs: LangChain, Google Gemini

Messaging: Telegram Bot API

Data Sources: Google Sheets

Notifications: Gmail

Memory Handling: Session-based conversational memory

📂 Repository Structure
/workflows
 ├── AI_Mentor_Chatbot.json
 ├── Certificate_Eligibility_Generation.json
README.md


Each workflow is exported as a .json file and can be directly imported into n8n.

▶️ How to Use

Clone this repository

Import the desired workflow JSON into n8n

Configure required credentials (Telegram, Google, Gmail, LLM APIs)

Activate the workflow

✨ Highlights

Modular and reusable workflow design

Clear separation of logic and integrations

Secure credential handling

Scalable for real-world deployments
