# Oliwier

I work in logistics IT and build personal projects around workflow automation, applied AI, and data pipelines.

Lately I've been building local media workflows, from rendering and lyric alignment to publishing and job recovery. I also build tools that turn support tickets, documents, and raw data into results people can review and act on.

## Featured Projects

### [Nightcore Automation Factory](https://github.com/noongarD/nightcore-automation-factory)

Local media pipeline that turns audio and artwork into YouTube visualizers, vertical shorts, and thumbnails. It aligns lyrics with Whisper, encodes video with FFmpeg, and can retry publishing finished videos without rendering them again.

**Stack:** n8n, Node.js, Playwright, FFmpeg, Whisper, PowerShell

### [Helpdesk AI Triage](https://github.com/noongarD/helpdesk-ai-triage)

Local web app that classifies IT support tickets, suggests a support team, and assigns a P1–P4 priority based on impact and risk signals. It shows prediction confidence and the terms that influenced the classification.

**Stack:** Python, FastAPI, scikit-learn, SQLite, Docker

### [Retail Pipeline Healthcheck](https://github.com/noongarD/retail-pipeline-healthcheck)

Python and SQL pipeline that turns synthetic retail CSVs into a daily sales report. It checks for duplicates and invalid orders, quarantines rejected records with reasons, and logs each run.

**Stack:** Python, SQL, SQLite, GitHub Actions

### [DocuMind Pipeline](https://github.com/noongarD/documind-pipeline)

Python pipeline that classifies business documents from text, extracts fields such as invoice numbers and amounts, and suggests follow-up actions. It records each processing step and includes an AWS deployment blueprint in Terraform.

**Stack:** Python, LangGraph (optional), AWS, Terraform, pytest

### [AI Workflow Triage Studio](https://github.com/noongarD/ai-workflow-triage-studio)

Next.js demo that turns a rough client brief into a workflow plan with proposed steps, risks, and points for human review. It runs with a local mock model and includes JSON schema validation and evaluation checks.

**Stack:** TypeScript, Next.js, React, Zod, Vitest

### [MiniSprintBoard](https://github.com/noongarD/MiniSprintBoard)

ASP.NET Core REST API for tracking team tasks, with SQL Server persistence and unit and integration tests. Docker Compose starts the API and database together, and the repository includes AWS deployment notes.

**Stack:** C#, ASP.NET Core, EF Core, SQL Server, Docker Compose, GitHub Actions

## More Projects

- [AI Review Board](https://github.com/noongarD/ai-review-board): Blazor app that flags risky patterns in C# snippets and stores review findings in PostgreSQL.
- [Data Engineering Portfolio](https://github.com/noongarD/data-engineering-portfolio): Three Dockerized projects covering API ingestion, PostgreSQL warehouse modeling, and data quality monitoring.
- [GamePatch Copilot](https://github.com/noongarD/gamepatch-copilot): Demo that groups player feedback into patch priorities, QA checks, and experiments using a local mock model.
- [GameOps Analytics](https://github.com/noongarD/gameops-analytics): Python and SQLite pipeline that turns synthetic game telemetry into scheduled Markdown and CSV reports.
- [SEO LocalBoost Portfolio](https://github.com/noongarD/seo-localboost-portfolio): Technical SEO demo with structured data and a JavaScript audit tool. [Live demo](https://noongard.github.io/seo-localboost-portfolio/)

## Technical Focus

- Workflow automation and self-hosted tooling with n8n and Docker
- Media processing and publishing with FFmpeg, Playwright, and Whisper
- Applied AI for ticket classification, document processing, and structured outputs
- Data pipelines, SQL modeling, and data quality checks
- REST APIs, automated tests, and CI

## Repository Guide

The featured and pinned repositories are the best starting points. Smaller repositories cover individual concepts, datasets, and programming exercises.

## Tools

`Python` `SQL` `n8n` `Docker` `FastAPI` `scikit-learn` `PostgreSQL` `SQLite` `FFmpeg` `Playwright` `TypeScript` `C#` `ASP.NET Core` `GitHub Actions` `Terraform`
