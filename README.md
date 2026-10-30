## Hi, I'm Viktor 👋

Odoo ERP developer · Python & PostgreSQL · Batumi, Georgia (remote)

I build and speed up Odoo for warehouses and distribution: tracking goods by unique codes, box packing, handheld scanners, and database queries that stay fast on tables with tens of millions of rows.

Most of my work is in private company repositories under NDA, so this page shows only a small part of it.
Here you'll find my early Python projects and an Odoo module for tracking goods.

### 🔧 What I do

- Warehouse and product tracking modules from scratch: unique codes for every item, boxes inside boxes, handheld scanner support, millions of codes in production.
- Performance: find the slow part with a profiler, rewrite queries and add indexes, then prove the result matches the old calculation. Typical outcome: minutes become seconds.
- Data migrations on tables with tens of millions of rows, with tests and a rehearsal on a copy of the production database.
- Production support: find the root cause in logs and data, fix it safely, add a test so it does not come back.
- Business processes in Odoo: procurement with multi-level approvals and budgets, landed costs, plan-vs-actual sales planning that replaced Excel.
- Team practices: I wrote the module architecture standard my team follows, and did hundreds of code reviews for teammates.

### 🛠 Stack

- Odoo 13 to 19, Python, PostgreSQL / PostGIS, JavaScript, XML
- Docker, GitLab CI, GitHub Actions
- Automated unit and browser tests

### 🤖 AI-assisted engineering

Claude Code is my main development tool, and I've built my own setup around it:

- A code review pipeline of 13 agents: eight reviewers check the change, one agent challenges their findings, and four more research the code and its history, score the reviewers and write the report.
- Custom Claude Code skills (reusable instructions) that let the agent drive a handheld scanner emulator, search server logs, restore a database from a snapshot in seconds, and measure performance before and after a change.
- A step-by-step QA guide for every change, checked in a real browser with Playwright.
- Spec-driven workflow: a proposal, design, task list and verification report are written before the code is merged.

### 📫 Contacts

- LinkedIn: [linkedin.com/in/viktor-efimochkin](https://www.linkedin.com/in/viktor-efimochkin)
- Email: veek47@gmail.com
- Telegram: [@foma111](https://t.me/foma111)
