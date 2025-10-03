In this project, I developed a Sales Analytics Dashboard in Power BI. The primary objective was to help the company visualize key business metrics such as month-on-month sales trends, growth across regions and product categories, and areas where profit margins could be optimized.

The data sources included a combination of a SQL database and Excel sheets. Using Power Query, I performed extensive data cleaning—handling missing records, correcting data types, and merging multiple tables into a structured dataset.

For the data model, I designed a star schema with one central fact table (Sales) and supporting dimension tables (Date, Product, and Region). Relationships were established using one-to-many joins to ensure consistency and scalability.

I created several DAX measures to drive business insights, including:

Total Sales = SUM(Sales[Amount])

Profit Margin = DIVIDE(SUM(Sales[Profit]), SUM(Sales[Amount]))
Additionally, I implemented advanced measures using CALCULATE with filters to support dynamic analysis.

The dashboard incorporated a variety of visuals, such as slicers for filtering, drill-down charts for detailed analysis, line charts for sales trends, bar charts for category performance, and KPI cards for quick overviews. Through this, we uncovered key insights: for example, Region B showed a noticeable decline in sales during Q3, while some product categories exhibited high profit margins but relatively low sales volume.

I also faced a few challenges. The initial dataset was very large, which caused performance issues. To address this, I optimized the model by removing unnecessary columns, leveraging DAX variables for efficiency, and maintaining query folding in Power Query.



Overall, this project demonstrates my ability to work end-to-end in Power BI—from data preparation and modeling to visualization and business insights.

**NOTE**
If you are not able to see dashboard here you can save that raw file.


