# Adit Reddy
📍 Stone Ridge, VA | 📧 [aditreddya@gmail.com](mailto:aditreddya@gmail.com) | 📞 (571) 444-3144
[LinkedIn](https://www.linkedin.com/in/adit-reddy-5214672b1) | [GitHub](https://github.com/GoldnShadow) | [Download PDF Resume](./Adit-Reddy_Resume_Final-Draft.pdf)

## Education
**George Mason University** | Fairfax, Virginia
*B.S. in Computer Science* | Expected May 2027
* **Relevant Coursework:** Data Structures, Object-Oriented Programming (Java), C & Unix, Python, Statistics for Engineers, MySQL/SQL, and Data Sciences (R).

## Technical Skills
* **Languages:** Python (Pandas, NumPy, yFinance), Java, C, R (Plotly), SQL (PostgreSQL, MySQL), JavaScript (Node.js, React), Brightscript.
* **Tools & Platforms:** Docker, AWS (CodeBuild/Deploy), Git, VMWare, VSCode, PyCharm.
* **Testing & Workflow:** Postman, JUnit, Thunder Client, JIRA, Shell Scripting, Agile Methodologies.

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

