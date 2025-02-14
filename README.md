# Manufacturing Operational Dashboard – AdventureWorks
### 1. INTRODUCTION
This **Operational Dashboard** provides a comprehensive overview of **manufacturing operations** at AdventureWorks, focusing on efficiency, production output, and inventory management. 

* It integrates key performance indicators (KPIs) such as machine downtime, production throughput, defect rates, and cost analysis, enabling stakeholders to **monitor performance trends and optimize decision-making**. 
* With interactive visualizations and real-time insights, this dashboard **enhances operational efficiency, reduces bottlenecks, and improves overall manufacturing productivity**.

### 2. DATASET
   
**AdventureWorks database** supports standard online transaction processing scenarios for Adventure Works Cycles. Scenarios include Manufacturing, Sales, Purchasing, Product Management, Contact Management, and Human Resources.

* **Dataset**: The dataset can be found in Google BigQuery under ID: adventureworks2019
* **Data Dictionary**: https://drive.google.com/file/d/1bwwsS3cRJYOg1cvNppc1K_8dQLELN16T/view

### 3. DASHBOARD
### **View 1: Inventory Mangement**
![Inventory Mangement](https://github.com/user-attachments/assets/a2b15c33-3af3-4f83-8400-8bcda5f736d0)


➡️ Insights:

* The inventory consists of 335,974 items across **432 products**, with **84.03% in safe stock** and **12.35% requiring reorder**. 
* Key storage areas like Subassembly and Miscellaneous Storage hold the highest quantities, while specialized areas have minimal stock. **Critical products**, including Hex Nut 1 and Lower Head Race, need immediate restocking to prevent shortages.
* To **optimize inventory**, redistribute stock, improve categorization, and prioritize reorder items for better supply chain efficiency.


### **View 2: Manufacturing Management**
  ![Manufacturing Management](https://github.com/user-attachments/assets/36b5f3c4-a3f8-46ed-a128-8459012b63a6)

➡️ Insights:
* The manufacturing process handled 4.5 million orders with 72,591 work orders, but 31.4% were overdue, impacting efficiency. Good efficiency was observed in 43.89% of processes, while 56.11% had inefficiencies.
* **The scrap ratio was 0.24%**, with major causes including paint process failures, trim length issues, and drill size errors.
* To **enhance production**, reducing process failures and improving on-time performance are key priorities.


### **View 3: Product Details**
![Product Details](https://github.com/user-attachments/assets/89c96fd0-6dd5-4642-8291-5b76b8b9f7ed)

* The Product Detail dashboard provides a comprehensive view of individual product specifications, inventory status, and manufacturing details.
* It displays key information such as order quantity, total orders, material components, and scrapped items due to defects like color issues and primer failures.
* Inventory insights highlight current stock levels, reorder status, and quantity distribution across locations. This dashboard enhances product tracking, quality control, and production efficiency monitoring.


### 4. RECOMMENDATIONS
**Inventory Management**
* Optimize inventory levels by setting automated reorder alerts for critical products to prevent shortages.
* Reallocate storage space by redistributing stock from overstocked locations to reduce congestion.
* Enhance forecasting accuracy by analyzing sales trends to prevent excessive stockpiling of low-demand products.
* Improve supplier coordination to ensure a steady inflow of inventory, reducing dependency on emergency reorders.

**Manufacturing Management**
* Implement process optimization by identifying and addressing inefficiencies to improve production speed and reduce waste.
* Enhance workforce training to minimize manual errors leading to defects and scrapped products.
* Improve scheduling and capacity planning to ensure timely order fulfillment and reduce overdue work orders.
* Use predictive maintenance to minimize equipment downtime and enhance overall efficiency.

**Product Details**
* Standardize quality control checks to minimize minor defects and improve overall product quality.
* Analyze material usage patterns to optimize procurement strategies and reduce costs.
* Improve defect root cause analysis to further decrease scrap rates and enhance production efficiency.
* Automate product tracking with advanced analytics to provide real-time insights into product availability and order processing.






