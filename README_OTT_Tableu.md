# OTT Viewer Drop‑off & Retention Dashboard (Tableau)

This repo documents a Tableau dashboard built on an OTT content‑level dataset to analyze **viewer drop‑off, completion, and retention risk** across shows, seasons, and episodes. It contains **episode‑level features** such as content attributes, engagement scores, and retention risk (no user‑level data).
## Daset Used
Kaggle Dataset: https://www.kaggle.com/datasets/eklavya16/ott-viewer-drop-off-and-retention-risk-dataset
## Dashboard 
https://github.com/karthic180/tableau_dashboards/blob/main/OTT_Dashboard_Tableau.pdf

# Dataset Schema
The core columns in the dataset:

- **show_id:** Unique ID per show
- **title:** Show or episode title
- **platform:** Streaming platform
- **genre:** Content genre
- **release_year:** Year of release
- **season_number:** Season number
- **episode_number:** Episode number
- **episode_duration_min:** Duration of episode in minutes

- **pacing_score:** Numeric score for pacing
- **hook_strength:** Strength of the opening / hook
- **dialogue_density:** Amount of dialogue
- **visual_intensity:** Visual richness / action level

- **avg_watch_percentage:** Average percentage of episode watched
- **pause_count:** Number of pauses
- **rewind_count:** Number of rewinds
- **skip_intro:** Whether intro is skipped (count/flag)

- **cognitive_load:** How demanding the content is
- **attention_required:** How much attention it needs
- **night_watch_safe:** Whether suitable for late‑night watching

- **drop_off:** Drop‑off rate (percentage)
- **drop_off_probability:** Probability of drop‑off (0–1 or %)
- **retention_risk:** Risk score for retention
- **dataset_version:** Version of the underlying dataset

> Note: This dataset is **episode/content‑level** only (no user_id/session_id), so all KPIs and charts are built around **content performance**, not viewer counts.

---
