# futsal-arena-n8n-automation
n8n workflow for automated Futsal Arena booking processing and AI voice confirmation using Vapi.
# Futsal Arena AI Booking Automation

An n8n automation workflow that processes Futsal Arena bookings and connects them with an AI voice confirmation assistant.

## Workflow

Customer Booking
↓
n8n Webhook
↓
Edit Booking Fields
↓
Set Booking Status
↓
Vapi AI Voice Assistant
↓
Customer Confirmation

## Features

- Receives booking data through webhook
- Processes customer information
- Handles sport, date, time, duration and price
- Generates booking confirmation status
- Integrates with Vapi AI
- Supports dynamic booking variables
- Enables AI-powered voice confirmation

## Technologies

- n8n
- Vapi AI
- REST API
- Webhooks
- AI Voice Automation

## Booking Data

The workflow processes:

- Customer Name
- Phone
- Sport
- Booking Date
- Booking Time
- Duration
- Price
- Booking ID

## Note

API keys, credentials, and private configuration values are excluded from this repository.
