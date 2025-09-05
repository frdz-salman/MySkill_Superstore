# MySkill_Superstore

## Table of Contents

- [MySkill\_Superstore](#myskill_superstore)
  - [Table of Contents](#table-of-contents)
  - [Project Background](#project-background)
  - [Executive Summary](#executive-summary)
  - [Insights Deep-Dive](#insights-deep-dive)
    - [Monthly \& Seasonal Sales Patterns](#monthly--seasonal-sales-patterns)
    - [Category Trends \& Year-on-Year Changes](#category-trends--year-on-year-changes)
    - [Weekday vs Weekend Sales Behavior](#weekday-vs-weekend-sales-behavior)
    - [Top Product Performance](#top-product-performance)
    - [Brand Performance](#brand-performance)
    - [Payment Methods \& Consumer Behavior](#payment-methods--consumer-behavior)
    - [Unpaid Orders \& Risk Factors](#unpaid-orders--risk-factors)
  - [Recommendations](#recommendations)
    - [Maximize High-Performing Categories and Products](#maximize-high-performing-categories-and-products)
    - [Leverage Seasonal and Weekly Insights](#leverage-seasonal-and-weekly-insights)
    - [Invest in Continuous Customer Engagement](#invest-in-continuous-customer-engagement)
    - [Address Unpaid Orders Proactively](#address-unpaid-orders-proactively)
  - [Clarifying Questions, Assumptions, and Caveats](#clarifying-questions-assumptions-and-caveats)
    - [Questions for Stakeholders](#questions-for-stakeholders)
    - [Assumptions and Limitations](#assumptions-and-limitations)
  - [Detailed Reports](#detailed-reports)

---

## Project Background

As part of the MySkill Data Analyst Bootcamp, this project showcases my ability to transform complex transaction data into informative and interactive visualizations using Tableau. By developing a comprehensive sales performance dashboard, I designed strategic filters and visual elements to monitor key metrics such as customer count, revenue trends, payment methods, and product category performance, enabling data-driven decision-making.

---

## Executive Summary

This analysis of 2021–2022 e-commerce data, based on 3,955 customers and 8,307 valid orders, generated Rp 3.67 billion in revenue and Rp 820 million in net profit. Revenue grew 90.41% year-on-year, supported by a 46.86% increase in quantity sold and a 44.49% rise in average order value. Mobiles & Tablets—driven by Samsung and Apple—led with 147.82% growth, while Others and Books declined. Sales peaked in September due to promotions, dipped sharply in October, and were consistently stronger on weekdays. Cash on Delivery dominated payment preferences, highlighting trust and accessibility factors, yet 1,379 unpaid orders remain a revenue risk. The findings illustrate how analysis can identify trends, address inefficiencies, and guide strategic decisions.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/ERD.webp" alt="Sales Trends" width="900">
</p>

<p align="center">Superstore Dataset ERD
</p>

---

## Insights Deep-Dive

### Monthly & Seasonal Sales Patterns

- In 2021, August (IDR 227.86M) and December (IDR 217.31M) were peak months, likely driven by Independence Day promotions and holiday spending.
- September 2022 recorded the sharpest spike (YoY +48.13%, MoM +635.66%), followed by a dramatic drop in October (MoM -89.94%).
- April was the weakest month (IDR 22.21M), signaling an opportunity for targeted campaigns.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/total%20sales.webp" alt="Sales Trends" width="1200">
</p>

### Category Trends & Year-on-Year Changes

- Mobiles & Tablets recorded the strongest growth from 2021 to 2022, increasing transactions by 147.82% (from IDR 370.6M to IDR 918.45M) and dominating total revenue, driven by rising demand for electronics and mobile devices.
- Women Fashion and Superstore also posted positive growth, while Others saw the steepest decline (-46.27%) and Books dropped by -32.91%, reflecting shifting consumer preferences towards digital media.
- Overall business performance showed strong gains, with total revenue growing 90.41%, quantity sold increasing 46.86%, and average order value rising 44.49%, indicating higher customer spending per order.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/category.webp" alt="Sales Trends" width="900">
</p>

### Weekday vs Weekend Sales Behavior

- Average daily sales were higher on weekdays than weekends during Oct–Dec 2022.
- November had the highest weekend sales average, while December had the lowest weekday average.
- Data was analyzed before discount to reflect organic buying behavior without campaign influence.


### Top Product Performance

- The IDROID BALRX7 Gold dominated 2022 sales with 1,000 units sold, far surpassing the Jet Black variant (31 units).
- Other notable products, such as the Infinix Hot 4 Gold (15 units), Infinix Zero 4 Grey (10 units), and Samsung Grand Prime Plus Black (11 units), recorded relatively low sales, indicating weaker demand compared to the category leader.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/top%20product.webp" alt="Sales Trends" width="1200">
</p>

### Brand Performance

- Samsung led total transactions with IDR 588.76M, followed by Apple (IDR 403.44M).
- Other brands such as Sony, Huawei, and Lenovo competed in much smaller segments, with relatively similar sales values.
- The gap between the top two brands and the rest indicates a market dominated by Samsung and Apple.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/brand.webp" alt="Sales Trends" width="600">
</p>

### Payment Methods & Consumer Behavior

- Cash on Delivery (COD) remained the dominant payment method with 1,809 transactions, driven by trust, limited access to digital payments, and habit.
- Payaxis was the most-used digital payment option, though far behind COD, while other methods like Customer Credit, Easypay, and Jazzwallet recorded minimal usage.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/payment.webp" alt="Sales Trends" width="600">
</p>

### Unpaid Orders & Risk Factors

- A total of 1,379 customers had unpaid orders, increasing unpaid revenue and profit risks.
- This points to possible payment process issues or high cancellation/abandonment rates.

<p align="center">
  <img src="https://raw.githubusercontent.com/frdz-salman/MySkill_Superstore/refs/heads/main/Visualization/unpaid.webp" alt="Sales Trends" width="700">
</p>

---

## Recommendations

### Maximize High-Performing Categories and Products

- Maintain momentum in Mobiles & Tablets by expanding top-performing models like IDROID BALRX7 Gold through exclusive promotions, accessory bundling, and limited-edition variants.
- Apply similar strategies to other growing categories (Women Fashion, Superstore) to sustain growth and capture more market share.
- For Books and Others, pilot new formats (e-books, audiobooks, community engagement campaigns) to test demand revival.

### Leverage Seasonal and Weekly Insights

- For peak months (August, September, December), prepare early with increased inventory, pre-launch teasers, and multi-channel ad campaigns.
- For low months (April, March), use themed sales events (“Mid-Year Sale”, “Back-to-School”) to drive engagement.
- Run targeted weekend promotions or exclusive product drops to lift sales on weaker days.

### Invest in Continuous Customer Engagement

- Launch loyalty programs rewarding repeat purchases, referrals, and digital payment use.
- Use purchase history and behavior analytics to deliver personalized product recommendations.
- Collect post-purchase feedback to improve customer experience

### Address Unpaid Orders Proactively

- Identify customer segments with high non-payment rates and deploy tailored recovery strategies.
- Introduce early-payment discounts or flexible installment options for high-value orders.
- Implement automated reminders via SMS, WhatsApp, and email for pending payments.


---

## Clarifying Questions, Assumptions, and Caveats

### Questions for Stakeholders

1. Should revenue reporting focus on before discount for behavioral insights, after discount for actual earnings, or maintain both for different decision-making needs?
2. Unpaid Orders:
   - What is the primary reason for the high number of customers with unpaid orders?
   - Are most of these unpaid orders canceled, or is there a successful collection process?
   - Are unpaid statuses standardized (e.g., pending, canceled, payment failed)?
3. Is there a loyalty or retention program to encourage repeat purchases?
4. Does the business focus remain on COD as the dominant method, or is there a target to increase the use of digital payments?

### Assumptions and Limitations

- Revenue Calculation: Before discount values were used to analyze sales behavior unaffected by promotions, while after discount would more accurately reflect realized revenue. The chosen metric should align with the analysis goal.
- Unpaid Orders Impact: All unpaid orders are assumed to represent unrealized revenue. Their high volume could distort potential revenue figures if recovery rates are low.
- Digital Adoption: The assumption that digital investment will increase online sales may not hold true if customer preference remains skewed towards physical stores .

---

## Detailed Reports

- **Dataset Overview**: [merged_clean.csv](https://drive.google.com/file/d/1FUIc4RpZ3hXFPilEs3oJdapXtPfjdNmL/view?usp=sharing)
- **Github Repo**: [README.md](https://github.com/frdz-salman/MySkill_Superstore.git)
- **Jupyter Notebook**: [myskill_superstore.ipynb](https://github.com/frdz-salman/MySkill_Superstore/blob/main/Exploration/myskill_superstore.ipynb)
- **SQL Scrypt**: [myskill_superstore.sql](https://github.com/frdz-salman/MySkill_Superstore/blob/main/Exploration/myskill_superstore.sql)
- **Tableau Dashboard**: [Global Electronics Retail Dashboard](https://public.tableau.com/app/profile/faridz.salman.al.parissy/viz/Finpro-Myskill/Campaign)

---
