# Diagnosing Underpowered Studies and P-Hacking

## Objective
In this lab, I looked at how small sample sizes and multiple tests can lead to misleading results.

## Methodology
- Used t-tests and power analysis to check whether the sample size was large enough.
- Calculated the sample size needed for 80% statistical power.
- Applied BH correction to 20 p-values.
- Ran 1,000 simulations to check the chance of false positives.
- Compared regular t-tests, trimmed t-tests, and permutation tests.

## Key Findings
In Diagnosis 1, the original study had only 10.9% power with 15 people per group. I found that 222 people per group were needed, and the new study showed a significant result (p = 0.0012).

In Diagnosis 2, none of the 20 groups remained significant after BH correction. The theoretical chance of at least one false positive was 64.2%, and my simulation showed 65.8%.

In the extension, the regular mean-based tests were not significant (p = 0.2650 and 0.3496), while the trimmed mean tests were significant (p = 0.0066 and 0.0056). This showed me how outliers can affect the results.
