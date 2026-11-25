
# 📊 Conversion Funnel Analysis and A/A/B Testing for a Food App

## 🎯 Project Objective

The objective of this project was to analyze user behavior in a food startup's mobile application and address the following business questions:

- How do users progress through the purchasing journey?
- How many users actually reach the purchase stage?
- How many users drop off during the previous stages, and where do these drop-offs occur?
- Evaluate the impact of a design change (font modification) through an A/A/B test, comparing control and test groups.

## 📈 Results

The analysis revealed that approximately **48% of users who access the main screen complete a purchase**.

The highest drop-off rate occurs between the main screen and the offers screen, with **38% of users leaving during this transition**.

The A/A/B test showed that changing the fonts did not significantly influence user behavior. Conversion rates ranged from **46.7% to 48.9%** across the groups, with no statistically significant differences (p-values > 0.05 after Bonferroni correction).

These findings suggest that the design change can be implemented for aesthetic reasons without a measurable negative impact on the analyzed conversion metrics.

## 🛠️ Tools & Technologies

- **Python Libraries:**
  - Pandas: Data manipulation and analysis.
  - NumPy: Numerical operations and array processing.
  - Matplotlib and Seaborn: Data visualization (bar charts and histograms).
  - Plotly: Interactive visualizations, including conversion funnel charts.
  - Statsmodels: Statistical testing (initially Z-tests).
  - SciPy: Fisher's Exact Test for proportions.

- **Technologies:**
  - Jupyter Notebook: Development and documentation environment.
  - Python: Main programming language for data analysis.

## 📚 Skills Developed

Through this project, I developed practical skills in:

- **Conversion Funnel Analysis:** Building and analyzing conversion funnels to identify bottlenecks in the user journey.
- **Statistical Experimentation:** Applying statistical tests to evaluate A/A/B experiments, including Bonferroni correction for multiple comparisons.
- **Data Preprocessing:** Manipulating temporal and categorical data, cleaning, and preparing datasets for analysis.
- **Data Visualization:** Communicating insights through clear and effective visualizations.
- **Statistical Interpretation:** Interpreting experimental results to support data-driven business decisions.

## 🚀 Future Improvements

- **Advanced Segmentation:** Analyzing the conversion funnel across different user segments (e.g., new vs. returning users) to generate more granular insights.
- **Cohort Analysis:** Evaluating user retention and behavioral patterns over time.
- **Additional Experiments:** Running A/B tests focused on the identified bottleneck (main screen → offers screen), testing variations in CTAs or layouts.
- **Integration with Additional Data Sources:** Incorporating CRM data or user feedback to enrich the analysis.
- **Automation:** Developing scripts for continuous monitoring of the conversion funnel after implementation.

---

**Project Focus:** Conversion Funnel Analysis | A/A/B Testing | Statistical Hypothesis Testing | User Behavior | Python | Pandas | Plotly | SciPy
