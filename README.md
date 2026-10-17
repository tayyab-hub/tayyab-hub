<picture>
  <source media="(max-width: 600px)" srcset="assets/hero-mobile.svg">
  <img src="assets/hero.svg" alt="Muhammad Tayyab — Software Engineering, Full-Stack Development and Backend Development. Diploma in Computer Science at Methodist College Kuala Lumpur. Seeking a Software Engineering or IT internship starting January 2027." width="100%">
</picture>

**Available for internships from January 2027** · Kuala Lumpur, Malaysia<br>
Software Engineering · Full-Stack Development · Backend Development

[Explore projects](#featured-projects) · [Technology stack](#technology-stack) · [Contact me](#connect)

## About me

I'm Muhammad Tayyab, a **Diploma in Computer Science student at Methodist College Kuala Lumpur (MCKL)**. I build full-stack web applications, desktop software and Android coursework apps, working across interfaces, APIs and relational databases.

I enjoy turning practical problems into usable software—from explainable resume analysis in ResumeIQ and order preparation in SlipFlow to the SCAMGUARD team capstone and MCKL Mart coursework. My work includes automation, input validation, testing and deployment, with implementation details and limitations documented alongside the code. I'm seeking a **software engineering, full-stack or backend internship from January 2027**.

## Featured projects

### <img src="assets/projects/resumeiq.svg" width="28" height="28" alt=""> ResumeIQ

**Explainable resume analysis and job matching** · Personal full-stack project · Deployed demo

Comparing a resume with a job description should show the reasoning behind the result. ResumeIQ extracts text from PDFs, compares skills and presents an eight-category score with evidence and limitations.

- **Engineering:** bounded PDF processing, private saved reports, rotating refresh sessions and PostgreSQL integration tests.
- **Stack:** React · TypeScript · Python · FastAPI · PostgreSQL

[Source code](https://github.com/tayyab-hub/resumeiq) · **[Try the sample—no account needed](https://resumeiq-lemon-eight.vercel.app/sample)** · [Live app](https://resumeiq-lemon-eight.vercel.app/) · [Architecture](https://github.com/tayyab-hub/resumeiq/blob/main/docs/03-architecture.md)

<details>
<summary>View a real application screenshot</summary>

![ResumeIQ's hosted sample report showing a fictional candidate, an explained score and matched skills.](assets/screenshots/resumeiq-sample.jpg)

Actual hosted sample using a fictional resume and job description. The score follows the project's published rubric; it does not predict hiring outcomes. AI is disabled in the hosted demo.

</details>

---

### <img src="assets/projects/slipflow.svg" width="28" height="28" alt=""> SlipFlow

**Offline order review and production management** · Independent desktop project · Windows v1.0.0

Informed by my support work in family manufacturing operations, SlipFlow turns marketplace order exports into reviewed production instructions. It imports order files, maps product variants to factory SKUs, guides operator review and generates A4 tailor slips.

- **Engineering:** source-line traceability, duplicate handling, controlled batch states, SQLite persistence and verified backup/restore workflows.
- **Stack:** Electron · React · TypeScript · SQLite

[Source code](https://github.com/tayyab-hub/SlipFlow) · **[Windows installer](https://github.com/tayyab-hub/SlipFlow/releases/tag/v1.0.0)** · [User guide](https://github.com/tayyab-hub/SlipFlow/blob/main/docs/user-guide.md) · [Testing evidence](https://github.com/tayyab-hub/SlipFlow/blob/main/docs/testing.md)

<details>
<summary>View a real application screenshot</summary>

![SlipFlow desktop dashboard showing order import, production review and print workflows with synthetic marketplace data.](assets/screenshots/slipflow-dashboard.png)

Actual Electron application capture using synthetic fixtures. Live marketplace formats, physical printers and factory operation still need field validation.

</details>

---

### <img src="assets/projects/scamguard.svg" width="28" height="28" alt=""> SCAMGUARD

**Scam-awareness and analysis workspace** · Team capstone in development

Suspicious content needs context before a user acts on it. SCAMGUARD analyses messages and URL structure, explains warning signals and uncertainty, and keeps analysis history private to each account. Implemented phone and QR tools extend the same workspace.

- **Engineering:** local message and URL models, explicit evidence limits, session-based ownership, CSRF protection and bounded input handling.
- **My contribution:** frontend and backend workflows for input handling, authentication, private history and risk explanations; support for automated testing and deployment.
- **Stack:** React · TypeScript · Python · FastAPI · PostgreSQL

[Source code](https://github.com/tayyab-hub/scamguard-my) · **[Live prototype—account required](https://scamguard-my.vercel.app/)** · [Architecture](https://github.com/tayyab-hub/scamguard-my/blob/main/docs/ARCHITECTURE.md) · [Limitations](https://github.com/tayyab-hub/scamguard-my/blob/main/docs/LIMITATIONS.md)

Results are indicators, not proof of fraud or safety. This capstone is still being developed; independent real-world detection accuracy is not claimed.

---

### <img src="assets/projects/mckl-mart.svg" width="28" height="28" alt=""> MCKL Mart

**Academic e-commerce application** · Individual Web Computing coursework · Deployed demo

A convenience-store workflow from product discovery to a database-backed order. MCKL Mart implements authentication, a session cart, checkout and account-owned order history with PHP and a relational database.

- **Engineering:** PDO prepared statements, password hashing, CSRF checks, server-calculated totals and transactional stock updates with row locks.
- **Stack:** PHP · JavaScript · HTML/CSS · MariaDB

[Source code](https://github.com/tayyab-hub/MCKL-Mart) · **[Try the demo store](https://mcklmart.site.je/)** · [Database design](https://github.com/tayyab-hub/MCKL-Mart/blob/main/database/README.md) · [Testing evidence](https://github.com/tayyab-hub/MCKL-Mart/blob/main/docs/TESTING.md)

Orders, payments and delivery are simulated. This is an independent academic project, not a college-operated store.

<sub>ResumeIQ and SCAMGUARD use free API hosting, which can take time to wake after inactivity. Use fictional data when exploring the demos.</sub>

## Technology stack

Tools used in my public projects and Java/Android coursework. Public repositories link to implementation and testing evidence.

<p>
  <img src="assets/tech/python.svg" width="40" height="40" alt="Python">
  <img src="assets/tech/typescript.svg" width="40" height="40" alt="TypeScript">
  <img src="assets/tech/react.svg" width="40" height="40" alt="React">
  <img src="assets/tech/fastapi.svg" width="40" height="40" alt="FastAPI">
  <img src="assets/tech/postgresql.svg" width="40" height="40" alt="PostgreSQL">
  <img src="assets/tech/electron.svg" width="40" height="40" alt="Electron">
</p>

| Area | Technologies and practices |
| :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, PHP, SQL; Java (Android coursework) |
| **Frontend** | React, HTML, CSS, Tailwind CSS, Vite |
| **Backend & APIs** | REST APIs, FastAPI, Pydantic, SQLAlchemy, PHP/PDO |
| **Databases** | PostgreSQL, MariaDB, SQLite; relational modelling, transactions and Alembic migrations |
| **Desktop** | Electron, React, TypeScript, SQLite; Windows packaging |
| **Mobile coursework** | Java, Android Studio / SDK, XML layouts, Activities, SharedPreferences |
| **Tools & deployment** | Git, GitHub, GitHub Actions, Docker; Vercel, Render, Neon |
| **Testing & reliability** | pytest, Vitest, Playwright, integration tests; JUnit and Android instrumented tests (coursework) |

## Education and recognition

**Diploma in Computer Science**<br>
Methodist College Kuala Lumpur (MCKL), Malaysia · **2025–Present**<br>
**Dean's List — two recognitions**

Academic development includes the **SCAMGUARD team capstone**, individual **MCKL Mart** Web Computing coursework, and **MoneyPersona**, a Java-based Android coursework app using XML interfaces, local persistence with SharedPreferences, validation, unit tests and instrumented Android tests.

<details>
<summary>Selected learning and course certificates</summary>

- Google — **[Foundations: Data, Data, Everywhere](https://www.coursera.org/account/accomplishments/verify/29AJI6MDE1O9)** · Individual course, 2026.
- Google — **[Foundations of Data Science](https://www.coursera.org/account/accomplishments/verify/9SXNIF6M0USW)** · Individual course, 2026.
- **AWS Academy Cloud Foundations** · Training completion, 2026.

The Google credentials are individual courses within the Data Analytics and Advanced Data Analytics pathways. AWS Academy training is a course completion, not a professional AWS certification.

</details>

## Currently developing

Continuing **SCAMGUARD with my capstone team** while strengthening my understanding of backend system design, database-backed applications, API development, automated testing and reliable deployment.

## Connect

I'm seeking a **Software Engineering, Full-Stack, Backend or IT Development internship starting January 2027**.

**[Email Muhammad Tayyab](mailto:tayyabofficial0978@gmail.com)** · [LinkedIn](https://www.linkedin.com/in/tayyab-muhammad-tayyab-969a69351/) · [GitHub](https://github.com/tayyab-hub)

<sub>Project links lead to the source, architecture and testing notes. GitHub's native contribution activity is available below this profile.</sub>
