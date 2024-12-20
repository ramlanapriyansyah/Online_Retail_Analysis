# Project Overview
Transaction Data is a valuable source of deep business insights for a company. Analyzing transaction data can provide a clear picture of business performance over a period of time and offer essential information for the next decision-making process. This allows the company to evaluate whether the business performance was satisfactory enough or requires further review.

# Research Questions
1. How did the company's business perform over the period?
2. What was the trend of product sales? What products had the highest sales?
3. What was the company’s sales distribution? What country had the highest revenue? 
4. What was the customer’s segmentation based on RFM Analysis? Which customers were categorized as top customers and what were the criteria?

# Data and Assumption
The dataset is a compilation of transaction data at an online retail company located in the United Kingdom. The dataset consists of 9 columns and 541,908 rows, as you can see in:
: [`online_retail_dataset`](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/blob/main/online_retail_dataset.zip)

Assumption: </br>
In the **Recency** calculation, it was assumed that the PRESENT time was December 15th, 2011. It was based on the last recorded data, i.e. December 9th, 2011. 

# Data Analysis
## A. Sales Analysis
### 1. Total Sales

![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/ef84078e-7917-4ed8-9e68-830fd57973a0)

From December 2010 to August 2011, the company experienced fluctuations in total orders and total revenue. However, there was a significant increase in both from August to November 2011. </br>
Although there is no detailed information about the trend, it is assumed that this increase occurred because this period includes holidays such as Back-to-School, Labor Day, Thanksgiving, and the lead-up to New Year. 
</br>
Customers tend to shop more during these times to provide for their holiday needs, including gifts, clothes, and other goods.


### 2. Sales by Product
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/df6d0cd4-9ecb-42fa-a453-5a3dfd2c8a9b)


The most sold product was a toy named WORLD WAR 2 GLIDERS ASSTD DESIGNS. It sold 51,852 items from December 2010 - November 2011. The next most sold products were JUMBO BAG RED RETROSPOT, ASSORED COLOUR BIRD ORNAMENT, WHITE HANGING HEART T-LIGHT HOLDER, and PACK OF 72 RETROSPOT CAKE CASES.

### 3. Sales by Country
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/8d374329-2d1d-4b8b-bf45-e245b7297fd7)

The graphs above show that the highest revenue comes from the United Kingdom, which is expected since the company is located there. </br>
The graphs also show that the company’s export capability was quite good. From the top 4 countries, the company received an average revenue of approximately USD 234,000.

## B. Customer Analysis
The customer analysis was conducted using the RFM Analysis method. </br>
RFM Analysis is a technique used in marketing and customer analysis to understand customer buying behavior and classify them based on three main dimensions: 
1. **Recency**: Measuring how recently customers have made a purchase.
2. **Frequency**: Measuring how frequently customers have purchased in a certain period. 
3. **Monetary**: Measuring customers' spending in a certain period.


![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/e068fa75-3368-49d4-9d9a-3d04bd46685f)

The table above shows the top customers based on the RFM analysis. </br>
The highest monetary value belongs to the customer with ID 14646, who has spent a total of USD 279,489. This customer has made 2,085 total purchases, with the most recent transaction occurring 6 days ago.

# Conclusion
1. The company’s business performance was quite good. This was reflected by the increasing sales trend in the last four months. 
2. The top products based on the total items sold were very diverse, including accessories, toys, and household appliances. The best-selling product was a toy called WORLD WAR 2 GLIDERS ASSTD DESIGN. 
3. The highest revenue comes from the United Kingdom with total revenue of USD 6,767,873.
4. The top customer was the one with ID 14646. This customer had the highest monetary value, as well as high frequency and recency values.

# Recommendations
1. Maintain and enhance the increasing sales trend.
2. Develop a global marketing strategy. Based on the analysis, the international market opportunity is very potential. Therefore, an effective marketing strategy is needed to reach a broader target market.

*The whole analysis process can be seen in this Jupyter Notebook file: [`jupyter_notebook_file`](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/blob/main/jupyter_notebook_file.ipynb)













