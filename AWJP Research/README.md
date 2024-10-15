# AWJP Survey Data on Women and Journalism in Africa

## Introduction

This folder contains raw datasets from surveys conducted internally by the Africa Women Journalism Project (AWJP). These surveys aim to shed light on the experiences, challenges, and opportunities faced by women journalists across Africa.


## Surveys

The first report in this series, **"Gender, Journalism, and Power: Role of Women in Francophone African Newsrooms,"** explores the barriers women face when reporting on gender issues, the skill gaps they experience, and the systemic issues that hinder their advancement in the media industry. The data covers:
- **Challenges in the newsroom:** Identifying the structural, cultural, and social barriers women encounter in their professional environments.
- **Gender-specific reporting obstacles:** Exploring the difficulties women face when reporting on gender-related issues, including backlash or censorship.
- **Skill development needs:** Insights into the professional skills women journalists feel they need to better perform their roles and advance their careers.
- **Systemic barriers:** Understanding the organizational policies or practices that may limit women's contributions to journalism.


## How to Use the Data

1. **Download the Data:** You can download the raw data sets directly from this folder.
2. **Data Cleaning & Preparation:** The data is provided in raw format and may require cleaning before use. Tools for cleaning the data can be found in the `scripts/` folder.
3. **Data Analysis:** Use any statistical software or programming languages like Python, R, or SPSS for analysis. The data is structured to facilitate a variety of analyses including cross-tabulations, frequency distributions, and regression models.

### Example: Loading the Data in Python
```python
import pandas as pd

# Load the dataset
df = pd.read_csv('path/to/francophone_africa_women_journalists_survey.csv')

# Display the first few rows
print(df.head())
```

## Attribution and Licensing

Please ensure proper attribution to AWJP when using this dataset. The dataset is available under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/). You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may not use the material for commercial purposes.

## Contributing

If you wish to contribute additional datasets, analyses, or improvements to this folder, please follow our contribution guidelines available in the [CONTRIBUTING.md](https://github.com/AWJP/AWJP-data/blob/main/CONTRIBUTING.md) file.

## Contact Information

For more information on this dataset or any related questions, please contact us at [data@theawjp.org](mailto:data@theawjp.org). For more stories and reports on women journalists in Africa, visit our [website](https://theawjp.org/).
