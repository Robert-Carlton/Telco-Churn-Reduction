# Summary
This project addresses the challenge of customer churn in the telecommunications industry, where customers frequently switch providers, causing lost revenue and higher acquisition costs. I built a machine learning model to predict which customers are most likely to leave so the company can take targeted action to retain them. Using a large dataset of customer information—including account details, service usage patterns, and past complaints—the model identifies key factors linked to churn.

The process involved cleaning and preparing the data, selecting relevant features, and testing several algorithms, including Logistic Regression, Random Forest, and Gradient Boosting, to find the best predictor. The final model was evaluated using accuracy, precision, recall, and F1-score to ensure balanced performance between correctly identifying churners and avoiding false alarms. By applying these insights, telecom companies can design personalized offers, improve customer service, and proactively address the issues most likely to cause customers to leave.

The predictive framework used here can be applied to any industry where retaining customers is critical. For subscription-based services like streaming platforms or gyms, similar models can identify at-risk members and trigger tailored engagement efforts. In financial services, they could flag clients likely to close accounts or move investments. Even in B2B settings, such methods can forecast contract cancellations or vendor switching. By integrating behavioral, transactional, and demographic data, businesses can anticipate churn across diverse sectors and respond with targeted retention strategies before it’s too late.

# Highlights

:heavy_check_mark:Business Problem
  * Customer churn significantly impacts telecom profits due to high customer acquisition costs.
  * Predicting churn allows for proactive retention strategies.

:heavy_check_mark:Data Used
  * Customer demographics and account details.
  * Service usage statistics (e.g., minutes used, data consumption).
  * Billing history and complaint records.

:heavy_check_mark:Modeling Steps
  * Data preprocessing: handling missing values, encoding categorical features, and scaling numerical variables.
  * Three different approaches to imputing missing data were tested and evaluated, including predictive mean matching (PPM), classificatoin and regression trees (CART), least absolute shrinkage and selection operator
 (LASSO).  Missing data is a very common problem is analytics/AI.
  * Balancing the data in classification prediction is extrememly important, though the research on balancing data often deals with rare occurrences (e.g. bank fraud, cancer detection, intrusion detection) in a data set. In this analysis both under-sampling and over-sampling were evaluated.
  * Feature selection to highlight the most predictive factors.
  * Model comparison between Logistic Regression, Random Forest, and Gradient Boosting.

:heavy_check_mark:Evaluation Metrics
  * Accuracy, Precision, Recall, and F1-score used to measure performance.
  * Balanced focus on correctly identifying churners while minimizing false positives.

:heavy_check_mark:Results
  * The best-performing model provided actionable insights into the top drivers of churn.
  * These drivers can inform targeted marketing and service improvements.

:heavy_check_mark:Outcomes 
  * Enables telecom operators to intervene before customers leave, improving retention rates and profitability.
  * I implemented a model similar to this at one of the largest US telcos for their long distance business saving more than $34M annually in lost customer revenue. The model predicted when customers would churn out, and tested various promotions to keep them as a customer (tied to their lifetime value (LTV)). At the time, per-minute revenue was 1-4 cents, so the savings was significant.


