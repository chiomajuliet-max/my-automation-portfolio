# AI Email Sorter (n8n + Gemini + Gmail)

An AI agent built in n8n that reads my incoming Gmail messages and sorts them into labels automatically. Urgent emails get extra handling.

## What it does
- Watches my Gmail inbox for new emails
- Uses Google Gemini to decide which category each email belongs to
- Adds the matching Gmail label automatically
- For Urgent emails, it also writes a draft reply and sends me a Telegram alert

## Labels
Job Applications, Learning and Events, Newsletters, Finance Apps, LinkedIn Job Offers, Shopping, Urgent, Billing

## How it works
1. Gmail Trigger picks up a new email.
2. Google Gemini reads it and chooses a category.
3. A Switch node sends it down the right path.
4. Gmail Add Label applies the label.
5. On the Urgent path, a reply is drafted in Gmail and a Telegram alert is sent.

## Tools used
- n8n
- Google Gemini
- Gmail
- Telegram

## Files in this folder
- Screenshots: the workflow and the sorter at work
- The workflow JSON file: import it into n8n and add your own credentials
