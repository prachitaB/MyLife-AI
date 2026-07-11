# MyLife AI – Software & System Requirements

## Project Name

**MyLife AI – Human-in-Control AI Personal Life Operating System**

---

# 1. Overview

MyLife AI is an AI-powered personal productivity and life management system that helps users:

- Plan long-term goals
- Generate milestones
- Create actionable tasks
- Maintain a daily journal
- Receive AI-powered coaching
- Track personal growth and productivity

The system integrates Artificial Intelligence, Workflow Automation, Google Sheets, and a modern web interface to provide an intelligent personal assistant.

---

# 2. Software Requirements

## Workflow Automation

- n8n Cloud (Latest Version)

---

## Artificial Intelligence

- OpenAI API
- OpenAI Chat Model
- Structured Output Parser

---

## Database

- Google Sheets
- Google Drive

---

## Frontend

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript (ES6)

---

## Backend / Automation

- n8n Workflows
- Webhooks
- HTTP Requests

---

## Version Control

- Git
- GitHub

---

## Browser

Recommended:

- Google Chrome (Latest)

Also Supported:

- Microsoft Edge
- Mozilla Firefox

---

## Code Editor

Recommended:

- Visual Studio Code

Extensions:

- Live Server
- Prettier
- Tailwind CSS IntelliSense
- GitHub Pull Requests
- GitLens

---

# 3. Hardware Requirements

## Minimum

Processor:
- Intel Core i3 (4th Generation) or equivalent

RAM:
- 4 GB

Storage:
- 500 MB free space

Internet:
- Stable internet connection

Display:
- 1366 × 768 resolution

---

## Recommended

Processor:
- Intel Core i5 / AMD Ryzen 5 or better

RAM:
- 8 GB or higher

Storage:
- SSD

Internet:
- Broadband connection

Display:
- Full HD (1920 × 1080)

---

# 4. Accounts Required

- GitHub Account
- OpenAI Account
- Google Account
- n8n Cloud Account

---

# 5. APIs Used

- OpenAI API
- Google Sheets API (via n8n)
- Google Drive Integration
- n8n Webhook API

---

# 6. Technologies Used

| Category | Technology |
|----------|------------|
| Frontend | HTML5 |
| Styling | Tailwind CSS |
| Scripting | JavaScript |
| Workflow Automation | n8n |
| AI | OpenAI GPT |
| Database | Google Sheets |
| Storage | Google Drive |
| Version Control | Git |
| Repository | GitHub |

---

# 7. Development Environment

Operating System:

- Windows 10 / Windows 11

Development Tools:

- Visual Studio Code
- Live Server Extension
- Google Chrome

---

# 8. Folder Structure

```
MyLife-AI/
│
├── frontend/
│   └── index.html
│
├── workflows/
│   ├── Goal-Planner.json
│   ├── Task-Generator.json
│   ├── Journal-Agent.json
│   └── AI-Coach.json
│
├── database/
│   └── MyLife_AI_Database.xlsx
│
├── screenshots/
│
├── docs/
│
├── README.md
├── requirements.md
├── LICENSE
└── .gitignore
```

---

# 9. Functional Requirements

The system shall:

- Allow users to create goals.
- Generate milestones using AI.
- Generate tasks from milestones.
- Store all data in Google Sheets.
- Accept journal entries.
- Analyze journal mood and energy.
- Provide AI coaching.
- Display dashboard statistics.
- Communicate using REST Webhooks.

---

# 10. Non-Functional Requirements

- User-friendly interface
- Responsive design
- Fast workflow execution
- Modular architecture
- Easy maintenance
- Scalable workflow design
- Secure cloud-based automation
- JSON-based API communication

---

# 11. Internet Requirements

The application requires an active internet connection because it uses:

- n8n Cloud
- OpenAI API
- Google Sheets
- Google Drive

Offline mode is not supported.

---

# 12. Future Enhancements

- React Frontend
- Mobile Application
- Progressive Web App (PWA)
- Authentication System
- User Login
- Multi-user Support
- Dashboard Analytics
- Calendar Integration
- Email Notifications
- Habit Tracking
- Gamification
- XR / AR / VR Integration
- Voice Assistant
- AI Memory
- Local Database Support
- Docker Deployment

---

# 13. Installation Summary

1. Clone the repository.
2. Import the n8n workflows.
3. Create the Google Sheets database.
4. Configure OpenAI credentials in n8n.
5. Update webhook URLs in the frontend.
6. Run the frontend using Live Server.
7. Open the application in a browser.

---

# 14. Tested Environment

- Windows 11
- Google Chrome
- Visual Studio Code
- Live Server
- n8n Cloud
- OpenAI GPT
- Google Sheets

---

# 15. Author

**Omkar Gujar**

Computer Engineering Student

Saraswati College of Engineering

Mumbai University

---

**Version:** 1.0

**Status:** Prototype / Academic Project
