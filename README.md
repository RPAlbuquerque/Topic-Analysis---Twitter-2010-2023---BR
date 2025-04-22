# Topic Analysis — Twitter 2010–2023 (Brazil)
#Mapping Cultural Mood in Digital Discourse: A Longitudinal Topic Analysis of 10 Years of Brazilian Tweets

This repository contains the full pipeline and documentation for the paper:

**"Mapping Cultural Mood in Digital Discourse: A Longitudinal Topic Analysis of 10 Years of Brazilian Tweets"**

### 🧠 Abstract
We analyze over 10 billion geotagged tweets from Brazil (2013–2023) to uncover macro-level cultural mood structures using BERT embeddings, unsupervised clustering, and LLaMA-based topic labeling. The study reveals how public sentiment is structured and evolves in response to major events such as elections and the COVID-19 pandemic.

### 📁 Structure

- `data/` – Dataset descriptions (no raw data due to institutional restrictions)
- `notebooks/` – Jupyter notebooks used in the full modeling pipeline
- `scripts/` – Modular Python scripts for embedding, clustering, and labeling
- `results/` – CSV outputs of trends, macrothemes, and visual summaries
- `paper/` – Paper draft and publication materials
- `figures/` – Plots and visualizations for the manuscript
- `utils/` – Helper functions for pre-processing and visual analytics

### 🛠️ Key Components
- Semantic modeling with BERT
- KMeans clustering of over 5.7 million tweet embeddings
- LLaMA zero-shot labeling for interpretability
- Temporal trend analysis (116 months)
- Cultural mood structures and event-based shifts




---
## ✍️ Authors

- **Rafael Albuquerque** — PPGA/UFRGS & Harvard University Fellow - Center for Geographic Analysis
- **Devika Kakkar** - Harvard University - Center for Geographic Analysis
- **Vinícius Brei** — PPGA/UFRGS & MIT Media Lab Fellow
  
> For contact: rafaelpereiraalbuquerque@fas.harvard.edu

---

## 🎁 Acknowledgments

Special thanks to the Harvard CGA for access to the *Geotweet Archive v2.0*  
and to the broader research team who helped refine this project.
