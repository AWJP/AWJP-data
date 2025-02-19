# The AWJP Data Repository

## Introduction

Welcome to the Africa Women Journalism Project (AWJP) Data Repository. This repository is dedicated to providing a comprehensive collection of datasets on various topics relevant to the mission of AWJP. Our goal is to support journalists, researchers, policy-makers, and activists by making data easily accessible to the public and other developers.

## About AWJP

The Africa Women Journalism Project (AWJP) is committed to promoting the role of African women journalists in reporting on underreported and underrepresented communities. We focus on issues such as gender-based violence, health, education, economic empowerment, and human rights. Through data, we aim to highlight critical areas of need and drive positive change across the continent, by empowering women journalists to tell these important stories.

## Repository Structure

This repository is organized into several main topics, each containing relevant datasets. Below is an overview of the structure:
- **AWJP Research**
  - Challenges of women journalists in francophone Africa in the newsroom and in their gender reporting role
- **Health & Well-being**
  - Covid-19
  - Mental Health
  - Child Health
  - Vaccines
  - Sexual & Reproductive Health
- **Education & Employment**
  - Education
  - Work
  - Employment & Wages
- **Governance & Policy**
  - Governance & Policy
  - Elections
  - Government Expenditure
  - Law & Justice
  - Police
  - Insecurity
- **Social Issues & Human Rights**
  - Demographics
  - Human Rights
  - Gender Equity
  - Tradition, religion and beliefs 
  - Sexual & Gender-based Violence (SGBV)
  - LGBTQ+
  - Female Genital Mutilation (FGM)
  - Child Marriage
  - Teenage Pregnancy
  - Refugees
  - Disability 
- **Environment & Economy**
  - Environment & Climate Change
  - Economy
  - Blue Economy
  - Water, Sanitation and Hygiene (WASH)
  - Poverty
  - Agriculture & Land
  - Food & Nutrition
  - Development 

  
Each topic folder contains the datasets, README files with detailed descriptions, and any relevant scripts or tools for data analysis.

## How to Use the Datasets

### Accessing the Data 

To access the datasets, navigate to the relevant topic folder. Each folder contains CSV files and a README file with detailed information, including the description of the sub-topics covered within each folder.

### Using the Data

1. **Download the Datasets:** You can download the datasets directly from the repository.
2. **Data Analysis:** Use the provided scripts in the `scripts/` folder or your preferred tools to analyze the data.
3. **Attribution:** Ensure you provide proper attribution to the data sources as specified within each CSV file.

### Example

```markdown
# Example Usage
# Importing a dataset using Python (Pandas)
import pandas as pd
# Load the dataset
df = pd.read_csv('path/to/your/dataset.csv')
# Display the first few rows
print(df.head())
```

## Contributing to the Repository

We welcome contributions to enhance the data and resources available in this repository. Please follow our contribution guidelines:
1. **Fork the Repository:** Create a personal fork of the repository.
2. **Clone the Fork:** Clone your fork to your local machine.
3. **Create a Branch:** Create a new branch for your changes.
4. **Make Changes:** Add your data or improvements.
5. **Submit a Pull Request:** Submit a pull request to merge your changes into the main repository.

For detailed instructions, please refer to our [CONTRIBUTING.md](CONTRIBUTING.md).

## Licensing and Attribution

The data produced by third parties and made available by AWJP is subject to the license terms from the original third-party authors. We always indicate the original source of the data in each CSV file, and you should always check the license of any such third-party data before use.

## Contact Information

For any questions or support, please open an issue on this repository or contact us at [data@theawjp.org](mailto:data@theawjp.org).

## Stay Connected

Stay updated with the latest news and updates from AWJP by visiting our [website](https://theawjp.org/) and following us on social media. Don't forget to read our Fellows' stories [here](https://theawjp.org/stories/).
