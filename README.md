# 🍾Zingg Case Study - Cost Benefit Analysis
<img src="https://github.com/user-attachments/assets/4430a3b1-7c3e-4c2f-aaa5-a0f2d04e40dd" alt="CandyMonkey Logo" width="200"/>

# For the comprehensive understanding and formulas used in the project, please refer to the [Google Sheet](https://docs.google.com/spreadsheets/d/1Rrdg4YddUoKNBgYildJ3fI1s_JJfXadMH-jTyEV4uMo/edit?usp=sharing)

## 🔍Project Overview
The Cold Drink Station is a beverage company that sells cold drinks under the brand name 'Zingg'. For the upcoming summer season, they aim to appeal to young customers in India by marketing their brand during the World Cup. The marketing head is very excited about the brand launch, but the finance manager is a bit skeptical and has requested a cost-benefit report for the event. 

As a data analyst in the marketing department, you have been asked to prepare a comprehensive cost-benefit analysis and present it through a dashboard to the marketing head.

The marketing team has decided to introduce a new bottle for Zingg, featuring World Cup-related images. This initiative will incur additional costs for a new mould and higher packaging expenses. The new bottle will replace the regular Zingg bottles for six months.

## 🚀Objective
- **Assess the financial impact of the new marketing campaign.**
- **Compare the costs and revenue projections under the old and new plans.**
- **Identify the profitability of the new initiative over the six months.**
- **Provide actionable insights and recommendations to the marketing team.**

## 📜Requirements Gathering and Documentation
As a business analyst, the first step would be to gather all the requirements necessary for the analysis and document it. Documentation is the most critical part of project development as it is the foundation of all further project deliverables describing what inputs and outputs are associated with each process function.

### I have created a Business Requirement documentation for our business case [Here](https://github.com/itskshitija/Zingg-Cost-Benefit-Analysis/blob/main/Zingg-CostBenefitAnalysis_BRD.pdf)

## 📊Exploratory Data Analysis

### Sales Units (in '000')
This table represents the expected number of Zingg bottles sold per month under two different plans:
- **Old Plan:** The company originally expected sales to start at 725,000 units in March, increasing by 5% month-over-month.
- **New Plan:** With the new marketing strategy (World Cup-themed bottles), sales are projected to start higher at 800,000 units in March, increasing by 10% month-over-month.

| Month     | March | April | May  | June | July | August |
|-----------|-------|-------|------|------|------|--------|
| **Old Plan** | 725   | 762   | 801  | 842  | 885  | 930    |
| **New Plan** | 800   | 880   | 968  | 1065 | 1172 | 1290   |

- Under the old plan, sales would have grown steadily, reaching 930,000 units in August.
- Under the new plan, sales growth is significantly higher, reaching 1.29 million units in August due to increased demand driven by marketing efforts.

### Price per Unit (₹)
This table shows that the selling price of each Zingg bottle remains constant at ₹82 per bottle, regardless of the sales plan.
| Month     | March | April | May  | June | July | August |
|-----------|-------|-------|------|------|------|--------|
| **Old Plan** | 82    | 82    | 82   | 82   | 82   | 82     |
| **New Plan** | 82    | 82    | 82   | 82   | 82   | 82     |

- The price per unit remains unchanged, meaning revenue growth will be entirely driven by increased sales volume, not by price adjustments.

### Per Unit Material Consumption (in ml)
This table details the amount of each raw material used per **1000 ml** bottle of Zingg across different months.

| **Material**         | **March** | **April** | **May** | **June** | **July** | **August** |
|----------------------|----------|----------|---------|---------|---------|----------|
| **Water**           | 850      | 850      | 850     | 850     | 850     | 850      |
| **Sugar Syrup**     | 100      | 100      | 100     | 100     | 100     | 100      |
| **Flavoring**       | 20       | 20       | 20      | 20      | 20      | 20       |
| **Carbonated Water**| 20       | 20       | 20      | 20      | 20      | 20       |
| **Preservatives**   | 5        | 5        | 5       | 5       | 5       | 5        |
| **Coloring Agents** | 5        | 5        | 5       | 5       | 5       | 5        |

- The material consumption per bottle remains **constant** across all months.

### Raw Material Consumed (in Thousand Litres) - Old Plan
This table details the raw material consumption for producing **Zingg** cold drink under the **old plan**.

| **Material**         | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|----------------------|----------|----------|---------|---------|---------|----------|
| **Water**           | 616.25   | 647.7    | 680.85  | 715.7   | 752.25  | 790.5    |
| **Sugar Syrup**     | 72.5     | 76.2     | 80.1    | 84.2    | 88.5    | 93       |
| **Flavoring**       | 14.5     | 15.24    | 16.02   | 16.84   | 17.7    | 18.6     |
| **Carbonated Water**| 14.5     | 15.24    | 16.02   | 16.84   | 17.7    | 18.6     |
| **Preservatives**   | 3.625    | 3.81     | 4.005   | 4.21    | 4.425   | 4.65     |
| **Coloring Agents** | 3.625    | 3.81     | 4.005   | 4.21    | 4.425   | 4.65     |

- The raw material consumption **increases every month** due to the **5% growth** in sales under the old plan.
- Water has the **highest consumption** since it makes up **85% of each bottle**.

### Raw Material Consumed (in Thousand Litres) - New Plan
This table details the raw material consumption for producing **Zingg** cold drink under the **new plan**.

| **Material**         | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|----------------------|----------|----------|---------|---------|---------|----------|
| **Water**           | 680      | 748      | 822.8   | 905.25  | 996.2   | 1096.5   |
| **Sugar Syrup**     | 80       | 88       | 96.8    | 106.5   | 117.2   | 129      |
| **Flavoring**       | 16       | 17.6     | 19.36   | 21.3    | 23.44   | 25.8     |
| **Carbonated Water**| 16       | 17.6     | 19.36   | 21.3    | 23.44   | 25.8     |
| **Preservatives**   | 4        | 4.4      | 4.84    | 5.325   | 5.86    | 6.45     |
| **Coloring Agents** | 4        | 4.4      | 4.84    | 5.325   | 5.86    | 6.45     |

### Old Plan - Raw Material Consumption Cost
This table outlines the **cost incurred** for raw material consumption under the **old plan** for producing **Zingg** cold drink.

| **Material**         | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|----------------------|----------|----------|---------|---------|---------|----------|
| **Water**           | 6,163    | 6,477    | 6,809   | 7,157   | 7,523   | 7,905    |
| **Sugar Syrup**     | 5,075    | 5,334    | 5,607   | 5,894   | 6,195   | 6,510    |
| **Flavoring**       | 4,350    | 4,572    | 4,806   | 5,052   | 5,310   | 5,580    |
| **Carbonated Water**| 290      | 305      | 320     | 337     | 354     | 372      |
| **Preservatives**   | 1,450    | 1,524    | 1,602   | 1,684   | 1,770   | 1,860    |
| **Coloring Agents** | 1,813    | 1,905    | 2,003   | 2,105   | 2,213   | 2,325    |
| **Total Cost**      | 19,140   | 20,117   | 21,146  | 22,229  | 23,364  | 24,552   |
| **Cost per Unit (Rs.)** | 26 | 26 | 26 | 26 | 26 | 26 |

- The total cost of raw materials **increases monthly** due to growth in sales.
- **Sugar Syrup & Water** contribute the most to cost.
- Cost per unit remains **constant at Rs. 26**, ensuring stable pricing.
  
### New Plan - Raw Material Consumption (in Rs. '000')
This table outlines the **cost incurred** for raw material consumption under the **new plan** for producing **Zingg** cold drink.
| **Material**         | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|----------------------|----------|----------|---------|---------|---------|----------|
| **Water**           | 6,800    | 7,480    | 8,228   | 9,053   | 9,962   | 10,965   |
| **Sugar Syrup**     | 5,600    | 6,160    | 6,776   | 7,455   | 8,204   | 9,030    |
| **Flavoring**       | 4,800    | 5,280    | 5,808   | 6,390   | 7,032   | 7,740    |
| **Carbonated Water**| 320      | 352      | 387     | 426     | 469     | 516      |
| **Preservatives**   | 1,600    | 1,760    | 1,936   | 2,130   | 2,344   | 2,580    |
| **Coloring Agents** | 2,000    | 2,200    | 2,420   | 2,663   | 2,930   | 3,225    |
| **Total Cost**      | 21,120   | 23,232   | 25,555  | 28,116  | 30,941  | 34,056   |
| **Cost per Unit (Rs.)** | 26 | 26 | 26 | 26 | 26 | 26 |

- **Total cost increases each month** due to rising production volume.  
- **Water, Sugar Syrup & Flavoring** remain the most significant contributors to cost.  
- **Cost per unit remains constant at Rs. 26**, ensuring price stability.  

### Old Plan - Sales & Variable Cost (in Rs. '000')
This table presents the **sales revenue, variable costs, and contribution margin** for **Zingg** cold drink under the **old plan**.

| **Category**              | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|---------------------------|----------|----------|---------|---------|---------|----------|
| **Sales (Total Revenue)** | 59,450   | 62,484   | 65,682  | 69,044  | 72,570  | 76,260   |
| **Material Cost**         | 19,140   | 20,117   | 21,146  | 22,229  | 23,364  | 24,552   |
| **Bottling Cost**         | 1,450    | 1,524    | 1,602   | 1,684   | 1,770   | 1,860    |
| **Processing Cost**       | 4,350    | 4,572    | 4,806   | 5,052   | 5,310   | 5,580    |
| **Total Variable Cost**   | 24,940   | 26,213   | 27,554  | 28,965  | 30,444  | 31,992   |
| **Contribution (Sales - Variable Cost)** | 34,510 | 36,271 | 38,128 | 40,079 | 42,126 | 44,268 |
| **Contribution per Unit (Rs.)** | 48 | 48 | 48 | 48 | 48 | 48 |

- **Total sales steadily increase each month** as more units are sold.  
- **Material costs make up the largest portion** of variable costs.  
- **Contribution margin remains stable at Rs. 48 per unit**, ensuring profitability growth.  

### New Plan - Sales & Variable Cost (in Rs. '000')
This table presents the **sales revenue, variable costs, and contribution margin** for **Zingg** cold drink under the **new plan**.

| **Category**              | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|---------------------------|----------|----------|---------|---------|---------|----------|
| **Sales (Total Revenue)** | 65,600   | 72,160   | 79,376  | 87,330  | 96,104  | 105,780  |
| **Material Cost**         | 21,120   | 23,232   | 25,555  | 28,116  | 30,941  | 34,056   |
| **Bottling Cost**         | 2,400    | 2,640    | 2,904   | 3,195   | 3,516   | 3,870    |
| **Processing Cost**       | 4,800    | 5,280    | 5,808   | 6,390   | 7,032   | 7,740    |
| **Total Variable Cost**   | 28,320   | 31,152   | 34,267  | 37,701  | 41,489  | 45,666   |
| **Contribution (Sales - Variable Cost)** | 37,280 | 41,008 | 45,109 | 49,629 | 54,615 | 60,114 |
| **Contribution per Unit (Rs.)** | 46.60 | 46.60 | 46.60 | 46.60 | 46.60 | 46.60 |

- **Sales are higher compared to the old plan**, showing better market demand.  
- **Variable costs increase proportionally**, but economies of scale improve profitability.  
- **Contribution per unit remains stable at Rs. 46.60**, ensuring profitability growth.  

### Incremental Contribution & Profit Analysis (New Plan)
This analysis compares the **old and new plans** for **Zingg Cold Drink**, highlighting **incremental contribution, expenses, and profits**.

#### Incremental Contribution & Profits (in Rs. '000')

| **Category**              | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|---------------------------|----------|----------|---------|---------|---------|----------|
| **Contribution (Old Plan)** | 34,510  | 36,271   | 38,128  | 40,079  | 42,126  | 44,268   |
| **Contribution (New Plan)** | 37,280  | 41,008   | 45,109  | 49,629  | 54,615  | 60,114   |
| **Incremental Contribution** | 2,770  | 4,737    | 6,981   | 9,550   | 12,489  | 15,846   |

### Incremental Expenses
| **Expense Category**       | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|---------------------------|----------|----------|---------|---------|---------|----------|
| **Ads Preparation**       | 10,000   | 0        | 0       | 0       | 0       | 0        |
| **New Bottling Mould**    | 95       | 0        | 0       | 0       | 0       | 0        |
| **Incremental Advertising** | 3,833  | 3,833    | 3,833   | 3,833   | 3,833   | 3,833    |
| **Total Incremental Expenses** | 13,928 | 3,833  | 3,833  | 3,833  | 3,833  | 3,833    |

### Incremental Profits (New Plan - Old Plan - Expenses)
| **Category**              | **March** | **April** | **May**  | **June**  | **July**  | **August** |
|---------------------------|----------|----------|---------|---------|---------|----------|
| **Incremental Profit**    | -11,158  | 903      | 3,148   | 5,716   | 8,656   | 12,013   |

- **The new plan starts with an initial loss of Rs. 11,158K** in March due to high ad costs.  
- **By April, profits turn positive** and continue increasing through August.  -
- **By August, incremental profits reach Rs. 12,013K**, indicating the **success of the new plan**.  

## Dashboard
![image](https://github.com/user-attachments/assets/560514d6-674d-4ab1-bc58-c3ac784184c1)

## Insights
- In a new plan a forecast is that the sales quantity will be 24.87% higher than the old plan forecast.
- Cost-Benefit analysis of new plan shows that it will generate an incremental profit of Rs. 19,278,000
