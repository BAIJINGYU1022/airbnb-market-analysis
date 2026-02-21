# airbnb-market-analysis:::writing{variant=standard id=81462}

Airbnb Market Analysis

📌 Project Overview

This project analyzes the structure of the Airbnb market using real listing data.
The goal is to understand pricing patterns, host types, supply concentration, and rating differences across segments.

This analysis was conducted as part of a data analytics learning project.

⸻

📊 Dataset
	•	Source: Inside Airbnb (public dataset)
	•	Scope: Listings data
	•	Key variables analyzed:
	•	price
	•	room_type
	•	host_id
	•	availability_365
	•	review_scores_rating

⸻

🔍 Key Questions
	•	How does price vary by room type?
	•	Are there professional hosts dominating the market?
	•	What is the distribution of listings per host?
	•	Do professional hosts receive higher or more stable ratings?

⸻

🛠️ Methods
	•	Data cleaning using pandas
	•	Aggregation and grouping analysis
	•	Distribution analysis (histogram, boxplot)
	•	Correlation analysis
	•	Log transformation for skewed distributions
	•	Market share calculation

⸻

📈 Key Findings

1. Price Structure
	•	Entire homes/apartments have the highest median prices
	•	Shared rooms are significantly cheaper
	•	Price distributions are highly skewed with many outliers

2. Host Structure
	•	The distribution of listings per host is strongly right-skewed
	•	Most hosts own only a few listings
	•	A small number of professional hosts control a large share of supply

3. Market Concentration
	•	Although professional hosts represent a minority,
they account for a disproportionately large share of listings,
indicating a long-tail market structure with supply concentration

4. Ratings by Host Type
	•	Both host types have generally high ratings
	•	Private hosts show slightly higher median ratings
	•	Professional hosts exhibit greater variability in scores

⸻

📦 Tools Used
	•	Python
	•	pandas
	•	numpy
	•	matplotlib
	•	seaborn
	•	Jupyter Notebook

📂 Repository Structure
  airbnb-market-analysis/
│
├── README.md
├── notebooks/
│   └── airbnb_analysis.ipynb
├── data/
│   ├── raw/
│   └── processed/
└── outputs/
    └── figures/
🚀 Future Work
	•	Build predictive models for price estimation
	•	Analyze geographic patterns
	•	Study demand factors such as reviews and availability
	•	Compare multiple cities

⸻

👩‍💻 Author

Independent learning project for data analytics portfolio development.
:::
