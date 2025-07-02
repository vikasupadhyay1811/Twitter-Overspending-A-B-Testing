# Twitter-Overspending-A-B-Testing
How can Twitter effectively reduce overspending in ad campaigns, given the delay in click reporting that leads to exceeding advertiser budgets? Is the new ad product, which charges advertisers per impression instead of per click, successful in minimizing overspending compared to the existing click-based model, as demonstrated by the recent A/B test results.

📂 Dataset Description
The dataset contains 15,474 advertising campaigns with the following key features:

treatment: Billing model (True = Impression-based, False = Click-based)

company_size: Size of the advertiser (small, medium, large)

campaign_spend: Total amount spent on the campaign

campaign_budget: Budget allocated for the campaign

🛠️ Methodology
Exploratory Data Analysis (EDA)
T-Test to compare mean overspending percentages
One-Way ANOVA to assess company size impact
Chi-Square Test to check the association between billing model and overspending
Variance Comparison to evaluate consistency in spending behavior
Data Visualization using Matplotlib and Seaborn

📈 Key Findings
✅ Average Overspending Reduced: From 25.32% (control) to 17.61% (treatment)
✅ Statistically Significant: T-Test p-value = 2.53e-11
✅ Chi-Square Association: Billing model and overspending status significantly related (p-value = 1.70e-21)
✅ Company Size Impact: Significant difference in overspending patterns across company sizes (ANOVA p-value < 0.05)
✅ No Budget Manipulation Detected: No significant difference in campaign budgets between groups (p-value = 0.156)

🛠️ Tools & Technologies
Python
Pandas
Seaborn
Matplotlib
Scipy (stats module)

