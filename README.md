# Anime Series Data Analysis & Feature Extraction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Shubhanshu-Fartyal/anime-mini-project/blob/main/P5_animeproject.ipynb)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)](https://pandas.pydata.org/)

A data manipulation and feature engineering project built using **Python** and **Pandas**. The project processes an Anime series dataset to extract structured temporal and categorical metrics out of unstructured text fields.

---

## Project Overview

Raw real-world datasets often lump multiple attributes into a single string. In this dataset, the `Title` column contains the series title, format (TV/Movie/OVA), episode count, and airing time span.

This project extracts:
1. **Episode Count (`Episodes`)**: Parsed from string format `(X eps)` into clean numerical integers.
2. **Airing Duration (`Total Time`)**: Isolated date range strings representing release spans.
3. **Air Time Span in Months (`Months`)**: Calculated month differences derived via `datetime` parsing.

---

## Key Insights from Data

- **Highest Scoring Anime**: *Fullmetal Alchemist: Brotherhood* (Score: 9.10)
- **Most Episodes**: *Gintama* with **201 episodes**
- **Longest Running Anime**: *Ginga Eiyuu Densetsu* (Legend of the Galactic Heroes), airing across **111 months** (Jan 1988 – Mar 1997)

---

## Project Structure

```text
anime-mini-project/
├── anime.csv                     # Anime dataset
├── feature_extraction_code.ipynb # Data processing notebook
├── requirements.txt              # Required dependencies
├── .gitignore                    # Ignored cache and temporary files
└── README.md                     # Project documentation
