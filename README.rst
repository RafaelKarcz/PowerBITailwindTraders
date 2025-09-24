===============================
Tailwind Traders (Power BI)
===============================

A minimal publication of my Tailwind Traders capstone for the Microsoft Power BI Data Analyst course.
This repo intentionally includes only the **Power BI Desktop file** and the **cleaned Excel sources** used after Power Query transformations.

What’s Included
---------------

- ``pbix/TailwindTraders.pbix`` — final report.
- ``data/*.xlsx`` — cleaned input files used to build the model.
- ``assets/*.png`` — (optional) minimal screenshots (Sales/Profit pages).

Report Pages
------------

1. **Sales Overview**
   - KPIs: Stock, Sum Quantity Purchased, Median Sales
   - Slicer: Country Name
   - Visuals: Loyalty Points by Country (Bar), Quantity Sold by Product Category (Column),
     Median Sales Distribution by Country (Pie), Median Sales Over Time (Line)

2. **Profit Overview**
   - KPIs: YTD Profit Margin, Net Revenue (USD), Gross Revenue (USD by Date)
   - Slicer: Date
   - Visuals: Net Revenue by Product (Bar), Yearly Profit Margin by Country (Doughnut),
     Yearly Profit Margin Over Time (Area)

Quick Start
-----------

1. Open ``pbix/TailwindTraders.pbix`` in **Power BI Desktop**.
2. If prompted, confirm the **data source paths** for the Excel files under ``data/``.
3. Refresh the report to validate data and visuals.

Screenshots (Optional)
----------------------

.. image:: assets/report-sales-overview.png
   :alt: Sales Overview page
   :width: 900px

.. image:: assets/report-profit-overview.png
   :alt: Profit Overview page
   :width: 900px

License
-------

This project is licensed under the MIT License — see the ``LICENSE`` file for details.
