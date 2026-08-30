🤖 n8n AI Email Automation

An AI-powered email automation workflow built with n8n, Google Sheets, Google Gemini, and Gmail.

This workflow automatically reads contact information from Google Sheets, generates personalized cold emails using an AI Agent powered by Google Gemini, sends the emails through Gmail, and updates the contact status in Google Sheets after sending.

🚀 Features

- ⏰ Automated workflow scheduling using n8n
- 📊 Reads contact data from Google Sheets
- 🤖 Uses Google Gemini AI to generate personalized emails
- ✉️ Automatically sends emails through Gmail
- 🎯 Personalizes emails using the recipient's name and company
- 📝 Generates structured email subject and body
- ✅ Updates the Google Sheets status after sending
- 🔄 Reduces repetitive manual email work

🔄 Workflow

Schedule Trigger
       ↓
Google Sheets
       ↓
AI Agent (Google Gemini)
       ↓
Structured Output Parser
       ↓
Gmail
       ↓
Update Google Sheets

🧠 How It Works

1. Schedule Trigger
   Starts the workflow automatically according to the configured schedule.

2. Google Sheets
   Retrieves contact information such as:
   
   - Name
   - Company
   - Email
   - Status

3. AI Agent – Google Gemini
   Uses the contact's name and company to generate a short, personalized cold email focused on AI and automation services.

4. Structured Output Parser
   Formats the AI response into:
   
   - Email Subject
   - Email Body

5. Gmail
   Sends the generated email automatically to the recipient.

6. Update Google Sheets
   After successfully sending the email, the contact's status is updated to "Send".

🛠️ Technologies Used

- n8n – Workflow automation
- Google Gemini – AI-powered email generation
- Google Sheets – Contact and status management
- Gmail – Automated email delivery

📋 Google Sheets Structure

The workflow expects contact information with columns such as:

Name | Company | Email | Status

Example:

Ali | ABC Company | ali@example.com | Pending

After the email is sent:

Ali | ABC Company | ali@example.com | Send

⚙️ Setup

1. Install or open your n8n instance.
2. Import the "n8n Email Automation.json" workflow.
3. Connect your Google Sheets account.
4. Connect your Google Gemini API credentials.
5. Connect your Gmail account.
6. Configure your Google Sheet with the required columns.
7. Add your contacts and set their status appropriately.
8. Activate the workflow.

⚠️ Important

Before using the workflow, configure your own credentials for Google Sheets, Google Gemini, and Gmail. Never upload API keys, passwords, OAuth tokens, or other private credentials to GitHub.

🎯 Use Cases

This automation can be useful for:

- Cold email campaigns
- AI/automation service outreach
- Lead generation
- Business networking
- Sales outreach
- Personalized email campaigns

📁 Files

n8n Email Automation/
│
├── n8n Email Automation.json
└── README.md

👨‍💻 Author

Moazzam Ali

Software Engineering | AI & Machine Learning | AI Agents | Automation
