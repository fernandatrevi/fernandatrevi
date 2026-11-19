<div align="center">

# Fernanda Treviño

### Business Intelligence | Commercial & Supply Chain Analytics | Engineering Management

**Data quality → Business KPIs → Forecasting → Better operational decisions.**

[**Featured work ↓**](#featured-projects) &nbsp;·&nbsp; [**Live dashboards ↓**](#live-dashboards) &nbsp;·&nbsp; [**All repositories ↗**](https://github.com/fernandatrevi?tab=repositories)

</div>

---

## About me

I'm an **Engineering Management student** focused on **Business Intelligence, commercial and supply chain analytics**, especially for data-intensive organizations in consumer goods, manufacturing, and distribution.

I work with Python, R, and interactive dashboards to clean and validate datasets, define operational KPIs, compare forecasting approaches, and communicate findings that help teams make decisions. My academic and portfolio projects cover **supplier delivery performance, reproducible data preparation, demand forecasting methodology, and historical trend analysis**.

**Areas I want to contribute to:** commercial performance reporting, data quality, demand planning, inventory and service-level analysis, and process improvement. I have not worked with Sigma's internal systems or datasets; the projects below are independent examples of transferable analytical skills.

## Featured projects

### 01 · Supplier Delivery Performance | Operational BI

**Business question:** How reliably are deliveries completed on time, and how can performance be compared across suppliers and destinations?

- Cleaned and analyzed historical **2006–2015** purchasing/shipment records: **10,324 original product lines** and **7,030 distinct shipment references**.
- Defined shipment-level KPIs after checking duplicates and date consistency. Among **7,020 evaluable shipments, 88.63%** were on time; ten references required date review.
- Built interactive filters by supplier, year, and country, plus CSV exports for reporting.
- **Tools:** `Python` · `pandas` · `Streamlit`

[**Dashboard ↗**](https://panel-proveedores-salud-fernandatrevi.streamlit.app/) · [**Code & methodology ↗**](https://github.com/fernandatrevi/panel-proveedores-salud)

<sub>Transferable to supplier scorecards and service-level monitoring. Historical descriptive results; no causal attribution or claims about current business performance.</sub>

---

### 02 · Data Engineering Process | Reliable Reporting Data

**Business question:** How can inconsistent raw records be transformed into a clean and reusable dataset for analysis?

- Documented a reproducible workflow for missing-value treatment, type correction, text standardization, duplicate review, and feature creation.
- Added quality checks and exports to CSV and Excel for downstream reporting.
- Worked with an anonymized employee-performance dataset; the methodology is transferable, but it was **not** built on retail, sales, or Sigma data.
- **Tools:** `Python` · `pandas` · `NumPy` · `Jupyter`

[**View the data-cleaning workflow ↗**](https://github.com/fernandatrevi/data-engineering-process)

---

### 03 · Demand Forecasting & Capacity Buffer | Planning Methodology

**Business question:** How can weekly demand forecasts and historical forecast errors inform capacity planning?

- Designed an analytical workflow using public Scottish emergency-department activity data, with careful selection and aggregation of weekly observations.
- Documented baseline forecasts, moving averages, exponential smoothing, and evaluation using **MAD, MAPE, RMSE, and forecast bias**.
- Proposed chronological training/validation/test splits and a capacity buffer based on historical errors.
- **Status:** documented project methodology; the README describes planned comparisons and **does not establish validated forecasting results**.
- **Tools:** `Python` · time-series forecasting concepts · KPI design

[**Review forecasting project ↗**](https://github.com/fernandatrevi/pronostico-demanda-urgencias)

<sub>Healthcare demand is the example domain; the forecast-evaluation principles may transfer to commercial demand planning after adaptation and validation.</sub>

---

### 04 · Mexico Healthcare Access | Interactive Business Reporting Skills

**Business question:** How do population-weighted and percentage-based indicators change the interpretation of geographic trends?

- Compared official INEGI estimates for **32 Mexican states** across **2016, 2018, 2020, 2022, and 2024**.
- Developed interactive comparisons, historical trends, national benchmarks, and downloadable reports.
- Documented limitations to distinguish observed changes from causal explanations.
- **Tools:** `R` · `Shiny` · `Plotly` · `readxl`

[**Interactive dashboard ↗**](https://fernandatrevi.shinyapps.io/mexico-healthcare-access/) · [**Methodology ↗**](https://github.com/fernandatrevi/mexico-healthcare-access-analysis)

<sub>Public-health subject matter, transferable dashboard and metric-communication skills. Descriptive analysis only.</sub>

---

## Additional software & quantitative projects

**AI Investment Portfolio Optimizer** — Historical portfolio-risk comparisons, minimum-variance optimization, drawdowns, and chronological holdout analysis. [Live app](https://ai-investment-portfolio-optimizer-tsjajqgwafh9vj3tavxaoj.streamlit.app/) · [Source](https://github.com/fernandatrevi/ai-investment-portfolio-optimizer). Educational analysis, not investment advice.

**Vínculo** — Experimental full-stack nonprofit-management prototype with organization directory, account workflows, and permission-controlled manual donor records. [Portfolio](https://fernandatrevi.github.io/vinculo-portfolio/) · [Demo](https://vinculo-donantes-1.onrender.com/). Fictional data; no payment processing or production donor records.

## Live dashboards

| Project | Focus | Open |
|:--|:--|:--|
| **Healthcare Supplier Performance** | Supplier scorecards and on-time delivery KPIs | [Dashboard ↗](https://panel-proveedores-salud-fernandatrevi.streamlit.app/) |
| **Mexico Healthcare Access** | Interactive BI-style geographic and trend reporting | [Shiny app ↗](https://fernandatrevi.shinyapps.io/mexico-healthcare-access/) |
| **AI Investment Portfolio Optimizer** | Portfolio risk and allocation analysis | [Dashboard ↗](https://ai-investment-portfolio-optimizer-tsjajqgwafh9vj3tavxaoj.streamlit.app/) |
| **FormAI Live** | Experimental video-based exercise feedback | [Demo ↗](https://formai-live.onrender.com/) |
| **Vínculo** | Nonprofit management prototype | [Demo ↗](https://vinculo-donantes-1.onrender.com/) |
| **BrainScan AI** | Educational medical-imaging analytics interface (synthetic data) | [Web app ↗](https://brainscan-ai-one.vercel.app/) |
| **Wall Street Web Crawler** | SEC filing and PDF text search | [App ↗](https://wall-street-web-crawler-h2lubtjvapebqhgglspbg8.streamlit.app/) |
| **StudyPilot AI** | PDF study tools and quizzes; local Ollama tutor not verified online | [Web app ↗](https://studypilotai.streamlit.app/) |

<sub>Third-party hosted demos may be unavailable or take time to initialize. A link is not a claim of production readiness or independently verified uptime.</sub>

## Additional projects

- **[FormAI](https://github.com/fernandatrevi/formai-portfolio)** — browser-based video analysis using pretrained pose estimation; [portfolio](https://fernandatrevi.github.io/formai-portfolio/).
- **[Wall Street Web Crawler](https://github.com/fernandatrevi/wall-street-web-crawler)** — financial filing and PDF term search; [live demo](https://wall-street-web-crawler-h2lubtjvapebqhgglspbg8.streamlit.app/).
- **[StudyPilot AI](https://github.com/fernandatrevi/studypilot-ai)** — document-based study assistant with quizzes and locally configured tutoring; [web demo](https://studypilotai.streamlit.app/). The Ollama tutor is not verified in the hosted version.
- **[BrainScan AI](https://github.com/fernandatrevi/brainscan-ai)** — educational medical-imaging interface with simulated results; [web demo](https://brainscan-ai-one.vercel.app/). Not a diagnostic tool.
- **[AnimeMatch AI](https://github.com/fernandatrevi/animematch-ai)** — content-based recommendation prototype; [demo](https://animematch.onrender.com/).

## Technical toolkit

| Business capability | Demonstrated tools and methods |
|:--|:--|
| **Business intelligence & reporting** | Python, R, pandas, Plotly, Streamlit, Shiny, dashboard filters, KPI definition, CSV exports |
| **Data preparation & validation** | Missing-value treatment, duplicate analysis, data-type correction, standardization, reproducible data-cleaning workflows |
| **Supply chain & planning analytics** | Supplier delivery KPIs, service-level measurement, demand forecasting methodology, MAD, MAPE, RMSE, forecast bias |
| **Additional engineering** | SciPy optimization, scikit-learn, SQL concepts, PostgreSQL, React, TypeScript, FastAPI, Git/GitHub |

<sub>Power BI, enterprise ERP systems, and live consumer-goods datasets are not presented as proven professional experience in this portfolio.</sub>

## How I work

**Problem framing → Data validation → Model / KPI design → Interactive delivery → Critical interpretation**

I prioritize clear metric definitions, reproducible calculations, documented assumptions, and honest reporting of prototype limitations.

---

<div align="center">

### Open to internships and early-career roles in Business Intelligence, Commercial Analytics, Demand Planning, and Supply Chain Analytics.

[**Browse my projects ↗**](https://github.com/fernandatrevi?tab=repositories)

<sub>Portfolio by Fernanda Treviño · Selected academic and experimental projects.</sub>

</div>

---

## Contribution activity

<div align="center">

<img src="https://raw.githubusercontent.com/fernandatrevi/fernandatrevi/output/contributions-count.svg" alt="Contributions in the last year, updated automatically" width="100%" />

<sub>Annual contribution total and snake are refreshed daily through GitHub Actions.</sub>

<!-- Generated daily by Platane/snk; the animation uses GitHub's contribution graph,
     without publishing source code from private repositories. -->
<img src="https://raw.githubusercontent.com/fernandatrevi/fernandatrevi/output/github-contribution-grid-snake.svg" alt="Animated blue snake eating contribution squares on a light-blue GitHub contributions grid" width="100%" />

<sub>Blue contribution snake · Daily automatic updates</sub>

</div>
