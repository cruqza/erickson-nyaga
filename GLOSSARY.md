# Portfolio Glossary

This glossary records the vocabulary accepted for this portfolio. It is the
shared language between a recruiter, a hiring manager and the code in this
repository. It is **vocabulary only** — no implementation detail, no architecture
decisions, no internal tooling.

Terminology is captured inline as it is resolved, never batched.

## Discipline

- **End-to-end** — every project runs from raw data in to a verified answer out,
  with no hand-waving between steps.
- **Verified answer** — a result whose claims are guarded by the repo's own
  tests/metrics, not the recruiter's word.
- **Persona** — the professional hat a project wears: Analytics, Machine
  Learning, or Data Engineering & Pipelines. People wear all three.
- **Flagship** — the single project used to signal a discipline first.
- **Pipeline** — a repeatable flow that moves data from one state to another
  (collect → clean → model/shape → report), usually with a documented diagram.

## Skills referenced in this portfolio

- **Python** — the shared language across the analytics and ML projects.
- **SQL** — the language of the pipeline projects (staging, cleaning, joins).
- **Power BI** — the dashboarding layer used in the analytics and pipeline work.
- **scikit-learn / pandas** — the ML + data-work tools behind the churn and
  analytics projects.
- **PostgreSQL** — the database behind the Haraka Rides pipeline.
- **Streamlit** — the interactive scoring app used to demo the churn model.
- **Git / Docker** — version control and reproducible environments.

## Personas

| Persona | Business problem | Proof |
|---|---|---|
| Data Analytics & Business Insights | Answering a CEO's questions with the data | Safari Travels, Tembo-Hotel-Data-Analysis |
| Machine Learning & Data Science | Predicting and explaining churn | Telco Customer Churn, Churn Demo |
| Data Engineering & Pipelines | Clean, reproducible data movement | Haraka Rides, Sales-Analytics |
