# Netflix Data Exploration and Visualisation

## Project Overview

This project is a business case study on Netflix’s content catalog. The objective was to explore the dataset, perform preprocessing, carry out non-graphical and visual analysis, and generate business insights that could help Netflix decide what type of shows or movies to produce and how to grow across different countries.

The analysis was completed in a Jupyter Notebook using Python.

---

## Business Problem

Netflix is one of the world’s leading video streaming platforms, with a large global content library of movies and TV shows.

The goal of this case study was to analyze Netflix’s dataset and answer business-focused questions such as:

- What type of content dominates the catalog?

- How has content changed over time?

- Which countries contribute the most content?

- Which genres are most common?

- Does Netflix appear to be focusing more on TV shows in recent years?

- What kind of content strategy may help Netflix grow internationally?

---

## Dataset Information

The dataset contains information about Netflix titles, including:

- `show_id`

- `type`

- `title`

- `director`

- `cast`

- `country`

- `date_added`

- `release_year`

- `rating`

- `duration`

- `listed_in`

- `description`

---

## Tools and Libraries Used

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Jupyter Notebook

---

## Project Workflow

### 1. Problem Understanding

Defined the business problem and the objective of the case study.

### 2. Data Loading and Inspection

- Loaded the Netflix dataset

- Checked shape, columns, and data types

- Reviewed missing values and duplicate rows

- Generated summary statistics

### 3. Data Preprocessing

- Converted `date_added` into datetime format

- Extracted `year_added` and `month_added`

- Split `duration` into:

  - `duration_int`

  - `duration_type`

- Converted selected columns to category type

- Unnested / exploded:

  - country

  - listed_in

  - director

  - cast

### 4. Non-Graphical Analysis

- Counted Movies vs TV Shows

- Studied release year distribution

- Checked most frequent ratings

- Analyzed top countries, genres, directors, and actors

- Compared duration patterns for movies and TV shows

### 5. Visual Analysis

Created plots to understand:

- content type distribution

- release year trends

- rating distribution

- movie duration distribution

- month-wise additions

- Movies vs TV Shows by year

- top countries and genres

- outlier patterns in movie durations and TV show seasons

### 6. Missing Value and Outlier Check

- Identified columns with the highest missing values

- Reviewed missing value percentages

- Examined movie duration outliers

- Examined long-running TV shows

### 7. Business Insights and Recommendations

Converted EDA findings into business insights and practical recommendations for Netflix’s content strategy.

---

## Key Insights

- Movies dominate the Netflix catalog, but TV shows also form an important share.

- The catalog is concentrated in recent years, showing Netflix’s focus on relatively modern content.

- Ratings such as TV-MA and TV-14 are highly common, suggesting strong focus on teen/adult audiences.

- International Movies and International TV Shows are major parts of the library.

- Countries such as the United States, India, and the United Kingdom contribute large portions of content.

- Most TV shows are short-run series, while a smaller group of shows runs for many seasons.

- Most movies follow standard feature-film runtimes.

---

## Business Recommendations

- Continue investing in high-performing movie genres.

- Expand international and multilingual content production.

- Strengthen content strategy in important markets such as India.

- Use short-run TV shows as a low-risk experimentation format.

- Extend selected successful shows into long-running franchises.

- Improve metadata quality for better analysis and decision-making.

---

## Project Files

- `sample.ipynb` → full notebook

- `netflix.csv` → dataset

- `README.md` → project documentation

---

## Conclusion

This project shows how exploratory data analysis can be used to move from raw entertainment data to business-focused insights and recommendations. The results suggest that Netflix’s content growth strategy is strongest when it combines global scale, strong international content, flexible show formats, and broad genre coverage.
