# A/B Test Analysis: E-commerce Recommender System

## 📖 Overview
This project analyzes an A/B test for a new product recommendation algorithm. The goal was to determine if the new system (Group B) improved user conversion rates compared to the old system (Group A). The analysis revealed a **statistically significant decrease in purchase conversions** for the test group, leading to a recommendation to stop the test.

## 🔧 Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, SciPy, Matplotlib, Seaborn
*   **Environment:** Jupyter Notebook
*   **Tools:** Git, GitHub

## 📊 Results Summary
The new recommender system (Group B) led to a significant drop in the most critical business metric.

| Funnel Stage | Group A (Control) | Group B (Treatment) |
| :--- | :--- | :--- |
| **Login** | 99.98% | 100.0% |
| **Product Page** | 66.56% | 65.52% |
| **Product Cart** | 32.12% | 33.66% |
| **Purchase** | **35.32%** | **33.10%** |

**Key Finding:** A **Z-test for proportions** confirmed that the ~2.2% absolute decrease in purchase rate for Group B was statistically significant (p-value < 0.05). This represents a **6.3% relative decrease** in conversions.

## 🗂 Project Structure
├── notebooks/
│ └── AB final project (2).ipynb # Complete analysis & visualization
├── assets/
│ └── funnel_comparison.png # Funnel visualization
├── data/
│ └── .gitkeep # Raw data directory (data excluded)
├── README.md
└── requirements.txt

## 🚀 How to Run
1.  Clone the repo: `git clone https://github.com/AnyaDom/recommender-ab-test.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Open the Jupyter Notebook: `jupyter notebook "notebooks/AB final project (2).ipynb"`

## 📌 Conclusion & Recommendation
**Recommendation: Stop the test and do not roll out the new recommender system.**

The analysis provides evidence that the new algorithm (Group B) harms business performance by reducing the number of final purchases. The existing system (Group A) should be maintained.

## ⚠️ Usage Restrictions
This code and analysis are part of my professional portfolio. You may view and fork this repository for learning purposes, but please do not:
- Redistribute the code or analysis without permission.
- Use it for commercial purposes.
- Claim it as your own work.
