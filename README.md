# Praharshitha Kota (Krishna Praharshitha Devi K)

I'm looking for product analyst, business analyst and product roles in healthcare.

I trained as a perfusion technologist and spent over a year in the cardiac operating theatres of KIMS Sunshine and KIMS Hospitals. Then I joined KareXpert Technologies as a product intern and looked at the other side: their hospital information system's registration/ADT, EMR and billing modules, and where automation could take work off staff. I'm now doing a PGDM in AI and Data Science in Healthcare at IIHMR Bangalore.

So I can sit with a clinician, see what slows them down, and write it up in a way a product or data team can use.

## Products I've built and designed

| Product | The problem and what I made | Built with |
|---|---|---|
| [WholePerf](https://github.com/praharshitha-ai/wholeperf) | Perfusion teams repeat the same calculations and record-keeping for every case. I built one app for that work, based on my own time in cardiac theatres: BSA, blood flow, heparin and cannula calculators, per-patient procedure logs and a disposables inventory. Firestore rules keep each clinician's records private. [Live demo](https://wholeperf.netlify.app) | React, TypeScript, Firebase |
| [PRANA](https://v0-prana-healthcare-app-inky.vercel.app/) | Panchakarma therapy runs over many days and several practitioners, which makes it easy to lose track of a patient's plan. I designed a care-coordination app with therapy tracking, treatment plans, patient reminders and separate dashboards for each role. | Product design, prototype |
| [Future-U](https://future-u-chalo-upgrade.netlify.app) | A student career-guidance site. I reworked its user flows and responsive layout and helped with testing and deployment. | UI/UX, web |
| [Sentiment analysis dashboard](https://github.com/praharshitha-ai/Sentiment-Analysis) | A tool for a non-technical user to check the tone of reviews: type text or upload a CSV and get positive, neutral or negative labels. Compares Naive Bayes, logistic regression and SVM on TF-IDF features. [Demo video](https://youtu.be/Zb4HXzh-gXI) | Python, scikit-learn, Streamlit |

Two more concepts are written up on my [portfolio](https://prahashitha-portfolio.netlify.app): SAARTHI, for managing MBBS interns posted to rural health centres, and Echo Lens, an AI-assisted workflow for echocardiogram reports.

## Analysis

| Project | Question, finding and takeaway | Built with |
|---|---|---|
| [IDSP disease surveillance (Telemedicon 2026)](https://github.com/praharshitha-ai/idsp-disease-surveillance) | Can India's outbreak surveillance data be forecast well enough to plan with? Abstract with Renuka Prasanthi Dandi on 44,952 IDSP records. Median forecast error rose from 77% nationally to 105% at district level, and a simple linear trend was never beaten by Prophet or SARIMA. Takeaway: at district level, forecasts alone shouldn't drive stocking or staffing. Includes a React and D3 dashboard of 16 diseases. | Python, Prophet, React, D3 |
| [Heart attack risk dashboard](https://github.com/praharshitha-ai/heart-attack-risk-tableau) | Which patients should a prevention programme target? Across 8,763 patients the risk rate stays near 36% for every group (smokers, diabetics, over-60s), with no significant differences. Takeaway: check that an outcome relates to anything before building dashboards on it. 18 worksheets, 2 dashboards and a story. | Tableau |
| [Chlorhexidine trial: survival analysis](https://github.com/praharshitha-ai/chlorhexidine-vap-survival-analysis) | Does chlorhexidine delay ventilator-associated pneumonia? 103 patients and 8 events, analysed with Kaplan-Meier curves, a log-rank test (p = 0.20) and a Cox model adjusted for age, APACHE II score and gender. Takeaway: too few events to tell the arms apart; a firm answer needs a larger trial. | Python, pandas, lifelines |
| [Crypto trader behaviour vs market sentiment](https://github.com/praharshitha-ai/crypto-trader-sentiment-analysis) | Do traders size positions differently in fear and greed phases? Joins a fear/greed index with trade records to compare position size and profit by phase. | Python, pandas, seaborn |

## Engineering

| Project | What it does | Built with |
|---|---|---|
| [FastAPI CI/CD pipeline](https://github.com/praharshitha-ai/fastapi-cicd-render) | A prediction API whose tests run in GitHub Actions on every push and, when they pass, trigger a deploy to Render. | FastAPI, pytest, GitHub Actions, Render |
| [Employee attrition (in progress)](https://github.com/praharshitha-ai/employee-attrition-mlops-system) | Random Forest pipeline on HR data with a Streamlit front end, a FastAPI service and CI. | scikit-learn, FastAPI, Docker |

## Tools

- **Analysis:** SQL and PostgreSQL, Excel, Power BI, Tableau, Python (pandas, scikit-learn, lifelines), R
- **Product and design:** Figma, UX research, prototyping
- **Engineering:** React, Firebase, Streamlit, FastAPI, Docker, GitHub Actions

## Background

- **Product intern, KareXpert Technologies** (2026). Studied the scope for AI-driven automation in the ADT, EMR and billing/RCM modules of their HIS and wrote up the findings.
- **Perfusion trainee in cardiac surgery**, KIMS Hospitals and KIMS Sunshine Hospitals (2023 to 2025)
- **Research:** [abstract](https://github.com/praharshitha-ai/idsp-disease-surveillance) with Renuka Prasanthi Dandi on how forecastable India's IDSP surveillance data is (44,952 outbreak records, 2009 to 2026), submitted to Telemedicon 2026
- **Education:** PGDM, AI and Data Science in Healthcare, IIHMR Bangalore (2025 to 2027) · Bachelor of Perfusion Technology
- **Certifications:** AI Product Manager (Simplilearn, 2026) · Power BI Data Modelling (Simplilearn, 2025) · Product Management and Data Analytics job simulations (Forage, Deloitte, 2026) · AI for Management (NPTEL, IIT Madras, 2026)

## Contact

kotapraharshitha@gmail.com · [LinkedIn](https://www.linkedin.com/in/praharshithakota-ai-datascience/) · [Portfolio](https://prahashitha-portfolio.netlify.app) · [Resume (PDF)](https://prahashitha-portfolio.netlify.app/Krishna_Praharshitha_Devi_K_Resume.pdf)
