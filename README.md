# ab-testing-website-background-impact
## **Overview**
A/B testing analysis comparing white vs black website backgrounds to determine impact on user engagement and conversion rates for a UK-based retail website. 

*Note: Analysis performed on synthetic data for demonstration purposes.*
## **Key Findings**
- Conversion rate increased from 5.4% to 14.1% with black background
- No significant impact on page views or time spent on site
- Consistent positive effect across all user segments (device, location)
- Medium effect size (Cohen's h = 0.30) indicates practical significance
## **Dataset**
- Source: [Kaggle A/B Testing Practice Dataset](https://www.kaggle.com/datasets/adarsh0806/ab-testing-practice) 
- Size: 5,000 users across the UK
- Type: Synthetic dataset (not real user data)
## **Technologies**
- Python, Pandas, NumPy
- Statistical Testing (Z-test, Mann-Whitney U)
- Matplotlib, Seaborn
- SciPy, Statsmodels
## **Business Impact**
- 8.67 percentage point improvement in conversion rate
- Number needed to expose: 12 users for 1 additional conversion
## **How to Run**
1. Clone repository
2. Install: pip install pandas numpy matplotlib seaborn scipy statsmodels
3. Run ab_testing_analysis.ipynb
