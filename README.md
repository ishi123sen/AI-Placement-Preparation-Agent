# AI Placement Preparation Agent

An AI-powered placement preparation system built using n8n, Gemini API, Google Sheets, Gmail, Google Drive, and Docker.

##  Project Overview

The AI Placement Preparation Agent helps students prepare for placements by analyzing their resume and generating personalized placement recommendations.

The system automates resume analysis, evaluates placement readiness, identifies missing skills, and provides actionable suggestions.

##  Features

- AI-powered resume analysis
- ATS score generation
- Resume strengths and weaknesses
- Missing skills identification
- Personalized placement suggestions
- Google Drive resume monitoring
- Google Sheets student data management
- Automated Gmail notifications
- Scheduled placement preparation workflow
- Gemini AI integration
- Docker-based n8n setup

## 🔄 Workflows

### Resume Feedback Agent

The Resume Feedback Agent:

1. Monitors a Google Drive folder.
2. Detects newly uploaded resumes.
3. Downloads the resume.
4. Extracts text from the PDF.
5. Sends the resume to Gemini AI.
6. Generates:
   - ATS Score
   - Strengths
   - Weaknesses
   - Missing Skills
   - Suggestions
   - Overall Feedback

### AI Placement Preparation Agent

The Placement Preparation Agent:

1. Runs on a scheduled trigger.
2. Reads student information from Google Sheets.
3. Uses Gemini AI to generate placement preparation recommendations.
4. Updates the student's information in Google Sheets.
5. Sends the result through Gmail.

##  Technologies Used

- n8n
- Gemini API
- Google Drive
- Google Sheets
- Gmail
- Docker
- JSON
- AI / LLM

##  Project Structure

```text
AI-Placement-Preparation-Agent/
│
├── workflows/
│   ├── AI Placement Preparation Agent.json
│   ├── Resume Feedback Agent.json
│   └── README.md
│
├── README.md
├── Workflow.json
├── docker-compose.yml
├── prompt.txt
└── report.pdf
