# AI Lead Management & Automated Follow-up System

## Project Overview
An AI-powered lead management automation system built using n8n, Telegram, Google Sheets, and Google Gemini API.

The project automates lead collection, AI-assisted responses, lead tracking, and follow-up messages.

## Workflows

### 1. Telegram AI Lead Bot
- Receives messages through Telegram.
- Retrieves relevant lead information from Google Sheets.
- Uses Google Gemini AI to generate contextual responses.
- Updates lead information in Google Sheets.
- Sends the AI-generated response back through Telegram.

### 2. Automated Follow-up
- Runs automatically on a scheduled trigger.
- Checks leads that require follow-up.
- Identifies eligible leads based on their status and last contact time.
- Sends follow-up messages through Telegram.
- Updates follow-up status in Google Sheets.

## Technologies Used
- n8n — Workflow automation
- Google Gemini API — AI-generated responses
- Telegram Bot API — Messaging
- Google Sheets — Lead database and CRM

## Setup Requirements
Users need their own:
- n8n instance
- Telegram Bot credentials
- Google Sheets account and spreadsheet
- Google Gemini API key

Import the JSON workflow files into n8n and configure your own credentials and spreadsheet.

## Security
API keys and personal credentials are not included in these workflow exports.

## Project Objective
To demonstrate how AI and workflow automation can reduce manual lead management work, improve response times, and automate customer follow-ups.
