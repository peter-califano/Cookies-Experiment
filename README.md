# Cookies-Experiment
Experiment examining the effects of chemical leaveners on cookie diameter and height. Showcasing experiment design and R for statistical analysis.

## Project Overview
This experiment investigates the impact of different chemical leaveners—baking soda, double-acting baking powder, and no leavener (control)—on the physical properties of chocolate chip cookies. By analyzing the cookies' height and diameter, we aimed to better understand the science behind leavening and its influence on baking outcomes.

## Objective
To determine how different leaveners affect the size and shape of cookies, providing insights into their role in baking. The study focuses on:
- Comparing the effects of baking soda, baking powder, and no leavener.
- Quantifying differences in cookie height and diameter using statistical analysis.

## Technologies Used
- **R**: Statistical analysis and data visualization.
- **Excel**: Initial data entry and organization.

## Methodology
1. **Experimental Setup**:
   - Prepared three batches of cookie dough: one with baking soda, one with double-acting baking powder, and one control batch with no leavener.
   - Controlled for confounding variables such as ingredient weight, mixing times, oven temperature, and dough ball sizes.

2. **Data Collection**:
   - Measured cookie height (in mm) and diameter (in mm) for each batch.
   - Recorded data in Excel for further analysis.

3. **Data Analysis**:
   - Conducted statistical analyses using R:
     - ANOVA to evaluate significant differences between treatments.
     - Pairwise t-tests with Bonferroni correction for multiple comparisons.
   - Visualized results with R-generated plots.

## Key Results
- **Height**:
  - Baking powder produced the tallest cookies (17.28 mm on average).
  - Baking soda resulted in the shortest cookies (13.85 mm on average).
  - Control cookies were intermediate (16.80 mm on average).

- **Diameter**:
  - Baking soda cookies were the widest (66.70 mm on average).
  - Baking powder cookies had the smallest diameter (59.57 mm on average).
  - Control cookies were in between (60.55 mm on average).

- ANOVA and pairwise comparisons confirmed significant differences in height and diameter between some treatments.


## Findings
1. Baking soda cookies were shorter and wider, likely due to the increased pH slowing protein coagulation during baking.
2. Baking powder and control cookies were similar in height and diameter, possibly due to insufficient water in the dough to activate the baking powder.
3. Future experiments could explore the effects of leaveners in higher-moisture baked goods like cakes or breads.
