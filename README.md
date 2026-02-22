# airbnb-market-analysis
Airbnb Market Analysis

📌 Project Overview

This project analyzes the structure of the Airbnb market using real listing data.
The goal is to understand pricing patterns, host types, supply concentration, and rating differences across segments.

This analysis was conducted as part of a data analytics learning project.

---

## 📊 Dataset
- Source: Inside Airbnb (public dataset)
- Scope: Listings data
- Key variables: `price`, `room_type`, `host_id`, `availability_365`, `review_scores_rating`

---

## 🔍 Key Questions
- How does price vary by room type?
- Are there professional hosts dominating the market?
- What is the distribution of listings per host?
- Do professional hosts receive higher or more stable ratings?

⸻

## 🛠️ Methods
- Data cleaning using pandas
- Aggregation and grouping analysis
- Distribution analysis (histogram, boxplot)
- Correlation analysis
- Log transformation for skewed distributions
- Market share calculation

⸻

## 📈 Key Findings

- **1.** Price Structure
	•	Entire homes/apartments have the highest median prices
	•	Shared rooms are significantly cheaper
	•	Price distributions are highly skewed with many outliers

- **2.** Host Structure
	•	The distribution of listings per host is strongly right-skewed
	•	Most hosts own only a few listings
	•	A small number of professional hosts control a large share of the supply

- **3.** Market Concentration
	•	Although professional hosts represent a minority, they account for a  disproportionately large share of listings, indicating a long-tail market structure with supply concentration

- **4.** Ratings by Host Type
	•	Both host types have generally high ratings
	•	Private hosts show slightly higher median ratings
	•	Professional hosts exhibit greater variability in scores

### Price Distribution by Room Type

![Price Distribution](outputs/figures/Price_distribution_room_type.png)

Entire homes tend to have higher median prices and larger variability, while shared rooms are significantly cheaper and more concentrated.

---

### Supply Structure: Listings per Host

![Listings per Host](outputs/figures/listings_per_host.png)

The distribution is strongly right-skewed, indicating a long-tail market where a small number of hosts control a large share of listings.

⸻

## 📦 Tools Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Data Source

The dataset used in this project is publicly available Airbnb listings data.

To reproduce the analysis:

1. Download the dataset from:
   https://insideairbnb.com/get-the-data/

2. Place the file in the following directory:

data/raw/listings.csv

## 📁 Repository Structure

```text
airbnb-market-analysis/
├── README.md
├── requirements.txt
├── notebooks/
│   └── airbnb_analysis.ipynb
├── data/
│   ├── raw/           
│   └── processed/
│       └── clean_listings.csv
└── outputs/
    └── figures/
        ├── price_distribution.png
        └── listings_per_host.png

```

🚀 Future Work
- Build predictive models for price estimation
- Analyze geographic patterns
- Study demand factors (reviews, availability)
- Compare multiple cities

⸻

👩‍💻 Author

Independent learning project for data analytics portfolio development.

