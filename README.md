# Assignment_hypothesis_test description:
To investigate the restaurant owners' claim about the increase in weekly operating costs using hypothesis testing. Data Provided:

• The theoretical weekly operating cost model: W =  1,000+
 5X

• Sample of 25 restaurants with a mean weekly cost of Rs. 3,050

• Number of units produced in a week (X) follows a normal distribution with a mean (μ) of 600 units and a standard deviation (σ) of 25 units

### Hypothesis Testing

Hypothesis testing is a statistical method used to make inferences or draw conclusions about a population based on a sample of data. It involves making a claim or hypothesis about a population parameter and then using sample data to assess the validity of that hypothesis.

### Key Concepts

1. **Null Hypothesis (H₀):** The default assumption or statement that there is no effect or no difference. It is what you aim to test against.
2. **Alternative Hypothesis (H₁ or Ha):** The statement that there is an effect or a difference. It is what you want to prove.
3. **P-value:** The probability of obtaining test results at least as extreme as the observed data, assuming the null hypothesis is true.
4. **Significance Level (α):** A threshold for determining whether to reject the null hypothesis, commonly set at 0.05 or 0.01.
5. **Test Statistic:** A standardized value used to determine the p-value. It depends on the type of test being performed.

### Types of Hypothesis Tests

1. **Z-Test**
   - **Purpose:** Used to determine if there is a significant difference between sample and population means or between two sample means, assuming the sample size is large (n > 30) or the population variance is known.
   - **When to Use:** When comparing sample means to a population mean or comparing two independent samples.
   - **Example:** Testing if the average height of students in a class is different from the national average height.

2. **T-Test**
   - **Types:** 
     - **One-Sample T-Test:** Tests if the sample mean is significantly different from a known population mean.
     - **Independent Samples T-Test:** Tests if the means of two independent samples are significantly different.
     - **Paired Sample T-Test:** Tests if the means of two related groups (e.g., before and after treatment) are significantly different.
   - **When to Use:** When the sample size is small (n < 30) and the population variance is unknown.
   - **Example:** Testing if a new drug reduces blood pressure by comparing patients' blood pressure before and after treatment.

3. **Chi-Square Test**
   - **Types:**
     - **Chi-Square Test for Independence:** Tests if there is a significant association between two categorical variables.
     - **Chi-Square Goodness of Fit Test:** Tests if a sample distribution fits an expected distribution.
   - **When to Use:** When dealing with categorical data.
   - **Example:** Testing if there is an association between gender and voting preference.

4. **ANOVA (Analysis of Variance)**
   - **Purpose:** Tests if there are significant differences between the means of three or more independent groups.
   - **When to Use:** When comparing means across multiple groups.
   - **Example:** Testing if different teaching methods lead to different student performance levels.

5. **F-Test**
   - **Purpose:** Compares two population variances to determine if they are significantly different.
   - **When to Use:** When comparing the variances of two samples.
   - **Example:** Testing if the variability in test scores is different between two schools.

### When to Use Hypothesis Testing

- **Comparing Means:** To compare the means of two or more groups (e.g., control vs. treatment group).
- **Assessing Relationships:** To determine if there is a relationship or association between variables (e.g., correlation between hours studied and test scores).
- **Testing Proportions:** To compare proportions between groups (e.g., success rates of two different marketing campaigns).
- **Model Validation:** To test the assumptions and validity of statistical models.

### Advantages of Hypothesis Testing

1. **Decision-Making:** Provides a structured framework for making data-driven decisions.
2. **Objectivity:** Offers an objective method for evaluating evidence against a null hypothesis.
3. **Error Control:** Controls the probability of making Type I (false positive) and Type II (false negative) errors.
4. **Statistical Significance:** Helps determine the statistical significance of results, which is crucial in research and scientific studies.

### Disadvantages of Hypothesis Testing

1. **Dependence on Sample Size:** Results can be heavily influenced by sample size; large samples can detect trivial differences as significant.
2. **P-Hacking:** Researchers may manipulate data or experiment design to achieve statistically significant results.
3. **Binary Decision:** Provides a yes/no answer without indicating the magnitude of the effect or its practical significance.
4. **Misinterpretation:** P-values are often misinterpreted, leading to incorrect conclusions about the data.
5. **Assumption Sensitivity:** Many hypothesis tests assume normality and homogeneity of variance, which may not hold true in real-world data.
