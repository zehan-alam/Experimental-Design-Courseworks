# Experimental Design | STAT 5080

**Bowling Green State University | Spring 2026**  
**Coursework Portfolio: Homework, Midterm & Final Examination**

This repository documents my work in **Experimental Design**, where I learned to move from choosing an appropriate experimental structure to estimating effects, checking model assumptions, and drawing defensible statistical conclusions. The homework assignments include collaborative submissions, while the midterm and final reflect my individual exam work. I used **R and R Markdown** for randomization, statistical modeling, diagnostic plots, hypothesis testing, and reproducible reporting.

## Homework Assignments

### Homework 1 — Statistical Inference and Hypothesis Testing

- **Concepts:** One-sample, independent two-sample (Welch), and paired *t*-tests; one-sided hypotheses; confidence intervals; independence; normality assessment; Shapiro–Wilk test.
- **What I did:** Tested a claim about the age of first-time insurance buyers, compared government and private-sector coffee-break times, and analyzed before-and-after sales for stores adopting online advertising. I matched each problem to its sampling structure, used R's `t.test()`, and checked assumptions with histograms, Q–Q plots, and formal tests.

### Homework 2 — Completely Randomized Designs and Estimability

- **Concepts:** Completely Randomized Design (CRD), random treatment allocation, randomized run order, nuisance variables, one-way ANOVA, effects/means models, estimable functions, and Best Linear Unbiased Estimators (BLUEs).
- **What I did:** Created a randomized assignment and execution order for 100 patients receiving four drugs; explained why soil-acidity measurements should be randomized; and compared circuit response times using descriptive graphs, ANOVA, treatment-mean estimates, and confidence intervals. I also evaluated estimability of treatment-effect combinations.

### Homework 4 — ANOVA, Contrasts, and Multiple Comparisons

- **Concepts:** One-way ANOVA; treatment contrasts; orthogonality; sums of squares; planned versus unplanned comparisons; Bonferroni, Scheffé, Dunnett, and Tukey procedures.
- **What I did:** Analyzed rat activity under two drugs and different dosages, constructed contrasts for control-versus-treatment, drug type, and dose effects, and evaluated their significance with appropriate family-wise error adjustments. I then designed meaningful contrasts for a placebo-controlled vitamin experiment and checked which were orthogonal.

### Homework 5 — Family-Wise Error and ANOVA Diagnostics

- **Concepts:** Holm's step-down procedure; Bonferroni adjustment; planned versus post-hoc contrasts; Scheffé's method; normality and homoscedasticity; Levene's and Bartlett's tests; power transformations; Kruskal–Wallis and permutation tests.
- **What I did:** Compared multiple-testing decisions for drug-treatment contrasts and showed how the timing of contrast selection affects statistical significance. For a seed-germination experiment, I examined residual and variance patterns, assessed ANOVA assumptions, and applied rank-based and permutation alternatives.

### Homework 6 — Power Analysis and Random-Effects Models

- **Concepts:** Chi-square confidence limits for error variance; power and sample-size calculations; noncentral *F* distributions; Bonferroni/Tukey interval precision; one-way random-effects ANOVA; expected mean squares (EMS); variance components and variance ratios.
- **What I did:** Determined sample sizes for a drug experiment under power and confidence-interval requirements. I analyzed differences among randomly sampled textile looms and filling-machine heads, estimated between-unit and residual variability, and worked through EMS-based inference for the random-effects model.

### Homework 7 — Randomized and Incomplete Block Designs

- **Concepts:** Randomized Complete Block Design (RCBD), replicated complete blocks, Incomplete Block Design (IBD), Balanced Incomplete Block Design (BIBD), block randomization, intrablock ANOVA, and Tukey comparisons.
- **What I did:** Used subjects as blocks when studying eye-focus time at different distances, separating subject variation from treatment effects. I generated treatment allocations for complete and incomplete blocks, verified BIBD conditions through replication and pair co-occurrence counts, and analyzed paper strength across hardwood concentrations while controlling for production day.

### Homework 8 — Two-Factor Experiments and Model Selection

- **Concepts:** Two-way factorial ANOVA; main effects and interactions; fixed, random, and mixed-effects models; EMS and variance components; Tukey/Bonferroni simultaneous intervals; precision- and power-based sample-size planning.
- **What I did:** Calculated replication requirements for two-factor experiments and compared multiple-comparison methods. In a copper-plate warping study, I tested temperature and copper-content effects, interpreted interactions, evaluated alternative effect assumptions, and identified the copper level associated with lower warping.

## Examinations

### Midterm — Integrated One-Way ANOVA and Experimental Planning

- **Concepts:** CRD and one-way ANOVA; Tukey HSD and Holm-adjusted pairwise tests; residual diagnostics; Shapiro–Wilk and Bartlett tests; Kruskal–Wallis; permutation inference; noncentral-*F* power analysis; random-effects ANOVA and variance components.
- **What I did:** Compared circuit designs on noise level and recommended a lower-noise design using graphical and adjusted inferential comparisons. For insulating fluids, I contrasted parametric, nonparametric, and permutation-based conclusions. I also planned sample sizes and assessed batch-to-batch variability using a random-effects model.

### Final — Advanced Blocking, Factorial, Mixed, and Nested Designs

- **Concepts:** Three-way mixed-effects models and exact *F*-tests; two-factor interactions and lack-of-fit tests; fixed/mixed ANOVA and EMS; Latin Square Design; BIBD and intrablock analysis; nested effects; blocking in factorial experiments; variance-component estimation and multiple comparisons.
- **What I did:** Worked through seven experimental settings: constructed a three-factor mixed-model ANOVA; modeled glass-type and temperature effects on light output; analyzed drill speed and feed rate; controlled batch and day effects with a Latin square; evaluated tire compounds with a BIBD; tested operators nested within machines; and analyzed chemical yield across temperature, pressure, and day blocks. I selected test denominators to match the design and used the models to support treatment recommendations.

## Key Takeaways

Through these assignments, I learned that experimental analysis starts **before** a statistical test: randomization, replication, blocking, and the choice of fixed versus random effects determine what can be estimated and how uncertainty should be quantified. Across the course, I practiced translating those design decisions into reproducible **R-based analysis**, assumption checks, multiplicity-adjusted inference, and interpretable conclusions.

## Assignment Questions and Submitted Solutions

The links below use **relative repository paths** so they work when the `questions/` and `solutions/` folders are uploaded alongside this README.

| Assessment | Question | Solution |
|:--|:--|:--|
| Homework 1 | [View question](questions/HW01.docx) | [View solution](solutions/HW01.pdf) |
| Homework 2 | [View question](questions/HW02.docx) | [View solution](solutions/HW02.pdf) |
| Homework 4 | [View question](questions/HW04.docx) | [View solution](solutions/HW04.pdf) |
| Homework 5 | [View question](questions/HW05.docx) | [View solution](solutions/HW05.pdf) |
| Homework 6 | [View question](questions/HW06.docx) | [View solution](solutions/HW06.pdf) |
| Homework 7 | [View question](questions/HW07.docx) | [View solution](solutions/HW07.pdf) |
| Homework 8 | [View question](questions/HW08.docx) | [View solution](solutions/HW08.pdf) |
| Midterm | [View question](questions/Midterm.docx) | [View solution](solutions/Midterm.pdf) |
| Final | [View question](questions/Final.docx) | [View solution](solutions/Final.pdf) |

*Note: Homework 3 is not included because its files were not provided.*
