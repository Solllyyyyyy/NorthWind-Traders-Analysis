# NorthWind Traders Analysis

<img width="1214" height="716" alt="Screenshot 2026-10-07 173609" src="https://github.com/user-attachments/assets/4371c6ab-2d56-44ce-8323-4e06ce175b41" />


### What was I trying to understand?

NorthWind Traders had a large amount of sales data, but I wanted to go beyond simply looking at total revenue.

I wanted to understand what was actually driving the company's sales performance.

Which products were carrying the business? Which categories were strongest? Were some employees or markets performing significantly better than others? And were there operational areas, such as shipping, that could be affecting profitability?

I used Power BI to explore these questions and turn the findings into an interactive sales performance dashboard.

## Dataset

The dataset contains NorthWind Traders' sales information covering **July 2013 to April 2015**.
[Northwind Traders Dataset-20260426T212151Z-3-001.zip](https://github.com/user-attachments/files/33181769/Northwind.Traders.Dataset-20260426T212151Z-3-001.zip)


The analysis includes data relating to:

* **830 orders**
* **77 products**
* **91 customers**
* **9 employees**
* **3 shippers**
* **8 product categories**
* Product and supplier information
* Order and sales information

This gave me enough data to look at NorthWind's performance from both a sales perspective and an operational perspective, rather than focusing on revenue alone.


### The Analysis

I looked at the business from four main angles:

* Revenue trends: How sales changed over time and where growth was coming from
* Products & categories: Which products and categories were contributing most to revenue
* People & markets: How employee and regional performance differed
* Shipping: How shipping providers compared in terms of cost, delivery time, and revenue

### What I Found

The analysis revealed several things that stood out.

**Revenue growth was largely volume-driven.** Sales increased considerably toward the end of 2014 and into early 2015, with revenue reaching more than €0.3M in Q1 2015.

**A relatively small group of products was driving a large portion of sales.** Côte de Blaye, Thüringer Rostbratwurst, Raclette Courdavault and Camembert Pierrot were among the strongest revenue contributors.

**There was an interesting opportunity hiding in discontinued products.** The analysis identified approximately €91K in sales associated with discontinued products, suggesting that some products marked as discontinued may be worth reassessing based on their historical demand.

**Performance also varied across employees and markets.** Margaret Peacock was the strongest-performing employee by revenue, while the USA was NorthWind's strongest regional market.

**Shipping presented a trade-off.** United Package generated the most revenue but also had the highest average shipping cost and delivery time among the three shippers analyzed.

### What would I recommend?

Based on these findings, I would recommend that NorthWind:

* Prioritize products and categories that consistently generate strong revenue.
* Reassess selected discontinued products rather than treating all discontinued products as lost opportunities.
* Identify practices used by top-performing employees that could be replicated across the sales team.
* Investigate weaker-performing markets to understand the reasons behind lower sales.
* Review shipping providers based on both cost and delivery performance, rather than revenue contribution alone.

[NorthWind Project Report.pdf](https://github.com/user-attachments/files/33181863/NorthWind.Project.Report.pdf)

<img width="1225" height="667" alt="Screenshot 2026-10-07 174505" src="https://github.com/user-attachments/assets/4aaa8632-15e2-410b-a25c-f85702cc6924" />

<img width="1197" height="725" alt="Screenshot 2026-10-07 174622" src="https://github.com/user-attachments/assets/6e2f24f6-af03-4e7e-aea3-9ac3b1092778" />

<img width="1224" height="722" alt="Screenshot 2026-10-07 174600" src="https://github.com/user-attachments/assets/ac0e0d4f-bd0a-4077-ae26-5353bd7ea35e" />



### Tools

Power BI
Data visualization | Business intelligence | Sales performance analysis

### Project Outcome

This project helped me practice something I consider important in data analysis: moving from "what happened?" to "why does it matter?"

The dashboard makes the numbers easier to explore, but the real goal of the analysis was to identify the patterns behind those numbers and turn them into decisions the business could act on.
