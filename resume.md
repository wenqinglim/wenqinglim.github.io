---
title: Resume
aside: false
---

{% include button.html text="View PDF" link="/assets/wenqinglim_resume.pdf" %}

## Summary

Machine Learning Engineer with 7+ years shipping production ML systems across FinTech, AdTech, FoodTech, and HR Tech, plus an MSc (Distinction) in Sound and Music Computing with published research on hierarchical VAE/GNN music generation. Skilled in fine-tuning LLMs and embedding models, LLM evaluation, audio signal processing, and production-first engineering (CI/CD, Docker, MLOps). Focused on building reliable, observable AI systems from research through to production.

## Skills

- **Machine Learning & AI:** LLMs & NLP (PyTorch, HuggingFace, LangChain), LLM evaluation, Embedding Models, Audio AI & Music Computing
- **MLOps & Infrastructure:** AWS (Bedrock, SageMaker), GCP, Snowflake, Docker, Airflow, MLFlow, CI/CD
- **Production ML Systems:** Model serving, monitoring, evaluation pipelines
- **Leadership:** Cross-functional collaboration, mentorship, technical strategy
- **Languages:** English (Fluent), Chinese (Conversational)

## Work History

### Machine Learning Engineer — Personio, London, UK
*Apr 2026 – Present · Python, AWS Bedrock, Snowflake, Hex, Kotlin*

- Built a structured evaluation pipeline for an LLM-powered HR Assistant used by thousands of employees, including a failure taxonomy and an LLM-as-judge model tuned on manually annotated data.
- Led the annotation effort to create ground-truth data, directly improving judge model accuracy and reliability.
- Drove team-wide adoption of "failure rate" as the core reliability metric, shaping sprint prioritisation based on judge outputs.
- Productionising a daily-run judge pipeline (AWS Bedrock, Snowflake, Hex) for continuous model performance monitoring.

### Lead Data Scientist (Founding-stage Research) — Octavate, London, UK
*2025 – Present · Part-time*

- Lead a team of ML researchers building models to predict breakout artists from quantitative and qualitative signals.
- Architected the ML research framework for artist success prediction, and own the research roadmap and technical mentorship.

### Python Developer & Data Scientist — SilentEight, Singapore / UK
*Apr 2023 – Apr 2026 · Python, PySpark, CI/CD, Docker, AWS SageMaker, PyTorch, LangChain*

- Drove adoption of LLM-based entity matching, improving recall by 44% through synthetic data generation and fine-tuning.
- Optimised PySpark pipelines, cutting processing runtime by 70% and enabling large-scale batch inference.
- Delivered 2 greenfield client integrations (REST APIs, ETL pipelines, Docker packaging) under tight deadlines.
- Built explainable ML for entity matching using clustering and visual similarity models.

### Data Scientist — Twitter, Singapore
*May 2022 – Jan 2023 · SQL, Python, Vertica, Google BigQuery, Looker*

- Led a cross-functional initiative with Engineering to build Sales tools, saving 50,000 hours annually.
- Standardised Ads Performance metrics and data quality frameworks across Sales teams.

### Machine Learning Engineer — foodpanda, Singapore
*Jan 2021 – May 2022 · Python, SQL, Airflow, GCP, Docker, MLFlow*

- Architected an entity matching system in production across 9 countries and 4 languages, powering competitive intelligence and price governance.
- Designed a human-in-the-loop feedback framework adopted as the standard for model improvement; mentored 3 junior MLEs on system design and production best practices.
- Built a cuisine classification system cutting labelling time by 1 week per 1,000 tags, via NLP experimentation (W2V, TF-IDF, zero-shot) and A/B testing ([Article](https://link.medium.com/wMyddn8Paxb)).

### Data Scientist — UCARE.AI, Singapore
*Dec 2018 – Jan 2021 · Python, PySpark, SQL, Airflow, Docker, MLFlow*

- Built an internal ML platform (Docker, MLFlow), reducing project setup time by 2–3 days per data scientist.
- Improved hospital bill prediction MAPE by 33% through feature engineering and boosted-tree modelling (XGBoost, LightGBM).

## Education

- **Queen Mary University of London** — MSc Sound and Music Computing, AI and Music Data Science Stream (Distinction), 2023–2024
- **National University of Singapore** — BSc Business Analytics (Second Upper Honours); NUS Overseas Colleges Silicon Valley Program, 2015–2019
- **Stanford University, SCPD** — Management Science and Engineering coursework, 2018–2019

## Projects

### Audio AI & Music Generation Research

**MSc Thesis: Hierarchical Symbolic Music Generation (2024)**

- Developed a novel GNN architecture (2-stage CNN/GCN VAE) capturing local and global musical structure for long-form generation, trained on POP909.
- Published at the 17th International Symposium on Computer Music Multidisciplinary Research ([Paper](https://zenodo.org/records/17488858)).

**Multi-model Pitch Transcription (2024)**

- Built an end-to-end pipeline combining vocal source separation (ConvTasNet) and CNN-based pitch transcription (CREPE), evaluated on MIR-1K ([GitHub](https://github.com/wenqinglim/singing_transcription), [Article](https://codingintune.substack.com/p/karaoke-chaos-part-i-multi-singer)).

**Beat Tracking & Audio Fingerprinting (2024)**

- Implemented and evaluated Ellis' (2007) beat tracking algorithm (Ballroom dataset) and Phillips' audio fingerprinting algorithm (GTZAN dataset) ([GitHub](https://github.com/wenqinglim/beat_tracking)).

**Computational Creativity: Multi-modal Generation (2024)**

- Designed a multi-modal pipeline integrating text, music, and video generation with mood/genre classification and conditional generation ([GitHub](https://github.com/wenqinglim/hum_me_a_melody), [Article](https://codingintune.substack.com/p/sentient-machines-one-computers-dream)).

### AI & Machine Learning Applications

**AI Summit London Hackathon (2024)**

- Winner (1 of 3 teams): led technical architecture for an agentic RAG system automating insurance policy recommendations ([LinkedIn](https://www.linkedin.com/posts/fetch-ai_the-smart-approach-activity-7209165525304725504-LHwN?)).

**Omdena — Data Science for Social Good, Volunteer (2020–2021)**

- Lead ML Engineer: led an 8-week project using text mining and clustering for online safety research ([Article](https://medium.com/omdena/exploring-scientific-literature-on-online-violence-against-children-via-natural-language-processing-d8765240e60a)).
- Singapore Chapter Lead: co-led a 10-week COVID-19 mental health impact study ([Article](https://link.medium.com/osTsr1z6ckb)).

Thanks for reading! 👋
