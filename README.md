# [Power BI] Marketing Campaign Report

# I. Introduction
## 1. Dataset overview
- This dataset contains multiple tables with information and metrics on hundreds of campaigns conducted in May 2024:
  + mkt_camp_by_sku_cost: each rows represent a single product and thier metrics
  + mkt_camp_cost: campaign budget and spending by day
  + order: each row represents an order and their information in May 2024
  + danh sach san pham: list of all products in the store
## 2. Business requirement:
- Develop tactical reports to help company leadership understand budget expenditure and the performance of marketing campaigns, link sales revenue to marketing spending, and optimize marketing budget efficiency based on KPIs—subsequently proposing tactics to improve performance.

# II. Design thinking method
## Step 1: Empathize
<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/8673b716-f515-475e-9e85-45b19358cddb" />

## Step 2: Define POV
<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/f70a7d7b-a303-48be-b014-b6e8af35893f" />

## Step 3: Ideate
<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/62a4cecf-91db-4b5a-841d-7f9d4836add3" />
<img width="1024" height="572" alt="image" src="https://github.com/user-attachments/assets/4c6ce217-82c5-42fc-a6dc-761452c89f79" />

## Step 4: Prototype
Build a complete report:
- Choose the right visual/theme
- Choose the right metrics
- Arrange all elements according to a suitable layout (easy to read, limit visual clutter)

## Step 5: Review
Review each part of the report, returning to step 4 if necessary.

# III. Data model
<img width="967" height="780" alt="image" src="https://github.com/user-attachments/assets/7b356e2c-3bca-47d8-9dae-c0dcf96821b8" />

# IV. Visualization
## 1. Executive Overview
<img width="1417" height="797" alt="image" src="https://github.com/user-attachments/assets/c52c8815-3284-48d9-9a05-9ced65ecc593" />

## 2. Campaign Analysis
<img width="1412" height="802" alt="image" src="https://github.com/user-attachments/assets/f45e5b8d-ffc3-4044-ba46-c6a4b31bd30d" />

## 3. Product Analysis
<img width="1421" height="802" alt="image" src="https://github.com/user-attachments/assets/bb2cab41-995a-4ef0-b01e-cd3cf917067c" />

# V. Insights
## 1. Key insight:
  Many campaigns—such as "Lisa IG" and "Audrey Shirt LAL new"—have delivered exceptional returns (with ROAS ranging from 10x to as high as 90x), yet their budget utilization remains suboptimal (only 46–70%). Conversely, capital is being indiscriminately poured—exceeding set limits by 10–60%—into underperforming campaigns with low ROAS, such as "IVANA SET" and "VERENA SET."
=> The system is currently "burning money" on ineffective campaigns while "stifling" those with the potential to generate significant cash flow.

## 2. Core messages:
- **Immediate capital reallocation**:
  Cease the practice of spreading budgets too thinly or misallocating funds. Reduce spending limits for over-budget campaign groups (IVANA SET, MAIA DRESS) and redirect those resources toward high-performing "cash cow" products (Lisa IG, Audrey Shirt IG) to optimize overall ROAS.
- **Product pricing and margin restructuring:**
  The "Separates - Tops(Ao tach Set)" category has the highest sales volume across the system, yet it suffers from severely negative profit margins. It is essential to review the Cost of Goods Sold (COGS) or adjust retail prices to prevent a scenario where higher sales volume leads to greater losses.
  The "Separates - Skirts(Chan vay tach Set)" and "Separates - Pants(Quan tach Set)" categories show both low sales volume and negative profit margins; consider phasing these out and halting further procurement.
- **Capitalize on "golden hours" and optimize creatives:** Concentrate advertising resources and sales support staff during peak hours (09:00 – 12:00). Additionally, manage ad frequency to improve the current, relatively low Click-Through Rate (CTR) of 0.82%.

# V. Recommendations:
- Reallocate 30% of the budget from over-budget and underperforming campaigns to campaigns with high profit potential.

  => Objective: Increase overall ROAS and reduce CAC.
- Pause advertisements for product categories such as "Separates" (tops, skirts, and bottoms sold individually) and shift focus toward "Question Mark" categories—specifically loose-fit flared dresses and waist-cinching, form-fitting dresses.

  => Objective: Minimize low-margin or profit-eroding items and improve overall profit margins.
- Adjust campaign scheduling by concentrating ad spend during the 09:00–12:00 and 21:00–24:00 time slots.

  => Objective: Improve CTR and conversion rates.
