# Sales Copilot

AI-powered sales meeting analysis application built with Lovable, n8n and OpenAI.

## Overview

Sales Copilot helps sales teams analyze meeting transcripts using AI.

The application allows users to upload a meeting transcript and automatically generates:

- Executive Summary
- Opportunity Score
- Customer Insights
- SPIN Selling Assessment
- Follow-up Recommendations

---

## Architecture

Frontend:
- Lovable

Workflow & Orchestration:
- n8n

AI:
- OpenAI GPT

Flow:

User uploads transcript
↓
Lovable
↓
n8n Webhook
↓
OpenAI
↓
Structured JSON
↓
Lovable Dashboard

---

## Tech Stack

- Lovable
- n8n
- OpenAI API
- JSON
- Webhooks

---

## Features

- Upload .txt meeting transcripts
- AI-powered meeting analysis
- Executive summary generation
- Opportunity scoring
- SPIN Selling assessment
- Customer insights extraction
- Follow-up recommendations

---

## Future Improvements

- PDF and DOCX support
- Analysis history
- CRM integration
- Downloadable reports
- Authentication

---

## Author

Developed by Letícia Oliveira.
