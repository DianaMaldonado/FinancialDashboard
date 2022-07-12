Hello!

This is a financial dashboard elaborated with Power BI.  
The purpose of this dashboard is to identify the main financial indicators to inform of the general state of the business. The guide questions are the following:
1. What is the profit year to date?
2. What is the profit of the current month? Total and by product?
3. What was the profit of the last month?
4. What is the profit variance since last month?
5. How the costs affect sales revenue?
![Captura de Pantalla 2022-07-12 a la(s) 17 23 56](https://user-images.githubusercontent.com/74566268/178606305-08793287-7182-4b8d-8853-ee8ae770f0f4.png)

In a second page of the dashboard the sales and costs definitions are detailed. Following the next questions:
1. What is the gross sales of the current month? Total, Country, Segment, and Product.
2. What are the Cost of Sold Goods (COGS), Discounts, and Manufacturing Cost by product and compared to Profit?
![Captura de Pantalla 2022-07-12 a la(s) 17 24 23](https://user-images.githubusercontent.com/74566268/178606453-dc06c55d-0f9d-4eb4-a367-3b18b7c28359.png)

In a thrid page there is a further explanation of Gross Sales, considering that this information could be used for marketing purposes:
- The correlation between Sale Price of each Product and Units Sold.
- Number of sales by each day of the week by product.
- Number of sales by discount band by product.
![Captura de Pantalla 2022-07-12 a la(s) 17 24 44](https://user-images.githubusercontent.com/74566268/178606556-ee14bf49-72e3-49a7-81b3-fd62237b1196.png)

The dataset used in this case is from Kaggle: https://www.kaggle.com/datasets/luckyrao/financial-sample-data. 
An .xlsx file was imported into Power BI, cleaned, transformed, and loaded using Power Query.
![Captura de Pantalla 2022-07-12 a la(s) 17 35 19](https://user-images.githubusercontent.com/74566268/178609868-381b039c-73ea-47a3-8494-3f441b5a1474.png)

The dataset was split into two to ensure report optimization: a fact table for the financials and a dimension table for the products. A dates table was also created to reduce space in the report and use time intelligence measures.
The three tables were modelled through a star scheme.
![Captura de Pantalla 2022-07-12 a la(s) 17 35 50](https://user-images.githubusercontent.com/74566268/178609925-c66954eb-6e00-42c4-9370-c23e8399eab2.png)

Several measures were calculated to better perform the report, and visuals were added once they were finnished.
![Captura de Pantalla 2022-07-12 a la(s) 17 36 27](https://user-images.githubusercontent.com/74566268/178609993-9e14dac2-36fc-4de2-a9cb-e82de1f83cf0.png)
