# devpilot-demo
# 🚀 DevPilot AI

> AI-powered Code Review & Developer Assistant built with n8n.

DevPilot AI is an intelligent workflow automation project that helps software development teams automate code reviews, generate pull request summaries, detect potential issues, and notify developers using AI.

Instead of manually reviewing every code change, DevPilot AI analyzes commits or pull requests and generates actionable feedback in seconds.

---

## ✨ Features

- 🤖 AI-powered code review
- 📝 Pull Request summary generation
- 🐞 Bug and code smell detection
- 🔒 Basic security recommendations
- 📊 Code quality scoring
- 📩 Email/Slack notifications
- 📁 Stores review history in Airtable
- 🔄 Fully automated using n8n workflows

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Groq API | AI Code Analysis |
| GitHub API | Repository & Pull Request Integration |
| Airtable | Store AI Review Reports |
| Gmail / Slack | Notifications |
| JavaScript | Workflow Logic |

---

## 📌 Problem Statement

Software developers spend significant time reviewing code, writing summaries, and documenting changes.

DevPilot AI automates these repetitive engineering tasks, allowing developers to focus on building software instead of managing workflow overhead.

---

## 💡 Solution

Whenever a developer pushes code or opens a Pull Request, DevPilot AI automatically:

1. Detects the new commit or Pull Request
2. Fetches changed files from GitHub
3. Sends the code to an AI model
4. Generates a professional code review
5. Calculates a code quality score
6. Suggests improvements
7. Publishes the review
8. Stores the results
9. Notifies the development team

---

## 🏗 Workflow Architecture

```
GitHub
   │
   ▼
Webhook (n8n)
   │
   ▼
Fetch Changed Files
   │
   ▼
AI Code Review
   │
   ▼
Generate Report
   │
   ├────────► GitHub Comment
   │
   ├────────► Slack Notification
   │
   └────────► Airtable
```

---

## 📂 Project Structure

```
DevPilot-AI/

README.md

workflows/
    devpilot-review.json

screenshots/

demo/

docs/
```

---

## 📸 Screenshots

Coming soon...

---

## 🎥 Demo

Coming soon...

---

## 🚧 Roadmap

- [ ] GitHub Webhook
- [ ] AI Code Review
- [ ] Pull Request Summarizer
- [ ] GitHub Comment Automation
- [ ] Slack Notifications
- [ ] Email Notifications
- [ ] Release Notes Generator
- [ ] README Generator
- [ ] AI Documentation Generator
- [ ] Multi-Repository Support

---

## 👨‍💻 Author

**Talha Khan**

Software Engineering Student

Interested in:
- AI Automation
- React Native
- Workflow Automation
- Backend Development
- AI Agents

---

## ⭐ Future Improvements

- Multi-LLM Support (OpenAI, Claude, Gemini)
- Jira Integration
- GitLab Support
- Docker Deployment
- Kubernetes Deployment
- Dashboard & Analytics
...............................................