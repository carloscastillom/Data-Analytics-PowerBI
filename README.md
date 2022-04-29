# Power-Query

Udacity Projects- Use of power Query. All databasets in this repository were provided by Udacity and they were use for an academic purpose. 


## 1. Preparing and Modeling Data.

Training in Extract, Transform and Load of data provided using Power Query and creationand use of measures in DAX, in the following images, you are able to see a very simple data schema and a basic table. 

  Data Schema of the data supplied by Udacity.  
  ![datschema](https://user-images.githubusercontent.com/65776444/159014165-333d86e6-42bd-4ba7-9163-b1b5506ef68e.PNG)

The image above show a very simple star schema. You can clearly see the different tables with their respective columns. the fact table is connected through 3 dimension tables and Each conections is one-to-many. 

  ![DaxQuick](https://user-images.githubusercontent.com/65776444/159014761-af262076-f018-4b1e-8836-cc25fcf7962e.PNG)
  
  
## 2. Seven Sage Brewing Company

Application of Extract, Transform and Load of data provided by Udacity for a company called Seven Sage Brewing Company (SSBC) 

### Main Steps
Here are the main steps. We'll go over each of these in more detail on the pages that follow.

  * Source files. Download and familiarize yourself with the source files provided by SSBC.
  * Sketch the data model. Sketch out the data model you intend to build.
  * Use Get Data. Use Get Data to load the data from the starter materials into Power BI.
  * Structure, combine, and clean the data. Clean and format your data so that it will work well in your data model.
  * Create your date table. Create a date table to support time intelligence.
  * Build relationships between your tables. Build a relationship from each dimension to the relevant key on the fact table.
  * Write your measures. To satisfy the CFO's requirements, we will need to write six measures—to calculate Sales, Cost of Sales and Gross Profit Margin in two       different currencies.
  * Create a report. Build a basic visual report to display your findings.


![image](https://user-images.githubusercontent.com/65776444/162724752-5b70439a-c8b8-4027-af7b-3fbc32d3de6a.png)

The table above is sorted by total sales. The distributors are responsible for 94 Million dollars which is more than half of total sales for the fiscal year. Their gross profitranges from 9% to 16%. on the other side, After SSBC testing room, the Bars have the highest Gross Profit margin in the customer types inside the customer type, we have varied profit margins that ranges from 33% as low as 4%. It is worth it to look for opportunities in the bar segment as new incoming customer may provide a large profit.


![image](https://user-images.githubusercontent.com/65776444/162725284-0bfeb25e-b692-4bd2-a90b-4673959daad2.png)

The table above is sorted by sales by product. The 2 products with the highest profit margin also have 68% of total sales. The company's
efforts and resources should be invested in Bamboo Grove and Imperial Poet. On the other hand, the Scholar Saison product has a very low profit margin
and ranks third in total sales by product. Further research and discussion with the marketing team is needed as to whether it makes sense to keep the item
in the company's portfolio.

![image](https://user-images.githubusercontent.com/65776444/162725832-50d8d590-b99b-4b9c-b484-f05f0773d4f7.png)

The Half Keg is the product type that on average is most profitable. Followed by the Keg, Six pack and the tasting room pour, on that
order. The brand name Scholar Saison have a very low per serving gross profit across all product types, in the Six pack even have a negative gross profit.

![image](https://user-images.githubusercontent.com/65776444/162725909-7b4614c9-6186-4cff-ad41-9eb064c965bb.png)

It seems there there are peak of sales in May, November and Decemenber. The Product Poet had consistence sales until may from then on, it seems the
Scholars Saison took over cannibalize those sales. The Other Products range between 400 to 800 following the sames general seasonality.


## 3. Compelling Data Visualization

Training in graphs and charts making. Based on the dataset supplied by udacity I created the following charts in Power BI


![image](https://user-images.githubusercontent.com/65776444/163197223-d7687a04-61fa-45e3-b012-df431f53846f.png)



![image](https://user-images.githubusercontent.com/65776444/163197295-30fc3c26-6060-4376-bea7-c61ff16a2f6a.png)


![image](https://user-images.githubusercontent.com/65776444/163197356-43912fb8-f971-4097-b33f-6504d3411647.png)


## 5. Waggle project

all pages have a define spaces for Filters and buttons for page navigation on the left hand side of the dashboard.

![image](https://user-images.githubusercontent.com/65776444/163332962-fc1e3832-7ff0-4f0b-940b-e1d33e4bd793.png)



Home Page

![image](https://user-images.githubusercontent.com/65776444/163332355-165f8f41-72ea-412a-9a38-c258032275c2.png)


Pets Insights

![image](https://user-images.githubusercontent.com/65776444/163332432-d14299e6-77d1-4847-803c-912c84731cb7.png)

Family Insights

![image](https://user-images.githubusercontent.com/65776444/163332585-e25fa616-6910-4eab-a96e-028cf82b984b.png)







## 5. Market Analysis Report for National Clothing Chain

Project Description
An online national clothing chain needs your help creating a targeted marketing campaign. Sales have been flat and they want to lure lost customers back. They want to advertise specific products to specific customers in specific locations, but they don’t know who to target. They have three products in mind:
 - Shirt: $25
 - Sweater: $100
 - Leather Bag: $1,000


You’ll need to present your analysis as a 1 page written summary and visual report in Power BI. Use the following visuals to present your data:

- Income Distribution: Histogram
- Household Income by Location: Map
- Correlations: Scatter Plot with Trendline and Card with R^2 value
- Use other visuals as-needed to further present the results of your analysis.


Include the analysis

