# Travel Agency AI Agent – Customer Enquiry Automation

An AI-powered customer service automation built using **n8n, Google Gemini, Google Sheets and Gmail**.

This project demonstrates how AI agents and workflow automation can help travel agencies manage customer enquiries, reduce manual administrative work and improve customer communication.

## Project Overview

The AI agent interacts with customers through a chatbot, collects holiday enquiry details and automatically processes their requests.

It supports three main actions:
- Answering general holiday-related questions
- Creating new customer enquiries
- Updating existing enquiries using unique enquiry IDs

## Key Features

- **AI Chatbot:** Uses Google Gemini to communicate with customers and collect information.
- **Automated Data Collection:** Records customer names, destinations, budgets, travel dates and traveller numbers.
- **Google Sheets Integration:** Automatically stores and updates customer enquiries.
- **Email Notifications:** Sends Gmail notifications when new enquiries are received.
- **Unique Enquiry IDs:** Generates identifiers to track individual enquiries.
- **Duplicate Detection:** Identifies potential duplicate submissions using customer details.
- **Enquiry Updates:** Allows customers to modify existing enquiries using their enquiry ID.
- **Error Handling:** Provides appropriate responses when an operation fails.

## Technologies Used

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Google Gemini | AI chatbot and natural language processing |
| Google Sheets | Customer enquiry storage |
| Gmail | Automated email notifications |
| JavaScript | Duplicate detection and data processing |

## Workflow

1. A customer sends a message to the AI chatbot.
2. Google Gemini interprets the request and identifies the required action.
3. The workflow routes the request to the appropriate process.
4. New enquiries are checked for duplicates before being saved.
5. Existing enquiries can be updated using their unique enquiry ID.
6. Successful new enquiries trigger an email notification.
7. The customer receives a confirmation or an appropriate error message.

## Workflow Screenshot

![Travel Agency AI Agent Workflow](Screenshot%202026-11-23%20140943.png)

## Testing

The workflow was tested using example customer enquiries, including:

- Successful new enquiry submissions
- Duplicate enquiry detection
- Updating existing customer details
- Handling invalid enquiry IDs
- Google Sheets and email error handling

## Project Status

**Completed portfolio demonstration.**

The workflow has been developed and tested in n8n. It is intended as a demonstration project rather than a production-ready travel agency booking system.

## Setup

The repository includes a sanitised n8n workflow JSON file.

To use the workflow, import the JSON into n8n and configure your own Google Gemini, Google Sheets and configure your own Google Gemini, Google Sheets and Gmail connections, including the relevant spreadsheet settings.

No live travel booking or availability-checking functionality is included.
