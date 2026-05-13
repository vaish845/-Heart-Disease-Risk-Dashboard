# 🫀 Heart Disease Risk Dashboard

A **Power BI** interactive dashboard for analyzing and visualizing heart disease risk factors across a patient dataset of 270 individuals.

![Dashboard Preview](heart_risk_dashboard.png)

---

## 📊 Overview

This dashboard provides a comprehensive visual analysis of heart disease presence and absence across various demographic and clinical factors. It is built using **Microsoft Power BI** and leverages a heart disease prediction dataset to surface meaningful patterns in patient data.

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Patients | 270 |
| Disease Count | 120 |
| Disease Rate | 44.44% |
| Average Age | 54.43 |

---

## 🔍 Visualizations

| Chart | Description |
|---|---|
| **Donut Chart** | Distribution of patients by Heart Disease status (Absence vs Presence) |
| **Grouped Bar Chart** | Total patients by Age Group and Heart Disease status |
| **Scatter Plot** | Sum of Cholesterol vs Sum of Max HR by Heart Disease |
| **Combo Bar Chart** | Sum of Sex and Total Patients by Heart Disease |
| **KPI Cards** | High-level summary metrics (Total Patients, Disease Count, Disease Rate %, Avg Age) |

---

## 🗂️ Dataset

- **File:** `Heart_Disease_Prediction` (loaded in Power BI)
- **Records:** 270 patients
- **Key Columns:**
  - `Age` — Patient age
  - `Sex` — Patient sex (encoded numerically)
  - `Cholesterol` — Serum cholesterol in mg/dl
  - `Max HR` — Maximum heart rate achieved
  - `Heart Disease` — Target variable (`Presence` / `Absence`)

> **Note:** This dataset is commonly derived from the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease).

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **DAX** (for calculated measures)
- **Power Query** (for data transformation)

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)

### Steps to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/heart-disease-risk-dashboard.git
   cd heart-disease-risk-dashboard
   ```

2. **Open the Power BI file**
   - Launch Power BI Desktop
   - Open `heart_risk_dashboard.pbix`

3. **Refresh the data** *(if needed)*
   - Go to **Home → Refresh**
   - Ensure the dataset file path is correctly linked

4. **Explore the dashboard**
   - Use slicers and filters to interact with the visuals
   - Cross-filter by clicking on any chart element

---

## 📁 Repository Structure

```
heart-disease-risk-dashboard/
│
├── heart_risk_dashboard.pbix       # Power BI report file
├── heart_risk_dashboard.png        # Dashboard screenshot
├── Heart_Disease_Prediction.csv    # Source dataset
└── README.md                       # Project documentation
```

---

## 💡 Insights

- **44.44%** of patients in the dataset have heart disease — nearly half, indicating a high-risk cohort.
- Patients in the **50–59** age group represent the largest segment with heart disease presence.
- Patients **under 50** show a higher proportion of disease **absence**.
- Higher **Max HR** values appear loosely correlated with disease **absence** in the scatter plot.
- **Sex** distribution differs between Presence and Absence groups, suggesting it as a notable risk factor.

---

## 📌 Future Improvements

- [ ] Add slicers for Sex, Chest Pain Type, and Fasting Blood Sugar
- [ ] Incorporate predictive scoring using Azure ML integration
- [ ] Publish to Power BI Service for web access
- [ ] Add drill-through pages for individual patient profiles
- [ ] Connect to a live SQL Server data source

---
<img width="1918" height="1078" alt="heart risk dashboard" src="https://github.com/user-attachments/assets/a57ea88f-727f-4380-a4bc-6ff1ba7548fd" />

## 🤝 Contributing

Contributions are welcome! Please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-visual`)
3. Commit your changes (`git commit -m 'Add new visual'`)
4. Push to the branch (`git push origin feature/new-visual`)
5. Open a Pull Request

---


## 🙏 Acknowledgements

- Dataset sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
