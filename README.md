# AI-Automation-Internship

This repository contains my work and practical assignments completed during my AI Automation Internship.

## Day 03 – Git, GitHub, APIs & Postman

### Lead Management API

For this assignment, I built a Lead Management API using **n8n Webhooks** and **Google Sheets** as the data storage system.

### Current API Workflows

The following API endpoints have been implemented:

#### 1. Create Lead

**Method:** POST  
**Endpoint:** `/create-lead`

This endpoint receives lead information and stores it as a new row in Google Sheets.

Example data:

```json
{
  "name": "Muhammad Ahmad",
  "email": "ahmad@gmail.com",
  "phone": "+923001234567",
  "company": "MATalogics",
  "interest": "AI Automation"
}
