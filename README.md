### Bayesian Optimization
https://medium.com/data-science/bayesian-optimization-concept-explained-in-layman-terms-1d2bcdeaf12f

### The Logic Behind Each Test in Feature Selection
| Test                              | When Used in ML                      | Type of Feature           | Type of Target  | What It Checks                               |
| --------------------------------- | ------------------------------------ | ------------------------- | --------------- | -------------------------------------------- |
| **Chi-Square**                    | Classification (categorical target)  | **Categorical**           | **Categorical** | Association between feature and target       |
| **ANOVA (f\_classif)**            | Classification                       | **Numerical**             | **Categorical** | Whether means differ across classes          |
| **Mutual Info (MI)**              | Classification or Regression         | Categorical or Continuous | Any             | Measures general dependence                  |
| **Correlation (Pearson)**         | Regression                           | **Numerical**             | **Numerical**   | Linear relationship                          |
| **Kruskal-Wallis / Mann-Whitney** | Non-parametric alternatives to ANOVA | Numerical                 | Categorical     | Group differences when normality is violated |
