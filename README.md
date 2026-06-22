# 🤖 AI Impact on Jobs 2030 — Exploratory Data Analysis

An exploratory data analysis (EDA) project examining how Artificial Intelligence is expected to impact various job roles by 2030, using a dataset of 3000 job records across multiple industries.

---

## 📁 Project Structure

```
├── job.ipynb                    # Main analysis notebook
├── AI_Impact_on_Jobs_2030.csv   # Dataset
├── requirements.txt             # Python dependencies
├── .gitignore                   # Files to ignore in git
└── README.md                    # Project documentation
```

---

## 📊 Dataset Overview

| Feature | Description |
|---|---|
| `Job_Title` | Name of the job role |
| `Average_Salary` | Average annual salary (USD) |
| `Years_Experience` | Years of experience required |
| `Education_Level` | Required education (High School / Bachelor's / Master's / PhD) |
| `AI_Exposure_Index` | How much the job is exposed to AI (0–1) |
| `Tech_Growth_Factor` | Growth factor driven by technology |
| `Automation_Probability_2030` | Probability of automation by 2030 (0–1) |
| `Risk_Category` | Low / Medium / High automation risk |
| `Skill_1` to `Skill_10` | Skill scores relevant to the job |

- **Rows:** 3000
- **Columns:** 18

---

## 🔍 Analysis Performed

- Dataset loading and structure inspection (`shape`, `info`, `describe`)
- Top 10 highest paying job roles (bar chart)
- Distribution of automation risk categories
- Salary vs automation probability
- AI exposure across different job types

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-impact-jobs-eda.git
cd ai-impact-jobs-eda
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook job.ipynb
```

---

## 🛠️ Tech Stack

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## 👤 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
