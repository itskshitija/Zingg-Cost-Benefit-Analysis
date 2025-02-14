# 🍾Zingg Case Study - Cost Benefit Analysis
<img src="https://github.com/user-attachments/assets/4430a3b1-7c3e-4c2f-aaa5-a0f2d04e40dd" alt="CandyMonkey Logo" width="200"/>

# For the comprehensive understanding and formulas used in the project, please refer to the [Google Sheet](https://docs.google.com/spreadsheets/d/1Rrdg4YddUoKNBgYildJ3fI1s_JJfXadMH-jTyEV4uMo/edit?usp=sharing)

## 🔍Project Overview
The Cold Drink Station is a beverage company that sells cold drinks under the brand name 'Zingg'. For the upcoming summer season, they aim to appeal to young customers in India by marketing their brand during the World Cup. The marketing head is very excited about the brand launch, but the finance manager is a bit skeptical and has requested a cost-benefit report for the event. 

As a data analyst in the marketing department, you have been asked to prepare a comprehensive cost-benefit analysis and present it through a dashboard to the marketing head.

The marketing team has decided to introduce a new bottle for Zingg, featuring World Cup-related images. This initiative will incur additional costs for a new mold and higher packaging expenses. The new bottle will replace the regular Zingg bottles for six months.

## 🚀Objective
- **Assess the financial impact of the new marketing campaign.**
- **Compare the costs and revenue projections under the old and new plans.**
- **Identify the profitability of the new initiative over the six months.**
- **Provide actionable insights and recommendations to the marketing team.**

## 📜Requirements Gathering and Documentation
As a business analyst, the first step would be to gather all the requirements necessary for the analysis and document it. Documentation is the most critical part of project development as it is the foundation of all further project deliverables describing what inputs and outputs are associated with each process function.

### 📄I have created a Business Requirement documentation for our business case [Here](https://github.com/itskshitija/Zingg-Cost-Benefit-Analysis/blob/main/Zingg-CostBenefitAnalysis_BRD.pdf)

## 📌Key Details of Beverage Pricing and Cost Analysis

### 1. Item Pricing
| Item  | Bottle (in ml) | Existing Price (in Rs. per Bottle) | New Price (in Rs. per Bottle) |
|-------|---------------|-----------------------------------|-----------------------------------|
| Zingg | 1000          | 82                                | 82                                |

### 2. Material Details of Each Bottle
| Item             | Price/Litre (in Rs.) | Material % |
|-----------------|---------------------|------------|
| Water          | 10                  | 85%        |
| Sugar Syrup    | 70                  | 10%        |
| Flavoring      | 300                 | 2%         |
| Carbonated Water | 20                | 2%         |
| Preservatives  | 400                 | 0.50%      |
| Coloring Agents| 500                 | 0.50%      |

### 3. Bottling and Processing Cost
|  | Existing Bottle (in Rs.) | New Bottle (in Rs.) |
|--------------------------------|----------------------|----------------------|
| Bottling Cost                  | 2                    | 3                    |
| Processing Cost                 | 6                    | 6                    |

### 4. Sales Quantity and Growth
| Plan      | March Sales (in units) | Month-on-Month Growth % |
|----------|----------------------|-------------------------|
| Old Plan | 725,000              | 5%                      |
| New Plan | 800,000              | 10%                     |
### 5. Factory Expenses
| Expense              | Cost (in Rs.) |
|----------------------|--------------|
| Factory Rent        | 150,000       |
| Cold Storage Cost   | 75,000        |
### 6. Marketing Expenses

| Budget Type           | March Budget (in Rs.) | Month-on-Month Growth % |
|----------------------|----------------------|-------------------------|
| Old Marketing Budget | 800,000              | 10%                     |
### 7. Incremental Marketing Cost
| Expense                 | 1st Month Cost (in Rs.) |
|-------------------------|------------------------|
| Ads Preparation         | 10,000,000             |
| New Bottling Mould      | 95,000                 |
| Incremental Advertising | 3,833,333              |

## 📊Exploratory Data Analysis

_**Note:**_ _The company will launch the advertising campaign in March and continue it until August._

### Monthly Sales of Cold Drinks under the Old Plan vs. the New Plan
| Month  | Old Plan Sales Units | New Plan Sales Units |
|--------|----------------------|----------------------|
| March  | 725,000              | 800,000              |
| April  | 762,000              | 880,000              |
| May    | 801,000              | 968,000              |
| June   | 842,000              | 1,065,000            |
| July   | 885,000              | 1,172,000            |
| August | 930,000              | 1,290,000            |

- In the Old Plan, from the third month i.e. from May, the company sees 5% month-on-month growth
- In the New Plan, from the third month i.e. from May, the company sees 10% month-on-month growth

### Price per bottle (in Rs.) under Old Plan Vs New Plan
**_Note:_** _The company has decided not to change the price of the cold drink bottle under the new plan_
| Month  | Old Plan Price per Unit (Rs.) | New Plan Price per Unit (Rs.) |
|--------|------------------------------|------------------------------|
| March  | 82                           | 82                           |
| April  | 82                           | 82                           |
| May    | 82                           | 82                           |
| June   | 82                           | 82                           |
| July   | 82                           | 82                           |
| August | 82                           | 82                           |

### Raw Material Consumption per bottle (in ml)
| Item             | Price per Litre (Rs.) | Material % |
|-----------------|----------------------|------------|
| Water          | 10                    | 85%        |
| Sugar Syrup    | 70                    | 10%        |
| Flavoring      | 300                   | 2%         |
| Carbonated Water | 20                   | 2%         |
| Preservatives  | 400                   | 0.50%      |
| Coloring Agents| 500                   | 0.50%      |

Based on the composition table, the cold drink consists of:  
- **85% Water**  
- **10% Sugar Syrup**  
- **2% Flavoring**  
- **2% Carbonated Water**  
- **0.50% Preservatives**  
- **0.50% Coloring Agents**  

#### Material Consumption per Bottle (in ml) Calculation  
To determine the material consumption per bottle, we apply the given percentage composition to the total bottle volume.  

For eg. In March Month, Material Consumption per Bottle (in ml) = 1000 * 85% = 850

| Month            | March | April | May  | June | July | August |
|-----------------|-------|-------|------|------|------|--------|
| **Water**       | 850   | 850   | 850  | 850  | 850  | 850    |
| **Sugar Syrup** | 100   | 100   | 100  | 100  | 100  | 100    |
| **Flavoring**   | 20    | 20    | 20   | 20   | 20   | 20     |
| **Carbonated Water** | 20 | 20  | 20   | 20   | 20   | 20     |
| **Preservatives** | 5   | 5     | 5    | 5    | 5    | 5      |
| **Coloring Agents** | 5  | 5     | 5    | 5    | 5    | 5      |

The following table represents the quantity of each raw material consumed in thousand litres for the Old Plan over six months.
| Month             | March  | April  | May    | June   | July   | August |
|------------------|--------|--------|--------|--------|--------|--------|
| **Water**        | 616.25 | 647.7  | 680.85 | 715.7  | 752.25 | 790.5  |
| **Sugar Syrup**  | 72.5   | 76.2   | 80.1   | 84.2   | 88.5   | 93     |
| **Flavoring**    | 14.5   | 15.24  | 16.02  | 16.84  | 17.7   | 18.6   |
| **Carbonated Water** | 14.5  | 15.24  | 16.02  | 16.84  | 17.7   | 18.6   |
| **Preservatives** | 3.625  | 3.81   | 4.005  | 4.21   | 4.425  | 4.65   |
| **Coloring Agents** | 3.625 | 3.81   | 4.005  | 4.21   | 4.425  | 4.65   |

The following table represents the quantity of each raw material consumed in thousand litres for the New Plan over six months.
| Item              | March | April | May   | June  | July  | August |
|------------------|-------|-------|-------|-------|-------|--------|
| **Water**        | 680   | 748   | 822.8 | 905.25| 996.2 | 1096.5 |
| **Sugar Syrup**  | 80    | 88    | 96.8  | 106.5 | 117.2 | 129    |
| **Flavoring**    | 16    | 17.6  | 19.36 | 21.3  | 23.44 | 25.8   |
| **Carbonated Water** | 16  | 17.6  | 19.36 | 21.3  | 23.44 | 25.8   |
| **Preservatives**| 4     | 4.4   | 4.84  | 5.325 | 5.86  | 6.45   |
| **Coloring Agents** | 4  | 4.4   | 4.84  | 5.325 | 5.86  | 6.45   |

- The new plan results in a higher consumption of all raw materials.
- This is expected due to the increase in sales quantity in the new plan (from 725,000 units in March to 800,000 units and growing at a higher rate).
- The new plan aims for higher sales growth, leading to increased raw material consumption. While this can drive higher revenue, it also increases material costs, requiring careful cost management and supply chain efficiency. 🚀

### Cost Comparison: Old Plan vs. New Plan Cost (in Rs. '000')
#### Old Plan
| Month        | March  | April  | May    | June   | July   | August |
|-------------|--------|--------|--------|--------|--------|--------|
| **Water**   | 6,163  | 6,477  | 6,809  | 7,157  | 7,523  | 7,905  |
| **Sugar Syrup** | 5,075  | 5,334  | 5,607  | 5,894  | 6,195  | 6,510  |
| **Flavoring** | 4,350  | 4,572  | 4,806  | 5,052  | 5,310  | 5,580  |
| **Carbonated Water** | 290    | 305    | 320    | 337    | 354    | 372    |
| **Preservatives** | 1,450  | 1,524  | 1,602  | 1,684  | 1,770  | 1,860  |
| **Coloring Agents** | 1,813  | 1,905  | 2,003  | 2,105  | 2,213  | 2,325  |
| **Total Cost** | 19,140 | 20,117 | 21,146 | 22,229 | 23,364 | 24,552 |
| **Cost per Unit (Rs.)** | 26     | 26     | 26     | 26     | 26     | 26     |

#### New Plan
| Month        | March  | April  | May    | June   | July   | August |
|-------------|--------|--------|--------|--------|--------|--------|
| **Water**   | 6,800  | 7,480  | 8,228  | 9,053  | 9,962  | 10,965 |
| **Sugar Syrup** | 5,600  | 6,160  | 6,776  | 7,455  | 8,204  | 9,030  |
| **Flavoring** | 4,800  | 5,280  | 5,808  | 6,390  | 7,032  | 7,740  |
| **Carbonated Water** | 320    | 352    | 387    | 426    | 469    | 516    |
| **Preservatives** | 1,600  | 1,760  | 1,936  | 2,130  | 2,344  | 2,580  |
| **Coloring Agents** | 2,000  | 2,200  | 2,420  | 2,663  | 2,930  | 3,225  |
| **Total Cost** | 21,120 | 23,232 | 25,555 | 28,116 | 30,941 | 34,056 |
| **Cost per Unit (Rs.)** | 26     | 26     | 26     | 26     | 26     | 26     |

**Total Cost:** The total cost of raw material consumption is significantly higher in the New Plan compared to the Old Plan due to the increase in sales volume.

**Cost Per Unit:** Even though the total cost has increased, the cost per unit remains unchanged at ₹26.
- This indicates that the new plan does not impact the raw material cost structure but mainly increases due to higher production.

- The new plan increases raw material costs due to higher production, but since the cost per unit remains stable, profitability will depend on sales price adjustments and operational efficiencies. 📊🚀

### Contribution: Old Plan Vs New Plan
Contribution refers to the portion of revenue that remains after deducting variable costs. It represents the amount available to cover fixed costs and generate profit.

```Contribution = Sales Quantity - Variable Quantity```

```Contribution per Unit=Selling Price per Unit−Variable Cost per Unit```

#### Some Important points about Contribution
- A higher contribution indicates better profitability.
- If the contribution is greater than fixed costs, the company makes a profit.
- If the contribution is equal to fixed costs, the company breaks even (no profit, no loss).
- If the contribution is less than fixed costs, the company incurs a loss.

#### Contribution of the Old Plan
**Sales (Amount in Rs. '000')**
| Month   | March  | April  | May    | June   | July   | August |
|---------|--------|--------|--------|--------|--------|--------|
| Sales Revenue | 59,450 | 62,484 | 65,682 | 69,044 | 72,570 | 76,260 |
| **Total Sales** | **59,450** | **62,484** | **65,682** | **69,044** | **72,570** | **76,260** |

**Variable Cost (Amount in Rs. '000')** 
| Month   | March  | April  | May    | June   | July   | August |
|---------|--------|--------|--------|--------|--------|--------|
| Material Cost  | 19,140 | 20,117 | 21,146 | 22,229 | 23,364 | 24,552 |
| Bottling Cost  | 1,450  | 1,524  | 1,602  | 1,684  | 1,770  | 1,860  |
| Processing Cost | 4,350  | 4,572  | 4,806  | 5,052  | 5,310  | 5,580  |
| **Total Variable Cost** | **24,940** | **26,213** | **27,554** | **28,965** | **30,444** | **31,992** |

**Contribution (Amount in Rs. '000')**
| Month   | March  | April  | May    | June   | July   | August |
|---------|--------|--------|--------|--------|--------|--------|
| Contribution (Sales - Variable Cost) | 34,510 | 36,271 | 38,128 | 40,079 | 42,126 | 44,268 |
| Contribution per Unit (in Rs.) | 48 | 48 | 48 | 48 | 48 | 48 |

#### Contribution of the New Plan
**Sales (Amount in Rs. '000')**  
| Month   | March  | April  | May    | June   | July   | August |
|---------|--------|--------|--------|--------|--------|--------|
| **Old Plan** | 59,450 | 62,484 | 65,682 | 69,044 | 72,570 | 76,260 |
| **New Plan** | 65,600 | 72,160 | 79,376 | 87,330 | 96,104 | 105,780 |
| **Total Sales** | **65,600** | **72,160** | **79,376** | **87,330** | **96,104** | **105,780** |

**Variable Cost (Amount in Rs. '000')** 
| Month   | March  | April  | May    | June   | July   | August |
|---------|--------|--------|--------|--------|--------|--------|
| **Material Cost (Old Plan)**  | 19,140 | 20,117 | 21,146 | 22,229 | 23,364 | 24,552 |
| **Material Cost (New Plan)**  | 21,120 | 23,232 | 25,555 | 28,116 | 30,941 | 34,056 |
| **Bottling Cost (Old Plan)**  | 1,450  | 1,524  | 1,602  | 1,684  | 1,770  | 1,860  |
| **Bottling Cost (New Plan)**  | 2,400  | 2,640  | 2,904  | 3,195  | 3,516  | 3,870  |
| **Processing Cost (Old Plan)** | 4,350  | 4,572  | 4,806  | 5,052  | 5,310  | 5,580  |
| **Processing Cost (New Plan)** | 4,800  | 5,280  | 5,808  | 6,390  | 7,032  | 7,740  |
| **Total Variable Cost (Old Plan)** | **24,940** | **26,213** | **27,554** | **28,965** | **30,444** | **31,992** |
| **Total Variable Cost (New Plan)** | **28,320** | **31,152** | **34,267** | **37,701** | **41,489** | **45,666** |

**Contribution (Amount in Rs. '000')**
| Month   | March  | April  | May    | June   | July   | August |
|---------|--------|--------|--------|--------|--------|--------|
| **Contribution (Old Plan)** | 34,510 | 36,271 | 38,128 | 40,079 | 42,126 | 44,268 |
| **Contribution (New Plan)** | 37,280 | 41,008 | 45,109 | 49,629 | 54,615 | 60,114 |
| **Contribution per Unit (Old Plan)** | 48 | 48 | 48 | 48 | 48 | 48 |
| **Contribution per Unit (New Plan)** | 46.60 | 46.60 | 46.60 | 46.60 | 46.60 | 46.60 |

1. **Increased Sales in New Plan**  
   - The **New Plan** generated higher sales across all months compared to the **Old Plan**.  
   - March sales increased by **10.4%** (from **₹59,450K** to **₹65,600K**).  

2. **Higher Variable Costs in New Plan**  
   - The **New Plan** resulted in **higher raw material costs** and **bottling & processing costs**.  
   - Total Variable Cost in **August** increased by **42.8%** (from **₹31,992K** to **₹45,666K**).  

3. **Contribution Growth in New Plan**  
   - Despite higher costs, the **New Plan** still achieved higher **total contribution** every month.  
   - **June contribution increased** by **23.8%** (from **₹40,079K** to **₹49,629K**).  

4. **Lower Contribution per Unit in New Plan**  
   - The **New Plan** has a lower **Contribution per Unit (₹46.60)** compared to the **Old Plan (₹48.00)**.  
   - This suggests that while total profits are increasing, the profit **per unit is decreasing** due to **higher costs**.  

- The **New Plan** is more **profitable in absolute terms** but has **increased variable costs** leading to a **lower per-unit profit margin**. If costs continue to rise, long-term profitability may be affected.

### Cost Benefit Analysis

#### Incremental Contribution
Incremental Contribution refers to the additional contribution (Sales Revenue - Variable Costs) gained when switching from the Old Plan to the New Plan. It represents the extra earnings generated due to the new strategy, before considering any additional fixed costs or expenses.

```Incremental Contribution=New Plan Contribution−Old Plan Contribution```

| Amount (in Rs. '000') | March  | April  | May    | June   | July   | August |
|----------------------|--------|--------|--------|--------|--------|--------|
| **Old Plan Contribution** | 34,510  | 36,271  | 38,128  | 40,079  | 42,126  | 44,268  |
| **New Plan Contribution** | 37,280  | 41,008  | 45,109  | 49,629  | 54,615  | 60,114  |
| **Incremental Contribution** | 2,770  | 4,737  | 6,981  | 9,550  | 12,489  | 15,846  |

#### Understanding Incremental Expense & Incremental Profits
**Incremental Expenses** are additional costs incurred due to the New Plan. These include:
- **Ad Preparation Costs** (one-time in March)
- **New Bottling Mould Cost** (one-time in March)
- **Incremental Advertising** (recurring monthly expense)

```Incremental Profit=Incremental Contribution−Incremental Expense```
| Expense Type           | March  | April  | May    | June   | July   | August |
|------------------------|--------|--------|--------|--------|--------|--------|
| **Ads Preparation**     | 10,000 | 0      | 0      | 0      | 0      | 0      |
| **New Bottling Mould**  | 95     | 0      | 0      | 0      | 0      | 0      |
| **Incremental Advertising** | 3,833  | 3,833  | 3,833  | 3,833  | 3,833  | 3,833  |
| **Total Incremental Expense** | 13,928 | 3,833  | 3,833  | 3,833  | 3,833  | 3,833  |

| Amount (in Rs. '000') | March   | April  | May    | June   | July   | August |
|----------------------|---------|--------|--------|--------|--------|--------|
| **Incremental Profit** | -11,158 | 903    | 3,148  | 5,716  | 8,656  | 12,013 |

- The **New Plan** initially incurs a loss in March due to high one-time costs.  
- From **April onwards**, the incremental profit turns positive.  
- By **August**, the **Incremental Profit reaches ₹12,013K**, demonstrating the **long-term profitability** of the new strategy.

### Cost Benefit Analysis Dashboard
![image](https://github.com/user-attachments/assets/aeef60a1-ab61-4386-9250-b131e236c226)


### Summary of Insights
- In a new plan a forecast is that the sales quantity will be 24.87% higher than the old plan forecast.
- Cost-Benefit analysis of the new plan shows that it will generate an incremental profit of Rs. 19,278,000

