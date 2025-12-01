# Hi, I'm Aaron 👋
### Revenue Operations Leader & Full-Stack Developer

I specialize in bridging the gap between **Sales Strategy** and **Engineering**. I build the internal tools, API integrations, and data pipelines that power high-growth revenue teams.

---

### 🔒 Why are my contributions private?
Most of my recent work involves proprietary **commercial source code** for *The Sales Factory* and *Pitchpilot*, which resides in private organization repositories. 

While I can't share the code, I can share **what I build:**

## 🛠️ Technical Architecture & Projects

### 1. Enterprise Revenue Infrastructure - The Sales Factory
*Role: Head of Data & Technology Operations*

I architected a centralized data engine to replace manual reporting. This system synchronizes data between our CRM stack, Airtable, and our internal warehouse to provide real-time visibility for 80+ reps.

**The Stack:** `Python` • `Airtable` • `PostgreSQL` • `R Shiny` • `HubSpot API`

```mermaid
graph LR
    A[HubSpot/Outreach APIs] -->|Python ETL Scripts| B(PostgreSQL Warehouse);
    B -->|SQL Queries| C{R Shiny Apps};
    C -->|Write-Back Updates| A;
    C -->|Real-Time Dashboards| D[Executive Reporting];
```

```mermaid
graph LR
    A[HubSpot/Outreach APIs] <-->|Python 2-Way Sync| B(Airtable Base);
    B -->|Archival Scripts| C[(PostgreSQL Warehouse)];
    C -->|SQL Queries| D{R Shiny Apps};
    D -->|User Actions| B;
```

**API Integrations:** Built custom connectors to fetch call logs and deal stages from HubSpot & Outreach, bypassing native limitations.  
**Persistent State:** Developed R Shiny apps with write-back capabilities, allowing managers to edit database records directly from the dashboard.  
**Automation:** Automated reporting workflows to save 10+ managers over 5 hours per week each.  

### 2. SaaS Product Development - [Pitchpilot](https://www.pitchpilot.com/)
*Role: Co-Founder & Head of Engineering*

Co-developed an AI-driven GTM messaging platform from zero-to-one.
* **Full Stack:** Built the backend with **Flask (Python)** and frontend with **Vue.js**.
* **DevOps:** Managed CI/CD via **GitKraken** and GitHub PR workflows.
* **Database:** Designed the normalized schema in **PostgreSQL** to handle user authentication and data storage.

### 3. Open Source Research Tools
* **[easypower](https://cran.r-project.org/package=easypower):** I developed and published this R package on CRAN to make statistical power analysis more accessible for behavioral researchers.

---

## 💻 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat&logo=vuedotjs&logoColor=4FC08D)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white)

---

### 📫 Connect
* **LinkedIn:** [Connect with me!](https://www.linkedin.com/in/aaron-mcgarvey93/)
* **RPubs:** [R Examples](https://rpubs.com/McGarveyA)
