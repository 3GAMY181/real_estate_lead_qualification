# Telegram Leads Qualification Agent using n8n & Google Gemini

An intelligent n8n workflow that acts as a Telegram chatbot to qualify leads, maintain conversation memory, and automatically log qualified lead data into Google Sheets using Google Gemini AI.

## 🚀 Features
- **Telegram Integration:** Automatically triggers on incoming messages and responds back.
- **AI-Powered Agent:** Uses Google Gemini via n8n's Advanced AI nodes for natural conversation and lead qualification.
- **Conversation Memory:** Keeps track of chat history for a smooth user experience.
- **Google Sheets Integration:** Automatically appends extracted lead details into a spreadsheet.

## 📋 How to Import
1. Download the `Leads Qualification Agent.json` file from this repository.
2. Open your n8n instance.
3. Go to Workflows -> Click on the `...` (options) menu -> **Import from File**.
4. Select the downloaded JSON file.
5. Configure your own credentials:
   - Telegram Bot Token
   - Google Gemini API Key
   - Google Sheets OAuth2 / Credentials
   - <img width="1919" height="862" alt="image" src="https://github.com/user-attachments/assets/7a3d33d2-51d4-425e-aea9-500dcb8371e9" />
