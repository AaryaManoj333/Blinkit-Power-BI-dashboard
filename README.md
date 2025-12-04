This repository contains the source files and documentation for a Power BI Dashboard focused on analyzing the historical sales performance and key operational metrics for a large supermarket/grocery chain (simulating Blinkit data).

The goal of this project is to provide actionable insights into product sales, outlet performance, and operational efficiency across different store tiers and locations.

By examining two key metrics—**Total Sales (Revenue)** and **Average Sales (Basket Size)**—this dashboard reveals critical differences between where the company generates volume and where it achieves transaction value.
![Blinkit Sales Dashboard Screenshot](blinkit%20dashboard.png)

#### 1. Outlet Location & Performance: Volume vs. Value

| Category | Total Sales (Volume Driver) | Average Sales (Value Driver) | Key Comparative Insight |
| :--- | :--- | :--- | :--- |
| **Outlet Tier** | **Tier 3** is the revenue leader ($\$472.13K$), followed by Tier 2 ($\$393.15K$). | All tiers are virtually identical (Tier 2/3 at 142, Tier 1 at 140). | **Tier 3 drives volume/traffic**, but customers who shop there do not spend significantly more per trip than those at Tier 1 or 2 stores. The focus for increasing revenue must be on **customer acquisition** in Tiers 1 and 2, not on increasing their basket size. |
| **Outlet Type** | **Supermarket Type1** dominates total sales ($\$787.55K$). | All outlet types are virtually identical (ranging from 140 to 142). | The Supermarket Type1 model is superior for **generating overall sales volume**, but the average customer shopping trip value is uniform across the entire network. |

#### 2. Product Category Analysis: Fat Content

| Category | Total Sales (Revenue) | Average Sales (Basket Size) | Key Comparative Insight |
| :--- | :--- | :--- | :--- |
| **Fat Content** | **Regular** products generate nearly double the sales ($\$776.32K$) compared to Low Fat ($\$425.36K$). | **Regular** (142) and **Low Fat** (141) products have an almost identical average sale value. | This is a crucial finding: **Low Fat items are just as valuable per transaction** as Regular items. Their lower Total Sales is solely due to lower volume/traffic, not lower pricing or perceived value. Promotions on Low Fat items could significantly boost their overall revenue contribution without cannibalizing average basket size. |

#### 3. Top-Performing Item Types

* **Top by Total Sales Value:** Fruits & Vegetables ($\$0.18M$), Snack Foods ($\$0.16M$), Household ($\$0.14M$).
* **Top by Average Sales Value:** Household (149), Dairy (148), Starch (146).

The fact that **Household and Dairy** drive the highest *average basket value* but **Fruits & Vegetables / Snack Foods** drive the highest *total revenue* suggests different purchase behaviors: Household/Dairy items may be fewer, higher-priced goods (stocking up), while Fruits/Snacks are high-volume, lower-priced repeat purchases.

#### 4. Actionable Recommendations

1.  **Strategic Focus on Tier 3 & Type1:** Maintain superior operational standards and inventory levels in **Tier 3** locations and **Supermarket Type1** stores, as these are the company's primary revenue engines.
2.  **Targeted Low Fat Promotions:** Launch targeted marketing and shelf placement programs specifically for **Low Fat** products to increase their sales volume. Since their average sales value is high, increasing their volume will directly and efficiently boost total revenue.
3.  **Revenue vs. Basket Growth:** Use the **Household** and **Dairy** categories to focus on **upselling** (increasing basket size), and use **Fruits & Vegetables / Snack Foods** to focus on **volume and customer traffic**.
4.  **Operational Review:** Investigate the specific operational strategies (e.g., staffing, layout, local marketing) of the dominant **Supermarket Type1** to determine which practices can be scaled to other store types to lift their total sales volume.
