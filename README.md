# Netflix Content Evolution Analysis (2010 - 2025)

## Problem Statement
**Sector:**
Media & Entertainment — Streaming Analytics

**Context:**
Netflix has grown into one of the world’s leading streaming platforms by continuously expanding its catalog of Movies and TV Shows up to 2025.
With rapid content additions and changing viewer preferences, decision-makers require clear insights into:

- How content types have evolved
- Which genres dominate the platform
- How global distribution has shifted
- What trends are emerging over time

This project focuses on transforming raw Netflix content data into structured, actionable insights that can guide strategic content decisions.

## Core Question
How has Netflix’s content library evolved over time in terms of content type, genres, and global distribution — and what insights can guide future content strategy?

## Dataset Information
**Source:** Netflix Movies and TV Shows till 2025 (Kaggle dataset curated from TMDb)

### 🔗 Dataset Link:
https://www.kaggle.com/datasets/bhargavchirumamilla/netflix-movies-and-tv-shows-till-2025

### Dataset Overview

- ~16,000+ rows

- 18 columns


## Data Cleaning Process

1.  Dropped unnecessary columns
     - Removed **Duration** column.
     - Removed **Type** column since it contained only one constant value ("Movie").

2.  Formatted data types
    - Converted **Budget** and **Revenue** to currency format.
    - Ensured all columns were properly formatted.

3.  Removed garbage titles
    - Removed rows with invalid or corrupted title values.
    - Removed rows where **Country** or **Genres** were missing, as they are essential for analysis.
