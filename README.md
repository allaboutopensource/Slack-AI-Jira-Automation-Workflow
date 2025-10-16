# slack-ai-jira-automation-workflow-Using-N8n
End-to-end automation workflow using n8n, Slack, AWS Bedrock (Anthropic Claude Haiku), and Jira to intelligently manage ticket operations via conversational Slack commands.


# Slack AI-Powered Jira Automation Workflow

This repository contains an n8n workflow that integrates Slack, AWS Bedrock (Anthropic Claude Haiku), and Jira to automate ticket management through conversational commands. The workflow enables users to interact with a Slack bot to create, update, delete, or check the status of Jira tickets using natural language.

## 🚀 Features

- **Slack Bot Trigger**: Listens for mentions in Slack and initiates the workflow.
- **AI Agent (Claude Haiku via AWS Bedrock)**: Parses user intent from Slack messages using Anthropic's Claude model.
- **Jira Integration**: Performs ticket operations (create, update, delete, status check) based on AI interpretation.
- **Slack Response**: Sends confirmation or status messages back to the Slack channel.

## 🛠️ Technologies Used

- n8n – Workflow automation platform
- [lack API – For bot interaction and event triggers
- AWS Bedrock – For accessing Claude Haiku
- [Jira API](https://developer.atlassian.com/cloud/jira/platform/restck Trigger Node**: Activated when the bot is mentioned in a channel.
2. **AI Node (Claude Haiku)**: Processes the message and determines the user's intent.
3. **Jira Node**: Executes the appropriate action (create/update/delete/status).
4. **Slack Message Node**: Sends a response back to the user confirming the action.

<img width="1491" height="612" alt="image" src="https://github.com/user-attachments/assets/f78c6497-35b9-468d-820a-98b713fee2f0" />



## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/slack-ai-jira-automation-workflow.git


2) Import Workflow into n8n

Open your n8n instance.
Import the slack-ai-jira-workflow.json file.


3) Configure Environment Variables

Slack Bot Token & Signing Secret
AWS Bedrock credentials
Jira API credentials

4) Deploy and Test

Mention the Slack bot with a command like:
@your-bot create a Jira ticket for login issue in project ABC
