# Early-Agent-Performance-Prediction

The goal of this project is to build a machine learning system that predicts insurance agents who are likely to have a NILL month (i.e., zero new policies sold in the upcoming month). This allows the company to proactively engage and support underperforming agents before their productivity drops.

---

## 🧠 Our Solution Highlights

- ✅ **Custom target engineering** for future-month prediction
- 📊 **Comprehensive EDA** and correlation + mutual information analysis
- 🕒 **Advanced time-based and windowed features** to capture short-term behavior shifts
- 📉 **Class imbalance handling** using XGBoost with custom parameters (`scale_pos_weight`, `gpu_hist`)
- 💡 **Actionable recommendations** for at-risk agents based on predictive factors

---

## 📁 Repository Structure

```

├── Explanation Docs/
│   ├── Agent Performance Analysis.pdf
│   ├── Predict NILL Agents Report.pdf
│   └── README.md
│
├── Dashboard/
│   ├── PowerBI\_Dashboard.pbix
│   ├── Evidence\_Screenshots/
│   └── README.md
│
├── Notebooks/
│   ├── EDA.ipynb
│   ├── Model\_Building.ipynb
│   ├── Draft\_Notebooks/
│   └── README.md
│
├── Models/
│   ├── xgb\_model\_fold\_0.pkl
│   ├── ...
│   └── xgb\_model\_fold\_9.pkl
│   └── README.md

```

---

## 📝 Folder Descriptions

- [`Explanation Docs/`](./Explanation%20Docs)  
  Contains the core documentation of our approach — including agent behavior analysis and detailed model report.

- [`Dashboard/`](./Dashboard)  
  Includes the Power BI dashboard and visual evidence to support our findings and predictions.

- [`Notebooks/`](./Notebooks)  
  All Jupyter notebooks for data exploration, model development, and experimentation.

- [`Models/`](./Models)  
  Serialized XGBoost models trained on each fold of the dataset using stratified cross-validation.

---

## 🔍 Key Results

- Focused on recall for minority class (NILL agents) to better serve business goals.
- Engineered features and trends improved model interpretability and robustness.
- Delivered both predictive insights and practical actions to re-engage underperforming agents.

---

## 📢 Team

**Team Cognic AI**  

---

## 📬 Contact

Feel free to reach out if you want to collaborate, ask questions, or learn more about our approach!

---