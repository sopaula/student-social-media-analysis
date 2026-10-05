# Student Social Media Usage Analysis

Exploratory data analysis of student social media usage, focused on the relationships between social media habits, sleep, mental health and academic performance.

The project combines data processing, visualisation and simple analytical modelling in Python.

## Dataset

The dataset comes from Kaggle:

**Student Social Media Addiction Analysis Dataset**

It contains data for **705 students** and includes information such as:

- age
- gender
- academic level
- country
- average daily social media usage
- most used social media platform
- sleep duration
- mental health score
- academic performance impact
- conflicts related to social media
- addiction score

## Project Scope

The analysis includes:

- data inspection and preparation
- descriptive statistics
- analysis of social media usage patterns
- data visualisation
- comparison of user groups
- analysis of relationships between social media use and sleep
- analysis of social media use and academic performance
- analysis of age and social media usage
- creation of a custom Risk Index
- rule-based user classification
- simulation of reduced social media usage

## Exploratory Data Analysis

The project explores several questions, including:

- How much time do students spend on social media?
- Which social media platforms are used most often?
- Is higher social media usage associated with shorter sleep?
- Do students reporting an impact on academic performance spend more time online?
- Does social media usage differ by age or education level?
- Which groups show a higher risk of problematic social media usage?

## Risk Index

A custom **Risk Index** was created to identify students who may be more exposed to negative effects of social media usage.

The index combines:

- high daily social media usage
- low sleep duration
- high addiction score

The resulting score ranges from **0 to 1**, where higher values indicate potentially higher risk.

## User Classification

Students are also classified into behavioural groups using a rule-based approach.

This provides a simple and interpretable way to complement the numerical Risk Index.

## Scenario Simulation

The project includes a hypothetical scenario analysing how reducing daily social media usage could affect the Risk Index.

The simulation is intended as an analytical experiment rather than a prediction.

## Data Visualisation

The project includes visualisations of:

- gender distribution
- daily social media usage
- most popular platforms
- social media usage vs sleep
- social media usage vs academic performance
- social media usage by age
- country distribution
- Risk Index distribution
- Risk Index by education level
- simulated changes in Risk Index

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```text
student-social-media-analysis/
├── social_media_analysis.ipynb
└── README.md
