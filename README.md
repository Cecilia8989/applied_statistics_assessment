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
Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.

Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

Would you accept two errors? Explain.

</p>
</details>

### Task 2: Numpy's Normal Distribution

In this task, we assess the functionality of `numpy.random.normal()` by generating a sample of 100,000 values. We then use statistical tests, such as the Shapiro-Wilk test, to check if the sample follows a normal distribution. Additionally, a histogram is plotted alongside the theoretical normal distribution.

<details>
    <summary> Tasks Assignement </summary>
           <p>
              
In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.

Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.

Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.

</p>
</details>


### Task 3: t-Test Calculation

Here, we calculate the t-statistic for a dataset containing the resting heart rates of patients before and after a two-week exercise program. We compare the manually calculated t-statistic to the value provided by the `scipy.stats` library and explain the results in detail.

<details>
    <summary> Tasks Assignement </summary>
           <p>
              
>Consider the following dataset containing resting heart rates for patients before and after embarking on a two-week exercise program.


| Patient ID |  0  |  1  |  2  |  3  |  4  |  5  |  6  |  7  |  8  |  9  |
|------------|------|------|------|------|------|------|------|------|------|
| **Before** |  63  |  68  |  70  |  64  |  74  |  67  |  70  |  57  |  66  |  65  |
| **After**  |  64  |  64  |  68  |  64  |  73  |  70  |  72  |  54  |  61  |  63  |


Calculate the t-statistic based on this data set, using Python. Compare it to the value given by scipy.stats. Explain your work and list any sources used.

</p>
</details>

### Task 4: ANOVA

In this task, we simulate three samples using `numpy.random.normal()` and perform a one-way ANOVA test to determine whether there are significant differences between the three groups. We also assess the occurrence of Type II errors by repeating the test 10,000 times.


<details>
    <summary> Tasks Assignement </summary>
           <p>
              
In this test we will estimate the probability of committing a type II error in specific circumstances. To begin, create a variable called no_type_ii and set it to 0.

Now use a loop to perform the following test 10,000 times.

Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and the third a mean of 5.1.

Perform one-way anova on the three samples and add 1 to no_type_ii whenever a type II error occurs.

Summarize and explain your results.

</p>
</details>

### Project: PlantGrowth Dataset Analysis

For the project, the *PlantGrowth* dataset (from the `Rdatasets` repository) is analyzed. The analysis includes performing t-tests to compare the means of two treatment groups and conducting an ANOVA test to compare the means of three treatment groups. The project explains the assumptions of t-tests and ANOVA, the reasoning for using ANOVA when comparing more than two groups, and interprets the results of the statistical tests.

## Requirements

To run the notebooks, you will need the required Python libraries. These libraries are listed in the `requirements.txt` file in this repository. You can install all the necessary dependencies by running:

```bash
pip install -r requirements.txt
