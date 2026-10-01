# Amazon ML Challenge 2026 – Business Entity Resolution

This project was developed for the Amazon ML Challenge 2026 Business Entity Resolution Challenge.

## Project Overview

The goal is to identify matching business entities across multiple data sources using machine learning and text similarity techniques.

## Approach

- Data preprocessing and text normalization
- Country-aware blocking using normalized business names
- Character-level TF-IDF similarity
- Cosine similarity for name and address matching
- Combined similarity score using:
  - 60% business name similarity
  - 40% business address similarity
- Threshold-based entity matching

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- TF-IDF
- Cosine Similarity

## Dataset

The challenge provides multiple business entity data sources containing:

- Entity ID
- Business Name
- Business Address
- Country

The dataset is not included in this repository due to size and challenge restrictions.

## Files

- `Untitled6.ipynb` – Complete project code and analysis

## Team

**Team Name:** Data Mavericks

**Team Leader:** Dhiraj Kumar

**Team Member:** Vishal Kumar Yadav

## Note

This repository contains the project code developed for the Amazon ML Challenge 2026.
