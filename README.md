# Google ADK Projects

<p align="center">

  **Exploring Agentic AI with Google's Agent Development Kit**

  Building and experimenting with AI agents using Python and Google ADK.

</p>

---

## About This Repository

This repository contains my hands-on learning and development journey with **Google Agent Development Kit (ADK)**.

The goal is to understand how to build AI agents, configure their behavior, integrate tools, and develop agent-based applications using Python.

Rather than focusing only on theoretical concepts, this repository emphasizes practical implementation and experimentation with Google's agent development framework.

## What is Google ADK?

Google Agent Development Kit (ADK) is an open-source framework designed to simplify the development, orchestration, evaluation, and deployment of AI agents.

It provides developers with tools to build agents that can reason, interact with external tools, and execute tasks through structured workflows.

Official Documentation: https://google.github.io/adk-docs/

GitHub Repository: https://github.com/google/adk-python

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Primary programming language |
| Google ADK | AI agent development framework |
| Gemini | Large Language Model |
| VS Code | Development environment |
| Git & GitHub | Version control |

## Project Structure

```text
Google-adk/
│
├── .venv/              # Python virtual environment (local)
├── .gitignore          # Files excluded from Git
├── README.md           # Project documentation
└── ...                 # Agent implementation files
```

*The project structure will be updated as additional components are implemented.*

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/mayanknegi22/Google-adk.git
```

### 2. Navigate to the Project Directory

```bash
cd Google-adk
```

### 3. Create a Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### 5. Install Google ADK

```bash
pip install google-adk
```

### 6. Configure Environment Variables

Create a `.env` file in the appropriate agent directory and configure your Gemini API credentials.

Example:

```env
GOOGLE_GENAI_USE_VERTEXAI=FALSE
GOOGLE_API_KEY=your_google_api_key
```

**Important:** Never upload your actual API keys or `.env` files to GitHub.

### 7. Run the Agent

Once your agent implementation is ready, you can use the ADK CLI:

```bash
adk web
```

Run this command from the directory containing your agent package.

## Learning Objectives

Through this repository, I aim to explore:

- Understanding AI agents and their architecture.
- Building agents using Google ADK.
- Working with Large Language Models (LLMs).
- Integrating tools with AI agents.
- Understanding agent instructions and execution flow.
- Exploring multi-agent systems.
- Learning agent orchestration and workflows.
- Developing practical Agentic AI applications.

## Future Improvements

- Build more advanced AI agents.
- Integrate external APIs and tools.
- Explore multi-agent communication.
- Implement structured agent workflows.
- Experiment with memory and session management.
- Explore agent evaluation and deployment.

## Learning Resources

- [Google ADK Official Documentation](https://google.github.io/adk-docs/)
- [Google ADK Python GitHub](https://github.com/google/adk-python)
- [Google AI Studio](https://aistudio.google.com/)
- [Google AI for Developers](https://ai.google.dev/)

## Author

**Mayank Negi**

MCA Graduate | Aspiring AI Engineer | Generative AI & Agentic AI Enthusiast

- GitHub: https://github.com/mayanknegi22

---

<p align="center">
  If you find this repository useful, consider giving it a ⭐.
</p>