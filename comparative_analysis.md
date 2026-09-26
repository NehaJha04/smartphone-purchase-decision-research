# Comparative Analysis

## Purpose

The comparative analysis examines whether consumer characteristics and purchasing behavior vary across different consumer groups.

The analysis focuses on relationships identified in the research questions and hypotheses.

The dataset contains **220 synthetic respondents**. Therefore, the results presented in this analysis demonstrate the analytical methodology and should not be interpreted as evidence of actual consumer behavior.

---

# Analysis 1 — Age and Smartphone Brand Preference

## Research Question

**Does smartphone brand preference differ across age groups?**

## Variables

* Age group
* Current smartphone brand

## Method

A cross-tabulation was used to examine the distribution of current smartphone brands across age groups.

A **Chi-square test of independence** was then conducted to determine whether age group and current smartphone brand were statistically associated.

## Statistical Result

* Chi-square statistic: **36.464**
* Degrees of freedom: **36**
* p-value: **0.447**
* Significance level: **0.05**

## Interpretation

The p-value is greater than 0.05. Therefore, the analysis does not provide statistically significant evidence of an association between age group and current smartphone brand preference in the synthetic dataset.

Although the distribution of brands varies across age groups descriptively, these differences are not statistically significant based on the Chi-square test.

## Hypothesis Result

**H2 was not supported in the synthetic dataset.**

The result suggests that age group and current smartphone brand preference do not show a statistically significant relationship in this simulated sample.

---

# Analysis 2 — Income and Price Sensitivity

## Research Question

**Is income level associated with consumers' sensitivity to smartphone price?**

## Variables

* Monthly income
* Price statement agreement
* Likelihood of choosing a less expensive smartphone

## Method

Mean price-sensitivity scores were compared across income groups.

A Chi-square test was also conducted between monthly income and categorical price-statement responses.

## Mean Price-Sensitivity Scores

| Monthly Income      | Price Statement Agreement | Less Expensive Choice Likelihood |
| ------------------- | ------------------------: | -------------------------------: |
| Below ₹25,000       |                      3.26 |                             3.58 |
| No personal income  |                      3.35 |                             3.65 |
| Prefer not to say   |                      3.33 |                             3.33 |
| ₹1,00,000–₹1,49,999 |                      3.14 |                             3.19 |
| ₹1,50,000 or above  |                      3.50 |                             3.50 |
| ₹25,000–₹49,999     |                      3.05 |                             3.13 |
| ₹50,000–₹74,999     |                      3.22 |                             3.49 |
| ₹75,000–₹99,999     |                      2.86 |                             3.41 |

## Statistical Result

For the relationship between income and price-statement agreement:

* Chi-square statistic: **24.981**
* Degrees of freedom: **28**
* p-value: **0.629**
* Significance level: **0.05**

The relationship between income and likelihood of choosing a less expensive smartphone was also not statistically significant:

* Chi-square statistic: **27.761**
* Degrees of freedom: **28**
* p-value: **0.477**

## Interpretation

The p-values are greater than 0.05. Therefore, the analysis does not provide statistically significant evidence that income level is associated with the measured price-sensitivity variables in the synthetic dataset.

There are some descriptive differences between income groups, but these differences should not be interpreted as statistically established relationships.

## Hypothesis Result

**H3 was not supported in the synthetic dataset.**

---

# Analysis 3 — Smartphone Replacement Frequency and Product Priorities

## Research Question

**Do consumers with different smartphone replacement frequencies assign different levels of importance to smartphone attributes?**

## Variables

* Smartphone replacement frequency
* Smartphone purchase-factor importance scores

The analysis examined the following purchase attributes:

* Price
* Brand reputation
* Performance
* Camera
* Battery
* Storage
* Display
* Design
* Online reviews
* Recommendations
* Discounts
* After-sales service
* Connectivity
* AI features

## Method

Mean importance scores were compared across smartphone replacement-frequency groups.

A **one-way ANOVA** was conducted for each purchase attribute.

## Key Statistical Result

Most product attributes did not show statistically significant differences across replacement-frequency groups.

The strongest result was observed for **AI features**:

* F-statistic: **2.259**
* p-value: **0.0498**

The p-value is just below the 0.05 significance threshold.

For comparison:

| Purchase Attribute | F-statistic | p-value |
| ------------------ | ----------: | ------: |
| AI Features        |       2.259 |  0.0498 |
| Price              |       1.962 |  0.0855 |
| Performance        |       1.956 |  0.0865 |
| Discounts          |       1.472 |  0.2001 |
| Storage            |       1.113 |  0.3547 |

## Interpretation

The analysis provides exploratory evidence that the importance assigned to AI features differs across smartphone replacement-frequency groups in the synthetic dataset.

However, this result should be interpreted cautiously because multiple purchase attributes were tested separately. No multiple-comparison adjustment was applied to these exploratory ANOVA tests.

Therefore, the AI-feature result should be treated as an exploratory finding rather than definitive evidence.

## Hypothesis Result

**H5 received exploratory support at the 0.05 level through the AI-feature comparison.**

However, the finding should be validated using a larger real-world sample and appropriate multiple-comparison controls before drawing a firm conclusion.

---

# Analysis 4 — Current Smartphone Brand and Future Brand Preference

## Research Question

**Is current smartphone brand associated with the likelihood of considering the same brand for the next purchase?**

## Variables

* Current smartphone brand
* Future same-brand likelihood

## Method

A cross-tabulation was created between current smartphone brand and future same-brand likelihood.

A Chi-square test of independence was then conducted.

## Statistical Result

* Chi-square statistic: **31.548**
* Degrees of freedom: **36**
* p-value: **0.680**
* Significance level: **0.05**

## Descriptive Brand-Level Means

| Current Brand | Mean Future Same-Brand Likelihood |
| ------------- | --------------------------------: |
| Google Pixel  |                              3.71 |
| Vivo          |                              3.71 |
| Realme        |                              3.64 |
| OnePlus       |                              3.50 |
| Apple         |                              3.47 |
| Nothing       |                              3.21 |
| OPPO          |                              3.18 |
| Samsung       |                              3.13 |
| Motorola      |                              3.00 |
| Xiaomi        |                              2.87 |

These values represent descriptive averages in the synthetic dataset and should not be interpreted as a ranking of smartphone brands.

## Interpretation

The Chi-square p-value is greater than 0.05.

Therefore, the analysis does not provide statistically significant evidence of an association between current smartphone brand and future same-brand likelihood.

Although the descriptive averages differ between brands, the observed differences are not statistically significant based on the Chi-square test.

## Hypothesis Result

**H6 was not supported when operationalized as current smartphone brand versus future same-brand likelihood.**

---

# Analysis 5 — Brand Satisfaction and Future Brand Preference

## Research Question

**Does satisfaction with the current smartphone brand relate to the likelihood of purchasing the same brand again?**

## Variables

* Current brand satisfaction
* Future same-brand likelihood

## Method

Because both variables are measured on ordered scales, **Spearman rank correlation** was used to examine the relationship.

## Statistical Result

* Spearman correlation (ρ): **0.502**
* p-value: **< 0.001**
* Significance level: **0.05**

## Interpretation

The analysis identifies a statistically significant positive association between current brand satisfaction and future same-brand likelihood in the synthetic dataset.

In descriptive terms, respondents with higher satisfaction scores also tend to report a higher likelihood of considering the same brand for their next smartphone purchase.

However, correlation does not establish causation. The result indicates an association rather than proof that satisfaction directly causes future brand preference.

## Business Relevance

For a smartphone company, this type of relationship can be relevant to customer-retention strategies.

The result suggests that understanding and improving customer satisfaction may be useful when investigating repeat-purchase behavior and brand loyalty.

Because the dataset is synthetic, this implication should be treated as a demonstration of how such a relationship could be analyzed rather than as evidence of actual market behavior.

---

# Overall Statistical Summary

| Analysis                                   | Statistical Test     |               Test Result | p-value | Conclusion                       |
| ------------------------------------------ | -------------------- | ------------------------: | ------: | -------------------------------- |
| Age × Brand                                | Chi-square           |               χ² = 36.464 |   0.447 | Not significant                  |
| Income × Price Sensitivity                 | Chi-square           |               χ² = 24.981 |   0.629 | Not significant                  |
| Replacement Frequency × Product Priorities | ANOVA                | F = 2.259 for AI features |  0.0498 | Exploratory evidence             |
| Current Brand × Future Same Brand          | Chi-square           |               χ² = 31.548 |   0.680 | Not significant                  |
| Brand Satisfaction × Future Same Brand     | Spearman correlation |                 ρ = 0.502 |  <0.001 | Significant positive association |

---

# Key Findings

The comparative analysis of the synthetic dataset produced the following observations:

1. **Age group was not significantly associated with current smartphone brand preference.**

2. **Income level was not significantly associated with the measured price-sensitivity variables.**

3. **Replacement frequency showed an exploratory relationship with the importance assigned to AI features.**

4. **Current smartphone brand was not significantly associated with future same-brand purchase likelihood.**

5. **Current brand satisfaction showed a statistically significant positive association with future same-brand purchase likelihood.**

6. The statistical results demonstrate how market research data can be used to move beyond descriptive statistics and evaluate relationships between consumer characteristics and purchasing behavior.

---

# Research Interpretation

The analysis demonstrates an important distinction between **descriptive differences** and **statistically supported relationships**.

For example, different age groups may show different brand distributions, but a Chi-square test is required to determine whether the observed differences provide sufficient statistical evidence of an association.

Similarly, differences in average product-factor importance across consumer groups do not automatically indicate that the groups are statistically different.

The analysis therefore considers both:

* Descriptive patterns
* Statistical significance

Statistical significance should also be considered alongside practical business relevance.

---

# Limitations

The following limitations should be considered when interpreting these results:

### 1. Synthetic Dataset

The dataset contains simulated consumer responses and does not represent responses collected from actual consumers.

### 2. Sample Size

The analysis is based on 220 synthetic respondents. A larger real-world sample may produce different patterns and stronger statistical power.

### 3. Sampling

The research design proposes convenience sampling. Therefore, even a real-world implementation may not fully represent the entire smartphone consumer population.

### 4. Multiple Testing

Multiple product attributes were tested using separate ANOVA tests. No multiple-comparison correction was applied, so the AI-feature result should be treated as exploratory.

### 5. Association Does Not Mean Causation

The statistical tests identify associations between variables. They do not establish causal relationships.

### 6. Survey-Based Measurement

Several variables are based on self-reported Likert-scale responses. Actual purchasing behavior may differ from stated preferences.

---

# Conclusion

The comparative analysis demonstrates an end-to-end approach for evaluating consumer differences and relationships using survey data.

The analysis combines cross-tabulation, Chi-square testing, ANOVA, and Spearman correlation to investigate demographic differences, price sensitivity, product priorities, and brand loyalty.

The results illustrate how market research can progress from identifying descriptive patterns to testing whether observed relationships have statistical evidence.

Because the dataset is synthetic, the findings are intended to demonstrate the research and analytical methodology rather than represent actual smartphone consumer behavior.
