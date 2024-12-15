<h1 align="center">Applied Statistics  - Tasks and Project</h1>
<h1 align="center">Higher Diploma in Computer Science with Data Analytics</h1>
   <p align="center">
   Cecilia Pastore 

## Description

This repository contains the work required for the subject "Applied Statistics", part of the Higher Diploma in Computer Science with Data Analytics at Atlantic Technological University.

## Repository Structure

1. **tasks.ipynb**: A Jupyter notebook containing solutions to four tasks provided during lectures. These tasks cover various topics of interest discussed in the class.


### Task 1: Permutations and Combinations

This task involves calculating the probability that a person, who claims to have the ability to identify which cups of tea had the milk poured first, selects the correct six cups. We also explore the probability of selecting at most one error when guessing which cups contained milk. 

<details>
    <summary> Tasks Assignement </summary>
           <p>

</p>
</details>

### Task 2: Numpy's Normal Distribution

In this task, we assess the functionality of `numpy.random.normal()` by generating a sample of 100,000 values. We then use statistical tests, such as the Shapiro-Wilk test, to check if the sample follows a normal distribution. Additionally, a histogram is plotted alongside the theoretical normal distribution.

### Task 3: t-Test Calculation

Here, we calculate the t-statistic for a dataset containing the resting heart rates of patients before and after a two-week exercise program. We compare the manually calculated t-statistic to the value provided by the `scipy.stats` library and explain the results in detail.

### Task 4: ANOVA

In this task, we simulate three samples using `numpy.random.normal()` and perform a one-way ANOVA test to determine whether there are significant differences between the three groups. We also assess the occurrence of Type II errors by repeating the test 10,000 times.

### Project: PlantGrowth Dataset Analysis

For the project, the *PlantGrowth* dataset (from the `Rdatasets` repository) is analyzed. The analysis includes performing t-tests to compare the means of two treatment groups and conducting an ANOVA test to compare the means of three treatment groups. The project explains the assumptions of t-tests and ANOVA, the reasoning for using ANOVA when comparing more than two groups, and interprets the results of the statistical tests.

## Requirements

To run the notebooks, you will need the required Python libraries. These libraries are listed in the `requirements.txt` file in this repository. You can install all the necessary dependencies by running:

```bash
pip install -r requirements.txt
