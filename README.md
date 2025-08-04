# Personal_Loan_ML_b

🔸 Project Overview

 AllLife Bank, a U.S.-based financial institution, had a solid base of liability customers (depositors) but a limited number of borrowers. A recent marketing campaign for personal loans showed a modest 9% conversion rate. The bank wanted to increase its personal loan portfolio by identifying depositors most likely to accept a loan offer, enabling smarter targeting and improved ROI.

🔸 Objective

 Building a data-driven solution to predict which liability customers were likely to convert into personal loan customers. The goal was to provide the marketing team with a prioritized list of high-probability leads and segment profiles to inform targeted outreach strategies.

🔸 Approach & Implementation

1. Data Exploration & Preprocessing
   
Performed univariate and bivariate EDA to understand distributions and relationships.


Identified and handled missing values and outliers using domain logic and statistical methods.


Conducted feature engineering to enhance signal strength and simplify model inputs.


2. Predictive Modeling (Classification)
   
Built a Decision Tree Classifier to model the likelihood of loan acceptance.


Evaluated model performance using confusion matrix, accuracy, precision, and recall.


Used pre-pruning (e.g., max_depth, min_samples_split) to prevent the tree from overfitting.


Applied post-pruning using cost-complexity pruning to further generalize the model.


Visualized the tree structure for stakeholder understanding and interpretability.


3. Feature Importance Analysis
   
Used built-in feature importance scores to identify top predictors such as income, education, and CD account ownership.


Communicated these insights to the business team to help design tailored campaigns.


4. Clustering & Customer Segmentation
   
Standardized the feature set and applied K-Means Clustering to segment the customer base.


Used t-SNE for high-dimensional visualization of clusters.


Evaluated cluster cohesion using inertia and silhouette scores, and experimented with perplexity values in t-SNE for better separation.


Created cluster profiles with scatterplots and distribution plots to describe segment behaviors.


5. Final Presentation & Delivery
   
Delivered a full report including predictive model outputs, key features, cluster personas, and business implications.


Collaborated with marketing to translate the technical findings into targeted lead lists and campaign strategies.



🔸 Results

1. Targeted Marketing Strategy:
 The marketing team adopted the model’s predictions to prioritize outreach to high-probability customers, significantly improving campaign efficiency.
2. Insightful Feature Drivers:
 The model revealed that income, education, and existing CD account status were the strongest predictors, allowing more precise segmentation.
3. Customer Segmentation:
 Clustering enabled the business to identify hidden customer personas and build customized offers for each segment, improving conversion rates.
4. Business Value Delivered:
 The project enhanced data-driven decision-making for the bank, improved conversion targeting, and laid the groundwork for personalized marketing strategies that are scalable for future campaigns.
