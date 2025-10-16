# slack-ai-jira-automation-workflow
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

## 📁 Repository Structure
