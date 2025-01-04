# python_powerBI_sale-analysis

## Sales Data Analysis(Interactive Dashboard Creation Using Power BI)

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
- Dashboard href img only

## Process
- Loaded Data in power bi and opened Power query editor.
- Verify data for any missing values and anomalies,and sorted out it.
- Changed data type of some columns.
- Extracted year from date column using “mange column” with dax formula =Date.Year([order_date]).
- Derived delivery_days column using “conditional column” with dax formula =([ship_date]-[order_date]).
- joined the three(all) tables using drag-drop options.
- 
## Dashboard 
- <a href="https://github.com/ChandraMohaniitm/python_powerBI_sale-analysis/blob/main/Screenshot%202025-01-02%20175609.png">dashboard image</a>

## Project Insight
![Screenshot 2025-01-02 175609](https://github.com/user-attachments/assets/88a812cc-816f-4dbf-9e12-2ff5970d233d)

## Final Conclusion
