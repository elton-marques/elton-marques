# Elton Marques

**Software Developer focused on automation, web applications, integrations, and practical software products.**

I’m a developer from Brazil, currently pursuing a degree in **Systems Analysis and Development**.

I build software for practical problems, from internal tools and operational dashboards to OCR systems, integrations, and commercial applications.

I’m particularly interested in **automation, data processing, APIs, workflow integrations, backend development, and practical software solutions**.

> **Build software that solves real problems.**

---

## Products

### 🛡️ Invarly | Process Guardrails for monday.com

[**Website**](https://invarly.eltonmarques.com/) · **Commercial product** · **Source code private**

Invarly is a process guardrails application for monday.com designed to verify whether workflows actually reach their expected final state, not just whether an automation ran.

Teams can define time-bound rules such as:

> “When an item becomes Done, it must be moved to Archive within 10 minutes.”

Invarly monitors board activity and detects when the expected outcome does not occur within the configured timeframe.

Instead of focusing only on automation execution, Invarly validates the **actual result of the workflow**, helping teams identify broken automations, incomplete manual steps, and operational inconsistencies.

The application includes secure account connection, event-driven monitoring, role-based access, violation tracking, and support for multiple monday.com accounts.

**Key features:**

- Time-bound process guardrails
- Workflow state validation
- Violation tracking and resolution
- monday.com board integration
- Event-driven monitoring with webhooks
- Monitoring reconciliation
- Multi-account isolation
- Role-based permissions
- Monitoring health and error states
- Duplicate violation prevention

**Technologies used:** TypeScript, Node.js, monday.com GraphQL API, OAuth 2.1 + PKCE, Webhooks, monday Code, SecureStorage, Vitest.

**Focus:** workflow monitoring, process validation, monday.com integrations, B2B software, and event-driven applications.

*Invarly is being developed as a commercial application for distribution through the monday.com ecosystem. Its source code is private.*

---

## Projects

### 🌐 Personal Website & Developer Hub

[**Website**](https://eltonmarques.com/) · [**Repository**](https://github.com/elton-marques/eltonmarques-site)

My personal website and developer hub, built to showcase my projects, software products, technical work, services, and contact information.

It also serves as a central place for live applications, experiments, and public demos.

**Focus:** web development, deployment, product presentation, and developer portfolio.

---

### 📊 Cartão Mestre Dashboard

[**Live Demo**](https://eltonmarques.com/cartaomestre-demo/app/) · [**Repository**](https://github.com/elton-marques/cartao-mestre) · **Fictional data**

A dashboard designed to transform manually recorded operational data into useful information for analysis and monitoring.

The application provides:

- Interactive data visualization
- Filtering and exploration
- Historical analysis
- Operational metrics
- Report-oriented views

The public version uses **fictional data** and does not expose real company information.

The project originated from a real operational workflow and explores how manually maintained records can be transformed into a structured digital monitoring system.

**Focus:** dashboards, data processing, business intelligence, operational analytics, and web applications.

---

### 📝 MestreCheck | Handwritten Cartão Mestre OCR

[**Live Demo**](https://eltonmarques.com/leitor) · [**Repository**](https://github.com/elton-marques/leitor-matriculas)

MestreCheck is a specialized application designed to process handwritten **Cartão Mestre access-release forms**.

The system uses **PaddleOCR and OpenCV** to analyze the expected document structure, extract relevant information, validate the detected data, and reject documents that do not match the required format.

Unlike a generic OCR tool, MestreCheck is specialized for a specific operational document and workflow.

I also developed a desktop version using **Python and Tkinter**, sharing the same OCR processing core while adapting the interface to a different environment.

**Key capabilities:**

- Handwritten document processing
- Image preprocessing
- OCR-based data extraction
- Document layout validation
- Structured field extraction
- Invalid document detection
- Desktop and web interfaces

**Technologies used:** Python, PaddleOCR, OpenCV, Tkinter, and web technologies.

**Focus:** OCR, image processing, document validation, data extraction, and automation.

---

## What I Build

I’m particularly interested in software that reduces operational friction and improves repetitive or fragmented workflows.

Areas I work with include:

- Python automation and scripting
- Web applications
- Backend applications
- APIs and integrations
- Data processing and validation
- Excel, CSV, and spreadsheet workflows
- Web scraping and data extraction
- Dashboards and business intelligence
- Internal tools
- Workflow automation
- OCR and document processing
- Event-driven integrations
- Business process tooling

---

## Technologies Used in My Projects

These are some of the technologies, platforms, and tools used across my projects.

### Programming

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white" />
</p>

### Web & Backend

<p align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" />
</p>

### Data, Automation & Integrations

<p align="left">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth_2.0-3C4043?style=flat" />
  <img src="https://img.shields.io/badge/Webhooks-FF6C37?style=flat" />
</p>

### Tools & Infrastructure

<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailscale-000000?style=flat&logo=tailscale&logoColor=white" />
</p>

---

## How I Approach Development

Most of my projects begin with a concrete problem: a repetitive workflow, fragmented data, a manual process, or an opportunity to make an existing operation more reliable.

My usual approach is:

1. Understand the workflow and the problem.
2. Define what the software needs to accomplish.
3. Build a useful first version.
4. Test it with realistic scenarios.
5. Identify issues and improve the solution.
6. Refine usability, reliability, and maintainability.

I’m especially interested in the point where **software meets real operational processes**.

---

## About Me

I currently work in **loss prevention in retail** while developing software and studying Systems Analysis and Development.

Working close to day-to-day operations gives me direct exposure to processes that still depend heavily on spreadsheets, paper, manual verification, repetitive tasks, and disconnected information.

Many of my projects started from noticing those problems and asking:

> **Could this process be handled better by software?**

That mindset has led me to build automation tools, dashboards, OCR systems, web applications, integrations, and commercial software products.

I’m continuously improving my skills through hands-on development, experimentation, study, and real-world projects.

---

<p align="center">
  <i>Build. Learn. Improve. Repeat.</i>
</p>
