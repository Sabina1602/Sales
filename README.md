**Data Cleaning & Preparation**
I first tackled a data formatting issue by converting dates incorrectly stored as text into the proper Date format using the Text to Columns feature (To check the format I used ISNUMBER function). I also confirmed there were no blank values in the dataset. To prepare the data for analysis, I extracted the year and sorted the entire table by date in descending order to view the latest entries.
Finally, using IF function I identified the volume of sales dividing them on 3 categories (Small, Medium, Big). 

**Key Questions Answered**

**Which state generates the most income?**
To answer this, I created a Pivot Table with States in the rows and Total Sales in the values. I then sorted the table by Total Sales in descending order to identify the top-performing state. I used a chart to visually illustrate the sales performance across all states.

**What is the most popular product?**
Using a second Pivot Table, I placed Categories and Sub-categories in the rows and a Count of sales in the values. This allowed me to see the total sales for each product category. By sorting this table, I identified the most popular categories. Expanding a category's data then revealed the best-selling products within it. To show the sales distribution, I created a pie chart representing the sales ratio of each category.

**Conclusion**
The insights from this project are designed to be actionable. By understanding which products are most popular and profitable in each state, businesses can make data-driven decisions to optimize their marketing strategies.


