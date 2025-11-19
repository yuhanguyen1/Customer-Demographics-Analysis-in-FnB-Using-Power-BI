# 👥 Customer Demographics & Product Insights Analysis in F&B Using Power BI

<img width="2884" height="1756" alt="image" src="https://github.com/user-attachments/assets/28e5501c-7903-4d0f-aa5a-b0c0fb175a7e" />

**Author:** Nguyễn Anh Huy  
**Date:** August 2025  
**Tools Used:** Power BI, DAX, Data Modeling  

---

## 📑 Table of Contents  
- 📌 [Background & Overview](#-background--overview)  
- 📂 [Dataset Description & Data Structure](#-dataset-description--data-structure)  
- 🧠 [Design Thinking Process](#-design-thinking-process)  
- 📊 [Key Insights & Visualizations](#-key-insights--visualizations)  
- 🔎 [Final Conclusion & Recommendation](#-final-conclusion--recommendation)  

---

## 📌 Background & Overview  

### 🎯 Objective  
The goal of this project is to build a unified analytics dashboard that helps Naked Flavors - a rising Gelato brand in Ho Chi Minh City answer three core questions:

1️⃣ **What is the overall business situation of Naked Flavors?**

2️⃣ **Who are the customers and what are their shopping behaviors?**

3️⃣ **Which sales channels – timing – and areas bring the highest value?**

### 👤 Who is this project for?
This dashboard is designed primarily for:

✔️  **Founders & Management** who need visibility into business performance.

✔️  **Marketing & Growth** teams analyzing customer segmentation and buying behaviors.

✔️  **Operations & Distribution** teams monitoring performance by time and location. 

### ❓ Key Business Questions  
- How is revenue trending month-to-month?
- Which districts contribute most to sales and customer volume?
- Which products perform best across customer segments?
- What times of day or days of the week see the highest ordering activity?
- Which sales channel (Web, Harasocial, Zalo) drives the most value?

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
Internal transaction data exported from Naked Flavors’ sales management system for the year 2024.  

### 📊 Data Tables  
The dataset contains ~45,000 rows x 21 columns, including:

- Order information: Order ID, date, channel, district, delivery time

- Customer details: gender, purchase frequency, order count

- Product-level details: SKU, quantity

- Revenue metrics: net sales, unit price

---

## 🧠 Design Thinking Process  

1️⃣ Empathize

Understand the needs of Naked Flavors’ management:

- Clear visibility into revenue trends

- Ability to segment customer groups

- Understanding which channels and locations generate the most value

- Need for quick, decision-ready insights

2️⃣ Define

Frame the analytics challenges:

- Fragmented data with no unified reporting

- Difficulty identifying high-value customer segments

- Limited visibility into timing patterns and geographic efficiency

3️⃣ Ideate

Map out KPIs and visual frameworks:

- **Core KPIs**: Revenue, AOV, Order Volume, Customer Count

- **Customer KPIs**: RFM-style ordering patterns, gender composition, top buyers

- **Channel KPIs**: Revenue by channel, traffic distribution, time-based ordering

- **Location KPIs**: District contribution, potential growth areas

4️⃣ Prototype & Review

Develop interactive dashboards across 3 main lenses:

- **Overview Dashboard** – business health and top-level KPIs

- **Customer & Product Dashboard** – demographics, product preferences, buyer value

- **Time & Channel Dashboard** – time-based ordering patterns and channel performance

---

## 📊 Key Insights & Visualizations  

### I. Overview Dashboard  
<img width="1426" height="800" alt="image" src="https://github.com/user-attachments/assets/2bfd22b3-05ee-427e-b28e-59892d85f78e" />

📌 **Findings:**  
1. **Overall Performance Trend**: All key metrics—**Total Revenue (2.47B VND)**, **Total Customers (3193)**, **Total Orders (5209)**, and **AOV (474.76K VNĐ)**—show a significant decrease (ranging from **-8.7% to -30.9%**) compared to the previous period (Thg 12/24 vs Thg 11/24).
2.  **Positive Monthly Revenue Trend**: Despite the overall period-to-period decline shown on Page 1, the monthly revenue trend shows significant peaks and dips, notably a sharp **increase to 253M** in **Thg 2 (February)**, recovering from the lowest point of **168M** in **Thg 6 (June)**.
3.  **Top-Selling Product (Volume)**: The best-selling product by **Total Sales Volume** (Tổng số sản phẩm bán ra) is **Kem Khoai Môn Lá Cẩm** with 2349 units, followed by **Kem Dừa Tươi** with 2010 units. This is a different ranking from the revenue-based ranking on Page 2, suggesting these might be lower-priced but high-volume items.
4.  **Geographic Revenue Concentration**: **The revenue breakdown by district** (Phân bổ doanh thu theo quận/huyện) shows **TP. Thủ Đức** (Thủ Đức City) contributes the overwhelming majority of revenue (**0.43B VND**), significantly surpassing all other districts like Quận 1 (0.34B VND) and Quận 7 (0.27B VND). These are key economic areas, with many agencies and offices of large companies and corporations.
5.  **Sales Channel Revenue Share**: The sales channel analysis indicates a clear hierarchy: **Harasocia** is the largest revenue contributor (**68.12%**), followed by **Zalo** (**20.01%**), and lastly **Web** (**11.87%**).

---

### II. Market Dashboard  
<img width="1425" height="797" alt="image" src="https://github.com/user-attachments/assets/f2b429e7-fe40-476d-96d6-f5217e09699d" />

📌 **Findings:**  
1. **Gender Split in Orders**: The revenue breakdown by gender and time shows a strong dominance of **Female (Nữ)** customers contributing **72.59%** of the revenue (1.80B VND), while Male (Nam) contributes 18.27% (0.45B VND).
2. **Gender-Specific Peak Time/Location**: When looking at "Khu vực nào tập trung khách hàng tiềm năng dựa trên sự kết hợp của địa lý và giới tính" (Potential customer focus areas by geography and gender), **TP. Thủ Đức** (Thủ Đức City) has the highest number of customers for both **Male (Nam) (395)** and **Female (Nữ) (110)**, confirming it as the key market location. 
3. **Highest Revenue-Generating Product**: **Kem Chocolate** is the top product in terms of **Total Revenue** across all customer segments.
4. **High-Value Repeat Customers**: The list of "Bảng chi tiết thông tin khách hàng" (Customer detail information) highlights customers like **Khách tại 17 BHTQ** and **Nguyễn Thị Bích**, showing the importance of both loyal and walk-in customers, with the top customer generating over **89.52M VND** in revenue with **378 orders**. 

---

### III. Product Dashboard  
<img width="1426" height="798" alt="image" src="https://github.com/user-attachments/assets/1040453a-9479-4ec4-b87f-386acec703d4" />

📌 **Findings:**  
1. **Sales Channel Dominance**: The **Harasocial** channel is the primary contributor to total revenue, generating significantly more than Web and Zalo.
2. **Geographic Revenue Contribution (HCMC)**: Within Ho Chi Minh City (TP Hồ Chí Minh), Quận 1 (District 1) and TP. Thủ Đức (Thủ Đức City) are the top two districts by revenue contribution, with TP. Thủ Đức leading slightly. 
3. **Peak Order Time**: The highest number of orders occurs **"Trong giờ làm việc" (During working hours)**, with 1954 orders, followed by **"Sau khi ăn tối" (After Dinners)** with 1013 orders, indicating a strong midday/afternoon and evening focus for consumption.
4. **Order Frequency Disparity**: Order frequency (Tần suất đặt hàng) is significantly lower on **Ngày thường (Weekdays)** (11.0 orders/day) compared to **Cuối tuần (Weekends)** (13.8) and **Ngày lễ (Holidays)** (14.4), suggesting customers order more frequently when they are not working.  

---

## 🔎 Final Conclusion & Recommendation  

### 🔑 Final Conclusion 
Naked Flavors currently operates with a highly concentrated market strategy:

1. **Geographic Concentration**: Sales are dominated by **TP. Thủ Đức** and **Quận 1** in Ho Chi Minh City, with the overall market showing a strong revenue decline (over **-30.9%** drop in revenue in December).

2. **Demographic Concentration**: The core consumer is overwhelmingly **Female (72.59% of revenue)**, and the peak ordering time is **"Trong giờ làm việc"** (During working hours).

3. **Channel Concentration**: The **Harasocial** channel is the primary revenue driver **(68.12%)**, while Web and Zalo are secondary.

4. **Product/Volume Discrepancy**: High-volume items like **Kem Khoai Môn Lá Cẩm** are popular, but high-revenue items like **Kem Chocolate** show potential for margin focus.

The overall negative trend across all KPIs suggests a recent failure in either **marketing, seasonal strategy, or a specific operational issue** that needs immediate investigation.

---

### 🚀 Key Recommendations
Here are three focused recommendations to stabilize the business and capitalize on the current findings:

1. **Immediate Focus: Stabilize and Re-activate Harasocial Channel**
The Harasocial channel is the core business engine. Its performance is critical to reversing the -30.9% revenue slide.

- **Action**: Conduct an immediate audit on the Harasocial channel's **conversion rate, recent campaigns, and technical stability** during the period of the decline (Thg 12/24 vs Thg 11/24).

- **Targeted Campaign**: Launch an exclusive, data-driven promotion targeting **Female customers** in **Quận 1 and TP. Thủ Đức** during the peak purchase window (working hours), promoting the high-volume **Kem Khoai Môn Lá Cẩm** to drive rapid transaction recovery.

2. **Exploit Weekend and Holiday Order Frequency**
Customers order more frequently on **weekends and holidays (13.8 - 14.4 orders/day)** than on weekdays (11.0 orders/day). This represents an untapped opportunity for greater spend.

- **Action**: Develop a "Weekend & Holiday Exclusive" offering. This could be a new flavor, a bundled family pack, or a higher-AOV product.

- **Goal**: Shift some of the current weekday purchasing behavior to the weekend or increase the size of the weekend order to maximize the higher order frequency.

3. **Pilot Expansion: Target Males and Underperforming Districts**
The male demographic and certain districts represent the largest growth area by volume.

- **Action**: Investigate the products most purchased by the **Male (Nam)** segment (e.g., if any products show a higher male propensity than the average). Launch a small-scale, A/B tested ad campaign specifically targeting males with a tailored message/product bundle.

- **Goal**: Increase the male contribution from the current **18.27%** to a more balanced mix, while also allocating a small marketing budget to increase awareness in low-performing, but potentially growing, districts like **Quận 10 or Quận Tân Phú**.

--- 

---

### ✨ Overall Business Impact  
✔️ Enabled data-driven strategic decisions based on customer demographics

✔️ Improved visibility into operational and sales performance

✔️ Identified clear growth opportunities by time, channel, and district

✔️ Enhanced understanding of customer buying behavior for targeted marketing

✔️ Centralized data into a single Power BI dashboard with interactive filters
