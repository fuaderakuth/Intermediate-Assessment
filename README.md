# Intermediate-Assessment
## Codeathon

#### 1. Data Cleaning & Loading 
  *  The duplicates were removed upon loading the data to power query
  *  OrderDate field were standardized by using Locale. 
  *  Changed every Column type matching to it values.
  *  Replaced missing values in categorical fields with Unknown.
  *  Replaced missing values in quantitative fields like UnitPrice, Sales, Cost and Profit by Adding calculated columns ( Ex, if UnitPrice=null, replaced it by Sales/Quantity).
#### 2. Visualization 
  * Reference in the Screenshot "Charts & Measure.png".
#### 3. Data Visualization 
  * Created calculated table "EasterRegionOrders" using "Filter".
  * Created calculated column "ProfitCostDifference" by subtracting (Profit - Cost).  
  * TotalProift measure is found by Sum(SalesData[Profit]).   
