# Mobile App Market Analysis

## Project Overview

This project analyzes data from the Google Play Store and Apple App Store to identify patterns associated with successful mobile applications.

The analysis focuses on understanding how app characteristics such as genre, pricing, and user engagement relate to app popularity and potential revenue generation.

Since the hypothetical company behind this project earns revenue primarily through in-app advertisements, identifying app profiles that attract high user engagement is especially important.

---

## Objectives

- Clean and preprocess real-world app datasets
- Detect and remove inaccurate records
- Identify and remove duplicate entries
- Filter non-English applications
- Isolate free apps for focused analysis
- Explore app genres and market trends
- Identify app categories associated with high engagement

---

## Datasets

### Google Play Store Dataset
- Source: Kaggle / Dataquest
- Contains information on Android applications including:
  - Category
  - Ratings
  - Reviews
  - Installs
  - Pricing
  - Genres

### Apple App Store Dataset
- Source: Dataquest
- Contains information on iOS applications including:
  - Genre
  - User ratings
  - Pricing
  - App metadata

---

## Technologies Used

### Programming Language
- Python

### Libraries
- pandas
- numpy
- csv

### Environment
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Imported CSV datasets
- Converted datasets into pandas DataFrames for quick inspection

### 2. Data Exploration
- Built reusable functions to:
  - Explore rows
  - Display dataset dimensions
  - Inspect structure and columns

### 3. Data Cleaning
Performed several preprocessing steps:

#### Inaccurate Data Removal
- Removed corrupted Google Play Store row with shifted columns

#### Duplicate Removal
- Identified duplicate apps
- Retained only the most recent entry using review counts

#### Non-English App Filtering
- Built a custom ASCII-based filtering function
- Preserved apps with limited non-ASCII characters to avoid excessive data loss

#### Free App Isolation
- Filtered datasets to include only free applications

---

## Exploratory Data Analysis (EDA)

### Frequency Analysis
Generated frequency tables for:
- App genres
- Categories
- Market distribution

### User Engagement Analysis
Calculated:
- Average ratings by genre
- Estimated popularity trends
- Cross-platform app behavior

---

## Key Findings

### Apple App Store
- Games dominate the free app ecosystem
- Entertainment and photo/video apps are highly represented
- Navigation and social networking apps showed particularly strong engagement metrics

### Google Play Store
- More balanced ecosystem between entertainment and practical apps
- Strong representation of:
  - Productivity
  - Tools
  - Business
  - Lifestyle categories

### Business Insight
Apps combining:
- broad accessibility,
- strong engagement,
- and practical utility

may offer strong advertising revenue potential across both markets.

---

## Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Frequency Analysis
- Python Programming
- Custom Function Development
- Data Interpretation
- Business-Oriented Analysis

---

## Project Structure

```bash
04_app_analysis/
│
├── app_analysis_project.ipynb
└── README.md
```

---

## Future Improvements

Potential extensions for this project:
- Advanced visualizations using matplotlib/seaborn
- Sentiment analysis on app reviews
- Time-series trend analysis
- Predictive modeling for app success
- Cross-platform comparative dashboards

---

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter Notebook or JupyterLab
3. Ensure datasets are present in the project directory
4. Run notebook cells sequentially

---

## Author

Julia Wakoli
Aspiring Data Analyst | Bioinformatics & Data Science Enthusiast
