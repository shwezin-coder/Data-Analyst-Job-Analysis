# E-commerce & Tech Data Analyst Landscape: A Skills and Salary Analysis

This repository contains a comprehensive analysis of the **Data Analyst job market**, specifically tailored for the **e-commerce and tech sectors**. My primary objective was to uncover key skills, experience levels, and salary expectations to guide aspiring data analysts and inform talent acquisition strategies.

-----

## Overview

In today's dynamic digital economy, understanding the precise demands for data talent is crucial. This project leverages real-world job data to provide clarity on:

  * **In-demand skills**: What specific technical tools (e.g., Python, SQL, Tableau) and analytical concepts (e.g., Data Mining, Statistical Analysis) are most frequently sought.
  * **Experience requirements**: The typical years of experience requested for data analyst roles at various levels.
  * **Market trends**: Insights into salary ranges associated with different skill sets and experience tiers within the e-commerce and tech industries.

By transforming unstructured job description text into quantifiable data, this analysis offers a data-driven compass for navigating the data analyst career path.

-----

## Project Components

### 1\. **Data Acquisition & Preparation**

  * **Data Source**: Initiated by gathering the **Kaggle Data Analyst Jobs dataset**, a rich collection of job descriptions.
  * **Data Cleaning & Transformation**: Used **Python (pandas)** for meticulous data cleaning, handling missing values, and standardizing diverse text formats to ensure consistency and accuracy.

### 2\. **Skill & Experience Feature Engineering**

  * **Text Analysis & Extraction**: Employed **Python's `re` module** (Regular Expressions) and **NLTK (Natural Language Toolkit)** to perform advanced text analysis. This involved pattern matching to systematically extract explicit skills (e.g., "SQL", "Python") and implicit concepts (e.g., "Statistical Analysis") from unstructured job description text.
  * **One-Hot Encoding**: Leveraged `MultiLabelBinarizer` from **scikit-learn** to convert the extracted categorical skills into a binary (0/1) format, making them quantifiable for statistical analysis.
  * **Experience Extraction**: Systematically extracted and standardized years of experience mentioned in job descriptions, creating a numerical feature for analysis.

### 3\. **Data Segmentation & Visualization**

  * **Data Structuring**: Segmented the processed data into logical tables for skills and experience, linked by a unique job ID, optimizing the dataset for visual exploration.
  * **Interactive Dashboard**: Utilized **Tableau** to design and develop an intuitive and interactive dashboard. This dashboard allows users to visually explore skill demand, experience distribution, and salary insights.
  * **Visual Storytelling**: The visualizations highlight crucial findings, such as the high demand for **Data Mining**, **Python/R**, **SQL**, and **Tableau/PowerBI**, alongside the importance of statistical analysis and key soft skills.

-----

## Findings

The analysis revealed that while foundational skills like **SQL** and **Excel** remain crucial, advanced proficiencies in **Python** (including libraries like Pandas, NLTK, Scikit-learn), **Data Visualization** (Tableau/PowerBI), and **Data Mining** are increasingly vital for success in the e-commerce and tech sectors. Furthermore, a strong grasp of **statistical analysis** and critical thinking consistently appears as a key requirement. The project effectively quantifies these trends, providing a clear picture of the current market demands.

-----

## How to Explore This Project

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/data-analyst-job-analysis.git
    ```

    (Replace `yourusername` and `data-analyst-job-analysis` with your actual GitHub details)

2.  **Review the Code**: Navigate through the Python scripts to understand the data cleaning, feature engineering (including NLTK and one-hot encoding), and preprocessing steps.

3.  **Explore the Dashboard**: Open the **Tableau Public** dashboard (link below) to interact with the visualizations and dive deeper into the insights.

-----


## Contact

For any questions or feedback, please contact Hnin Shwe Zin Hlaing at hninshwezinhlaing05062001@gmail.com.
