# AI Content Calendar (n8n + Google Sheets + Gmail + Telegram)

An AI workflow that drafts social media captions, waits for my approval, and reminds me when it's time to post. I built it for my own TikTok content about AI and automation.

## The problem it solves
Writing captions every day takes a lot of time, and that leads to inconsistent posting. This workflow drafts the captions for me while I stay in control of what goes out.

## What it does
- Reads my planned posts from a Google Sheet (date, topic, platform, tone, status)
- Uses AI to draft a caption for each post
- Sends the draft to my Gmail for approval
- Updates the post status in the sheet after I approve
- Sends post-day reminders on Gmail and Telegram
- Connects to Buffer for scheduling

## Google Sheet columns
Post Date, Topic / Idea, Platform, Tone, Caption, Status, Approved

## Tools used
- n8n
- Google Sheets
- Gmail
- Telegram
- AI model for caption drafting
- Buffer

## Who it's for
Content creators, small brands and social media managers who want consistent posting without writing every caption by hand.

## Files in this folder
- Screenshots: the workflow and the approval and reminder messages
- The workflow JSON file: import it into n8n and add your own credentials
