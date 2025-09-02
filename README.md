 ***Amazon Product Reviews Capstone Project***

***Ask***

***Problem Statement:***  
How can Amazon and third-party sellers better understand review trends, product performance, and customer sentiment to improve sales and customer satisfaction?

 
 **Source**: Amazon product reviews dataset (Kaggle)  

***Pepare***

 Cleaning Steps:
  - Removed duplicate/missing reviews.  
  - Created calculated fields (review length, word count, rating category, price tier).  
  - Standardized product pricing into tiers (Budget, Midrange, Premium).  
  - Extracted date-based fields (review month, year) for trend analysis.  

Final dataset: W1466 after cleaning


***Key Variables***

review_id – unique review identifier

product_id – product being reviewed

review_text – customer feedback text

rating – numeric rating (1–5)

review_date – timestamp of review


***Process***

***Data Cleaning & Preparation***

Removed duplicates and missing reviews

Standardized and cleaned review text (lowercase, remove punctuation)

Tokenized text and removed stopwords for sentiment analysis

Created aggregated tables for average ratings and sentiment scores

Converted timestamps to month and year for trend analysis


***Tools & Skills Used**
- Excel / SQL: Data cleaning, pivot tables, calculated fields  
- Tableau: Dashboards and storytelling (customer behavior, trends, product performance)
- Powerpoint: Capestone project presentaion
- Github 


***Analyze & Share***


***Analysis & Insights:***

Key Questions Answered:

1. Which products have the highest positive or negative sentiment?
2. What keywords appear most frequently in negative reviews?
3. How do ratings and sentiment change over time?
4. Are there patterns in reviews by product category?


Key Insights
- Ratings vs Price: Premium products have higher ratings on average, but lower review volume.  
- Review Length: Longer reviews correlate with lower ratings, indicating customer dissatisfaction is explained in detail.  
- Review Trends Over Time: Spikes in reviews during seasonal shopping months (Nov–Dec).  
- Top Products: A few products account for the majority of revenue and review activity.  



Tableau Dashboard: [ https://public.tableau.com/views/AmazonSalesCustomerReviewAnalyticsDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link  ]
📈 View Dashboard

Includes:  
- Average Rating by Price Tier  
- Review Length vs Rating Analysis  
- Review Volume Over Time  
- Review Volume vs Average Rating  
- Top 10 Products by Sales & Rating  


***Act***

***Recommendations***
1. Product Tier Strategy  
   - Market Premium products based on strong ratings.  
   - Monitor Budget/Midrange products with lower reviews for quality improvements.  

2. Customer Feedback Loops  
   - Use insights from long, low-rated reviews to address recurring product issues.  

3. Seasonal Campaigns  
   - Prepare marketing pushes before seasonal peaks (holidays, sales events).  




***What I Would Do Differently**

Use advanced NLP techniques like topic modeling for deeper insights

Integrate sales data to correlate reviews with revenue

Track reviewer loyalty and repeat purchases for retention strategies

Build predictive models to forecast future review sentiment


***Conclusion**
Customer reviews are a powerful lens into both product performance and customer satisfaction. By combining **price tiers, review trends, and sales analysis**, Amazon sellers can improve product quality, optimize pricing, and maximize seasonal sales opportunities.  

