Netflix Dataset – Exploratory Data Analysis (EDA)

Problem Statement:

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Netflix dataset to identify trends, patterns, and relationships within the data. The analysis focuses on understanding content distribution, release trends, and correlations between different features.

Dataset Details:

The dataset contains information about movies and TV shows available on Netflix.They are as follows:

show_id,
type,
title,
director,
cast,
country,
date_added,
release_year,
rating,
duration,
listed_in,
description 

Approach:

1. Data Loading & Inspection
   
Imported libraries: pandas, numpy, matplotlib, seaborn
Loaded dataset using read_csv()
Checked:
Shape of dataset
Data types and structure (info())
Missing values\

2. Summary Statistics
   
Used describe() for numerical features
Used describe(include='object') for categorical features
Checked frequency of values like:
Release years
Content types

3. Correlation Analysis
   
Numerical Correlation
Used heatmap to visualize correlation between numeric features

Categorical Correlation
Applied Cramér’s V to measure association between:type,rating,country
Visualized results using a heatmap

4. Trend Identification
   
Content Type Distribution
Countplot used to compare:
Movies vs TV Shows
Release Trend Over Years
Line plot used to observe how content production changed over time
Top Producing Countries
Bar chart used to identify top 10 countries producing Netflix content

Results:

Movies are more common than TV shows on Netflix
Content production has significantly increased in recent years
A few countries dominate Netflix content production
Certain ratings are more frequent depending on content type
Categorical correlation shows relationships between content type, rating, and country
Trends indicate Netflix’s growing investment in global and diverse content
