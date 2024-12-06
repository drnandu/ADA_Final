Titile of the stdy: Examining Racial and Socioeconomic Disparities in Oral Cancer Staging: Insights from a Cross-Sectional SEER Study

Description
This project explores the association between late-stage oral squamous cell carcinoma (OSCC) diagnoses and racial, socioeconomic, and demographic disparities in the United States. Using data from the SEER (Surveillance, Epidemiology, and End Results) database for the period 2010–2020, the analysis evaluates predictors of late-stage diagnosis, including race/ethnicity, income, gender, and marital status. The study aims to address gaps in understanding how social determinants impact the timing of OSCC diagnosis, with implications for targeted interventions and policymaking to reduce disparities.
Features
•	Comprehensive Analysis: Includes data wrangling, visualization, and statistical modeling steps in a reproducible R Markdown file.
•	Multiple Imputation: Utilizes the mice package to handle missing data for robust analysis.
•	Advanced Modeling: Applies logistic regression and random forest models to evaluate predictors and compare their predictive accuracy.
•	DAG Visualization: Includes Directed Acyclic Graph (DAG) for conceptualizing the relationships between variables.
•	Interactive Visualizations: Offers plots showing relationships between gender, race, and late-stage diagnoses.

Contents
•	oscc.seer2.Rmd: R Markdown file containing all code, analyses, and visualizations.
•	README.md: This guide to understanding and reproducing the project.
•	LICENSE: Licensing information.
•	Figures: Histogram, Box plot, Directory containing DAGs, forest plots, and other visualizations generated during the analysis.

Requirements
To reproduce the analysis, ensure you have the following:
Software
•	R: Version 4.4.1 or higher
•	RStudio
R Packages (loaded via pacman):
•	tidyverse: For data manipulation and visualization
•	readr: For reading tabular data
•	naniar, VIM: For exploring and handling missing data
•	mice, lattice: For multiple imputation
•	table1: For creating descriptive tables
•	DiagrammeR, rsvg: For DAG visualization
•	dplyr: For data wrangling
•	car: For regression diagnostics
•	pROC: For plotting and analyzing ROC curves

Usage
1.	Clone the repository:
bash
Copy code
git clone https://github.com/drnandu/Oral_Cancer_Disparities_Analysis 
Open the R Markdown file: Open oscc.seer2.Rmd in RStudio.
2.	Run the analysis:
o	Click the "Knit" button to generate an HTML or PDF report of the analysis and results.
o	Alternatively, execute code chunks interactively to explore the workflow.
3.	View Results:
o	Includes logistic regression and random forest modeling results.
o	Visualizations of racial and demographic disparities in late-stage OSCC diagnosis.

Results
Key Findings:
•	Non-Hispanic Black populations are at significantly higher odds of late-stage diagnosis compared to Non-Hispanic White populations.
•	Socioeconomic factors, including income, are strongly associated with diagnostic delays.
•	Random forest models demonstrated better accuracy compared to logistic regression, highlighting potential non-linear interactions.
Implications:
•	Findings warrants the need for targeted interventions to improve early detection in marginalized communities especially Non-Hispanic Black.
•	Results can inform healthcare policies aimed at reducing racial and socioeconomic disparities in oral cancer outcomes.
By conducting a rigorous analysis of SEER data, this study sheds light on critical factors affecting late-stage OSCC diagnoses, paving the way for meaningful public health initiatives.

