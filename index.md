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
* [View Repository]: As personal information is included in the source code for this project, I will not be allowing public view for this repository.
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
* [cite_start]Spearheaded the development of full-stack "Capture the Flag" (CTF) challenges, ranging from entry-level to advanced difficulty, focused on **web-based attack platforms**. 
* [cite_start]Designed and engineered a **complex Joint Webattack/OSINT challenge**, leading a cross-functional team to integrate multiple security disciplines into a single objective. 
* [cite_start]Conducted rigorous testing and troubleshooting of challenge environments to ensure stability and security during high-traffic competitive events. 
* [cite_start]Facilitated live technical walkthroughs and judging for over 100 participants, providing deep-dive explanations of exploit vectors and remediation strategies. 
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

## Live Applications
* [**ETF Analytics Dashboard**](https://etf-dashboard-stream.streamlit.app/) – Live quantitative analysis of 34 ETFs.


## Contact Info
I am currently seeking internship opportunities or full-time positions in Software Engineering, Quantitative Analysis, AI/ML Development, Data Engineering/Manipulation, Cybersecurity, Information Technology, 

📫 **Email:** [aditreddya@gmail.com](mailto:aditreddya@gmail.com)  
🔗 **LinkedIn:** [linkedin.com/in/aditreddy](https://www.linkedin.com/in/adit-reddy-5214672b1/)  
💻 **GitHub:** [github.com/GoldnShadow](https://github.com/GoldnShadow)
