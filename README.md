
# Financial_Analysis-Dashboard

### Dashboard 
![Full](https://github.com/user-attachments/assets/79923886-6f77-4963-9afa-8505bc0cefbb)

## Problem Statement

This dashboard helps businesses understand their financial performance better. It provides insights into total revenue, average revenue, and total transactions. It allows companies to identify revenue distribution across different stores, products, and regions, helping them to optimize their strategies and improve overall performance.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Ensure data profiling is based on the entire dataset: profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty .

Key Findings:

- Step 5 : In the report view, under the Format page, Canvas background was selected.
- Step 6 : New measure was created for Total Revenue and Average Revenue. 
- Step 7: Two card visuals were added. One representing Total Revenue and other representing Average Revenue.

  ![Total Revenue](https://github.com/user-attachments/assets/26042471-f403-431d-837c-f3b8d99d2f7e)

  ![AVg rev](https://github.com/user-attachments/assets/8c5657fc-c312-4897-9920-4da241fbbbc5)

- Step 8 : New measure was created to find Total number of transactions. Using Card visualizations, o was created Total number of transactions.

  ![Total cu](https://github.com/user-attachments/assets/cae3d1dc-c51e-436c-ac79-49370f2adfbd)

- Step 9 : Visual filters (Slicers) were added for four fields named "products", "Gender" & "Years".

- Step 10 : Pie chart was also added to the report design area representing the total revenue by Regions in perecntage. 
    U.S.A.: 78.65M (61.73%)
    U.K.: 32.14M (25.2%)
    Asia: 16.62M (13.06%)

- Step 11: Revenue Distribution - I was created total revenue by stores. Using Line Chart visual to diplay the revenue.
    Store 1: 61.95M
    Store 2: 27.81M
    Store 3: 19.87M
    Store 4: 17.78M

- Step 12 : Using Bar chart visual to display total and average revenue by Products
    Smartphones: Smartphones are the top revenue-generating product.
    The highest total revenue for Smartphones Revenue is 20.8M.
    The highest revenue for Accessories is 5.6M.
    The highest for Laptops is 3.6M, and for Tablets, it’s 3.3M.

- Step 13 : Using Clustered bar chart for Total Revenue by Products and Rank.
    Top Products by Revenue:
      Smartphones: 39M
      Tablets: 17M
      Laptops: 12M

- Step 14 : I was created Total revenue by Quater using stacted area chart.
    Q1: Highest revenue
    Q4: Lowest revenue
        
- Step 15 : This Clustered bar chart that represents the total revenue segmented by region and rank for different stores
    The total revenue for Asia is the highest at 40M with the major contribution from Rank 1 at 21M.
    The total revenue for the U.K. is 14M, with Rank 1 contributing the highest at 8M.
    The total revenue for the U.S.A. is 8M, with Rank 1 contributing 6M.

- Step 16 : This table Chart represents the Sales Representatives Performance.

    Top performers:
      Andrew T.: 20 transactions, 20M revenue
      Louis N.: 19 transactions, 19M revenue
      Jansen B.: 13 transactions, 13M revenue

Conclusion:
The Financial_Analysis-Dashboard offers valuable insights into the financial performance of the business, highlighting key areas of strength and opportunities for improvement. By focusing on high-performing regions, optimizing the product mix, enhancing sales rep performance, and adjusting for seasonal trends, the business can enhance its overall financial health and achieve sustained growth.
