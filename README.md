

📁 Dataset Description
The dataset contains real-world transactional data from an online retail store. It includes:

InvoiceNo: Unique ID for each transaction

StockCode: Unique product identifier

Description: Product name

Quantity: Number of units purchased

InvoiceDate and InvoiceTime: Date and time of the transaction

UnitPrice: Price per unit in GBP

CustomerID: Unique customer identifier

Country: Country of the customer

🧹 Data Cleaning Steps
Before analysis, the dataset was cleaned to ensure quality and accuracy:

Removed Negative Quantities

Records with Quantity < 1 (indicating returns or errors) were excluded.

Filtered Invalid Prices

Records where UnitPrice <= 0 were removed.

Added Custom Columns

Revenue = Quantity * UnitPrice

Year and Month columns were extracted from InvoiceDate.

📊 Dashboard Features
The Power BI dashboard includes the following visuals:

1. Monthly Revenue Trend
Shows how revenue changes over time using a line chart. Helps identify sales spikes or slow months.

2. Country-wise Sales Distribution
Displays total revenue and quantity sold by country using a bar chart or map visual.

3. Top Products by Revenue
Ranks products based on their total revenue contribution.

4. Top Customers by Purchase Value
Highlights customers who made the highest purchases in total — useful for understanding high-value users.

5. Data Filters
Interactive filters are available for:

Year / Month

Country

Customer ID

Product
