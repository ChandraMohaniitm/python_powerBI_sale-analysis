# python_powerBI_sale-analysis

## Sales Data Analysis (EDA with Python) and (Interactive Dashboard Creation Using Power BI)

## Project Objective
The company wants to create an annual sales report for 2012,2013,2014.So that,the owner of the company can understand their customer and grow more sales in future.

## Dataset Used
- <a href="https://github.com/ChandraMohaniitm/python_powerBI_sale-analysis/blob/main/global_superstore_2016.xlsx">view dataset</a>

## Questions (KPIs)
- What is the Total Sales over all year
- How many quantity has sold over all yaer
- What is average delivery per day
- How many orders has been returned
- what is top sold product
- what is the top loss-making products
- which are the countries where we made high sale
- which are the top markets based on sale
- find top segment where we made high sales
- Find the states of the country with high sale and most sold categories.


## Process
- Loaded Data in power bi and opened Power query editor.
- Verify data for any missing values and anomalies,and sorted out it.
- Changed data type of some columns.
- Extracted year from date column using “mange column” with dax formula =Date.Year([order_date]).
- Derived delivery_days column using “conditional column” with dax formula =([ship_date]-[order_date]).
- joined the three(all) tables using drag-drop options.
- I have performed some EDA on data using Python.
  

## Project Insight
- Power BI

![Screenshot 2025-01-02 175609](https://github.com/user-attachments/assets/bcd10dca-ae29-451b-8c40-55423210c5c4)


![Screenshot 2025-01-05 000741](https://github.com/user-attachments/assets/b5515b5d-151f-4d42-a9e2-4d009d9aaaf5)

- Python
  
  ![p2](https://github.com/user-attachments/assets/d69e906e-c8f3-460a-bda6-0b2564e399a8)
  ![p3](https://github.com/user-attachments/assets/31894a86-3dc6-41cf-905b-3b1635b28f2e)
  ![p4](https://github.com/user-attachments/assets/9d315646-e003-4520-9bb5-4b9b88bcb44d)
  ![p5](https://github.com/user-attachments/assets/a97e8f73-cbec-4020-8a7d-1f4b0c3b15c9)
  ![p6](https://github.com/user-attachments/assets/ddc983df-6b0a-458d-9742-9f5cec621ec3)
  ![p1](https://github.com/user-attachments/assets/40e772bd-33a4-4360-97b7-b63ba9f52239)


- After analysis of data we can see that:
- We have made high sales in the western Europe,Central America,Oceania and Southeastern Asia Region.
- United States,Australia ,France,India and China these are the country where we have made high sale.
- Florida,Indiana and Washington are top state of united state where we made high sale and these are top selling category   technology and office supply.
- South Australia,New south wales and Queensland top Australian states with high sale contribution and office supply,furnicher,techonology top selling category.

## Dashboard 
- <a href="https://github.com/ChandraMohaniitm/python_powerBI_sale-analysis/blob/main/Screenshot%202025-01-02%20175609.png">dashboard image</a>

## Python Code
- <a href="https://github.com/ChandraMohaniitm/python_powerBI_sale-analysis/blob/main/bypy.ipynb">view code</a>


## Final Conclusion
- To get more profit and grow our business we should advertise our high selling products(category).we could scale our number of shopes and products in that country and states of that country where we have made high sales and we should provide additional discount on that top selling products for customers who spend more amount.
