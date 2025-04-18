### Email Campaign Performance Analysis with ML Optimization ###
This project explores how an email campaign performed using real user interaction data. We dive into how people opened and clicked emails, and we even used machine learning to suggest how future email campaigns could be improved — all built and tested in Google Colab.

**Project Goals**

We aimed to answer four real-world marketing questions using data and predictive models:

1.What percentage of users opened the email and clicked on the link?

2.Can we build a model that improves how we send emails (and increases clicks)?

3.How much would that model improve the click-through rate (CTR)?

4.Are there any interesting patterns across different user groups or email types?

**We worked with 3 datasets:**

•email_table.csv: Records of all sent emails and their metadata.

•email_opened_table.csv: Users who opened the emails.

•link_clicked_table.csv: Users who clicked on links inside emails.

## Step 1: Data Preparation & CTR Analysis##

Merged datasets to find out how many people opened and clicked.

Calculated:

→Open Rate = users who opened / total users

→Click Rate = users who clicked / total users

✅ Click-Through Rate (CTR) calculated successfully.

## Step 2 & 3: Machine Learning Modeling

Objective
Can we predict who will click the email?

 Models Used:
Random Forest Classifier (baseline model)

XGBoost Classifier (optimized, better results)

➡ XGBoost significantly improved recall — it found more actual clickers, which is key for marketing.

 How to Test in Real Life:
Run an A/B test: send emails using current method vs model-recommended method, then compare CTR.

## Step 4: User Segment Insights
We explored how click rates vary by:

Insight: English-speaking countries (US/UK) have better engagement.
Insight: Personalized emails lead to higher clicks.

 Visual Insights
🔹 Click Rate by Country
🔹 Click Rate by Email Version

## Tools Used
•Python (Pandas, NumPy) – data wrangling
•Seaborn/Matplotlib – charts
•Scikit-learn & XGBoost – ML models
•Google Colab – everything coded here

 ## How to Run This Project
Open the .ipynb file in Google Colab.
Upload the three CSV files.
Run each cell step-by-step.

You can tweak models, see visual charts, and generate insights instantly.

## Results
XGBoost helps identify more likely clickers (recall ↑ from 14% to 86%).
Personalized emails are better.
US/UK users are more engaged than others.

## Conclusion
This project shows how data + machine learning can make marketing smarter, reduce guesswork, and increase engagement.
Anyone running campaigns can use this setup to:

Monitor email success,
Learn what works by segment,
Predict future clicks with better precision.

## Questions or Feedback?
Feel free to open an issue or fork this repo to extend the analysis!



