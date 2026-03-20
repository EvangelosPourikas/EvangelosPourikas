# Hi, I'm Evangelos Pourikas 👋

## About Me

I am an MSc student in Applied Social Data Science at the London School of Economics (LSE), with a BSc in Criminology & Data Analytics from City, University of London. I'm extremely passionate about using quantitative methods and computational tools to make sense of complex social problems, while I also hold an interest in understanding current industry markets and how data driven findings can alter business decision-making.

## What I Work With

- **Languages:** Python, R, SQL
- **Tools & Platforms:** GitHub, SPSS, MS Excel
- **Methods:** Logistic & Linear Regression, Statistical Modelling, Survey Data Analysis, Causal Inference
- **Currently Learning:** Machine Learning, Deep Learning, NLP, Advanced Computational Methods

## Research Interests

- Quantitative social research and policy evaluation
- Labour market analysis and household economics
- Applying machine learning to large-scale social survey data
- Data-driven approaches to criminology and justice

## Featured Work

- **MSc Dissertation (In Progress):** The Causal Effect of Breadwinning Transitions on General Gender Attitudes – A UK Spousal Household Study
- **BSc Dissertation (75%):** Investigated how income contribution patterns affect household satisfaction among UK families using logistic and linear regression on the Understanding Society dataset
- **European Union Project – ICF:** Co-authored in a successful (chapter) Erasmus+ project worth over £2 million.

## Let's Connect

- 📧 evangelospourikas@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/evangelos-pourikas/)

---

## Quantitative Social Research

### Project: Household Income Contribution & Satisfaction Among UK Parents

**[GitHub Repository](https://github.com/EvangelosPourikas/Income-Contribution-to-Satisfaction-with-Household-Income)** | **[Full Documentation](https://github.com/EvangelosPourikas/Income-Contribution-to-Satisfaction-with-Household-Income/blob/main/README.md)**

**The Question**

Do dual-earner households report lower satisfaction with their income than single-earner ones? And does being a mother or father change this? Despite wide research on household dynamics, this specific relationship had barely been examined in the UK.

**The Approach**

Using Wave 14 (2023/2024) of the Understanding Society dataset (~40,000 UK households), I filtered to couple households with children under 16 and built a binary logistic regression model controlling for gender, general health, job status, household income, and housework hours. This was preceded by extensive bivariate analysis including chi-square tests, Cramér's V, correlations, and three-way crosstabulations. The analysis was originally conducted in SPSS and has been fully recreated in Python (Jupyter Notebook) for reproducibility.

**Key Findings**

- **Non-contributors and full contributors** to household income are the most satisfied — dual-earner households where both partners contribute partially report the lowest satisfaction.
- **Fathers are 35% more likely** to report dissatisfaction compared to mothers, likely driven by breadwinning social norms.
- **Mothers contributing 75%+** of household income show the highest rates of complete dissatisfaction — the opposite pattern to fathers.
- **General health** emerged as the strongest predictor: individuals in poor health were **173% more likely** to be dissatisfied, even after controlling for income and employment.
- These findings **contradict** a similar Czech study (Mysíková, 2016) which found no significant effects among parents — demonstrating that UK households behave differently.

![Contribution to Household Income by Satisfaction](https://github.com/EvangelosPourikas/Income-Contribution-to-Satisfaction-with-Household-Income/blob/main/outputs/figures/pct_contributed_cat_by_satisfaction.png?raw=true)

**Tools:** SPSS · Python (pandas, SciPy, statsmodels, matplotlib, seaborn) · Chi-Square Tests · Cramér's V · Binary Logistic Regression

👉 **[View full project, syntax, and documentation →](https://github.com/EvangelosPourikas/Income-Contribution-to-Satisfaction-with-Household-Income)**
