<h1> <p style="text-align: center";>  <B> SupplyChain Analytics </B> 

 <h2> Problem Background </h2>

 A DataSet of Supply Chains used by The company DataCo Global  of  information management consultancy providing a comprehensive service to the upstream oil and gas industry.

 The Company has significant amounts of data on its Supply chain efficiency,profitability and revenue ,Warehouse and inventory details.
 
### Insights and recommendations are produced on the following key areas:

- Supply Chain Efficiency → Metrics: On-Time Delivery Rate, Lead Time, Order Fulfillment Rate → To optimize logistics and reduce delays.
 
- Profitability & Revenue → Metrics: Gross Profit Margin, Revenue Growth, Cost per Order → To assess financial performance and maximize earnings.

- Markets & Customer Insights → Metrics: Customer Retention Rate, Sales by Region, Average Order Value → To identify growth opportunities and improve customer engagement.

- Warehouse & Inventory Details → Metrics: Inventory Turnover, Stockout Rate, Warehouse Utilization → To enhance inventory management and reduce holding costs.

 An interactive dashboard can be downloaded [here](https://github.com/Jeevith2004/SupplyChain_Analytics/raw/main/SupplyChain_Analytics.pbix)

 The Excel Spreadsheet utilized to inspect and perform quality checks can be found [here](https://d.docs.live.net/FBC0932A75D18E8C/Documents/Desktop/DataCoSupplyChainDataset.xlsx)

 The Excel spreadsheet aftre cleaning and preprocessing data can be found [here](https://1drv.ms/x/c/fbc0932a75d18e8c/EaJ_xrpbE2BImLfkzXbTfv8B9LiDpgBbpUuf4Zy8v4lKdA?e=ZnKAiv)

  <h2> Data Structure & Initial checks </h2>
  
  <h2> Executive Summary </h2>

  __Key Performance Index__

  The company is facing significant challenges in key performance metrics, with multiple areas underperforming against targets:

- Average Discount Per Order is __20.24__, exceeding the goal of __10 by 102.35%__, indicating higher-than-expected discounts __impacting profitability__.
  
- Total Revenue is __14.41K__, falling 27.96% short of the 20K goal, reflecting __lower than expected sales__.
  
- On-Time Delivery Rate is __41.18%__, significantly below the 95% target, suggesting major __inefficiencies in logistics and order fulfillment__.

However, some positive trends were observed:

- Average Fulfillment Time is __3.66__, which is __26.76% better than the target of 5__, indicating faster processing of orders.
  
- Customer Lifetime Value (CLV) stands at __14,420, slightly surpassing the 14.41K target by 0.09%__, showing stability in long-term customer value.
  
- Average Shipping Delay is __0.62, which is 68.96% better than the target of 1.99__, highlighting improved delivery speed in some cases.

 Below is the KPI page from the PowerBI dashboard and more examples are included throughout the report.


  ![Screenshot 2025-03-16 154909](https://github.com/user-attachments/assets/153a4d1c-a306-44c3-8f1a-e240a23dbb57)

 <h4> SupplyChain Efficiency </h4>

 - The company's On-time delivery rate is reduced by 42.51%,Less than half of the shipments arrive on time because of shipping inefficiencies, mainly due to 
   **heavy reliance on Second-Class shipping**, which has the highest delay rate.

 - Second-Class shipping has the highest average delay (1.97 days) due to **lower priority in carrier networks** and **bulk handling inefficiencies**, while 
   First- Class (1.00 days) also faces delays, likely due to **inefficient order fulfillment despite being a premium option**, whereas Same-Day and Standard Class 
   perform well because of **dedicated fast-track logistics** ensuring timely deliveries.

 - **Regions like Oceania, West Africa, and Central America** experience the highest shipping delays, driven by **weaker logistics infrastructure, customs 
   bottlenecks, and limited carrier options**, resulting in longer transit times. These regions consistently show higher average delays in historical trends, 
   impacting customer satisfaction and order fulfillment efficiency. In contrast, **Canada has the lowest delay rates, indicating a strong local distribution 
   network and faster last-mile deliveries**. Larger geographical regions, such as parts of Africa and Central America, naturally face extended shipping times due 
   to **remote deliveries, increasing the overall late delivery risk and operational costs**.

 - The consistently high late deliveries over time, as shown by the red trend, indicate persistent supply chain inefficiencies, with a **peak of 229 late 
   deliveries  in January 2016** due to seasonal demand spikes. Despite a slight improvement in on-time deliveries, the gap remains significant, suggesting that 
   process optimizations have not been effective in reducing overall delays.
   

 ![Screenshot 2025-03-16 161954](https://github.com/user-attachments/assets/5c9a2e65-b7d7-40f1-882d-bc283a8801e0)

 <h4> Profitability & Revenue Analysis </h4>

 - **Western Europe and Central America emerge as the highest profit-contributing regions, generating 244.15K and 241.78K**, respectively, indicating strong 
   market demand, efficient logistics, and favorable pricing strategies. Southern Europe, Northern Europe, and South America also contribute significantly but at 
   a lower scale, whereas regions like South Asia, Eastern Europe, and Central Africa have relatively low profit contributions, possibly due to limited market 
   penetration, delay in shipping due to the usage of second class shipping mode.

-  In terms of product categories, Fishing (0.30M) and Golf Clubs (0.19M) lead in profitability, followed by Camping Equipment (0.15M) and Cycling (0.12M), 
   reflecting strong customer demand and premium pricing in these segments. However,**many other product categories contribute minimal profits, likely due to 
   lower Sales volume, price sensitivity, or higher competition affecting margins**.

-  The Profitability Impact of Discounts visualization clearly shows that**excessive discounting reduces profit margins, with transactions offering more than 50% 
   discount experiencing a steep decline in profitability**. Most profitable transactions occur at lower discount levels, highlighting the need for an optimized 
   pricing strategy that balances sales volume with margin retention.

- Analyzing revenue and profit trends over time, **the Yearly and Monthly Analysis chart indicates consistent revenue growth with periodic fluctuations in 
  profitability**. While revenue remains stable and higher than profit, some months experience sharp drops in profitability, likely due to seasonal demand 
  variations, promotional campaigns, or rising operational costs. This suggests the business needs to refine its discounting and cost management strategies to 
  maintain profitability while sustaining revenue growth.

  ![Screenshot 2025-03-16 203922](https://github.com/user-attachments/assets/44ccf840-7cae-466b-aa24-5e91fad1fef3)


<h4> Customer & Market Insights </h4>

 - The Total Revenue by Order Region visualization highlights that **Central America (11,306 orders) and Western Europe (10,647 orders) are the top-performing 
   regions, indicating strong market presence and high customer engagement**. However, regions like South Asia (2,462 orders) and the Caribbean (3,411 orders) 
   have significantly lower order volumes, suggesting potential for market expansion.

 - The **Repeat Purchase Rate (71.12%) shows that a large portion of customers are returning**, with 9.75K repeat customers compared to only 3.96K new customers 
   (40.6%), emphasizing strong brand loyalty but also indicating a need to attract more new customers to sustain long-term growth.

-  The Total Profit by Customer Segment chart reveals that Consumer customers contribute the **highest profit (833.04K, 52.75%), followed by Corporate (482.65K, 
   30.56%)**, while Home Office accounts for only 263.44K (16.68%).which contributes the largest share of profits at 833.04K (52.75%), as individual consumers 
   place more frequent orders compared to corporate and home office customers. Additionally, pricing and discount strategies differ, with corporate and home 
   office  Customers likely receiving bulk discounts or special pricing, reducing their per-order profit margins despite significant sales. Furthermore, 
   variations in  product mix and order value play a role, as consumers may purchase higher-margin products, whereas corporate and home office segments often 
   focus on bulk  orders of lower-margin items such as office supplies.

-  The Sum of Sales trend over time remains relatively stable, averaging between 0.3M and 0.4M, but a sharp decline occurs towards the end of the timeline (early 
   2018). This could be due to ,**If repeat purchases declined during this period, it could have directly impacted sales,drop in sales from high-performing 
   regions** (such as Central America and Western Europe) could have contributed to the downturn.

   ![Screenshot 2025-03-16 181418](https://github.com/user-attachments/assets/5e6a7b17-6a4f-4daa-8290-2e9236feafc2)


  <h4> Warehouse & Inventory Optimization </h4>

  - The Total Revenue by Product Name analysis shows that Perfect Fitness is the top-selling product, **generating 6.47M, followed by Nike Men's Free 5.0+ with 
    3.24M in revenue. On the other hand, products like Porcelain Crafts and Dell Laptops contribute significantly less**. High revenue is likely driven by a 
    higher number of orders for fitness-related products, as they have a consistent consumer base. Products in the fitness and sports categories generally see 
    higher demand compared to niche categories like crafts or electronics, which may have slower purchase cycles.

  - The Avg Processing Time Per Location reveals that **Europe experiences the highest delays, while North and South America show better processing efficiency**. 
    These regional variations may be due to logistics challenges, customs delays, supply chain inefficiencies, or higher order volumes in Europe.And the Reason 
    could be **Shipping & Location Factors,Order Volume,Supplier and Distribution Centers**.
  
  - The Inventory Turnover Rate by Category highlights that **Computers (1,500), Strength Training (866), and Basketball (737) have the highest turnover rates, 
    indicating strong demand and fast stock movement. In contrast, categories like Fishing (400) and Cameras (452) have lower turnover**, which could be due to 
    seasonal fluctuations, oversupply, or lower consumer demand.High-priced items like computers move quickly because of consistent business and consumer demand
     on discounts and promotions, which can influence inventory movement. Categories with **frequent discounts could see higher turnover rates**.

    ![Screenshot 2025-03-16 192419](https://github.com/user-attachments/assets/3c85ab2d-f675-4a6b-8667-5ea18f06e137)

 <h4> Recommendations: </h4>

 Based on the uncovered insights,the following recommendations have been provided:

   - Optimize shipping methods by reducing reliance on Second-Class shipping, which has the highest delay rate, and prioritizing Standard and Same-Day shipping 
     for critical orders. Implement automated carrier selection based on region, urgency, and historical performance to improve on-time delivery rates.

   - Address regional logistics bottlenecks in high-delay regions such as Oceania, West Africa, and Central America by investing in stronger distribution 
     networks, regional fulfillment centers, or third-party logistics (3PL) partnerships to mitigate customs and last-mile delivery delays.

   - Improve demand forecasting and inventory allocation using predictive analytics to pre-stock inventory in high-demand regions, reducing processing times and 
      preventing stockouts. Dynamically allocate inventory based on regional demand patterns to minimize delays caused by cross-border shipments.

   - Refine the discounting strategy by reducing excessive discounting beyond 50%, which directly impacts profit margins. Implement data-driven price elasticity 
     modeling to set optimal discounts without eroding profitability.

   - Expand high-profit product categories, such as Fishing and Golf Clubs, by leveraging insights from product sales data and customer demand trends. Introduce 
     targeted marketing efforts to boost sales in these high-margin categories.

   - Strengthen customer segmentation and retention strategies by leveraging data-driven insights to offer personalized discounts and loyalty incentives to high- 
     value customers.


