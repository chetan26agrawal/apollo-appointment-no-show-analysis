# 🏥 Apollo Hospitals — Appointment No-Show & Patient Engagement Analysis

<p align="center">

**A Python Exploratory Data Analysis (EDA) Project**

Analyzing appointment trends, patient attendance, engagement effectiveness, financial performance, and doctor utilization.

</p>

---

## 📌 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Business Objectives](#-business-objectives)
- [📂 Dataset Overview](#-dataset-overview)
- [🛠️ Tools and Technologies](#️-tools-and-technologies)
- [📊 Project Analysis](#-project-analysis)
- [📈 Project Visualizations](#-project-visualizations)
- [🚀 Live Dashboard](#-live-dashboard)
- [💡 Key Business Insights](#-key-business-insights)
- [✅ Business Recommendations](#-business-recommendations)
- [📁 Repository Structure](#-repository-structure)
- [⚙️ Installation and Usage](#️-installation-and-usage)
- [📚 Skills Demonstrated](#-skills-demonstrated)
- [👨‍💻 Author](#-author)

---

## 📖 Project Overview

Appointment no-shows are an important operational challenge for healthcare providers. Missed appointments can affect doctor utilization, revenue realization, scheduling efficiency, and patient care.

This project explores Apollo Hospitals appointment data using Python to understand appointment attendance patterns, identify potential no-show risk factors, evaluate patient engagement strategies, and analyze financial and operational performance.

The analysis focuses on transforming raw appointment data into meaningful business insights through data exploration, aggregation, and visualization.

## 🎯 Business Objectives

- Analyze monthly and quarterly appointment trends.
- Understand appointment outcomes and no-show patterns.
- Compare no-show rates across specialties, cities, and appointment types.
- Evaluate booking lead time, booking channels, weekdays, and time-of-day patterns.
- Study reminder effectiveness and previous no-show history.
- Compare first-time and repeat patients.
- Explore demographic and membership-related patterns.
- Analyze revenue, payment methods, and insurance coverage.
- Evaluate doctor utilization and service quality.
- Develop actionable recommendations to improve appointment attendance.

## 📂 Dataset Overview

The project uses two datasets:

| Dataset | Records | Columns | Purpose |
|---|---:|---:|---|
| Appointment Fact Dataset | 75,000 | 52 | Appointment-level analysis |
| Doctor Dimension Dataset | 320 | 15 | Doctor-level analysis |

### Appointment Fact Dataset

Contains appointment-level information related to booking channels, appointment dates, patient demographics, reminders, appointment outcomes, revenue, payments, waiting time, and patient satisfaction.

### Doctor Dimension Dataset

Contains doctor-level information such as specialty, experience, qualifications, location, consultation fees, and ratings.

The datasets are connected using the `doctor_id` field.

> **Data privacy:** Do not publish real patient-identifiable or confidential healthcare information. Share only data that you are authorized to make public.

## 🛠️ Tools and Technologies

- **Python** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Pickle** — Python object serialization, where applicable
- **Jupyter Notebook** — Interactive analysis
- **Git & GitHub** — Version control and project documentation
- **HTML** — Dashboard presentation

## 📊 Project Analysis

### 1. 📅 Business Overview

- Monthly and quarterly appointment trends
- Appointment outcome distribution
- Booking channel volume and mix

### 2. 🚫 No-Show Analysis

- No-show rates by specialty and city
- Booking lead-time analysis
- Time-of-day and weekday/weekend comparisons
- Appointment type and booking channel comparisons

### 3. 📲 Reminder and Patient Engagement Effectiveness

- Reminder communication analysis
- Previous no-show history
- Apollo membership comparison
- First-time versus repeat patient behavior

### 4. 👥 Patient and Demographic Segmentation

- Age-group analysis
- Gender-based comparisons
- Chronic-condition segmentation
- Visit-reason analysis
- Specialty-specific age distribution

### 5. 💰 Financial Performance

- Estimated financial exposure associated with no-shows
- Average realized revenue by specialty
- Revenue by appointment type and city
- Payment method distribution
- Insurance coverage and patient out-of-pocket payments

### 6. 🩺 Doctor Utilization and Service Quality

- Doctor utilization by specialty
- Waiting-time analysis
- Consultation duration versus patient satisfaction
- Doctor experience versus standard consultation fees

## 📈 Project Visualizations

The `charts` folder contains selected visualizations generated during the analysis.

**[📂 Explore Project Charts](charts/)**

The visualizations cover appointment trends, no-show behavior, reminder effectiveness, patient segmentation, revenue performance, and doctor utilization.

To display individual charts directly in this README, use their exact filenames from the `charts` folder. For example:

```markdown
![Appointment Trends](charts/your-chart-filename.png)
```

Replace `your-chart-filename.png` with an actual image filename.

## 🚀 Live Dashboard

Explore the interactive dashboard for a visual overview of the project's analysis.

**[📊 View Live Dashboard](live%20dashboard/)**

> The link above opens the dashboard folder in GitHub. For a dashboard that opens and runs directly in the browser, publish the HTML file using GitHub Pages and replace this link with the published dashboard URL.

## 💡 Key Business Insights

The analysis is designed to help identify:

- Appointment segments with comparatively higher no-show rates.
- Relationships between booking lead time and attendance behavior.
- Differences in attendance across booking channels and appointment types.
- Potential associations between reminders and appointment attendance.
- Patient groups that may benefit from additional appointment communication.
- Financial exposure associated with missed appointments.
- Operational patterns in doctor utilization and patient waiting times.
- Opportunities to improve service quality and scheduling efficiency.

## ✅ Business Recommendations

Based on the patterns identified in the analysis, healthcare teams can consider:

1. **Improve appointment reminders:** Evaluate suitable reminder combinations and timing.
2. **Prioritize high-risk appointments:** Consider additional confirmations for segments with higher observed no-show rates.
3. **Improve patient communication:** Provide clear appointment details and rescheduling options.
4. **Monitor operational KPIs:** Track appointment attendance, doctor utilization, and waiting time.
5. **Review financial impact:** Monitor estimated revenue exposure associated with missed appointments.
6. **Continuously evaluate service quality:** Review consultation duration, patient satisfaction, and waiting-time patterns.

Recommendations should be validated against operational requirements and further evidence before implementation.

## 📁 Repository Structure

```text
apollo-appointment-no-show-analysis/
│
├── charts/
│   └── Project visualization images
│
├── live dashboard/
│   └── Dashboard HTML file
│
├── README.md
└── Jupyter Notebook / supporting project files
```

*The structure above is illustrative. Actual filenames and additional files may vary.*

## ⚙️ Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/chetan26agrawal/apollo-appointment-no-show-analysis.git
```

### 2. Navigate to the Project Folder

```bash
cd apollo-appointment-no-show-analysis
```

### 3. Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the project's `.ipynb` notebook and run the cells in order.

> Ensure that the required datasets are available at the file paths expected by the notebook. The live dashboard may have separate requirements depending on how its HTML file was created.

## 📚 Skills Demonstrated

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `EDA` · `Data Analysis` · `Data Visualization` · `Healthcare Analytics` · `Business Insights` · `Jupyter Notebook` · `GitHub`

## 👨‍💻 Author

**Chetan Agrawal**

GitHub: [@chetan26agrawal](https://github.com/chetan26agrawal)

Project Repository: [Apollo Appointment No-Show Analysis](https://github.com/chetan26agrawal/apollo-appointment-no-show-analysis)

---

⭐ If you find this project useful, consider giving the repository a star!
