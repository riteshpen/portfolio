Austin, TX · Statistics & Data Science, UT Austin

# Ritesh Penumatsa

I'm a Statistics & Data Science student at UT Austin, graduating December 2026. I build machine learning projects end-to-end — computer vision, NLP, and full-stack AI products — and I'm looking for full-stack data science roles.

[GitHub](https://github.com/riteshpen) [LinkedIn](https://www.linkedin.com/in/riteshpenumatsa/) [Email](mailto:riteshstem@gmail.com)

Portrait of Ritesh Penumatsa

## Experience

### Data Science Intern

May 2025 — May 2026

Data Sculpture · Austin, TX

- Engineered end-to-end data pipelines on Firebase and GCP Dataflow, applying NLP and hypothesis testing (SciPy) to improve semantic search and cut query latency by 20%.
- Ran EDA and descriptive stats on 10,000+ records to keep datasets reliable for downstream modeling.
- Built interactive FlexMonster dashboards for \~6 stakeholders and implemented end-to-end data encryption for secure reporting.
- Collaborated on a 4-person cross-functional team to turn analytical findings into product improvements.

**Tools:** Firebase · GCP Dataflow · SciPy · FlexMonster

### Coding Tutor

Sep 2024 — May 2025

Varsity Tutors · Austin, TX

- Designed and taught a curriculum on ML fundamentals, Python, and data analysis for 3 students.
- Mentored the same students on algorithm and data structure implementation.
- Adapted lesson plans and pacing to each student's level, adjusting explanations based on where they got stuck.

## Selected work

9 projects

### [ResumeMatch](https://github.com/riteshpen/Resume_Match_AI)

May 2026 — Present

A full-stack AI app that checks a resume against a job description, flags ATS keyword gaps, and rewrites each section — with PDF export and cover letters, and a serverless proxy keeping API keys off the client. Live at [resumematch.org](https://www.resumematch.org/).

Coverage 100%

- Generic resumes get filtered out before a human ever reads them.
- Solo — design and ship a tool that closes that gap.
- Built a full-stack app with a serverless proxy and a dual PDF-parsing pipeline with an AI fallback.
- Shipped to production at resumematch.org — learned to design for reliability at scale, not just a working demo.

**Tools:** Claude API · serverless functions · PDF parsing

### [Camera Traffic Analysis](https://github.com/riteshpen/Camera_Traffic_Analysis)

Sep – Dec 2025

An end-to-end study of Austin traffic patterns — hypothesis testing, regression and random forest models, and SHAP-based interpretability tying weather to roadway outcomes. [Notebook](https://github.com/riteshpen/Camera_Traffic_Analysis/blob/main/Final%20Project-Report/Final%20Project/Code/Final_Project.ipynb) · [Final report](https://github.com/riteshpen/Camera_Traffic_Analysis/blob/main/Final%20Project-Report/Final%20Report/Report/Team%2011%20-%20Final%20Report.pdf).

Models compared 2

- Austin traffic patterns and their drivers weren't well understood from the raw data.
- One of 5 teammates, leading the modeling and interpretability work.
- Ran hypothesis tests, built Linear Regression and Random Forest models, applied SHAP.
- Weather stood out as a key driver — learned to explain "black-box" model decisions with SHAP.

**Tools:** Python · scikit-learn · SHAP · Jupyter

### [Malaria Prevention & Child Mortality](https://github.com/riteshpen/Malaria_Incidence)

Sep – Dec 2025

Used UNICEF and World Bank data to test how bed-net coverage relates to child mortality across income groups, with a geospatial dashboard and fairness-checked random forest models. [View interactive dashboard](https://github.com/user-attachments/files/24095190/malaria__dashboard.html) · [Notebook](https://github.com/riteshpen/Malaria_Incidence/blob/main/Code/Final_Project_Code.ipynb).

ITN coverage vs. child mortality — r = 0.13

Each dot is a country-income group. The trend line is almost flat — ITN coverage alone barely moves mortality, which pointed the analysis toward socioeconomic drivers instead.

- Unclear whether bed-net (ITN) distribution actually lowers child mortality.
- One of 3 teammates, co-leading modeling and fairness evaluation.
- Built a Random Forest model, checked subgroup fairness with Brier scores, built the dashboard.
- Found only a weak link (r = 0.13, p = 0.32) — learned correlation isn't causation, and to check fairness across subgroups.

**Tools:** Python · Random Forest · Brier score · dashboarding

### [Real or Fake News Detection](https://github.com/riteshpen/Fake-Real_News)

Jul – Sep 2024

An NLP classification pipeline for news articles, paired with an interactive interface for checking new stories, cutting false positives by 35%. [Live app](https://fake-realnews.streamlit.app/).

Accuracy 98%

- Misinformation spreads faster than people can fact-check it.
- Solo — build and ship a working fake-news classifier.
- Built an NLP pipeline with a Gradient Boosting Classifier, deployed via Streamlit.
- 98% accuracy, 35% fewer false positives — learned text preprocessing and shipping a model end-to-end.

**Tools:** Python · scikit-learn · Streamlit

### [ChatGPT Reviews Regression](https://github.com/riteshpen/ChatGPT_Reviews)

Jul – Aug 2024

A regression model linking review sentiment and engagement to rating scores, built on sentiment-scored, feature-engineered review text. [Live app](https://chatgptreviews-5iapr3c5ldkezfesqpmtjk.streamlit.app/).

Accuracy 99%

- The team wanted to know what actually drives ChatGPT's app ratings.
- Solo — turn raw review text into a predictive model.
- Scored sentiment, engineered features from review text, trained a regression model.
- 99%+ accuracy — learned feature engineering can matter more than the model itself.

**Tools:** Python · scikit-learn · Matplotlib/Seaborn

### [Tomato Plant Image Classification](https://github.com/riteshpen/Tomato_Health)

Jul – Aug 2024

"I build models and the tools around them — from CNNs that diagnose plant disease to a full-stack app that rewrites resumes against a job description. Graduating December 2026, looking for full-stack data science roles."

A CNN that classifies tomato plant diseases from leaf photos, wrapped in a web app that has processed 1,500+ user-uploaded images. [Live app](https://tomatoplantclassifier.streamlit.app/).

Accuracy 95%

- Farmers need a fast way to catch tomato plant disease early.
- Solo — build and deploy an image classifier people could actually use.
- Trained a CNN on labeled leaf images, built a Streamlit web app around it.
- 95% accuracy, \~50% faster diagnosis — learned computer vision deployment end-to-end.

**Tools:** Python · CNN · Google Colab · Streamlit

### [Diabetes Prediction Calculator](https://github.com/riteshpen/Diabeties_Prediction)

Jun – Aug 2024

A Streamlit tool for self-assessing diabetes risk from age, BMI, and glucose, backed by a tuned classifier used by 100+ people. [Live app](https://diabetiespredictioncalc.streamlit.app/).

Accuracy 95%+

- People want a quick, private way to gauge their diabetes risk.
- Solo — turn a health dataset into a self-assessment tool.
- Trained and tuned a classifier on age, BMI, and glucose, wrapped in a Streamlit interface.
- 95%+ accuracy, used by 100+ people — learned to balance model reliability with an approachable UI.

**Tools:** Python · scikit-learn · Streamlit

### [Celebrity Image Classification](https://github.com/riteshpen/Celebrity_Classifier)

Jun – Aug 2024

A CNN trained on 5,000+ labeled images to recognize 10+ celebrities, with a Flask web app for real-time predictions.

Accuracy 92%

- Wanted to test how well classical feature-based CV could identify people, not just deep learning.
- Solo — build a working classifier and a demo for it.
- Extracted facial features with OpenCV, trained an SVM, built a Flask app.
- 92% accuracy — learned the trade-offs between classical feature engineering and deep learning.

**Tools:** Python · OpenCV · scikit-learn (SVM) · Flask

### [Atliq Hardware SQL Analysis](https://github.com/riteshpen/Atliq_Hardware)

Jun – Jul 2024

Complex SQL queries simulating a data-analytics-director brief — sales trends, inventory, and customer segmentation for a hardware company, documented for a business audience.

Insights delivered 10+

- Execs needed faster, data-backed answers to ad hoc business questions.
- Solo — simulate a junior analyst role: answer 10 SQL prompts.
- Wrote and optimized queries for sales, inventory, and customer segmentation.
- Delivered 10+ documented insights — learned to write SQL for a business audience, not just correctness.

**Tools:** MySQL Workbench · Google Sheets/Slides

© 2026 Ritesh Penumatsa · 469-850-9940 [GitHub](https://github.com/riteshpen) · [LinkedIn](https://www.linkedin.com/in/riteshpenumatsa/) · [riteshstem@gmail.com](mailto:riteshstem@gmail.com)
