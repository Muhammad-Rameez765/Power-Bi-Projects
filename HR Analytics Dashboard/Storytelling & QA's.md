## STORYTELLING

This HR Analytics dashboard tells the story of why employees leave, who is most at risk, and when attrition is most likely to happen.
Starting from raw HR data, I cleaned and structured the dataset, created business-driven DAX measures, and transformed the numbers into an interactive Power BI dashboard.

The analysis reveals that attrition is not random — it strongly increases among early-tenure employees, overtime workers, and those experiencing delayed promotions. Departments such as Sales and certain technical roles show consistently higher attrition, while employees with higher satisfaction and performance tend to stay longer.

By combining attrition trends, satisfaction signals, and tenure patterns, the dashboard enables HR teams to move from reactive hiring to proactive workforce planning, including estimating future hiring needs before attrition impacts business performance.


## Q & A SECTION

❓ Q1: What problem does this HR dashboard solve?

Answer:
It helps organizations understand where attrition is coming from, which employees are at risk, and what factors (overtime, tenure, satisfaction, promotions) are driving turnover. This allows HR teams to take preventive actions instead of reacting after employees leave.

❓ Q2: Why is the Attrition Rate important?

Answer:
Attrition Rate shows the percentage of employees leaving the organization. In this dashboard, an attrition rate of ~16% signals a retention risk, especially when broken down by department, job role, and overtime status.

❓ Q3: What insights did you find about overtime?

Answer:
Employees working OverTime = Yes have a significantly higher attrition rate compared to those who don’t. This clearly indicates workload imbalance as a major contributor to employee exits.

❓ Q4: How does tenure impact attrition?

Answer:
Attrition is highest during the early years of employment. Employees with fewer years at the company are more likely to leave, highlighting the importance of onboarding, engagement, and early career support.

❓ Q5: Why did you analyze promotion delay?

Answer:
Employees with long gaps since their last promotion show a noticeable spike in attrition. This suggests that career stagnation strongly affects employee retention.

❓ Q6: How is satisfaction linked with performance?

Answer:
The scatter plot shows that employees with high satisfaction and high performance have the lowest attrition. Low satisfaction combined with low performance represents the highest-risk group.

❓ Q7: How did you estimate future hiring needs?

Answer:
I used a DAX-based estimation model:

Expected Attrition Next Year = Attrition Rate × Current Headcount

Added a 10% growth buffer to calculate projected hiring needs

This provides a realistic and explainable workforce planning estimate.



### Happy to discuss feedback or improvements!
