# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Project Overview

This project analyses an insurance dataset to understand factors influencing insurance charges. Key variables include age, gender, smoking status, BMI, and region. Using Python, I performed exploratory data analysis through scatter plots, box plots, and bar charts to uncover meaningful trends.

## Data Cleaning

The original dataset required extensive cleaning before analysis. I used Python scripts in the terminal to preprocess the data, handling missing values, categorical encoding, and verifying data consistency. This process was challenging due to package dependencies and environment setup, requiring multiple installations and troubleshooting. Thankfully, AI tools like ChatGPT and GitHub Copilot were invaluable in guiding me through coding and debugging. The final cleaned data was saved as cleaned_insurance.csv, ensuring a reproducible and organised workflow.

## Visualisations Conducted

** Scatter plot: Insurance charges versus age, colour-coded by smoking status.

** Box plot: Distribution of insurance charges by gender.

** Bar chart: Average insurance charges for smokers versus non-smokers.

## Insights and Findings

The analysis reveals that smokers incur higher insurance costs, charges increase with age, and there are noticeable gender differences in costs. These findings help understand key drivers of insurance charges and can inform pricing and risk strategies.

## Challenges and Solutions

During the course of this project, I encountered several challenges that required perseverance and learning:

Data Cleaning and Preparation:
Initially, the dataset required cleaning to ensure accurate analysis. This involved handling missing values, encoding categorical variables, and ensuring consistency. Performing these steps via Python in the terminal was sometimes complex and time-consuming.

Plotting and Visualisation Issues:
I faced difficulties displaying interactive Plotly visualisations correctly, especially in different environments such as Jupyter notebooks and GitHub. Rendering errors and the need to export static images for GitHub previews required additional setup and troubleshooting.

Package Installation and Environment Setup:
Setting up the Python virtual environment with all required dependencies (such as nbformat, ipython, ipykernel, and kaleido) posed challenges due to version conflicts and installation errors.

How These Challenges Were Overcome:

To navigate these issues, I leveraged AI-assisted tools such as ChatGPT and GitHub Copilot extensively. These tools provided guidance on best coding practices, troubleshooting errors, and writing efficient data-cleaning and visualization scripts. Through iterative problem-solving and external help, I was able to streamline the data pipeline, ensure smooth plotting functionality, and maintain reproducibility.

## Conclusion and Next Steps

This project highlights the value of exploratory data analysis in uncovering patterns within insurance data. Future work could involve advanced statistical methods and predictive models to better estimate charges. Further data enrichment and feature engineering may also provide deeper insights.

## References

References
Pandas Documentation — for data manipulation and analysis:
https://pandas.pydata.org/docs/

Plotly Documentation — for creating interactive visualizations:
https://plotly.com/python/

Seaborn Documentation — for statistical data visualization:
https://seaborn.pydata.org/

Matplotlib Documentation — for static plotting:
https://matplotlib.org/stable/contents.html

ChatGPT by OpenAI — AI assistance in coding, debugging, and project guidance:
https://openai.com/chatgpt

GitHub Copilot — AI-powered code completion and suggestions:
https://github.com/features/copilot

Python Official Documentation — for language reference and modules:
https://docs.python.org/3/

Kaggle: Medical Insurance Dataset — source of healthcare insurance data used in this project:
https://www.kaggle.com/datasets/mirichoi0218/insurance