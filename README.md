# LLM Hiring Bias Study

Developed a Python-based evaluation framework to analyze demographic proxy bias in LLM-generated hiring assessments using repeated inference pipelines, statistical testing, and regression modeling.


## Overview

This project investigates whether large language models produce statistically measurable differences in hiring evaluation scores when candidate qualifications remain constant and only demographic proxy names are changed.

Using Gemini 2.5 Flash, the system repeatedly generated candidate evaluations under controlled prompting conditions to analyze scoring behavior across race- and gender-associated names.


## Objectives
- Evaluate fairness behavior in generative AI hiring evaluations
- Measure score variation across demographic proxy groups
- Build a reproducible LLM evaluation pipeline
- Apply statistical inference techniques to model outputs
- Explore bias detection methodologies for generative systems


### Data Generation Pipeline
- Implemented repeated prompting workflows using the Gemini API
- Generated structured JSON-based candidate evaluations
- Maintained controlled candidate qualifications across trials
- Automated response collection and dataset construction

### Data Processing
- Cleaned and standardized model-generated outputs
- Converted responses into analyzable tabular datasets
- Performed preprocessing using pandas and NumPy

### Statistical Analysis
- Exploratory data analysis (EDA)
- Distribution visualization and score comparison
- Hypothesis testing using t-tests
- Linear regression modeling for demographic proxy analysis


## Technologies Used
- Python
- pandas
- NumPy
- matplotlib
- scikit-learn
- Jupyter Notebook
- Gemini API


## Findings

The analysis identified statistically measurable variation in LLM-generated hiring scores across demographic proxy groups under controlled prompting conditions. Regression modeling and hypothesis testing revealed consistent directional scoring differences, demonstrating how repeated inference pipelines can be used to evaluate fairness behavior and bias patterns in generative AI systems.
