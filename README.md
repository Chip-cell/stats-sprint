# Stats Sprint

Interactive revision site for **Business Statistics for Entrepreneurs** (IIM Bangalore),
covering all three courses — BS1, BS2 and BS3.

92 lessons of condensed notes and **284 practice questions**, every one with worked
solutions. Each lesson opens with a plain-language explanation before any formula
appears, and every lesson carries at least one worked example.

## Business Statistics 1 — 70 questions

Papers of 1 February and 29 March 2026.

1. **Descriptive Statistics** — data types and scales, charts, centre, position, spread,
   z-scores and outliers
2. **Probability** — addition and multiplication laws, conditional probability,
   independence, two-way tables, Bayes
3. **Random Variables & Discrete Distributions** — probability tables, expectation and
   variance, linear combinations, Bernoulli, Binomial, Poisson
4. **Continuous Distributions** — Uniform, Exponential, Normal, normal approximation

## Business Statistics 2 — 147 questions

The 24 May 2026 paper plus the September 2026 quiz bank.

1. **Distributions Related to Normal** — linear combinations, correlated combinations,
   inverse normal, chi-square, Student's t, F, reading the tables
2. **Sampling & Sampling Distributions** — sampling process and methods, point
   estimation, standard error, the Central Limit Theorem, sampling distribution of a
   proportion, distribution of the sample variance
3. **Confidence Intervals & Estimation** — estimator properties, sampling vs
   non-sampling error, intervals for a mean, proportion and variance, sample size
4. **Hypothesis Testing** — H0 and Ha, Type 1 and Type 2 errors, p-values, tests for
   mean, proportion and variance, covariance and correlation

## Business Statistics 3 — 67 questions

1. **ANOVA & Chi-squared Tests** — one-way ANOVA, sums of squares, the F-test, post-hoc
   analysis, goodness-of-fit for multinomial, binomial, normal and exponential data,
   covariance and correlation
2. **Simple Linear Regression** — the model, OLS, R², the t- and F-tests, residual
   diagnostics, outliers and influential observations
3. **Multiple Linear Regression 1** — partial coefficients, adjusted R², overall vs
   individual tests, multicollinearity, omitted variable bias
4. **Multiple Linear Regression 2** — dummy variables and the (k-1) rule, parallel
   regressions, interaction terms and moderation

## Features

- Formulas badged GIVEN / DERIVED / NOT GIVEN so you know what has to be memorised
- Worked solutions on every question; the interval-option papers also show an
  answer-band strip marking where the computed value falls
- **Mock exam** — 35 mixed questions on a 60-minute timer, with question palette,
  flagging and a graded review naming your weakest topics. Whole papers can also be
  sat individually
- **Model-picker drill** — real question stems with the arithmetic stripped out
- **57 formula flashcards** — anything you flag comes back until it sticks
- **Calculators** — binomial, Poisson (with rate conversion), normal, exponential,
  uniform, and descriptive statistics from pasted data
- **Reference tables** — full formula sheet, Z table, t and chi-square critical values
- Progress saved in the browser, light and dark themes, search across everything

## A note on one answer

Of the 90 questions taken from the three exam papers, 89 match the official keys. The
exception is May 2026 Q1, the chi-square p-value: the alternative hypothesis is
sigma-squared > 20, an upper-tail test, so the p-value is 0.4430 (`CHISQ.DIST.RT`).
The official key marks the 0.50-0.75 band, which is the left tail, 0.5570
(`CHISQ.DIST`). Both readings lead to the same decision — do not reject H0 — and the
question carries a flag in the app showing both.

## Running it

One self-contained file. Open `index.html` in a browser, or serve the folder with any
static host. Live at https://chip-cell.github.io/stats-sprint/
