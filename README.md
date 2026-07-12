I build software where regulation meets data — turning environmental standards, financial rules and policy targets into testable, working systems.

Environmental engineer (10 years in wind energy & licensing, Brazil/France) turned founder-engineer. Based near Copenhagen 🇩🇰 · FR/PT native, EN professional.

🌬️ Energy & simulation — my home turf

[WindSound](https://www.windsound.app/) — SaaS platform for wind-farm acoustic compliance modelling. ISO 9613-2, IEC 61400-11-2 and ABNT NBR 10151 implemented as testable code; Monte Carlo uncertainty analysis (P50–P99) running in-browser via Web Workers; automated regulatory PDF reports. Demonstrated to major wind developers in Brazil.

[WFIV Operational Patterns from Public AIS Data](https://github.com/thiagolefebure/wfiv-installation-windows) — reconstructing the installation rhythm of a wind farm installation vessel (Wind Mover, Baltic Power OWF) from open Danish Maritime Authority AIS data: ~16h median per turbine position, port shuttle cycles, operational-state detection. An exercise in how far public data goes in explaining offshore logistics — limitations declared upfront.

[SEAFAIRER value-chain optimizer](https://github.com/thiagolefebure/seafairer-value-chain) — MILP optimisation of maritime biofuel supply chains (PuLP/CBC), Monte Carlo P10/P50/P90, ISO 14040 life-cycle GHG accounting, FuelEU compliance checks. React dashboard.

[Brazil Labor Transition Simulator](https://reforma-6x1-simulator.streamlit.app/) — probabilistic policy simulator (up to 50k Monte Carlo runs) for Brazil's 6×1 workweek reform, calibrated live against IBGE/PNAD and CAGED APIs. Streamlit.


🤖 AI / LLM systems

[AI Document Intelligence Engine](https://github.com/thiagolefebure/ai-document-intelligence-engine) — production-oriented FastAPI RAG service (LangChain/LangGraph, OpenAI, Dockerized). Beyond the chatbot demo: evidence-based answers with per-page citations, source deduplication, coverage scoring as an explainability signal, Markdown/PDF export endpoints.


📊 Data engineering & quality

[EU Waste Data Reporting Pipeline](https://github.com/thiagolefebure/eu-waste-data-pipeline) — CI-tested, config-driven data platform mirroring how the EEA tracks circular-economy progress: Eurostat API ingestion, Reportnet-style QA engine (severity model: completeness, consistency, plausibility), WFD distance-to-target indicators, SQLite star-schema warehouse with lineage.

[Credit Risk Simulation](https://github.com/thiagolefebure/credit-risk-simulation) — end-to-end PD/LGD/EAD pipeline with expected-loss computation, macro stress scenarios and a data-quality framework (BCBS 239-minded).


🌍 ESG & climate tooling


[Climate Stress Test Simulator](https://github.com/thiagolefebure/climate-stress-test) — NGFS scenarios on financial portfolios (transition & physical risk, stranded assets), aligned with ECB/EBA/TCFD guidance. React 19.

[Scope 3 GHG Dashboard](https://scope3-ghg-dashboard.vercel.app/) · [ESG Due Diligence Dashboard](https://esg-supply-chain-dashboard.vercel.app/) — supply-chain emissions and OECD 6-step due-diligence tooling (CSRD/CSDDD-aware).



Stack: Python (pandas, FastAPI, PuLP) · SQL · React/Vite · LangChain · Docker · GitHub Actions CI

The pattern across everything here: take a regulation or standard, turn it into an explicit computational specification, wrap it in QA, and ship it as a product someone can actually use.

📫 thiago.lefebure@gmail.com · [LinkedIn](https://www.linkedin.com/in/thiago-lefebure-m-sc-818a14b2/?locale=en-US)
