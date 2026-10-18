# Asteway Kebede — Data Analytics & Applied AI Portfolio

Source for [astewaykebede.com](https://www.astewaykebede.com), a recruiter-focused portfolio connecting operational analytics, machine learning, forecasting, reporting automation, and applied AI.

## Portfolio story

The site presents a clear progression from finance and operational analytics into AI-enabled decision support. It highlights the ability to:

- define governed metrics and diagnostic workflows;
- build analytical layers with Python, SQL, and BigQuery;
- create Tableau, Power BI, and interactive HTML reporting;
- connect structured data to AI agents and custom GPTs;
- apply machine learning and forecasting to operational decisions;
- communicate technical systems in clear business language.

## Featured work

### Flight Operations Intelligence Copilot

An operational analytics system built from 697,000 real U.S. DOT flight records, ten KPIs, national and regional scorecards, and traceable driver analysis.

[Project page](https://www.astewaykebede.com/flight-ops.html) · [GitHub repository](https://github.com/kasteway/flight-ops-intelligence)

### Applied AI Field Guide

A portable learning lab covering model selection, context engineering, tools, embeddings, RAG, MCP, agents, evaluation, security, governance, and production monitoring.

[Project page](https://www.astewaykebede.com/ai-field-guide.html) · [GitHub repository](https://github.com/kasteway/applied-ai-learning-lab)

## Technical structure

The portfolio is a lightweight static site built with semantic HTML, responsive CSS, and minimal JavaScript. Vercel deploys the `public` directory automatically from the main branch and serves the custom domain.

```text
public/
├── index.html
├── flight-ops.html
├── ai-field-guide.html
├── styles.css
├── case.css
├── resume.pdf
└── assets/
```

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Links

[Portfolio](https://www.astewaykebede.com) · [LinkedIn](https://www.linkedin.com/in/kasteway/) · [GitHub](https://github.com/kasteway)
