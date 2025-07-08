# 🎾 Tennis ATP 2000–2025

This project contains a cleaned and structured dataset of ATP (men’s professional tennis) matches from **2000 to 2025**. The data is useful for analysis, visualization, and building machine learning models related to tennis performance, rankings, and outcomes.

## 📁 Project Structure

```
tennis_atp_2000_2025/
│
├── data/
│   ├── atp_matches_2000_2025.csv         # Consolidated dataset of ATP matches
│   ├── raw_atp_data/                     # Raw CSV files by year (2000–2025)
│   └── ...
│
├── notebooks/
│   ├── EDA.ipynb                         # Exploratory data analysis notebook
│   └── model_training.ipynb             # Sample model for match outcome prediction
│
├── utils/
│   └── data_cleaning.py                 # Scripts for cleaning and merging raw data
│
├── .gitignore
├── README.md
└── requirements.txt
```

## 📊 Dataset Features

Each match entry includes:

- `tourney_id`, `tourney_date`, `tourney_name`, `surface`, `draw_size`, etc.
- `winner_name`, `winner_rank`, `winner_hand`, `winner_age`, etc.
- `loser_name`, `loser_rank`, `loser_hand`, `loser_age`, etc.
- Match stats: `minutes`, `w_ace`, `w_df`, `l_ace`, `l_df`, `score`, etc.

## 📌 Objectives

- 📚 Provide a reliable, long-term dataset for ATP match analysis
- 📈 Enable statistical and ML analysis (e.g., win prediction, ranking dynamics)
- 🎥 Facilitate player or tournament-level visualizations

## ✅ How to Use

1. Clone the repository:

```bash
git clone https://github.com/jegqwll/tennis_atp_2000_2025.git
cd tennis_atp_2000_2025
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Explore the data via Jupyter:

```bash
jupyter notebook notebooks/EDA.ipynb
```

## 📦 Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `jupyter`

(See `requirements.txt` for full list.)

## 🧹 Data Sources and Cleaning

The raw data was sourced from [Jeff Sackmann's ATP repository](https://github.com/JeffSackmann/tennis_atp) and processed to:

- Merge yearly files into a single dataset
- Standardize column names and data types
- Handle missing or inconsistent data

## 🚀 Future Work

- Add match-level Elo ratings
- Integrate player bio/stats data
- Build interactive dashboards
- Improve model accuracy for win/loss prediction

## 📬 Contact

Created by [jegqwll](https://github.com/jegqwll).  
Feel free to submit an issue or pull request for improvements or questions.
