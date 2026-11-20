# AI Code Buddy 🤖

AI Code Buddy is a multi-agent AI coding assistant built using n8n. It helps users with coding-related tasks by using AI agents to interact with GitHub repositories, manage documents, and deliver results through different services.

## 🚀 Features

- **AI Coding Assistance:** Handles coding-related queries through an AI-powered workflow.
- **GitHub Integration:** Retrieves repository information, files, and code using GitHub tools.
- **Document Management:** Creates and updates Google Docs.
- **Email Integration:** Delivers information through Gmail.
- **Multi-Agent Workflow:** Uses an orchestrator agent to coordinate specialized agents.

## 🛠️ Tech Stack

- n8n
- Generative AI / LLMs
- GitHub API
- Google Docs
- Gmail
- AI Agents

## ⚙️ How to Import

1. Download the `AI_Code_Buddy.json` file from this repository.
2. Open your n8n instance.
3. Import the workflow from the downloaded JSON file.
4. Configure the required credentials for GitHub, Google services, and the AI model.
5. Run the workflow and start interacting with AI Code Buddy.

## 📂 Project Structure

```text
AI-Code-Buddy/
├── AI_Code_Buddy.json
├── README.md
└── screenshots/
    ├── workflow.png
    └── output.png
```

## 📌 Note

This workflow is built for learning and experimentation with AI agents and workflow automation. Credentials are not included in this repository and must be configured separately.

