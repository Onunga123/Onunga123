# Onunga Christopher — Engineer (ML, IoT, Embedded Systems, Full‑stack & Automation)

I design and build practical technology solutions that combine machine learning, IoT and embedded systems, full‑stack web development, and automation; I move prototypes into production by integrating models, services, and workflows so solutions are reliable, observable, and maintainable. I ship end‑to‑end systems including model development and evaluation, optimized inference at the edge, secure APIs and web apps, and automated operational workflows. My experience covers both machine learning and non‑ML engineering — full‑stack applications, integrations, automation, and IoT solutions — with a strong focus on operational reliability and measurable user impact.

## Representative work (what each entails)

- **Help Desk System** — A full institutional helpdesk platform with an integrated HR application portal and a public‑facing applicant portal. Features include role‑based authentication, ticket management, file attachments, a searchable knowledge base, asset tracking, reporting and analytics, email (Brevo) and in‑app notifications, and exportable reports. The system is designed for secure deployment and operational monitoring in institutional environments.

- **Offline IoT-Based Real‑Time Low‑Cost Water Quality Monitoring System** — An offline ESP32‑based water quality monitor designed for rural households (Migori County, Kenya). Key elements:
  - ESP32 WROOM microcontroller running C++/Arduino‑style firmware, using SPIFFS for local storage and AP mode to serve a local dashboard.  
  - Sensors: TDS (Total Dissolved Solids) and DS18B20 temperature (GPIOs as configured in the prototype).  
  - Local mobile/web dashboard served directly from the device so users can view readings without internet or cloud dependencies.  
  - Focus on TDS and temperature reporting against WHO‑oriented thresholds; >1,000 real readings collected during prototyping.  
  - Future directions: on‑device anomaly detection, colour‑coded alerts, mesh networking, GIS tagging, and predictive analytics.

- **GroupMind** — A Telegram‑centric conversational agent that turns group chat into searchable organizational memory and action: detects tasks, responsibilities, decisions, and deadlines; persists structured state (Supabase/Postgres); answers questions from conversation context; and schedules reminders/actions via orchestrators such as Trigger.dev. Built with TypeScript/Node and focused on integrating LLM reasoning while keeping application code in control of actions.

- **farmer-weather-market-automation** — An n8n workflow that automates farmer advisories by combining weather (OpenWeather) and market price data (Google Sheets), composing contextual advisories, and delivering them via WhatsApp (Twilio) and Email (Brevo). Delivered as a deployable workflow with Docker/CI integration.

- **jengasafi-local** — A sustainability intelligence platform (Next.js/React) aimed at the construction industry: authentication and authorization, analytics dashboards, materials and carbon data features, and backend APIs to support data pipelines and decision support.

- **pdf-qa-system** — Retrieval‑augmented Q&A for documents: PDF extraction → chunking → embeddings (SentenceTransformers) → FAISS vector store → semantic retrieval → answer extraction (RoBERTa/Hugging Face). Packaged with a Streamlit demo for exploration and evaluation.

- **AIHealthTranslator** — An AI‑powered healthcare language support system to reduce language barriers between providers and patients. Focuses on English ↔ Kiswahili translation (Luo planned), sentiment analysis, and speech support. Built around a FastAPI backend with a modular architecture separating frontend, backend services, language models, and supporting scripts. Intended for locally relevant, accessible healthcare communication tools. (https://github.com/Onunga123/AIHealthTranslator)

- **Bruteforce-Detector** — AI‑powered login threat detection (Flask + Isolation Forest) for anomaly detection: log parsing, automatic IP blocking, email/SMS alerts (Twilio), and an admin interface for threat review and response. (https://github.com/Onunga123/Bruteforce-Detector)

- **financial-sentiment-analyzer** — Scrapes and analyzes live financial headlines using FinBERT and TextBlob, with an interactive Streamlit dashboard, data exports, and visualizations to track sentiment for tickers such as AAPL, TSLA, and GOOGL. (https://github.com/Onunga123/financial-sentiment-analyzer)

- **ms365-ai-assistant-mcp** — A Model Context Protocol (MCP) server that integrates LLM assistants with Microsoft 365 services (email, calendar, Planner, Teams, OneDrive, SharePoint). Provides secure OAuth integration, audit logging with PII redaction, rate limiting, tool exposure across M365 categories, and operational health monitoring. (https://github.com/Onunga123/ms365-ai-assistant-mcp)

## Contributors & collaborations

- jo-oseeph/BomaFlow — Contributor project: an all‑in‑one rental operations platform (properties, tenants, payments, maintenance, listings). (https://github.com/jo-oseeph/BomaFlow)  
- jo-oseeph/ENTELIX — Contributor project with a public site at https://entelix.vercel.app (https://github.com/jo-oseeph/ENTELIX)

If any attribution or phrasing is incorrect, tell me which repo or file to cite and I will refine the language.

## Core strengths

- IoT & embedded systems: model and firmware integration for constrained devices (ESP32, edge Linux), low‑power sensing, offline dashboards, and hardware integration.  
- Full‑stack engineering: React, Next.js, Node.js, secure APIs, authentication & RBAC, dashboards, and deployment.  
- Machine learning engineering: model design, training, evaluation, optimization and deployment (PyTorch).  
- Retrieval & RAG: FAISS vector stores, embeddings, and scalable document search.  
- Automation & integrations: n8n, Power Automate, Twilio, Brevo, and orchestration for operational workflows.  
- Production readiness & MLOps: CI/CD, monitoring, model/version management, and observability.

## How I work

Pragmatic, iterative process: prototype → measure → optimize → harden. I emphasize clear APIs, automated deployments, and operational observability, collaborating closely with product and operations teams to align technical choices with user and business needs.

## Technologies

Python · PyTorch · OpenCV · FAISS · FastAPI · Node.js · Next.js · React · Docker · Supabase · Vercel · Render · n8n · ESP32 · IoT · CI/CD

## Contact

- GitHub: https://github.com/Onunga123  
- Email: onungachristopher363@gmail.com  
- LinkedIn: https://www.linkedin.com/in/christopher-onunga-3a212b226/
