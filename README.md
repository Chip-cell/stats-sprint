# Stats Sprint

Interactive revision site for **Business Statistics for Entrepreneurs** (IIM Bangalore).

The four course modules condensed into notes, then 90 real past-paper questions from
the February, March and May 2026 papers — every answer recomputed from scratch rather
than copied from the answer key, and shown with its working.

## What is in it

- **Four course modules** — descriptive statistics, probability, random variables and
  discrete distributions, continuous distributions. Formulas are badged
  GIVEN / DERIVED / NOT GIVEN so you know what has to be memorised.
- **A separate Statistics II section** — sampling and confidence intervals, hypothesis
  testing. Not part of the four-module syllabus; it covers the May 2026 paper, whose
  header reads *Business Statistics for Entrepreneurs II*.
- **90 verified past-paper questions** with worked solutions and an answer-band strip
  showing where the computed value falls among the exam's interval options.
- **Mock exam** — 35 mixed questions, 60-minute timer, question palette and flagging,
  graded review that names your weakest topics.
- **Model-picker drill** — real question stems with the arithmetic stripped out; name
  the distribution the wording calls for.
- **37 formula flashcards** — anything you flag comes back until it sticks.
- **Calculators** — binomial, Poisson (with rate conversion), normal, exponential,
  uniform, and descriptive statistics from pasted data.
- **Reference tables** — full formula sheet, Z table, t and chi-square critical values.
- Progress saved in the browser, light and dark themes, search across everything.

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
