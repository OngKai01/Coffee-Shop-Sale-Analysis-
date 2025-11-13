# Coffee-Shop-Sale-Analysis

## I.Project Background and Overview

This project aims to analyze historical coffee sales data to uncover key business trends, understand customer preferences and retention, and identify oppurtunities for growth. 

## Tools Used 
- **Data Preparations**: Used Excel Power Query to clea, transfrom and structure the dataset 

- **Analysis**: Constructd Pivot tables to EDA through agregations, summariesmand intital insights. 

- **Visualization**: Created Pivot Graphs for visualizations and Slicers for interactive filtering

- **Dashboard** Developed a fully interactive Dashboard to uncover trends and present key findings for stakeholders and user


## II.Data Structure Overview

This analysis is built upon a transactional sales dataset. Each of the rows in the data represents an order from 
a customer. This data structure consists of 3 tables; Orders, Customer and Product

|**Order**     |    *Description*                                                    |
|-------------|---------------------------------------------------------|
| Order ID  | A unique Identifier for each transactin                  |
| Order Date | The date the order was placed                           |
| Customer ID| Unique identifier and tname of the purchasing customer  | 
| Product ID | Identifer from the coffee product                       |
| Quantity   | Quantity of products in the order                       |


|**Customer**  |  Data Type         |
|--------------|-----------|
|Customer ID  | String    |
|Customer Name| String    |
|Email        | String    | 
|Phone Number | Numbers   |
|Address Line | String    |
|City         | String    |
|Country      | String    |
|PostCode     | Numb      |
|Loyalty Card | String    |

|**Product**  |  Data Type       |
|--------------|----------|
|Product ID    | String  |
|Coffee Type   | String  |
|Roast Type    | String  |
|Size          | Number  |
|Unit Price    | Float64 |
|Price per 100g| Float64 |
|Profit        | Float64 |



## III.Insights Deep Dive/ Exploratory Data Analysis (EDA) 
<details>
<summary> Question: Does a Loyalty Card encourage clients to spend more on purchases?</summary>
<img width="422" height="120" alt="image" src="https://github.com/user-attachments/assets/adfea50f-76ef-4409-b91a-a9811f0999ea" />
<img width="1012" height="614" alt="image" src="https://github.com/user-attachments/assets/66104be2-ab82-454e-8584-db306f35eb03" />
**Key Insights**: 
  - Looking at the average and sum spending of those with and without royalty card, we see that there is a small margin between the two. In fact, we see that clients without the royalty card, on average spend more on an order than loyal customers. 
</details>
------------------------------------------------------
<details>
  <summary>Click to expand/collapse</summary>
  This is the content that will be hidden by default and revealed when     the summary is clicked.
</details>



## IV.Recommendations


## V.DashBoard 
<img width="2086" height="1250" alt="image" src="https://github.com/user-attachments/assets/050a86d8-1984-4fe5-af7f-0dd832165cbf" />






