# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Insurance Charges Analysis Project

## Project Overview

This project analyses an insurance dataset to understand the factors influencing insurance charges. Key variables considered include age, gender, smoking status, BMI, and region. Using Python, I conducted exploratory data analysis employing scatter plots, box plots, and bar charts to uncover meaningful trends within the data.

## Data Cleaning

The original dataset required extensive cleaning prior to analysis. I utilised Python scripts executed via the terminal to preprocess the data, which involved handling missing values, encoding categorical variables, and verifying data consistency. This process proved challenging due to complex package dependencies and environment configuration issues, requiring multiple installations and troubleshooting. Fortunately, AI tools such as ChatGPT and GitHub Copilot provided invaluable assistance in guiding me through the coding and debugging phases. The final cleaned dataset was saved as `cleaned_insurance.csv`, ensuring a reproducible and organised workflow.

## Visualisations Conducted

- Scatter plot: Insurance charges plotted against age, colour-coded by smoking status.
- Box plot: Distribution of insurance charges across gender.
- Bar chart: Comparison of average insurance charges for smokers versus non-smokers.

## Insights and Findings

The analysis reveals that smokers incur significantly higher insurance costs, charges tend to increase with age, and there are observable differences in charges between genders. These findings shed light on the primary drivers of insurance charges and may inform pricing and risk management strategies.

## Challenges and Solutions

Throughout the project, several challenges arose that required persistence and problem-solving:

### Data Cleaning and Preparation

Initially, the dataset demanded comprehensive cleaning to enable accurate analysis. This process involved addressing missing data, performing categorical encoding, and ensuring overall data integrity. Conducting these steps through Python scripts in the terminal was at times complex and time-consuming.

### Plotting and Visualisation Issues

Rendering interactive Plotly visualisations posed difficulties, particularly when attempting to display them consistently across different environments such as Jupyter notebooks and GitHub. Rendering errors necessitated exporting static images for GitHub previews, which involved additional setup and troubleshooting.

### Package Installation and Environment Setup

Establishing the Python virtual environment with all requisite dependencies — including `nbformat`, `ipython`, `ipykernel`, and `kaleido` — presented challenges related to version conflicts and installation errors.

### How These Challenges Were Overcome

To overcome these obstacles, I relied extensively on AI-assisted tools like ChatGPT and GitHub Copilot. These resources offered guidance on best coding practices, error resolution, and efficient scripting for data cleaning and visualisation. Through iterative debugging and external support, I successfully streamlined the data pipeline, ensured smooth visualisation functionality, and maintained reproducibility.

## Day 2 Progress Update

### Project Check-ins and Roadblocks

- Regularly sought guidance via ChatGPT and Copilot to troubleshoot package installation, kernel issues, and visualisation rendering problems.
- Addressed issues preventing Plotly charts from displaying correctly on GitHub by implementing static image exports alongside interactive plots.
- Maintained workflow stability through frequent environment restarts and consistent data validation.

### Task Management and Tracking

- Organised the project into clear, manageable phases: data cleaning, exploratory visualisation, insight generation, and documentation.
- Ensured transparency of progress by documenting completed tasks and updating the Jupyter Notebook and README files accordingly.

### ETL Process Refinement

- Delivered a clean, validated dataset saved separately, ready for further analysis and visualisation.
- Incorporated data validation steps to maintain accuracy throughout the ETL pipeline.

## Conclusion and Next Steps

This project highlights the importance of exploratory data analysis in uncovering key patterns within insurance data. Future work could extend to implementing advanced statistical techniques and predictive models to improve charge estimation. Additional data enrichment and feature engineering may further enhance insight and support more robust pricing strategies.

## References

- [Pandas Documentation](https://pandas.pydata.org/docs/) — for data manipulation and analysis.
- [Plotly Documentation](https://plotly.com/python/) — for creating interactive visualisations.
- [Seaborn Documentation](https://seaborn.pydata.org/) — for statistical data visualisation.
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html) — for static plotting.
- [ChatGPT by OpenAI](https://openai.com/chatgpt) — AI assistance with coding, debugging, and project guidance.
- [GitHub Copilot](https://github.com/features/copilot) — AI-powered code completion and suggestions.
- [Python Official Documentation](https://docs.python.org/3/) — language reference and modules.
- [Kaggle: Medical Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) — source of healthcare insurance data used in this project.

