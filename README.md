# Hi, I'm Oscar

Final-year Data Science and Analytics student at the University of Westminster (graduating June 2027). I design, build and deploy projects end to end: LLM-powered interfaces, multi-agent systems and RAG pipelines on live government data. I am looking for graduate roles starting in 2027.

- 1 of 28 selected across EMEA (from 180+ applicants) for the SharkNinja JailbreakEDU AI Hackathon. I led the technical build.
- Finalist at the first AI hackathon held in the UK Parliament (EasyA x House of Lords), from 1,000+ applicants.
- 2nd place at the TRL Autumn School Hackathon (Data Science, AI & Modelling for Air Transport).
- 3rd place at AWS GameDay: Agentic AI, AWS Summit London.
- Founder and president of the University of Westminster Data Science & AI Society, and course representative for my programme.

## Projects

- **[Flight Route Characterisation](https://github.com/3nd03/flight-route-characterisation):** Supervised research project for EUROCONTROL's Mercury model, presented at the Students as Co-Creators workshop at Westminster. Three-layer hierarchical KMeans on binary FIR route signatures across 639,192 flights and 7,345 origin-destination pairs. A deterministic cost model built from CRCO and Nav Canada rate tables gives per-cluster error bounds (p5/p95), with a modified z-score outlier audit. Sub-4% MAE on held-out validation for the EGLL-LGAV route pair.
- **[Trazer: Commitment Ledger](https://github.com/3nd03/trazer-commitment-ledger):** Built with a team at the EasyA x UK Parliament Hackathon, where I built the technical product (backend, frontend, data ingestion and verification pipeline). It ingests live Hansard debates and Written Answers, uses an LLM to extract verifiable ministerial commitments, then retrieves follow-up evidence (embeddings plus LLM judgement) and labels each one fulfilled, in progress or no evidence found, with a source link. Mid-build I found the Written Answers API was silently truncating 97% of responses to a 258-character preview. I fixed it and re-verified every result manually. In development.
- **[Careerly](https://github.com/3nd03/Careerly-Employment_App):** AI career platform for unemployed jobseekers (skill gap analysis, CV review, cover letters, role suggestions, LinkedIn outreach, interview prep). Built as a Streamlit prototype in one day at the Cloud Crew x Morgan Stanley hackathon, then extended as sole developer into a FastAPI and React stack on AWS RDS Postgres and S3. Includes a 116-test pytest suite with GitHub Actions CI, structured logging on all API calls and database writes, and a heuristic evaluation against Nielsen's 10 principles (10 findings, 5 major ones shipped). In development.
- **[World Cup 2026 Match Predictor](https://github.com/3nd03/World-Cup-2026-Predictions):** XGBoost Poisson regressors for goals scored, a custom ELO rating system written from scratch, and 10,000 Monte Carlo tournament simulations. Deployed as a Streamlit app.
- **[NL-to-SQL Football Analytics Tool](https://github.com/3nd03/NL-to-SQL-football-query-tool):** Turns natural language questions into SQL over 25,000+ matches across 11 leagues. Built with FastAPI, Streamlit and the Anthropic API.
- **[Lucid AI Agent](https://github.com/3nd03/Lucid_AI_Agent):** Multi-agent pipeline built for the Google & Kaggle AI Agents Intensive capstone. Agents profile a dataset, decide whether it needs cleaning, train and compare logistic regression and random forest, pick the better model and explain its predictions with SHAP. Built with Google ADK (SequentialAgent), a custom MCP server and Streamlit.
- **[UK Flight Forecast (ARIMA)](https://github.com/3nd03/UK-Flight-Prediction--ARIMA-):** Team project that won 2nd place at the TRL Autumn School Hackathon. ARIMA time-series model predicting daily flight arrivals into UK airports from September 2023 London traffic data.

## Stack

**Languages and libraries:** Python (pandas, NumPy, scikit-learn, XGBoost, SHAP, Matplotlib), SQL
**Tools:** FastAPI, Streamlit, Power BI, Git, pytest, GitHub Actions, Google ADK, MCP, AWS (S3, RDS), Anthropic API
**Areas:** machine learning, agentic AI, RAG, statistical modelling, data visualisation, NLP, process mining

## Reach me

[LinkedIn](https://www.linkedin.com/in/oscar-denche)
