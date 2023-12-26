# **SQL-PBI_Customer-Segmentation-and-Product_Analysis**

![3cca8b1c185889a32f976b50641d3084](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/311bb569-bde0-4abe-97e7-5597c7747c31)

## I. **Introduction**

### **1. Business Question**

Adventure Works Cycles, a **large, multinational manufacturing company**,  **produces and distributes metal and composite bicycles** to North American, European,  and Asian commercial markets. While its base operation is located in Bothell,   Washington, and employs 500 people, several regional sales teams are located throughout the company’s market region. In 2000, Adventure Works Cycles bought a   small manufacturing plant, Wide World Importers, which is located in Mexico City,  Mexico. Wide World Importers manufactures several critical subcomponents for the  Adventure Works Cycles product line. These subcomponents are shipped to the Bothell  location for final product assembly. In 2001, Wide World Importers became the sole  manufacturer and distributor of the touring bicycle product group.

After a successful fiscal year, Sales Manager of Adventure Works Cycles **is looking to broaden its market share by focusing its sales efforts on the company’s best customers and product category.** 

### **2. Dataset**

- Dataset: **adventureworks2019** (public Google BigQuery dataset)
- Dataset dictionary: Please reach file "Data Dictionary" attached above
- Dataset Schema: https://i0.wp.com/improveandrepeat.com/wp-content/uploads/2018/12/AdvWorksOLTPSchemaVisio.png?ssl=1
- Dataset access:
    - Log in to your Google Cloud Platform account and create a new project.
    - Navigate to the BigQuery console and select your newly created project.
    - In the navigation panel, select "Add Data" and then "Star a project by name".
    - Enter the project name "adventurework2019"

### **3. Data dictionary**

[https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/blob/main/02. AdventureWorks _ Data Dictionary.pdf](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/blob/main/02.%20AdventureWorks%20_%20Data%20Dictionary.pdf)

## **II. Design Thinking Method**

**Here are the five steps of design thinking:**

### Step 1 - Empathize

![1Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/2e001d0b-54ba-4d64-b438-e7e75884c417)

### Step 2 - Define

![2Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/a66ca427-489b-4770-873a-6783cbe2bb6c)

### Step 3 - Ideate

![3Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/a6a1a94d-c3ae-42de-ac84-2c0409281a44)

### Step 4 - Prototype

![4Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/43e7bd13-f10d-4a6a-9fac-8ebdbc008898)

### Step 5 - Review

![5Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/1b9393be-587b-4f4d-8bd6-7740aa2a3b70)

## III. Visualization

### 1. Customer segmentation

![6Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/a00c638f-4712-49b2-83cb-70df9fb0f679)

### 2. Product Category

![7Untitled](https://github.com/hatrang12/SQL-PBI_Customer-Segmentation-and-Product_Analysis/assets/107136018/0c62888f-ce09-4486-908a-a4f27bacf222)

## IV. Insights

- Overview:

In general, total revenue in the market tends to fluctuate year by year and grew strongly in the period 2011-2013, then decreased relatively sharply in 2014. Therefore, there is a need for a customer restructuring strategy. products and services with the goal of optimizing profits

- Customer segment:
    - Customers buy products mainly from the North America region with 75% of total revenue for the period. With 6 countries and 68 territories, this is Adventure Works' main market, accounting for more than half of the annual revenue and customer base.
    - On the other hand, it can be seen that in this market there is a tendency to use products from the Road production line (2011, 2012) to Standard and Mountain (2013, 2014) and back, so businesses need a way to Production projects appropriate to consumer trends.
    - Looking at customer segment groups by Segment, we see that the Loyalty group has a large number of customers with high product preference compared to the Champions and Potential Loyal groups, but the sales proportion is quite low compared to These 2 groups. Therefore, businesses need to find out why and focus on customer care for this group to promote revenue growth. From the Top 10 Customers table, we can identify priority customers to focus on research, thereby building a strategy for building long-term relationships based on regional characteristics, interests, etc.
- Product:
    - Bicycles are the main product of the business, accounting for a significant portion of revenue over time. Among them, Road Bikes are the most popular products in the entire period 2011-2014, however, two new product lines developed in the last two years 2013-2014, Mountain Bikes and Touring Bikes, promise to generate good and stable revenue growth, especially since 2014 although the price is higher than Road Bikes.
    - The market where Bike lines grow the most strongly is still North America. Therefore, it is still necessary to focus on product marketing and customer care strategies in this market. On the other hand, the Touring Bikes market also developed quite strongly in Europe and Pacific markets in 2014, accounting for the largest revenue in these two market groups, showing revenue potential if a marketing and care strategy is put in place. Proper customer care targets segments in these markets.
    - Realizing that March revenue is always the highest every year, demonstrating the potential demand of consumers to buy bicycles, so it is also necessary to promote marketing and advertising strategies during the above period.
    - Through the Top 10 table, we can identify outstanding products with significant revenue as well as always very high customer preference scores (SPL), especially some Mountain line products, from which we come up with a strategy. the right marketing strategy.
    - Through Bottom 10, we can identify ineffective business product groups to reduce and replace in production with the goal of optimizing business costs.

## V. Recommendations

Through analyzing the characteristics of customer segmentation and product category, there are some suggestions for business as follows:

Some improvement policies we suggest to focus on loyal customer service focused in North America and selected product category are as follows:

- **Proactive Communication:** Keep loyal customers informed about new products, promotions, and relevant industry updates. Proactively communicate with them through newsletters, emails, or personalized messages to show that you value their business.
- **Responsive Customer Support:** Ensure that customer support is easily accessible and responsive. Address queries and concerns promptly, and strive to exceed customer expectations. Use multiple channels such as live chat, email, and phone support.
- **Loyalty Programs:** Implement and optimize a loyalty program to reward customers for their repeat business. Offer discounts, exclusive promotions, or early access to new products for loyal customers.
- **Exclusive Offers and Events:** Provide exclusive offers or invite loyal customers to special events, such as product launches, VIP sales, or community rides. This makes them feel valued and part of an exclusive community.
- **Feedback Collection:** Actively seek feedback from loyal customers. Use surveys, reviews, and direct feedback to understand their preferences, identify areas for improvement, and tailor your offerings to better meet their needs.
- **Surprise and Delight:** Occasionally surprise your loyal customers with unexpected perks, such as a free accessory with a purchase or a personalized thank-you note. These small gestures go a long way in building emotional connections.
- **Seasonal Campaigns:** Plan and execute marketing campaigns around seasonal trends or events, such as biking season, holidays, or major cycling competitions. Capitalize on these opportunities to boost visibility and sales.
