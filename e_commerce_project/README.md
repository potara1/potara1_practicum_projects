## Mobile app analysis
--- 
### Research Goals
**The main goal** of this analysis is to segment customers based on their purchase history in order to develop more personalized offers. The research also aims to solve the following business challenges:
1. **Marketing Recommendations:** 
Based on customer segments, determine which customers should receive advertising offers, when to send them, and for which product categories.
2. **Sales Growth Strategy:**
Develop strategies to increase the quantity of products sold to each customer segment.
3. **Customer Loyalty Strategy:**
Suggest ways to improve customer retention across different segments.
---
### Data Description
The dataset represents transactions from the online store "Poka vse eshche tut", which sells home goods:
- `date` — order date, data type: int64;  
- `customer_id` — customer identifier, data type: object;  
- `order_id` — order identifier, data type: int64;  
- `product` — product name, data type: object;  
- `quantity` — number of items in the order, data type: int64;  
- `price` — price of the product, data type: float64.
---
### Summary
#### Data Preprocessing
- Cleaned the dataset, converted date to datetime, and created new columns.
- No outliers found in quantity and price.
#### Data Analysis
- Revenue and orders: General decline in revenue, orders fluctuated but increased by 2019.
- Categories: Stable performance in "Kitchenware" and "Tools", "Gardening" peaks in spring, "Home Goods" in December.
- Top buyers: Average revenue decreased, high profitability from mid-range spenders.
#### Key Insights
- Customer classification: Categories based on order frequency and receipt size, with premium customers making larger purchases.
#### Hypotheses
- Statistically significant differences between groups validate the classification.
