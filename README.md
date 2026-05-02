### Developer Market Analysis

This project analyzes a global developer survey dataset to identify trends in employment, education, technical roles, and compensation. It provides actionable insights for a staffing agency to help a rapidly growing client hire qualified developers.

### Key Steps & Findings

#### 1. Data Cleaning & Imputation
- **High missing data** was removed from columns like `NEWJobHunt` (>80% missing).
- **Backward filling** was used to complete missing `UndergradMajor` data for respondents, leveraging more recent survey responses.
- **Multiple Imputation** (IterativeImputer) was applied to estimate missing `YearsCodePro` and `ConvertedComp` values based on their strong correlation.

#### 2. Employment & Developer Roles
- The vast majority of respondents are **employed full-time**, making the data highly relevant for hiring contexts.
- Dominant skill sets include **front-end, back-end, and full-stack development**. The market highly values developers proficient across major parts of the development lifecycle.

#### 3. Educational Background
- Most developers hold a **Computer Science** degree.
- There was a notable decline in CS majors over the surveyed years, suggesting that candidates from other academic backgrounds are successfully entering the development workforce.

#### 4. Experience vs. Compensation
- **Years of professional coding experience correlate positively with compensation.**
- More experienced developers earn higher average salaries, even though individual earners exist at all levels.

### Conclusion

The analysis provides the client with a clear understanding of:
- Global developer distribution.
- The rising presence of non-CS graduates in tech roles.
- The direct relationship between experience and expected compensation, helping to guide hiring and budgeting strategies.
