# 📊 Sales, Supply Chain & Forecasting Analytics Dashboard

## 📌 Project Description
This project presents an end-to-end Business Intelligence solution developed using Power BI to analyze sales performance, profitability, supply chain efficiency, customer behavior, and future demand forecasting.
The dashboard integrates multiple analytical perspectives including:
- Profit & Loss analysis 
- A/B testing on discount strategies 
- Supply chain performance 
-	Customer segmentation 
-	Time-series trend analysis 
-	Forecasting using ARIMA through R Prgramming

## 🎯 Project Objectives
-	Analyze overall sales, profit, and operational performance 
-	Identify loss-making products and categories 
-	Evaluate the impact of discount strategies (A/B Testing) 
-	Assess delivery performance and supply chain efficiency 
-	Understand customer purchasing behavior 
-	Detect trends and seasonality in sales and profit 
-	Forecast future sales and profit for strategic planning 

## 📂 Data Source
-	Source: Kaggle 
-	Time Period: 2015 – 2018
  
⚠️ Note: This dataset is strictly used for educational and learning purposes without any modifications.

## ❓ Business Questions
-	How do discounts impact profitability? 
-	Which categories and products are loss-making? 
-	What drives high late delivery rates? 
-	Which customer segments contribute most to revenue? 
-	Are sales and profit improving over time? 
-	What is the future forecast of business performance?

## 📊 Dashboard

## 🟦 Dashboard Page 1: Executive Business Summary
### 📌 KPIs
-	Total Sales: 36.78M 
-	Total Orders: 66K 
-	Total Profit: 3.97M 
-	Profit Margin: 10.78% 
-	Late Delivery Rate: 54.83% 
-	Loss Orders: 37.49%

### 📊 Top Categories by Profit Contribution
-	Fishing category generates the highest profit at 0.76M, making it the leading revenue-driving category 
-	Cleats follows with 0.49M, showing strong but lower contribution compared to Fishing 
-	Camping & Hiking contributes 0.43M, indicating consistent performance 
-	Cardio Equipment generates 0.38M, reflecting moderate profitability 
-	Water Sports (0.33M) and Indoor/Outdoor Games (0.32M) show similar contribution levels 
-	Men’s Footwear contributes 0.31M, slightly lower than other top categories 
-	Indicates that profitability is concentrated in a few top-performing categories, with Fishing clearly outperforming others 

### 📊 Profit Performance by Discount Strategy (A/B Testing)
-	Low discount strategy generates 2.1M total profit, higher than high discount 
-	High discount strategy generates 1.8M profit, which is noticeably lower 
-	Despite offering higher discounts, profitability does not improve 
-	Indicates that increasing discounts does not translate into higher profit and may reduce margins 

### 📊 Order Distribution by Payment Method
-	Debt transactions have the highest order volume at 25K, indicating strong customer reliance on credit-based purchasing 
-	Transfer method follows with 18K orders, showing significant usage of digital payments 
-	Payment method contributes 15K orders, reflecting moderate adoption 
-	Cash transactions are lowest at 7K, indicating reduced preference for cash payments 
-	Suggests that customers prefer flexible or non-cash payment methods 

### 📊 Profit vs Loss Distribution
-	Profit orders account for 81.29% of total orders, indicating overall business profitability 
-	Loss orders represent 18.71%, which is a considerable portion 
-	Nearly one-fifth of total orders are loss-making, highlighting inefficiencies in pricing or cost control 

### 📊 Profit vs Loss by Category
-	Cleats category shows 20K profit orders vs 4.6K loss orders, indicating strong performance but with noticeable losses 
-	Men’s Footwear has 18.1K profit vs 4.2K loss orders, showing similar pattern 
-	Women’s Apparel records 17.1K profit and 3.9K loss orders, indicating stable but imperfect profitability 
-	Indoor/Outdoor Games shows 15.7K profit vs 3.6K loss, maintaining consistent performance 
-	Fishing category has 14.1K profit and 3.2K loss orders, showing high contribution but also some inefficiencies 
-	Camping & Hiking records 11.1K profit vs 2.6K loss orders 
-	Across all major categories, loss orders are consistently present alongside profit orders 
-	Indicates that even top-performing categories are not fully optimized for profitability 

## 🟥 Dashboard Page 2: Supply Chain & Customer Insights 
### 📊 Customer Sales Distribution
-	Sales remain up to 5K for the majority of customers, indicating a large base of medium-value customers 
-	After approximately 12K customer IDs, sales contribution declines significantly toward near zero 
-	Indicates that only a portion of customers contribute meaningfully to revenue 
-	Suggests opportunity to improve customer retention and increase high-value customers 

### 📊 Profit Efficiency by Category
-	Golf Bags & Carts show the highest average profit ratio at 0.191 
-	Toys follow with 0.162, indicating strong profitability 
-	Fitness Accessories and Women’s Clothing both at 0.151, showing stable margins 
-	Soccer (0.147) and Golf Clubs (~0.146) maintain consistent performance 
-	Indicates that certain niche categories achieve higher efficiency compared to high-volume categories 

### 📊 Average Delay by Market
-	USCA has the highest delay at 0.596 days 
-	Pacific Asia (0.569) and Europe (0.57) show similar delay patterns 
-	Africa (0.56) and LATAM (0.558) slightly lower 
-	Differences across markets are minimal 
-	Indicates that delivery delay is a widespread issue rather than region-specific 

### 📊 Delivery Performance Distribution
-	Late delivery accounts for 54.83%, representing the majority of orders 
-	Advance shipments contribute 23% 
-	On-time deliveries are only 17.84%, relatively low 
-	Shipping cancellations are 4.3% 
-	Indicates that more than half of deliveries are delayed, highlighting a major operational concern 

### 📊 Shipping Mode Efficiency
-	Second Class has the highest delay at 1.99 days, indicating inefficiency 
-	First Class shows 1.00 day delay, moderate performance 
-	Same Day delivery has 0.48 day delay, relatively efficient 
-	Standard Class shows 0 delay, likely due to scheduling alignment 
-	Suggests trade-offs between shipping mode, cost, and performance 

### 📊 Sales by Customer Segment
-	Consumer segment contributes 19.1M, the highest among all segments 
-	Corporate contributes 11.2M, showing strong business demand 
-	Home Office contributes 6.5M, the lowest among segments 
-	Indicates that individual consumers are the primary revenue drivers 

### 📊 Late Delivery Rate by Region
-	Central Africa shows highest delay rate at 0.58 
-	South Asia and East Africa follow at 0.56 
-	Western Europe also at 0.56, indicating developed regions are also affected 
-	Canada shows lowest delay at 0.49 
-	Caribbean and South Africa around 0.53 
-	Indicates regional disparities but overall high delay levels globally 

## 🟩 Dashboard Page 3: Trend Analysis 
### 📊 Sales & Profit Trend
-	Sales fluctuate between 28K to 40K from 2015 to September 2017 
-	After September 2017, sales drop sharply and show high volatility 
-	Profit follows a similar pattern, ranging between 10K to 20K before decline 
-	Indicates instability in recent performance 

### 📊 Profit Margin Trend
-	Profit margin remains stable at 0.11 from 2015 to 2017 
-	Slight decrease to 0.10 in 2018 
-	Indicates consistent but slightly declining profitability 

### 📊 Monthly Sales Pattern
-	January records highest sales at 3.46M 
-	Most months range between 2.7M to 3.2M 
-	September drops significantly to 0.16M, showing an abnormal decline 
-	Indicates stable performance with one major anomaly 

### 📊 Monthly Profit Pattern
-	Profit ranges from 281K to 367K across months 
-	Highest in January (367K) 
-	Lowest in December (281K) 
-	Indicates relatively stable profitability with slight seasonal variation 

### 📊 Category Trend Over Time
-	Fishing remains the top category from 2015 to 2017, then drops to near zero in 2018 
-	Cleats shows similar trend with decline in 2018 
-	Camping & Hiking and Cardio Equipment follow as next top contributors 
-	Indicates possible data limitation or business decline in 2018 

## 🟪 Dashboard Page 4: Forecasting 
### 📊 Forecast Insights
-	Forecast indicates a declining trend in both total sales and total profit 
-	From February 2018 to February 2019, both metrics show downward movement 
-	Suggests potential future reduction in business performance 
-	Highlights need for strategic action to stabilize growth

## 🧠 Business Answers
-	Low discount strategy generates 2.1M profit, while high discount generates 1.8M, indicating that higher discounts reduce profitability 
-	Loss-making orders are present across all major categories, including Cleats (4.6K loss orders) and Men’s Footwear (4.2K loss orders) 
-	Late deliveries account for 54.83% of total orders, with consistent delays across markets (~0.55–0.59 days), indicating supply chain inefficiencies 
-	Consumer segment contributes the highest revenue (19.1M), followed by Corporate (11.2M) and Home Office (6.5M) 
-	Sales and profit remain stable from 2015 to September 2017, then decline sharply and become volatile 
-	Forecast indicates a declining trend in both sales and profit, suggesting potential future performance decline 

## 🔑 Key Takeaways
-	Business generates strong sales (36.78M) but operates at moderate margin (10.78%) 
-	Discount strategy has a direct impact on profitability 
-	Nearly 1 in 5 orders (18.71%) is loss-making 
-	More than half of deliveries are delayed (54.83%) 
-	Revenue is highly dependent on the Consumer segment (19.1M) 
-	Sales and profit show instability in recent periods 
-	Forecast indicates potential decline in future performance 

## 📢 Business Recommendations
-	Optimize discount strategy to reduce excessive discounting and improve profitability 
-	Identify and minimize loss-making orders across key categories 
-	Improve supply chain operations to reduce late deliveries 
-	Focus on high-performing categories such as Fishing and Cleats 
-	Strengthen customer retention strategies to increase high-value customers 
-	Use forecasting insights for better planning and inventory management

