# 📊 Financial Researcher Crew

🚀 Company research used to take days. Not anymore. This multi-agent CrewAI system unleashes a team of AI agents that investigate, analyze, and report on any company — financials, market trends, risks, opportunities, and news — all collaborating autonomously to deliver a professional research report faster than your morning coffee brews. ☕
---

## 🚀 Features

* Company research and profiling
* Historical business performance analysis
* Market opportunity and risk assessment
* Recent news and event tracking
* Industry and competitive insights
* Future growth outlook evaluation
* Executive summary generation
* Professional report creation in Markdown format

---

## 🤖 AI Agents

### Senior Financial Researcher

Responsible for collecting and organizing critical information about a company, including:

* Company background
* Financial health
* Business performance
* Market position
* Recent developments
* Opportunities and challenges

### Market Analyst

Responsible for transforming research into a professional report by:

* Analyzing collected findings
* Identifying trends and patterns
* Generating business insights
* Creating executive summaries
* Producing structured financial reports

---

## 🛠️ Tech Stack

* Python 3.10+
* CrewAI
* Gemini 2.5 Flash Lite
* UV Package Manager
* YAML Configuration
* Markdown Report Generation

---

## 📂 Project Structure

```text
financial_researcher/
│
├── src/
│   └── financial_researcher/
│       ├── config/
│       │   ├── agents.yaml
│       │   └── tasks.yaml
│       ├── crew.py
│       └── main.py
│
├── output/
│   └── report.md
│
├── .env
├── pyproject.toml
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd financial_researcher
```

### 2. Create a UV Virtual Environment

```bash
uv venv
```

### 3. Activate the Environment

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux / macOS

```bash
source .venv/bin/activate
```

### 4. Install CrewAI

```bash
uv pip install crewai
```

### 5. Install Gemini Support

```bash
uv add "crewai[google-genai]"
```

### 6. Sync Dependencies

```bash
uv sync
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

From the project root directory:

```bash
crewai run
```

---

## 📄 Output

After execution, the crew generates a detailed company research report:

```text
output/report.md
```

The report typically includes:

* Executive Summary
* Company Overview
* Financial & Business Analysis
* Recent News & Events
* Opportunities & Risks
* Market Outlook
* Strategic Insights
* Conclusion

---

## 🎯 Use Cases

* Company Due Diligence
* Investment Research
* Market Intelligence
* Business Analysis
* Financial Reporting
* Competitive Research
* Industry Monitoring

---

## ⚠️ Disclaimer

This project is intended for research and educational purposes only. The generated reports should not be considered financial, investment, or trading advice. Always conduct independent verification before making financial decisions.

---

## 👨‍💻 Built With

Powered by **CrewAI**, **Gemini AI**, and **Python** to automate financial research and transform raw company data into actionable business intelligence.
