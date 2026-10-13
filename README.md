# 💼 KaamClear AI

**Turn confusing client messages into clear project briefs with local AI.**

KaamClear AI is a local-first AI assistant designed to help freelancers understand client requirements, identify missing information, estimate project effort, and prepare professional client replies.

## ✨ Features

- **Project Summary:** Convert unstructured client messages into clear project briefs.
- **Missing Questions:** Identify questions to ask before starting work.
- **Suggested Deliverables:** Outline the expected project outputs.
- **Risks and Assumptions:** Highlight potential challenges and dependencies.
- **Effort and Price Estimates:** Generate preliminary estimates based on the project scope.
- **Project Milestones:** Suggest a possible development timeline.
- **Client Reply Generator:** Draft a professional response to the client.
- **Downloadable Brief:** Download the generated project brief.

## 🧠 Built With

- Python
- Streamlit
- Ollama
- Gemma 3 (open-weight AI model)

## 🔒 Why Local AI?

KaamClear AI uses a locally running model through Ollama. This can help freelancers analyse client messages without sending them to a hosted AI API through this application's inference workflow.

Local processing does not automatically guarantee complete privacy. Keep Ollama and your computer secure, and avoid sharing sensitive client information unnecessarily.

## 🚀 Getting Started

### Prerequisites

Install:

- Python
- [Ollama](https://ollama.com/)
- Git (optional)

### 1. Download the project

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd KaamClearAI
```

Alternatively, download the repository as a ZIP and extract it.

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Download the AI model

```bash
ollama pull gemma3:4b
```

Make sure Ollama is running on your computer.

### 5. Run the application

```bash
python -m streamlit run d:\hf2project.py
```

Open the local URL shown in your terminal, usually `http://localhost:8501`.

## 📌 Important Notes

- AI-generated requirements, timelines, and prices are estimates, not guarantees.
- Review the generated brief before sharing it with a client.
- Actual performance depends on your computer and local model setup.
- This application currently uses local inference rather than a hosted AI service.

## 🛠️ Future Improvements

- More reliable, structured price calculations
- Budget-versus-estimate comparison
- Scope-reduction suggestions for limited budgets
- Improved output formatting
- More testing and error handling

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
