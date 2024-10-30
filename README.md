# Supplier Quality Insights Dashboard

## Overview
This repository provides a Power BI dashboard for in-depth analysis of supplier quality and performance. Focused on key metrics across vendors, plants, materials, and defect types, this dashboard enables manufacturers to monitor and improve quality, reduce downtime, and make data-driven decisions. 

Based on a real-world case study, this project helps a manufacturing company streamline its procurement data, identify quality issues, and address operational inefficiencies through comprehensive business intelligence.

## Key Features
- **Defect Monitoring**: Tracks defect types and quantities across vendors, materials, and plants.
- **Downtime and Cost Analysis**: Visualizes downtime hours and associated costs to illustrate the financial impact of defects.
- **Performance Highlights**: Identifies top-performing and underperforming vendors, plants, and materials based on defect rates and downtime.
- **Trend Analysis**: Shows monthly trends in defects and downtime to easily identify patterns and seasonal fluctuations.
- **Vendor-Plant/Material Risk Assessment**: Examines vendor relationships with specific plants or materials, uncovering high-risk areas.
- **Financial Impact Overview**: Quantifies financial losses linked to downtime, supporting data-driven improvements.

## Data Model
Built with a **Star Schema** data model, the dashboard is optimized for efficient analysis and performance. The data structure includes key dimensions in separate tables and a centralized fact table for tracking core metrics.

- **Fact Table**: Captures metrics like `Defect Quantity` and `Downtime Hours`.
- **Dimension Tables**: Organizes details for `Vendor`, `Plant Location`, `Material Type`, and `Defect Type`.
- **Date Table**: Supports time-based reporting, allowing for trend tracking and time-period filters.

## Getting Started
### Prerequisites
- **Power BI Desktop**: Install Power BI Desktop from [Microsoft's website](https://powerbi.microsoft.com/desktop/).

### How to Use
1. Clone the repository to your local environment:
   ```bash
   git clone https://github.com/yourusername/supplier-quality-insights-dashboard.git
   ```
2. Open the Power BI `.pbix` file in Power BI Desktop.
3. Connect the dashboard to your data by importing CSV files or linking databases as needed.
4. Refresh the data to populate the visualizations with your dataset.

### Dashboard Sections
The dashboard is organized into multiple sections, each focused on a different aspect of supplier quality and performance:

- **Overview**: Shows overall metrics like total defect counts, downtime hours, and financial impact.
- **Vendor Performance**: Analyzes vendors based on defect and downtime metrics to highlight areas of strength and improvement.
- **Plant Performance**: Assesses plant locations to identify sites with high defect rates or extended downtimes.
- **Material Quality**: Provides insights on defect trends by material type, helping pinpoint quality issues by product.
- **Downtime Cost Impact**: Quantifies the cost of downtime, highlighting high-impact periods and areas for improvement. 

## Conclusion
This Supplier Quality Insights Dashboard empowers manufacturers to manage and improve supplier performance by centralizing key data and providing actionable insights. By using this tool, companies can reduce downtime, address defects more effectively, and make strategic decisions to boost overall operational efficiency.
