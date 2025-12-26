# Salary Prediction using the Stack Overflow Developer Survey 2025

## Project Overview
This project is the final assignment for the Big Data Analytics course. 
The objective is focused on salary prediction using the Stack Overflow Developer Survey 2025. The project uses KNIME to perform data preparation and compare machine learning models, identifying key factors influencing developers’ compensation and deriving managerial insights.

## Research Objective
The main goal of the analysis is to identify the key technical, demographic, and professional factors that influence developers’ compensation and to assess the predictive performance of different machine learning models.

## Dataset
The dataset used in this project is the Stack Overflow Developer Survey 2025.
Due to GitHub file size limitations, the raw dataset is not included in this repository.

The dataset can be downloaded from the official Stack Overflow website:
https://survey.stackoverflow.co/

The downloaded archive contains:
- `survey_results_public.csv`, which includes respondents’ answers to the survey questions;
- `survey_results_schema.csv`, which provides the mapping between each survey question and its corresponding variable abbreviation;
- `2025 Developer Survey Tool.pdf`, which documents the survey structure and questions.

## Methodology
The analysis follows a structured data science pipeline:
- Data understanding and cleaning
- Feature selection and encoding
- Train/test split
- Comparison of multiple machine learning models

All preprocessing and modeling steps are implemented and documented in KNIME workflows.

## Tools
- KNIME Analytics Platform
- Stack Overflow Developer Survey 2025
- PowerPoint

## Reproducibility
To reproduce the analysis:
1. Download the dataset from the official Stack Overflow website.
2. Open the KNIME workflow located in the `knime/` folder.
3. Update the CSV Reader node to point to the local dataset file.
4. Execute the workflow.

## Results
The results of the analysis, including model comparison and managerial insights, are presented in the final report.

## Authors
This project was developed by a group of university students as part of the Big Data Analytics course.





