n8n Todoist Telegram Reminder

An automated workflow built with n8n that retrieves today's tasks from Todoist and sends them as a Telegram message on a scheduled basis.

## Features

- Daily scheduled execution
- Todoist API integration
- Telegram Bot notifications
- Automatic filtering of today's tasks
- JavaScript data processing inside n8n

## Workflow Overview

Schedule Trigger > Todoist > API Filter Today's Tasks > Telegram Notification

Example Message

Today's Tasks
Study n8n
Learn English
Workout

##Setup
1. Create a Todoist API Token
Get your API token from:
https://app.todoist.com/app/settings/integrations/developer
2. Create a Telegram Bot
Create a bot using BotFather and obtain your Bot Token.
3. Import Workflow
Import the workflow JSON file into n8n.
4. Configure Credentials
Replace:
YOUR_TODOIST_API_KEY
YOUR_TELEGRAM_CHAT_ID
with your own values.
5. Activate Workflow
Enable the workflow and keep your n8n instance running.


##USE Cases
Personal productivity
Daily planning
Task reminders
Habit tracking
