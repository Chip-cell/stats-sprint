# Stats Sprint

Interactive revision site for **Business Statistics for Entrepreneurs** (IIM Bangalore),
covering both Business Statistics 1 and Business Statistics 2.

Condensed notes, then 90 real past-paper questions from the February, March and May
2026 papers — every answer recomputed from scratch rather than copied from the answer
key, and shown with its working.

## Business Statistics 1

Papers of 1 February and 29 March 2026, 70 questions across four modules:

1. **Descriptive Statistics** — data types and scales, charts, centre, position,
   spread, z-scores and outliers
2. **Probability** — addition and multiplication laws, conditional probability,
   independence, two-way tables, Bayes
3. **Random Variables & Discrete Distributions** — probability tables, expectation and
   variance, linear combinations, Bernoulli, Binomial, Poisson
4. **Continuous Distributions** — Uniform, Exponential, Normal, normal approximation

## Business Statistics 2

Paper of 24 May 2026, 20 questions, with its own module numbering:

1. **Sampling & Confidence Intervals** — standard error, t-intervals, proportion and
   variance intervals
2. **Hypothesis Testing** — H0 vs Ha, test statistics, critical values, p-values

## Features

- Formulas badged GIVEN / DERIVED / NOT GIVEN so you know what has to be memorised
- 90 verified questions with worked solutions and an answer-band strip showing where
  the computed value falls among the exam's interval options
- **Mock exam** — 35 mixed questions, 60-minute timer, question palette and flagging,
  graded review that names your weakest topics
- **Model-picker drill** — real question stems with the arithmetic stripped out; name
  the distribution the wording calls for
- **37 formula flashcards** — anything you flag comes back until it sticks
- **Calculators** — binomial, Poisson (with rate conversion), normal, exponential,
  uniform, and descriptive statistics from pasted data
- **Reference tables** — full formula sheet, Z table, t and chi-square critical values
- Progress saved in the browser, light and dark themes, search across everything

## A note on one answer

89 of the 90 answers match the official keys. The exception is May 2026 Q1, the
chi-square p-value: the alternative hypothesis is sigma-squared > 20, an upper-tail
test, so the p-value is 0.4430 (`CHISQ.DIST.RT`). The official key marks the
0.50-0.75 band, which is the left tail, 0.5570 (`CHISQ.DIST`). Both readings lead to
the same decision — do not reject H0 — and the question carries a flag in the app
showing both.

## Running it

One self-contained file. Open `index.html` in a browser, or serve the folder with any
static host. Live at https://chip-cell.github.io/stats-sprint/
