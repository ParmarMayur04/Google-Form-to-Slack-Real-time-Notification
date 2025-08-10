# Google-Form-to-Slack-Real-time-Notification
An automation that sends real-time Google Form responses directly to a Slack channel using Google Apps Script and Slack Incoming Webhooks.

📌 Overview
Manually checking Google Form responses is time-consuming.
This project solves the problem by automatically sending a formatted message to Slack every time a form is submitted — so your team can act instantly.

Workflow:
Google Form → Google Sheet → Google Apps Script → Slack Webhook → Slack Channel
🚀 Features
Real-time notifications from Google Form to Slack

Cleanly formatted messages for easy reading

Trigger-based automation — no manual execution

Works with any Google Form

No third-party paid tools required

🛠 Tech Stack
Google Forms

Google Sheets

Google Apps Script (JavaScript-based scripting)

Slack Incoming Webhooks API



⚙️ Setup Instructions
1️⃣ Create a Google Form & Link to Sheet
Create your Google Form.

Link the responses to a Google Sheet.

2️⃣ Create a Slack App & Webhook
Go to Slack API: Incoming Webhooks
https://api.slack.com/messaging/webhooks

Create a new Slack App and enable Incoming Webhooks.

Copy the Webhook URL (looks like https://hooks.slack.com/services/XXXX/XXXX/XXXX).

3️⃣ Add Google Apps Script
Open your linked Google Sheet.

Go to Extensions → Apps Script.

Paste the following code from code.gs

4️⃣ Set Trigger
In Apps Script, go to Triggers.

Add a trigger for sendToSlack → Event type: On form submit.

📊 Impact
✅ Reduced manual checking time by 90%.
✅ Ensured instant team updates.
✅ Scalable — works for any form & any Slack channel.
