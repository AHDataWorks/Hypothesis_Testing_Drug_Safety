# Hypothesis Testing in Healthcare: Drug Safety Analysis
## Project Overview
This project focuses on conducting hypothesis testing within the healthcare sector, particularly analyzing drug safety. Utilizing a dataset of patient responses to a specific drug, the project applies statistical analysis to assess the drug's safety profile. The analysis is documented in a Jupyter notebook titled "Hypothesis Testing in Healthcare: Drug Safety," which outlines the step-by-step process of preparing data, conducting statistical tests, and interpreting results.

## Dataset Description
The drug_safety.csv file contains patient data collected during a drug safety study, including:

```age```: Age of the patient.

```sex```: Sex of the patient (male/female).

```trx```: Treatment group, indicating whether the patient received the drug or a placebo.

```week```: The week of the study in which data was collected.

```wbc```: White blood cell count per microliter of blood.

```rbc```: Red blood cell count in millions per microliter.

```adverse_effects```: Indicates whether any adverse effects were reported (Yes/No).

```num_effects```: Number of adverse effects reported.


This dataset serves as the basis for our statistical analysis, aiming to identify any significant safety concerns associated with the drug.

## Notebook Structure
The Jupyter notebook is structured into several main sections:

- Preliminary Setup: Initial configuration steps, including importing necessary Python libraries and loading the dataset.
- Data Preparation and Analysis: Cleaning and preparing the data for analysis. This includes handling missing values and summarizing key characteristics of the dataset.
- Statistical Analysis and Visualization: Conducting statistical tests to compare outcomes between treatment groups and visualizing the results.
- Normality Testing: Assessing the distribution of the data to ensure the validity of statistical tests.
- Final Analysis Steps: Age Data Selection and Non-parametric Testing: Applying non-parametric tests to subsets of the data, focusing on age-related effects.
- Understanding the P-value: A detailed explanation of the p-value concept and its importance in hypothesis testing.

## Getting Started
To run this analysis you'll need the following dependencies:

- pandas: For data manipulation and analysis.
- numpy: For numerical computing.
- scipy: For scientific computing, including statistical analysis.
- matplotlib: For data visualization.
- jupyterlab: An interactive development environment for working with Jupyter notebooks.

You can install all the necessary dependencies by running the following command in your terminal or command prompt:

```
pip install pandas numpy scipy matplotlib jupyterlab
```


## License

MIT License


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) 2024 AHData_Works
