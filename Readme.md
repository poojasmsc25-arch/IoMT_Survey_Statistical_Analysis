# IoMT Survey Statistical Analysis

## Project Overview
This project performs descriptive and inferential statistical analysis of survey data related to Internet of Medical Things (IoMT) security and authentication.

The analysis examines respondent characteristics, knowledge scores, professional experience, and relationships between selected survey variables.

## Dataset
- File: `survey_cleaned.xlsx`
- Number of respondents: 100
- Format: Excel
- Sheets used: `Clean_readable` and `Encoded_for_analysis`

## Objectives
- Perform descriptive statistical analysis.
- Conduct inferential statistical tests.
- Analyze knowledge scores across professional-experience groups.
- Examine relationships using Spearman correlation.
- Develop visualizations using Matplotlib and Seaborn.

## Statistical Methods
1. Descriptive statistics
2. Kruskal–Wallis test
3. Spearman rank correlation
4. Dunn's post-hoc test with Bonferroni correction

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- scikit-posthocs
- openpyxl

## Project Structure
- `data/`: Survey dataset
- `notebooks/`: Jupyter Notebook containing analysis code
- `figures/`: Generated visualizations
- `results/`: Statistical results
- `README.md`: Project documentation
- `requirements.txt`: Python dependencies

## How to Run
1. Download or clone this repository.
2. Install the required Python libraries.
3. Open `notebooks/IoMT_Statistical_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Upload the dataset into the `data/` folder or the notebook environment.
5. Execute the notebook cells sequentially.

## Main Findings
- Mean knowledge score: approximately 5.17 out of 8.
- Kruskal–Wallis test: H = 12.4903, p = 0.005879.
- Spearman correlation: ρ = 0.3139, p = 0.001470.
- Dunn's post-hoc test identified a significant difference between the 1–3 years and 8 or more years experience groups.

## Reproducibility
The notebook contains the code, statistical calculations, and visualization steps used in the analysis. The requirements file lists the Python dependencies needed to reproduce the workflow.

## Limitations
The survey measures self-reported knowledge and perceptions. It does not directly measure the technical security or performance of IoMT authentication mechanisms.