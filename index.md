# Adit Reddy
📍 Stone Ridge, VA | 📧 [aditreddya@gmail.com](mailto:aditreddya@gmail.com) | 📞 (571) 444-3144
[LinkedIn](https://www.linkedin.com/in/adit-reddy-5214672b1) | [GitHub](https://github.com/GoldnShadow) | [Download PDF Resume](./Adit-Reddy_Resume_Final-Draft%20(2).pdf)

## General Summary:
I am an American-born, **hands-on learner** and a **versatile developer** with a drive for creating **structured**, **optimized**, and highly organized **technical solutions**. I pride myself on being someone who is quick to master new technologies, from full-stack web development to quantitative financial modeling, to even **cloud development** and **fine-tuning AI models**. My approach is defined by a rigorous attention to detail and a commitment to efficient, clean, and primarily useful code.

Beyond the terminal, I am a strategic thinker and multi-disciplinary enthusiast with deep interests in **aerospace/aircraft**, **automotive engineering**, **competitive chess**, and more. These hobbies fuel my problem-solving mindset and my ability to analyze complex systems from multiple perspectives.

## Core Competencies
* **Productivity:** Expert proficiency in the **Google Workspace** and **Microsoft Office 365** suites for professional documentation and data management. Effective utiliser of Artificial Intelligence in an efficient environment. 
* **Soft Skills:** Driven by initiative, team-oriented, and highly adaptable to fast-paced technical environments. 
* **Versatility:** Capable of pivoting between data science (R), backend engineering (Node.js), and automated financial scripting (Python).

## Education
**George Mason University** | Fairfax, Virginia
*B.S. in Computer Science* | Expected May 2027
* **Relevant Coursework:** Data Structures, Object-Oriented Programming (Java), C & Unix, Python, Statistics for Engineers, MySQL/SQL, and Data Sciences (R).

## Technical Skills
* **Languages:** Python (Pandas, NumPy, yFinance), Java, C, R (Plotly, ggplot, imvar, modelr, broom), SQL (PostgreSQL, MySQL), JavaScript (Node.js, React), Brightscript.
* **Tools & Platforms:** Docker, AWS (CodeBuild/Deploy), Git, VMWare, VSCode, PyCharm, VSCode.
* **Testing & Workflow:** Postman, JUnit, Thunder Client, JIRA, Shell Scripting, Agile Methodologies.
* **Quantitative Finance:** CAPM, Fama-French 3-Factor, MPT Efficient Frontier, Risk-Adjusted Ratios (Sharpe/Sortino).

## Certifications:
* [**AI Fluency:** Anthropic's AI Fluency Certification.](assets/Ai Fluency Cert.pdf)
* [**Claude 101:** Anthropic's Claude 101 Certification.](assets/Claude 101 Cert.pdf)

## Experience

### AVCA | Office Intern
*August 2024 – September 2024*
* **Automation:** Engineered Python scripts to digitize 30% of company archives and automate reporting, resulting in a 15% increase in departmental productivity.
* **Optimization:** Reduced survey processing time by 200% through automated keyword indexing and streamlined operations by implementing new communication infrastructure.

### Mathnasium LLC | Instructor
*September 2023 – November 2024*
* **Instruction & Management:** Responsible for instructing students, managing academic paperwork, and coordinating scheduling/grading in an organized workspace.

## Honors & Volunteerism
* **HackFax x Patriothacks CTF:** Developer, Tester, and Volunteer for Capture the Flag challenges (Dec 2025 – Feb 2026).
* **Citizenship:** United States Citizen.

---

## Technical Projects
*A collection of engineering solutions focusing on quantitative finance, automation, and full-stack development.*

### NASDAQ Momentum & RSI Scanner
**Python | Pandas | Yahoo Finance API | SMTP (Email Automation)**
* Developed an automated market scanner that parses the official NASDAQ ticker list to calculate the **Relative Strength Index (RSI)** for ~3,500 equities.
* Engineered a chunk-based data processing pipeline using `yfinance` to bypass rate limits and optimize the download of historical OHLC data.
* Integrated an automated reporting system via **SMTP/MIMEMultipart** that generates and emails dynamic HTML heatmaps of overbought/oversold signals.
* Implemented defensive programming including environment-based secret management and error-handling for ticker symbol inconsistencies.
* As personal information is included in the source code for this project, I will not be allowing public view for this repository.
* If you still wish to see the code, I can provide an information-free alternative that requires the user to add their own Environment Passwords.

### ETF Quantitative Analysis Dashboard
**Python | Streamlit | Plotly | Pandas | NumPy | Yahoo Finance API**
* Engineered a full-stack financial dashboard evaluating 34 ETFs across 10 quantitative models, including **CAPM**, **Fama-French 3-Factor**, and **MPT Efficient Frontier**.
* Built a high-performance data layer with `yfinance` utilizing **automated caching (TTL: 1hr)** and multi-threaded data fetching to optimize live market data ingestion.
* Developed interactive visualizations using **Plotly** to chart risk-adjusted performance (Sharpe/Sortino), Tracking Error, and liquidity metrics.
* Implemented defensive programming and custom CSS within Streamlit to handle disparate data sources and ensure a responsive, professional UI.
* [View Repository](https://github.com/GoldnShadow/ETF-Dashboard-Python-Streamlit)
* Public website is available at: https://etf-dashboard-stream.streamlit.app/

### S&P 500 Financial Insights Dashboard
**R | tidyverse | Plotly | Flexdashboard | Crosstalk**
* Developed an interactive financial dashboard in **R** to analyze valuation metrics across the S&P 500 using `flexdashboard`.
* Leveraged **Crosstalk** to implement client-side filtering, allowing for real-time synchronization between sector-based filters and dynamic visualizations.
* Engineered comparative data visualizations, including sector-wise **P/E Ratio boxplots** and **EPS vs. Price scatter plots**, to identify market outliers and valuation trends.
* Applied `tidyverse` for rigorous data cleaning and outlier removal to ensure statistical integrity of financial ratios.
* [View Repository](https://github.com/GoldnShadow/S-P500Dashboard)

### HackFax x Patriothacks CTF | Developer & Lead Tester
**JavaScript | Web Security | OSINT | Docker**
* Spearheaded the development of full-stack "Capture the Flag" (CTF) challenges, ranging from entry-level to advanced difficulty, focused on **web-based attack platforms**. 
* Designed and engineered a **complex Joint Webattack/OSINT challenge**, leading a cross-functional team to integrate multiple security disciplines into a single objective. 
* Conducted rigorous testing and troubleshooting of challenge environments to ensure stability and security during high-traffic competitive events. 
* Facilitated live technical walkthroughs and judging for over 100 participants, providing deep-dive explanations of exploit vectors and remediation strategies. 
* [View Event Details](https://github.com/GoldnShadow/) There will be four repositories available for each challenge.

### PERN Stack CRUD API
**Node.js | Express | PostgreSQL | Docker | Joi (Validation)**
* Developed a robust RESTful API using the **PERN stack** (PostgreSQL, Express, React, Node) to manage user data with full Create, Read, Update, and Delete (CRUD) functionality.
* Architected a modular codebase following the **Controller-Service-Model** pattern, ensuring a clean separation of concerns between HTTP logic, business services, and database queries.
* Implemented strict input validation and data integrity using **Joi** and centralized error-handling middleware to improve API reliability and security.
* Engineered a database abstraction layer using `pg` connection pooling and automated table creation scripts to streamline local development and deployment.
* Validated system performance and endpoint reliability using **Postman**, **Docker**, and **Thunder Client** for comprehensive integration testing.
* [View Repository](https://github.com/GoldnShadow/PERN-CRUD-API)

### Automated Portfolio Data Pipeline
**Python | Pandas | yFinance | Logging**
* Engineered a lightweight data retrieval engine to perform periodic time-series sampling of asset prices via the Yahoo Finance API.
* Developed a persistent storage system that automates the aggregation of live market data into a structured CSV format for downstream quantitative analysis.
* Implemented a robust logging architecture to track script telemetry, execution timestamps, and API connection status in real-time.
* Designed the script for continuous deployment, utilizing infinite polling loops and exception-aware logic to maintain high data-collection uptime.
* [View Repository](https://github.com/GoldnShadow/PortfolioVisualization)

### Personal Assistant Agent
**Python | Groq (LLaMA 3.3-70B) | Google Calendar API | Gmail API | Telegram Bot API | OAuth2**
* Built an end-to-end personal assistant agent that parses natural-language requests and creates, reads, and queries Google Calendar events via the Google Calendar API v3.
* Implemented LLM-based intent routing using Groq's LLaMA 3.3-70B with forced function/tool calling to extract structured event data (title, datetime, location) from free-form text.
* Developed a Gmail integration that fetches recent inbox metadata and classifies job-application emails into 7 status categories (interview request, rejection, offer, etc.) using a Groq-powered classification agent.
* Deployed as a Telegram bot with inline confirmation buttons, an auth guard, and full command routing — accessible from any device via the Telegram mobile app.
* *Repository is private due to OAuth credentials and personal API tokens.*

### Squad Chat | Full-Stack Real-Time Chat App
**Node.js | Express | Socket.io | SQLite | JWT | Brevo**
* Engineered a real-time group chat application with a video game in-game chat aesthetic, supporting random room assignment and live messaging via **WebSockets (Socket.io)**.
* Built a secure authentication system with **JWT session management**, bcrypt password hashing, email verification, and password reset flows via Brevo transactional email.
* Architected a lightweight backend using **SQLite (better-sqlite3)** with no external database dependency, keeping the stack fully self-contained and portable.
* Hardened the API with **rate limiting** and HTTP security headers (Helmet) to mitigate abuse and common web vulnerabilities.
* [View Repository](https://github.com/GoldnShadow/squad-chat)

### Chess Notation App
**React | TypeScript | Express | PostgreSQL | Capacitor | chess.js | Tailwind CSS**
* Built a full-stack chess game notation application replicating a physical score sheet, featuring a 99-move grid with real-time **SAN (Standard Algebraic Notation) validation** powered by chess.js — invalid moves are rejected before they can be recorded.
* Engineered a **REST API** with Express and TypeScript, implementing JWT-based authentication, bcrypt password hashing, and zod input validation for all endpoints.
* Designed a PostgreSQL schema storing game metadata and moves as **JSONB**, enabling efficient retrieval and user-scoped game history.
* Deployed as a native **Android mobile app** using Capacitor, wrapping the Vite/React build with a native shell and configuring Android network security for local API communication.
* [View Repository](https://github.com/GoldnShadow/chess-notation-app)

### Medical Reddit Sentiment ETL Pipeline
**Python | PostgreSQL | SQLAlchemy | Prefect | VADER | HuggingFace Transformers | Groq | Streamlit | Plotly**
* Architected a full end-to-end **ETL pipeline** extracting posts from medical Reddit communities (`r/AskDocs`, `r/medicine`, `r/health`) via the Arctic Shift (Pushshift) API — no credentials required.
* Implemented a **dual-model sentiment scoring** system combining rule-based **VADER** scoring with neural inference via HuggingFace's `twitter-roberta-base-sentiment-latest`, enabling direct comparison of classical vs. deep learning approaches on the same data.
* Engineered **idempotent PostgreSQL upserts** via SQLAlchemy, ensuring pipeline reruns update existing records rather than duplicating data.
* Integrated a **Groq LLM insight agent** (`llama-3.3-70b-versatile`) into the Streamlit dashboard that analyzes aggregated sentiment data and surfaces written, data-driven findings — surfacing measurable sentiment gaps between patient and professional communities.
* Orchestrated pipeline execution with **Prefect**, separating extract, transform, and load into discrete tracked tasks.
* [View Repository](https://github.com/GoldnShadow/reddit-sentiment-pipeline)

### DMV Tech Job Market Scraper
**Python | PostgreSQL | SQLAlchemy | Adzuna API | Groq | Streamlit | Plotly**
* Built an **ETL job market intelligence tool** that pulls tech postings across Virginia, Washington DC, and Maryland via the Adzuna Jobs API, covering Software Engineering, Data/ML, AI/MLOps, and Cybersecurity roles.
* Developed a **two-layer requirement extraction system**: keyword matching against an expanded CS skills list (50+ tools and languages) paired with regex-based phrase extraction that pulls specifics like *"3+ years of experience with Kubernetes"* directly from job descriptions.
* Implemented **experience-level classification** (Entry / Mid / Senior) via title and description parsing, with the Streamlit dashboard organized into separate tabs per level — each showing its own requirement frequency chart.
* Integrated a **Groq AI market analysis agent** that aggregates posting data and generates actionable written insights on skill trends, in-demand tools, and recommendations tailored for CS students targeting the DMV market.
* Designed for **on-demand re-runs** — the full pipeline can be re-executed at any time to refresh the dataset with the latest postings.
* [View Repository](https://github.com/GoldnShadow/dmv-job-market-scraper)

## Live Applications
* [**ETF Analytics Dashboard**](https://etf-dashboard-stream.streamlit.app/) – Live quantitative analysis of 34 ETFs.


## Contact Info
I am currently seeking internship opportunities or full-time positions in Software Engineering, Quantitative Analysis, AI/ML Development, Data Engineering/Manipulation, Cybersecurity, or Information Technology.

📫 **Email:** [aditreddya@gmail.com](mailto:aditreddya@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/aditreddy](https://www.linkedin.com/in/adit-reddy-5214672b1/)  
💻 **GitHub:** [github.com/GoldnShadow](https://github.com/GoldnShadow)
