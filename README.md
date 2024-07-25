# Strategic Analysis of Beauty Product Sales and Supply

## Project by: Razi Haider

### Executive Summary
This project analyzes beauty product sales and supply data to identify key insights and trends in product performance, revenue generation, and supply chain efficiency. The primary objective is to enhance and optimize sales strategies, inventory management, and overall supply chain operations for a beauty product company. Key findings include insights into product performance across categories, stock management strategies, and recommendations for improving manufacturing and transportation efficiency.

### About the Project
The project focuses on analyzing beauty product sales data to uncover:
- Most popular product categories
- Highest revenue-generating products
- Daily and monthly sales trends
- Inventory management and stock levels
- Manufacturing costs and supply chain efficiency
- Transportation and carrier performance

The primary goal is to provide actionable insights to optimize operations, enhance sales strategies, and improve overall customer satisfaction.

### Data Description
The dataset contains various features related to sales and supply chain:

## Data Description

The dataset comprises various features related to beauty product sales and supply. Below is the detailed column information along with the data types for each column:

| Column                    | Description                                       | Data Type      |
|---------------------------|---------------------------------------------------|----------------|
| Product type              | Type of the beauty product                       | Object         |
| SKU                       | Stock Keeping Unit (unique identifier)           | Object         |
| Price                     | Price of each product                            | Float64        |
| Availability              | Stock availability status                        | Int64          |
| Number of products sold   | Total number of products sold                    | Int64          |
| Revenue generated         | Total revenue generated from sales                | Float64        |
| Customer demographics     | Demographic information of customers              | Object         |
| Stock levels              | Current stock levels of the product               | Int64          |
| Lead times                | Lead time for product availability                | Int64          |
| Order quantities          | Quantities of orders placed                       | Int64          |
| Shipping times            | Time taken for shipping                           | Int64          |
| Shipping carriers         | Carrier used for shipping                         | Object         |
| Shipping costs            | Cost associated with shipping                     | Float64        |
| Supplier name             | Name of the supplier                              | Object         |
| Location                  | Location of the supplier                          | Object         |
| Lead time                 | Lead time required by the supplier                | Int64          |
| Production volumes        | Volumes of production                             | Int64          |
| Manufacturing lead time   | Lead time for manufacturing                       | Int64          |
| Manufacturing costs       | Costs incurred in manufacturing                   | Float64        |
| Inspection results        | Results of product inspection                     | Object         |
| Defect rates              | Rate of defects observed                          | Float64        |
| Transportation modes      | Modes of transportation used                      | Object         |
| Routes                    | Routes taken for delivery                         | Object         |
| Costs                     | Total costs associated with transportation         | Float64        |



### Purpose of the Project
The main goal is to provide insights and actionable information to help the beauty product company:
- Optimize inventory management
- Improve sales and revenue generation
- Enhance supply chain efficiency
- Refine transportation and logistics strategies
- Tailor marketing efforts based on customer demographics

### Recommendations

#### 1. Revenue and Pricing Strategy
- **Focus on Non-Price Factors**: Since high revenue does not necessarily correlate with high price, evaluate factors beyond pricing that contribute to revenue. Analyze the top 5 revenue-generating products despite their lower price and explore marketing approaches that could be applied to other products.
- **Stock Management**: Address potential overstocking issues indicated by the negative correlation between stock levels and revenue. Implement inventory management practices to optimize stock levels and reduce excess inventory, especially for products with high stock but lower revenue.

#### 2. Product Category Insights
- **Leverage Success in Key Categories**: Identify top-performing product categories and continue investing in them. Explore strategies to enhance their performance, such as expanding the range or increasing marketing efforts.
- **Optimize Product Categories with Moderate Performance**: Adjust pricing, promotions, or product placement for categories that show steady demand to balance revenue and sales volume.

#### 3. Stock and Manufacturing Costs
- **Reduce Manufacturing Costs**: Investigate ways to reduce production expenses for high-cost items without compromising quality. Look into cost-efficient strategies used for other products as a benchmark.
- **Cost Per Unit Analysis**: Utilize economies of scale by increasing production volumes where feasible to take advantage of lower per-unit costs.

#### 4. Inventory Turnover and Lead Times
- **Improve Turnover Rates**: Analyze inventory turnover ratios to identify patterns and optimize inventory levels. Better inventory management practices can reduce high variability in turnover rates.
- **Optimize Lead Times**: Tailor supplier selection based on lead time performance to ensure timely availability of products.

#### 5. Transportation and Carrier Efficiency
- **Select Optimal Routes**: Use the most effective routes to minimize shipping times and costs. Avoid less efficient routes for specific product types.
- **Carrier Choice**: Choose the most efficient carriers based on shipping costs and delivery times. Use different carriers depending on the product type and cost concerns.

#### 6. Demographic Targeting
- **Tailor Marketing Efforts**: Use demographic insights to guide marketing strategies and target specific customer groups based on their purchasing behavior to maximize sales.

#### 7. Transportation Quality
- **Address Defect Rates**: Implement measures to reduce defect rates in transportation by improving quality control and using alternative transport modes where necessary.

#### 8. Predictive Analysis
- **Focus on Existing Patterns**: Refine existing strategies based on current insights and patterns in revenue, stock levels, manufacturing costs, and transportation efficiency to optimize operations.
