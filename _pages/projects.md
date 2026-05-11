---
title: "Projects"
layout: single
permalink: /projects/
---

## 🏆 Flagship Project

### SOC Anomaly Detection System
> Built after 6 months as a SOC Analyst + completing the Cybershujaa Data & AI Programme

Working in a SOC, I saw first-hand how much analyst time was consumed reviewing thousands of SIEM log lines manually. I first automated report generation with a Graylog API script, then used that data foundation to build an unsupervised ML model that flags anomalies automatically.

**What it does:**
- Uses **Isolation Forest** to detect anomalous patterns in server-generated SIEM logs
- Applies feature engineering to extract meaningful signals from high-volume raw log data
- Flags suspicious activity in real time with minimal false positives, reducing manual analyst workload

**Stack:** Python · Scikit-learn · Isolation Forest · Feature Engineering  
🔗 [GitHub Repository](https://github.com/KipkosgeiSang22/SOC_Monitor.git)

---

## Other Projects

### Graylog Report Automation
The precursor to the anomaly detection system. A Python script that asynchronously fetches, sanitises, correlates, and exports log data from multiple clients via Graylog's REST API. Designed for SOC reporting and operational efficiency. *(Executable script — not a web app.)*  
🔗 [GitHub Repository](https://github.com/KipkosgeiSang22/Graylog-Report-Automation.git)

---

### SIEM Input Health Checks
Automated verification of SIEM inputs using Python and the Graylog API — ensures log pipeline integrity before analysis.  
🔗 [GitHub Repository](https://github.com/KipkosgeiSang22/Automated-Graylog-input-health-check.git)

---

### Power BI SOC Dashboard
Visualised SIEM log data and incident trends using Power BI Desktop. Part of the Cybershujaa programme.  
📎 [View Dashboard](https://drive.google.com/file/d/1F6EnuJYH0ZWnb5Y8nXYDPPmkYKubEyzU/view?pli=1)

---

### Fashionhouse254
Full-stack e-commerce web application built with Django and Tailwind CSS. Dynamic product listings with efficient data handling.  
🔗 [GitHub Repository](https://github.com/KipkosgeiSang22/Fashionhouse254.git)

---

*See the [Data & AI Portfolio](/data-ai/) for all Cybershujaa programme assignments.*
