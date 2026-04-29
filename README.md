# Automated Follow-Up Reply System (n8n)

This project is a production-ready automation built using n8n.

## 🔧 What it does
- Collects job applications using an n8n Form Trigger
- Accepts resume uploads (PDF)
- Sends application email with resume attachment to recruiter
- Sends confirmation email to applicant
- Stores applicant data in Google Sheets
- Automatically tracks whether resume was uploaded (YES/NO)

## 🧩 Workflow Overview
Form Submission → Email to Recruiter → Confirmation Email → Google Sheets Logging

## 🛠 Tech Stack
- n8n (self-hosted, Docker)
- Gmail API (OAuth2)
- Google Sheets API
- Google Drive API
- ngrok (for local public testing)

## 🚀 How to use
1. Import the `.json` workflow file into n8n
2. Configure Gmail and Google Sheets credentials
3. Publish the workflow to enable production mode
4. Use the Production Form URL to collect submissions

## 🔐 Notes
- OAuth credentials are not included
- This repository contains only workflow logic
- Secrets must be configured locally

## 📌 Use Case
- Job application automation
- Resume collection systems
- HR / recruitment automation
