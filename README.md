# Amazon Sales Dashboard

# Problem Statement
The main objective of creating this dashboard is to analyze Amazon's sales data to understand various factors affecting sales performance. By identifying trends and patterns, the goal is to provide insights that can help optimize sales strategies, improve profitability, and enhance customer engagement across different product categories and regions

# Dataset Explanation
𝐎𝐫𝐝𝐞𝐫 𝐈𝐃: A unique identifier for each order made by customers.

𝐎𝐫𝐝𝐞𝐫 𝐃𝐚𝐭𝐞: The date on which the order was made.

𝐒𝐡𝐢𝐩 𝐃𝐚𝐭𝐞: The date on which the order was shipped.

𝐒𝐡𝐢𝐩 𝐌𝐨𝐝𝐞: The shipping method used for the order.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐈𝐃: A unique identifier for each customer.

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐍𝐚𝐦𝐞: The name of the customer.

𝐒𝐞𝐠𝐦𝐞𝐧𝐭: The customer segment (e.g., consumer, corporate).

𝐂𝐨𝐮𝐧𝐭𝐫𝐲: The country where the order was shipped.

𝐂𝐢𝐭𝐲:The city where the order was delivered.

𝐒𝐭𝐚𝐭𝐞: The state or province of the order delivery.

𝐑𝐞𝐠𝐢𝐨𝐧: The region of the order delivery.

𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐈𝐃: A unique identifier for each product.

𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲: The product category (e.g., electronics, home appliances).

𝐒𝐮𝐛-𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲: The sub-category of the product.

𝐏𝐫𝐨𝐝𝐮𝐜𝐭 𝐍𝐚𝐦𝐞: The name of the product.

𝐒𝐚𝐥𝐞𝐬: The total sales revenue from the order.

𝐐𝐮𝐚𝐧𝐭𝐢𝐭𝐲: The quantity of each product ordered.

𝐃𝐢𝐬𝐜𝐨𝐮𝐧𝐭 %: The discount percentage applied to the order.

𝐏𝐫𝐨𝐟𝐢𝐭: The profit from the order (sales revenue minus cost).

𝐒𝐡𝐢𝐩𝐦𝐞𝐧𝐭 𝐂𝐨𝐬𝐭: The cost of shipping the order.

# Steps Followed
𝐃𝐚𝐭𝐚 𝐋𝐨𝐚𝐝𝐢𝐧𝐠:
Start by importing the Amazon sales data into Power BI Desktop. Go to the Home tab, click on Get Data, and select the file format of your dataset.

𝐃𝐚𝐭𝐚 𝐐𝐮𝐚𝐥𝐢𝐭𝐲 𝐂𝐡𝐞𝐜𝐤:
Open Power Query Editor to check the data quality. Look for any anomalies, missing values, or errors. This can be done by selecting Transform Data from the Home tab.

𝐄𝐫𝐫𝐨𝐫 𝐚𝐧𝐝 𝐄𝐦𝐩𝐭𝐲 𝐕𝐚𝐥𝐮𝐞𝐬 𝐂𝐡𝐞𝐜𝐤:
Use the column headers to filter for errors and empty values. Correct any issues found or remove irrelevant data if necessary.

𝐃𝐚𝐭𝐚 𝐏𝐫𝐨𝐟𝐢𝐥𝐢𝐧𝐠:
Use the Data Profiling tools within Power Query to get a better understanding of the data distribution, column statistics, and more. This step helps identify any further data cleaning or transformations needed.

𝐃𝐚𝐭𝐚 𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠:
Replace or remove null values and handle any errors found in the data columns. Use functions like Remove Errors or Replace Errors available in Power Query.

𝐓𝐨𝐭𝐚𝐥 𝐌𝐞𝐭𝐫𝐢𝐜𝐬 𝐂𝐚𝐫𝐝𝐬:
Add card visuals to display the total sales, total quantity, total profit, and total shipment cost. Drag the respective measures to the canvas and format the cards.

𝐂𝐨𝐥𝐮𝐦𝐧 𝐂𝐡𝐚𝐫𝐭:
Create a column chart to show total sales by product category. Use Category on the axis and Sales on the values.

𝐋𝐢𝐧𝐞 𝐂𝐡𝐚𝐫𝐭:
Add a line chart to display the sales trend over time. Use the Order Date on the axis and Sales on the values. Ensure the date is properly formatted to show trends over months and years.

𝐒𝐜𝐚𝐭𝐭𝐞𝐫 𝐂𝐡𝐚𝐫𝐭:
Create a scatter chart to compare sales and profits across different customer segments by product categories. Use Category on the axis, Segment as legend, and Sales and Profit as the respective values.

𝐓𝐫𝐞𝐞𝐦𝐚𝐩:
Implement a treemap to illustrate sales revenue and profit across different product categories and sub-categories. Place Category and Sub-Category on the axis and Sales and Profit as values.

𝐁𝐚𝐫 𝐂𝐡𝐚𝐫𝐭 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧:
Use a bar chart to show sales and profit variations by region. Use Region on the axis and Sales and Profit as values.

𝐌𝐚𝐩 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧:
Add a map visualization to show the geographic distribution of customers by state, with states ranked by profit.

# Insights
𝐓𝐨𝐭𝐚𝐥 𝐒𝐚𝐥𝐞𝐬 𝐚𝐧𝐝 𝐏𝐫𝐨𝐟𝐢𝐭: 
The dashboard indicates a total sales amount of 2.30M and a profit of 0.29M, reflecting a profit margin of approximately 12.6%. This might suggest room for improvement in profit margins through cost reduction or increased pricing strategies.

𝐒𝐚𝐥𝐞𝐬 𝐆𝐫𝐨𝐰𝐭𝐡: 
The sales by year chart shows an upward trend from 2014 to 2017, indicating steady growth in sales. This trend signifies a positive trajectory for the business, with the highest sales occurring in 2017.

𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲 𝐏𝐞𝐫𝐟𝐨𝐫𝐦𝐚𝐧𝐜𝐞: 
The sales by category chart reveals that Technology leads in sales, followed by Furniture and Office Supplies. This suggests that these categories are the most profitable and possibly the most popular among customers.

𝐒𝐚𝐥𝐞𝐬 𝐚𝐧𝐝 𝐏𝐫𝐨𝐟𝐢𝐭 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧: 
The West region shows the highest sales and profit, indicating strong performance in this area. In contrast, the South region has the lowest figures, pointing to a potential need for strategic adjustments or market penetration efforts.

𝐒𝐚𝐥𝐞𝐬 𝐚𝐧𝐝 𝐏𝐫𝐨𝐟𝐢𝐭 𝐛𝐲 𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲 𝐚𝐧𝐝 𝐒𝐞𝐠𝐦𝐞𝐧𝐭: 
The consumer segment in Furniture has a significant impact on sales, with Office Supplies also performing well. This suggests that focusing on these segments could yield higher returns.

𝐏𝐫𝐨𝐟𝐢𝐭 𝐛𝐲 𝐒𝐭𝐚𝐭𝐞: 
The sum of profit by state map highlights variations in profitability across different states, suggesting that some states are more profitable than others. This information can help tailor state-specific strategies to maximize profit.

𝐒𝐚𝐥𝐞𝐬 𝐛𝐲 𝐒𝐮𝐛-𝐂𝐚𝐭𝐞𝐠𝐨𝐫𝐲: 
The sales distribution by sub-category shows that machines and phones dominate the Technology category, while chairs and tables are significant contributors in Furniture. This insight can guide inventory and marketing focus.

# Recommendations
𝐏𝐫𝐨𝐟𝐢𝐭 𝐌𝐚𝐫𝐠𝐢𝐧 𝐈𝐦𝐩𝐫𝐨𝐯𝐞𝐦𝐞𝐧𝐭: 
Analyze cost structures and pricing strategies to enhance profit margins. Focus on high-profit categories like Technology while managing costs in other areas.

𝐓𝐚𝐫𝐠𝐞𝐭𝐞𝐝 𝐌𝐚𝐫𝐤𝐞𝐭𝐢𝐧𝐠: 
Increase marketing efforts in the West region, leveraging its strong sales performance. Explore strategies to boost sales in the South region, such as localized marketing campaigns or partnerships.

𝐒𝐞𝐠𝐦𝐞𝐧𝐭 𝐅𝐨𝐜𝐮𝐬: 
Prioritize consumer segments in the Furniture and Office Supplies categories, as they show substantial sales contributions. Develop targeted promotions or loyalty programs for these segments.

𝐒𝐭𝐚𝐭𝐞-𝐋𝐞𝐯𝐞𝐥 𝐒𝐭𝐫𝐚𝐭𝐞𝐠𝐢𝐞𝐬: 
Develop tailored strategies for each state based on profitability data. Invest more in states with higher profits and analyze the factors contributing to lower profitability in other states.

𝐈𝐧𝐯𝐞𝐧𝐭𝐨𝐫𝐲 𝐌𝐚𝐧𝐚𝐠𝐞𝐦𝐞𝐧𝐭: 
Optimize inventory levels for high-demand sub-categories like machines, phones, chairs, and tables to ensure product availability and minimize stockouts.

𝐵𝑦 𝑢𝑠𝑖𝑛𝑔 𝑡ℎ𝑒𝑠𝑒 𝑖𝑛𝑠𝑖𝑔ℎ𝑡𝑠, 𝑡ℎ𝑒 𝑜𝑟𝑔𝑎𝑛𝑖𝑧𝑎𝑡𝑖𝑜𝑛 𝑐𝑎𝑛 𝑏𝑜𝑜𝑠𝑡 𝑠𝑎𝑙𝑒𝑠 𝑏𝑦 𝑡𝑎𝑟𝑔𝑒𝑡𝑖𝑛𝑔 ℎ𝑖𝑔ℎ-𝑝𝑜𝑡𝑒𝑛𝑡𝑖𝑎𝑙 𝑚𝑎𝑟𝑘𝑒𝑡𝑠 𝑎𝑛𝑑 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑠𝑒𝑔𝑚𝑒𝑛𝑡𝑠 𝑚𝑜𝑟𝑒 𝑒𝑓𝑓𝑒𝑐𝑡𝑖𝑣𝑒𝑙𝑦. 𝑇ℎ𝑖𝑠 𝑤𝑖𝑙𝑙 𝑒𝑛ℎ𝑎𝑛𝑐𝑒 𝑝𝑟𝑜𝑓𝑖𝑡 𝑚𝑎𝑟𝑔𝑖𝑛𝑠 𝑡ℎ𝑟𝑜𝑢𝑔ℎ 𝑏𝑒𝑡𝑡𝑒𝑟 𝑐𝑜𝑠𝑡 𝑚𝑎𝑛𝑎𝑔𝑒𝑚𝑒𝑛𝑡 𝑎𝑛𝑑 𝑠𝑡𝑟𝑎𝑡𝑒𝑔𝑖𝑐 𝑝𝑟𝑖𝑐𝑖𝑛𝑔. 𝐴𝑑𝑑𝑖𝑡𝑖𝑜𝑛𝑎𝑙𝑙𝑦, 𝑜𝑝𝑡𝑖𝑚𝑖𝑧𝑖𝑛𝑔 𝑠ℎ𝑖𝑝𝑝𝑖𝑛𝑔 𝑝𝑟𝑜𝑐𝑒𝑠𝑠𝑒𝑠 𝑐𝑎𝑛 𝑟𝑒𝑑𝑢𝑐𝑒 𝑐𝑜𝑠𝑡𝑠 𝑎𝑛𝑑 𝑖𝑚𝑝𝑟𝑜𝑣𝑒 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑠𝑎𝑡𝑖𝑠𝑓𝑎𝑐𝑡𝑖𝑜𝑛. 𝐸𝑥𝑝𝑎𝑛𝑑𝑖𝑛𝑔 𝑖𝑛𝑡𝑜 𝑛𝑒𝑤 𝑚𝑎𝑟𝑘𝑒𝑡𝑠 𝑏𝑎𝑠𝑒𝑑 𝑜𝑛 𝑔𝑒𝑜𝑔𝑟𝑎𝑝ℎ𝑖𝑐 𝑎𝑛𝑑 𝑐𝑢𝑠𝑡𝑜𝑚𝑒𝑟 𝑑𝑎𝑡𝑎 𝑐𝑎𝑛 𝑐𝑟𝑒𝑎𝑡𝑒 𝑛𝑒𝑤 𝑔𝑟𝑜𝑤𝑡ℎ 𝑜𝑝𝑝𝑜𝑟𝑡𝑢𝑛𝑖𝑡𝑖𝑒𝑠 𝑎𝑛𝑑 𝑖𝑛𝑐𝑟𝑒𝑎𝑠𝑒 𝑝𝑟𝑜𝑓𝑖𝑡𝑎𝑏𝑖𝑙𝑖𝑡𝑦.


# Snapshot of Amazon Sales Dashboard (Power BI Desktop)
![Amazon Sales Dashboard](https://github.com/user-attachments/assets/74f6a7d2-aa0f-4633-adca-0c55594162fa)


