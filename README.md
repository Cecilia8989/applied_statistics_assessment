
# Applied Statistics Assignment - Higher Diploma in Science in Computing (Data Analytics)

This repository contains the solution to the Applied Statistics assignment for the course *Higher Diploma in Science in Computing (Data Analytics)*, delivered by the Applied Technology Unit (ATU) of Galway. The assignment consists of multiple tasks related to statistical analysis, implemented using Python and Jupyter Notebooks.

## Repository Structure

- `task1.ipynb` - Jupyter notebook for Task 1: **Permutations and Combinations**
- `task2.ipynb` - Jupyter notebook for Task 2: **Numpy's Normal Distribution**
- `task3.ipynb` - Jupyter notebook for Task 3: **t-Test Calculation**
- `task4.ipynb` - Jupyter notebook for Task 4: **ANOVA**
- `project.ipynb` - Jupyter notebook for the **project**, which involves analyzing the *PlantGrowth* dataset
- `data/` - Folder containing the dataset used in the final project
- `img/` - Folder containing images referenced in the Jupyter notebooks (such as plots or charts)
- `requirements.txt` - Text file listing the Python packages required to run the notebooks
- `.gitignore` - A standard Git ignore file to exclude unnecessary files from the repository

## Overview

### Task 1: Permutations and Combinations

This task involves calculating the probability that a person, who claims to have the ability to identify which cups of tea had the milk poured first, selects the correct six cups. We also explore the probability of selecting at most one error when guessing which cups contained milk. The task provides an opportunity to apply combinatorial analysis and probability theory to a real-world scenario.

### Task 2: Numpy's Normal Distribution

In this task, we assess the functionality of `numpy.random.normal()` by generating a sample of 100,000 values. We then use statistical tests, such as the Shapiro-Wilk test, to check if the sample follows a normal distribution. Additionally, a histogram is plotted alongside the theoretical normal distribution.

### Task 3: t-Test Calculation

Here, we calculate the t-statistic for a dataset containing the resting heart rates of patients before and after a two-week exercise program. We compare the manually calculated t-statistic to the value provided by the `scipy.stats` library and explain the results in detail.

### Task 4: ANOVA

In this task, we simulate three samples using `numpy.random.normal()` and perform a one-way ANOVA test to determine whether there are significant differences between the three groups. We also assess the occurrence of Type II errors by repeating the test 10,000 times. The results of the simulation and an explanation of the findings are provided.

### Final Project: PlantGrowth Dataset Analysis

For the final project, the *PlantGrowth* dataset (from the `Rdatasets` repository) is analyzed. The dataset contains plant weights grouped by different treatment groups. The analysis includes performing t-tests to compare the means of two treatment groups and conducting an ANOVA test to compare the means of three treatment groups. The project explains the assumptions of t-tests and ANOVA, the reasoning for using ANOVA when comparing more than two groups, and interprets the results of the statistical tests.

## Requirements

To run the notebooks, you will need the following Python libraries:

- `numpy`
- `scipy`
- `matplotlib`
- `pandas`
- `seaborn`

You can install the required dependencies by running:

```bash
pip install -r requirements.txt
>>>>>>> 32ed2397b7dfdb463c7ec9de66a1d6554a759b16
