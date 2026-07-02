# AI-Powered Email Automation with n8n

An n8n workflow that monitors incoming emails, identifies high-priority messages using AI, adds a Gmail label, generates a professional reply using Google Gemini, and sends an automated response.

## Features
- Gmail email trigger
- AI-based high-priority email classification
- Automatic Gmail labeling
- Professional reply generation using Google Gemini
- Structured subject and email-body output
- Automated email response workflow

## Technologies Used
- n8n
- Gmail API
- Google Gemini
- AI Text Classification
- Workflow Automation
- JSON

## Setup
1. Import `workflow.json` into n8n.
2. Connect your own Gmail OAuth2 credentials.
3. Connect your own Google Gemini API credentials.
4. Create a Gmail label for high-priority emails.
5. Update the label ID in the workflow if needed.
6. Test the workflow before activating it.

## Security
No API keys, credentials, email addresses, or private webhook URLs are included in this repository.