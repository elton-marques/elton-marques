# Elton Marques

**Software developer building automation tools, web applications, and workflow integrations.**

I'm based in Brazil and currently studying **Systems Analysis and Development**. Alongside software development, I work in **retail loss prevention**, where I see firsthand how much daily work still depends on paper forms, spreadsheets, and manual checks.

That experience shapes what I build: tools that turn operational data into useful information, automate repetitive tasks, and help teams verify that their processes work as expected.

[Portfolio & contact](https://eltonmarques.com/) · [Public repositories](https://github.com/elton-marques?tab=repositories) · [Invarly](https://invarly.eltonmarques.com/)

## Featured work

### Invarly — Process guardrails for monday.com

**Commercial application in development · Private source code**

An application that checks whether a workflow reaches its expected final state. Teams define an expected outcome and a deadline, for example:

> When an item becomes Done, it must be moved to Archive within 10 minutes.

Invarly monitors board activity and tracks violations when the expected outcome does not occur in time. This helps surface broken automations, incomplete manual steps, and inconsistent processes.

- Time-bound rules and workflow state validation.
- Event-driven monitoring with webhooks and reconciliation.
- Violation tracking and resolution, with duplicate prevention.
- Role-based permissions, account isolation, and monitoring health states.

**Built with:** TypeScript, Node.js, monday.com GraphQL API, OAuth with PKCE, monday Code, and Vitest.

[Explore Invarly](https://invarly.eltonmarques.com/)

### Cartão Mestre Dashboard — Operational data analysis

A dashboard that turns manually recorded operational data into structured views for analysis and monitoring. It grew out of a real operational workflow and brings together interactive charts, filters, historical analysis, and operational metrics.

The public demo uses **fictional data** and does not expose real company information.

**Focus:** data processing, interactive visualization, and operational reporting.

[Live demo](https://eltonmarques.com/cartaomestre-demo/app/) · [Source code](https://github.com/elton-marques/cartao-mestre)

### MestreCheck — Handwritten document processing

A specialized OCR application for handwritten **Cartão Mestre access-release forms**. It uses image preprocessing and document layout checks to extract structured fields, validate detected data, and reject documents that do not match the expected format.

The project includes web and desktop interfaces. The desktop version uses Tkinter and shares the same OCR processing core.

**Built with:** Python, PaddleOCR, OpenCV, and Tkinter.

[Live demo](https://eltonmarques.com/leitor) · [Source code](https://github.com/elton-marques/leitor-matriculas)

### Personal website — Portfolio & developer hub

A central place for my projects, software products, services, and contact information, with links to live applications and public demos.

[Visit website](https://eltonmarques.com/) · [Source code](https://github.com/elton-marques/eltonmarques-site)

## Technical toolkit

Technologies and tools used across my projects:

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat)

### Web & backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

### Data & documents

![PaddleOCR](https://img.shields.io/badge/PaddleOCR-0062B0?style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

Document processing, data validation, and Excel and CSV workflows.

### Automation & integrations

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth-3C4043?style=flat)
![Webhooks](https://img.shields.io/badge/Webhooks-FF6C37?style=flat)

API integrations, workflow automation, web scraping, and data extraction.

### Tools & infrastructure

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=flat&logo=tailscale&logoColor=white)

## How I work

I start by understanding the existing workflow: who uses it, where information comes from, and which manual steps create unnecessary work or errors.

From there, I build a useful first version, test it against realistic scenarios, and refine its usability, reliability, and maintainability. I'm especially interested in **backend development, data validation, and integrations** that make everyday operations easier to manage.

## Get in touch

You can find more about my work, services, and contact information on [eltonmarques.com](https://eltonmarques.com/).
