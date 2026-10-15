# RIKI E-Commerce Sales Dashboard

An interactive Power BI dashboard for exploring e-commerce sales, profit, order quantity, customer performance, and product mix. Quarter and state filters let viewers examine how results vary across the available periods and locations.

## Dashboard Preview

Save the screenshot in this repository with the filename `Ecommerce sales dashboard screenshot.jpg` to display it here:

![RIKI E-Commerce Sales Dashboard](Ecommerce%20sales%20dashboard%20screenshot.jpg)

## Project Purpose

E-commerce teams need a quick way to review sales performance and understand which locations, products, customers, and payment methods contribute to results. This report brings those measures together in one view to support performance monitoring and exploration.

## Tools and Technologies

- **Power BI Desktop** — report authoring and interactive visualizations.
- **Power Query** — data preparation, if used in the project.
- **DAX** — measures and calculations, if used in the project.
- **Power BI report (`.pbix`)** — editable project file.
- **JPG** — dashboard preview image.

> The specific Power Query transformations, DAX measures, and model relationships have not been documented here because they could not be confirmed from the dashboard preview alone.

## Data

The report appears to use e-commerce records with sales, profit, quantity, customer, product category/subcategory, payment mode, state, and month or quarter fields. The source dataset and its license were not included in the project information provided. Add the dataset name, publisher/source link, date coverage, and any usage conditions here before sharing the repository publicly.

## Dashboard Highlights

- **Summary cards:** Total Sales, Average, Quantity, and Total Profit. The screenshot displays approximately **71K** sales, **11K** average, **458** quantity, and **17K** profit for the selected view. Values change with the report filters.
- **Quarter filter:** Select Qtr 1 through Qtr 4.
- **State filter:** Filter the report by state.
- **Sales by state:** Compare sales across states, with the screenshot showing California, Texas, Maryland, and New York.
- **Profit by subcategory:** Compare profit across product subcategories such as Accessories, Kitchen tools, Yoga, Personal Care, and Writing.
- **Sales by customer:** Compare sales for customers shown in the selected view.
- **Quantity by payment mode:** See how quantity is distributed among payment methods, including PayPal, credit card, digital wallet, gift card, and debit card.
- **Quantity by category:** Review the category mix, including Electronics, Apparel, Kitchen, Fitness, Stationery, Beauty, and Outdoor.
- **Monthly sales and profit:** View the measures by month for the period shown in the report.

## Business Questions

The report can help explore questions such as:

- Which states have the highest sales in the selected quarter?
- Which subcategories contribute the most profit?
- How do sales compare among customers?
- Which payment methods and product categories account for the most quantity?
- How do monthly sales and profit change over the displayed period?

## Repository Contents

```text
.
├── README.md
├── RIKI_ECOMMERCE.pbix
└── Ecommerce sales dashboard screenshot.jpg
```

Place the `.pbix` file and screenshot beside this README when uploading the project. The screenshot filename must match the image link above, or update that link to match your chosen filename.

## Open the Report

Download `RIKI_ECOMMERCE.pbix` and open it with Power BI Desktop. Depending on how the report connects to its source data, you may need access to that data and may need to update credentials or data-source settings.

## Sharing and Privacy

A public GitHub repository makes every committed file available for anyone to view or download. Check the `.pbix` and screenshot for private or sensitive data before uploading. GitHub hosts the project files; it does not render the `.pbix` as an interactive dashboard. To make the report interactive for a broad audience, publish it through Power BI using an appropriate public-sharing option, and only if the underlying data is safe to expose publicly.
