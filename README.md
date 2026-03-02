# YouTube Trending Data – Computer Science for Data Science

## Overview

This project was developed for the *Computer Science for Data Science* course.  
It focuses on data extraction, integration, and preprocessing of multi-country YouTube Trending datasets provided in CSV (video metadata) and JSON (category metadata) formats.

The objective was to transform heterogeneous raw data into a consistent and structured dataset ready for further analysis.

---

## Dataset

The project uses multi-country YouTube Trending data including:

- Video-level metadata (CSV files)
- Category metadata (JSON files)
- 10 countries

Due to size constraints, the raw dataset is not included in this repository.

You can download the data here:

https://drive.google.com/drive/folders/1XPOKiMt17aPKDiND1Tntwrx-JFbMKvmp?usp=drive_link

---

## Project Structure

- `yt-trending Data.ipynb` → Main notebook containing all preprocessing steps
- Data folder (external) → Raw CSV and JSON files

---

## Main Operations Performed

- Automated loading of multiple CSV and JSON files
- Schema alignment across countries
- Data merging and integration
- Deduplication logic for repeated trending videos
- Data cleaning and consistency checks
- Feature engineering (temporal variables, ratios)
- Tag parsing and restructuring (explode logic)
- Integration of category metadata from JSON files

---

## Requirements

Python 3.x

Main libraries:
- pandas
- numpy
- json

---

## Author

Course project – Computer Science for Data Science  
University project for academic purposes.
