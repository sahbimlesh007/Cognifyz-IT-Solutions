# Cognifyz Technologies — Data Analysis Internship

## Overview

This repository contains the analysis and deliverables for the **Data Analysis Internship Program** offered by **Cognifyz Technologies**. The project explores a restaurant dataset to uncover insights around cuisines, ratings, geography, pricing, and customer engagement.

As per the internship guidelines, candidates complete **any 2 of the 3 available levels** (Level 1, Level 2, Level 3), with a separate file/notebook produced for each completed level.

## Dataset

- **File:** `Dataset.csv`
- **Rows:** 9,551 restaurants
- **Columns (21):**
  - `Restaurant ID`, `Restaurant Name`, `Country Code`, `City`, `Address`, `Locality`, `Locality Verbose`
  - `Longitude`, `Latitude`
  - `Cuisines`
  - `Average Cost for two`, `Currency`
  - `Has Table booking`, `Has Online delivery`, `Is delivering now`, `Switch to order menu`
  - `Price range`, `Aggregate rating`, `Rating color`, `Rating text`, `Votes`

## Project Structure

Cognifyz IT Solutions/
│
├── .venv/
│
├── Images/
│ ├── Level_1_assets/
│ ├── Level_2_assets/
│ └── Level_3_assets/
│
├── .gitignore
├── Data Analysis.pdf
├── Dataset.csv
├── Level_1.ipynb
├── Level_2.ipynb
├── Level_3.ipynb
├── LICENSE
├── README.md
├── Report.docx
├── Report.pdf
└── requirements.txt

## Task Breakdown

### Level 1

1. **Top Cuisines** — Identify the top 3 most common cuisines and the % of restaurants serving each.
2. **City Analysis** — City with the most restaurants, average rating per city, and the top-rated city.
3. **Price Range Distribution** — Visualize price range distribution and calculate the % share of each category.
4. **Online Delivery** — % of restaurants offering online delivery; compare ratings with vs. without delivery.

### Level 2

1. **Restaurant Ratings** — Distribution of aggregate ratings, most common rating range, and average votes.
2. **Cuisine Combinations** — Most common cuisine combinations and their impact on ratings.
3. **Geographic Analysis** — Map restaurant locations by lat/long and identify geographic clusters.
4. **Restaurant Chains** — Detect restaurant chains and compare their ratings/popularity.

### Level 3

1. **Restaurant Reviews** — Text analysis of reviews for common positive/negative keywords; relationship between review length and rating.
2. **Votes Analysis** — Restaurants with highest/lowest votes; correlation between votes and rating.
3. **Price Range vs. Services** — Relationship between price range and availability of online delivery / table booking.

## Tools & Libraries

- Python 3
- pandas, numpy — data wrangling
- matplotlib, seaborn — visualization
- Jupyter Notebook — development environment
- (Level 3, optional) basic NLP for review text analysis

## How to Run

1. Install dependencies: `pip install -r requirements.txt`
2. Open the notebook/script for the level you want to review (e.g. `Level_1.py`)
3. Run the script/notebook top to bottom — it reads `Dataset.csv` from the project root.

## About Cognifyz Technologies

Cognifyz Technologies is a technology company specializing in data science, offering AI, machine learning, and data analytics solutions, along with training programs in these areas.

- 🌐 [www.cognifyz.com](http://www.cognifyz.com)
- ✉️ contact@cognifyz.com
- 🔗 LinkedIn: @cognifyz-Technologies
- 📸 Instagram: @cognifyz_tech

## Submission Notes

- Academic integrity must be maintained — no plagiarism or copied code.
- Each completed level should be submitted as a separate file.
- A demonstration video of completed tasks should be shared on LinkedIn, tagging Cognifyz Technologies with hashtags `#cognifyz #cognifyzTech #cognifyzTechnologies`.
