# Prodigy InfoTech Data Science Internship Task 3


![image](https://github.com/user-attachments/assets/06c4385d-a04a-431c-a976-635da5bcaf5a)

I am excited to share my fourth task as a Data Science Intern at Prodigy InfoTech. In this project, I analyzed and visualized sentiment patterns in social media data using a dataset from Kaggle. The objective was to understand public opinion and attitudes toward specific topics or brands. I applied text preprocessing techniques, performed sentiment analysis, and created insightful visualizations to showcase the distribution of sentiments across different entities.

# 1. Dataset Overview

The analysis uses the Twitter Entity Sentiment Analysis dataset, which contains tweets about various entities (brands, products, games, etc.) with sentiment labels. The dataset is divided into training and validation sets.

# 2. Data Exploration and Preparation

Before analysis, we explored the dataset structure to understand its contents. The dataset contains the following columns:
  
•	- ID: Unique identifier for each tweet  
•	- Entity: The brand, product, or topic mentioned in the tweet  
•	- Sentiment: The sentiment label (Positive, Negative, Neutral, or Irrelevant)  
•	- Tweet: The actual text content of the tweet  

For Excel-based analysis, we prepared several Excel files:

•	- A sample dataset with 1,000 randomly selected tweets  
•	- Separate sheets for each sentiment category  
•	- Entity-specific sentiment distribution  
•	- Summary statistics for sentiment analysis  
  
Example of the prepared Excel data:  
  
![image](https://github.com/user-attachments/assets/86dbb976-2fb9-44f2-832c-2dafa0980e3e)
Figure 1: Entity Sentiment Comparison Chart


# 3. Sentiment Analysis in Excel

We performed sentiment analysis in Excel using the following techniques:

1.	Conditional formatting to highlight positive and negative sentiment percentages  
2.	Calculation of sentiment ratio (positive to negative) for each entity  
3.	Creation of a weighted sentiment score using the formula:  
   Sentiment Score = (Positive% × 1 + Neutral% × 0.5 + Negative% × 0) / (Positive% + Neutral% + Negative%)
  	
The Excel-based analysis allows for easy visualization and comparison of sentiment across different entities. The conditional formatting helps quickly identify entities with particularly positive or negative sentiment.  

# 4. Creating Visualizations in Excel

•	Overall Sentiment Distribution:

![image](https://github.com/user-attachments/assets/5c3d5a47-2bb3-42d9-9078-06afc0002a3a)
Figure 2: Pie chart showing the distribution of sentiment categories across all entities

•	Entity Sentiment Comparison:

![image](https://github.com/user-attachments/assets/c8a4f12e-ad21-459e-a46c-9ceb70ca421d)
Figure 3: Bar chart comparing sentiment percentages across different entities

•	Sentiment Score Comparison:

![image](https://github.com/user-attachments/assets/7fc8a982-368e-4186-bf85-b03e2e242646)
Figure 4: Bar chart showing the calculated sentiment score for each entity

•	Positive to Negative Ratio:


![image](https://github.com/user-attachments/assets/f29ac41d-ac7e-4845-bc8c-fcfeda012788)
Figure 5: Bar chart displaying the ratio of positive to negative sentiment for each entity

# 5. Analyzing Sentiment Patterns
After creating visualizations, we analyzed the sentiment patterns to identify key insights:

**1. Overall Sentiment Distribution**

Total tweets analyzed: 23856  
Microsoft: 2400 tweets (10.06%)  
MaddenNFL: 2400 tweets (10.06%)  
TomClancysRainbowSix: 2400 tweets (10.06%)  
LeagueOfLegends: 2394 tweets (10.04%)  
CallOfDuty: 2394 tweets (10.04%)  
Verizon: 2382 tweets (9.98%)  
CallOfDutyBlackopsColdWar: 2376 tweets (9.96%)  
ApexLegends: 2376 tweets (9.96%)  
Facebook: 2370 tweets (9.93%)  
WorldOfCraft: 2364 tweets (9.91%)  
The most common sentiment in the dataset is Microsoft with 2400 tweets (10.06%).  
The ratio of Microsoft to MaddenNFL is 1.00.  


**2. Entity-Specific Sentiment Analysis**

# Entities Ranked by Sentiment Score (Most Positive to Most Negative):

MaddenNFL: Score 0.88 (Pos: 16.50%, Neg: 71.25%, Ratio: 8.38)  
Verizon: Score 0.64 (Pos: 22.17%, Neg: 46.10%, Ratio: 1.93)  
CallOfDuty: Score 0.63 (Pos: 18.80%, Neg: 37.34%, Ratio: 2.37)  
TomClancysRainbowSix: Score 0.62 (Pos: 22.00%, Neg: 46.75%, Ratio: 1.72)  
CallOfDutyBlackopsColdWar: Score 0.57 (Pos: 36.36%, Neg: 24.24%, Ratio: 1.60)  
Facebook: Score 0.48 (Pos: 7.34%, Neg: 30.38%, Ratio: 0.92)    
Microsoft: Score 0.48 (Pos: 25.25%, Neg: 32.25%, Ratio: 0.91)  
LeagueOfLegends: Score 0.45 (Pos: 25.81%, Neg: 26.82%, Ratio: 0.78)  
ApexLegends: Score 0.40 (Pos: 27.02%, Neg: 25.25%, Ratio: 0.64)  
WorldOfCraft: Score 0.28 (Pos: 31.22%, Neg: 14.47%, Ratio: 0.32)  

# Most Positive Entity:  
CallOfDutyBlackopsColdWar with 36.36% positive tweets  

# Most Negative Entity:  
MaddenNFL with 71.25% negative tweets  

# Most Neutral Entity:  
WorldOfCraft with 45.18% neutral tweets  

**3. Comparative Sentiment Analysis**

# Gaming vs. Tech Companies Sentiment Comparison:  
Average sentiment score for gaming entities: 0.55    
Average sentiment score for tech companies: 0.54  
Gaming entities have a more positive sentiment by 0.01 points.

**4. Key Insights and Patterns**

# Entities with Balanced Positive and Negative Sentiment:  
- Microsoft (Ratio: 0.91)  
- Facebook (Ratio: 0.92)
  
# Entities with Strongly Positive Sentiment (Ratio > 2):  
- MaddenNFL (Ratio: 8.38)  
- CallOfDuty (Ratio: 2.37)
  
# Entities with Strongly Negative Sentiment (Ratio < 0.5):  
- WorldOfCraft (Ratio: 0.32)
  
**5. Conclusion and Recommendations**

# Summary of Findings:  
- The Twitter sentiment analysis reveals varying levels of public opinion across different entities.  
- Overall, Microsoft sentiment is the most prevalent in the dataset.  
- CallOfDutyBlackopsColdWar enjoys the most positive sentiment, while MaddenNFL faces the most negative sentiment.
  
# Recommendations for Entities with Negative Sentiment:  
- Microsoft: Consider addressing negative sentiment through improved customer engagement and addressing common complaints.  
- LeagueOfLegends: Consider addressing negative sentiment through improved customer engagement and addressing common complaints.  
- ApexLegends: Consider addressing negative sentiment through improved customer engagement and addressing common complaints.  
- Facebook: Consider addressing negative sentiment through improved customer engagement and addressing common complaints.  
- WorldOfCraft: Consider addressing negative sentiment through improved customer engagement and addressing common complaints.
  
# Recommendations for Sentiment Monitoring:  
- Implement regular sentiment analysis to track changes in public opinion over time.  
- Focus on entities with high negative sentiment for reputation management strategies.  
- For entities with positive sentiment, identify successful factors that could be applied to other entities.  



