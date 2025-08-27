# Oil Well Location Selection

## 📌 Project Overview
This project focuses on selecting the optimal location for drilling an oil well.  
The main goal is to predict oil reserves in three regions, estimate the expected profit, and assess investment risks.

## 🚀 Project Steps
1. Load and explore geological survey data from three regions.
2. Train regression models to predict oil reserves.
3. Calculate expected profit and evaluate risks using the bootstrap method.
4. Select the region with the best profit-to-risk ratio.
5. Visualize the results of the analysis.

## 🛠️ Tech Stack
- Python 3.9+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Repository Structure

├── notebooks/
│ └── oil_well_location_selection.ipynb # main Jupyter Notebook with the solution
├── requirements.txt # project dependencies
└── README.md # project documentation

## ⚙️ Installation
Clone the repository and install the dependencies:

```bash
git clone https://github.com/your-username/oil-well-location-selection.git
cd oil-well-location-selection
pip install -r requirements.txt
```

## ▶️ Usage

Open the Jupyter Notebook to run the analysis step by step:
jupyter notebook notebooks/oil_well_location_selection.ipynb

## 📊 Results

1. Predictive models provide oil reserve estimates.
2. Bootstrapping is used to calculate confidence intervals for profit.
3. The analysis identifies the most profitable and least risky region.
