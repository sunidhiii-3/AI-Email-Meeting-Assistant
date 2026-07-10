# AI Email Meeting Assistant

## Overview

This project automates meeting scheduling from Gmail using AI and n8n.

Whenever a new email arrives, the workflow:

- Reads the email
- Detects whether it contains a meeting invitation
- Extracts meeting details using OpenAI
- Creates a Google Calendar event
- Labels the processed email in Gmail

## Tech Stack

- n8n
- OpenAI API
- Gmail API
- Google Calendar API
- JSON Structured Output

## Workflow

Gmail Trigger

↓

AI Agent

↓

Structured Output Parser

↓

IF Node

├── Meeting → Create Calendar Event → Add Gmail Label

└── Not Meeting → Add Different Label

## Preview ##

<img width="1201" height="424" alt="Screenshot 2026-07-10 at 2 53 16 PM" src="https://github.com/user-attachments/assets/1a7f0a86-c54d-4992-bdda-9e9ee147ad20" />


## Features

- Automatic meeting detection
- AI-powered information extraction
- Google Calendar integration
- Gmail label automation
- No manual intervention

## Future Improvements

- Outlook support
- Zoom & Teams support
- Meeting reminders
- Chrome Extension
- Web Dashboard

## Author ##
SUNIDHI
