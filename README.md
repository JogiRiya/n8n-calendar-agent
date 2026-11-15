**AI Calendar Agent (n8n + OpenAI)**

This project is an AI-powered conversational agent built using n8n and OpenAI. It automates the process of scheduling events in Google Calendar based on natural language chat inputs.

**Features**

Natural Language Processing: Understands casual conversation (e.g., "Schedule a meeting with Rahul tomorrow at 4 PM").

Smart Date Parsing: Automatically calculates the correct date and time based on the current day.

Autonomous Tool Calling: The AI agent independently decides to use the Google Calendar tool to create the event.

Context Memory: Uses Simple Memory to remember past interactions during the chat session.

**Tech Stack**

Automation Tool: n8n

AI Model: OpenAI (Chat Model)

Integration: Google Calendar API

**How it Works**

Chat Trigger: Receives the user's message.

AI Agent (with Memory): Analyzes the intent and extracts the required event details (title, date, time).

Google Calendar Tool: Creates the event directly in the connected Google Calendar.

Response: Returns a confirmation message to the user.
