# 🚀 Content Refresh Opportunity Scoring using Machine Learning

> **FlyRank AI Fluency Capstone Project**  
> Predicting which web pages should be refreshed before their search performance declines.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📖 Overview

Content teams often manage thousands of web pages, making it difficult to identify which pages need updating before search traffic begins to decline.

This project uses machine learning to analyze historical SEO and engagement metrics and predict pages that are likely to experience declining performance. The predictions help prioritize content refresh efforts and support data-driven SEO decisions.

This project was completed as part of the **FlyRank AI Fluency Capstone**.

---

# 🎯 Problem Statement

Refreshing every page on a website is expensive and time-consuming.

The objective of this project is to identify pages that are most likely to lose performance so that SEO teams can refresh the right content at the right time.

---

# 👥 Intended Users

- SEO Specialists
- Content Marketing Teams
- Website Owners
- Digital Marketing Agencies
- Data Analysts

---

# ✨ Features

- Data preprocessing
- Feature engineering
- Missing value handling
- Categorical encoding
- Machine Learning classification
- Content refresh opportunity prediction
- Model evaluation
- Priority ranking
- Result visualization
- Exportable predictions

---

# 📂 Dataset

**Dataset:** FlyRank Internship Starter Dataset

Dataset Characteristics:

- 30,000 anonymized webpages
- 44 SEO and engagement features
- Multiple website clients
- Historical traffic metrics
- Content metadata

Example Features:

- Search Volume
- Competition
- Word Count
- CTR
- Average Position
- Sessions
- Impressions
- Clicks
- Content Age
- Engagement Rate
- AI Traffic Percentage

Target Variable:

```
trend_direction
```

---

# 🏗️ Project Structure

```
flyrank/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── w01_research_question.ipynb
│   ├── w02_ml_task_framing.ipynb
│   ├── w03_data_contract.ipynb
│   ├── w04_baseline_score.ipynb
│   ├── w05_model.ipynb
│   ├── w06_validation_audit.ipynb
│   ├── w07_action_playbook.ipynb
│   └── capstone.ipynb
│
├── outputs/
│
├── scripts/
│
├── docs/
│
├── README.md
│
└── requirements.txt
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/amitkumar15x/flyrank.git
```

Move into the project

```bash
cd flyrank
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebooks/capstone.ipynb
```

Run all cells sequentially.

---

# 🔄 Machine Learning Pipeline

```
              Raw Dataset
                    │
                    ▼
          Data Preprocessing
                    │
                    ▼
         Feature Engineering
                    │
                    ▼
      Categorical Encoding
                    │
                    ▼
      Logistic Regression Model
                    │
                    ▼
          Model Evaluation
                    │
                    ▼
     Content Refresh Prediction
                    │
                    ▼
      Priority Recommendation
```

---

# 📊 Model Evaluation

The model was evaluated using standard classification metrics.

Metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The evaluation demonstrates that the baseline machine learning model can identify pages that are more likely to require content refresh based on historical SEO signals.

---

# 📈 Outputs

The project generates:

- Prediction results
- Evaluation metrics
- Visualizations
- Ranked refresh opportunities
- Action recommendations

---

# 💡 Example Workflow

```
Dataset
      ↓

Feature Engineering
      ↓

Model Training
      ↓

Prediction
      ↓

Rank Pages
      ↓

Recommend Refresh
```

---

# 📚 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Git
- GitHub

---

# ⚠️ Limitations

This project has several limitations:

- The dataset is anonymized.
- Labels are based on historical proxy signals rather than manual expert annotations.
- Logistic Regression serves as a strong baseline but may not capture complex nonlinear relationships.
- The model has not yet been validated on production SEO datasets.
- Feature importance is limited compared to tree-based models.

---

# 🚀 Future Improvements

Potential future work includes:

- XGBoost
- LightGBM
- Random Forest
- SHAP Explainability
- Hyperparameter Optimization
- Time-Series Forecasting
- Streamlit Dashboard
- Automated Content Refresh Recommendation System
- Production API Deployment

---

# 📄 Research Summary

This project demonstrates how machine learning can support SEO decision-making by prioritizing content refresh opportunities using historical performance data.

Instead of relying solely on manual analysis, the model provides a scalable and reproducible workflow for identifying pages that may benefit from updates.

---

# 🤖 AI Transparency

This project was developed with assistance from AI tools, including ChatGPT and Claude, for brainstorming, planning, debugging, documentation, and code review.

All code, notebook execution, experimentation, evaluation, verification, and final project decisions were reviewed and validated by me before submission.

This statement is included to promote transparency regarding AI-assisted development in accordance with the FlyRank AI Fluency framework.

---

# 📜 License

This project is intended for educational purposes as part of the FlyRank AI Fluency Internship.

---

# 👤 Author

**Amit Kumar**

GitHub: https://github.com/amitkumar15x

Portfolio: https://portfolio-realm.vercel.app/

LinkedIn: https://www.linkedin.com/in/amitkumar15x/

Capstone: https://amitkumar15.netlify.app/

---

# 🙏 Acknowledgements

Special thanks to:

- FlyRank AI Fluency Program
- FlyRank Mentors
- Anthropic Claude

for providing guidance, tools, and educational resources that supported the development of this capstone project.
