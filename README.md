# Supply Chain Analytics Dashboard

![Dashboard Preview](images/dashboard-preview.png) *(Optional: Add screenshot image)*

## Overview
This Power BI dashboard provides comprehensive visibility into supply chain operations, analyzing product performance, supplier efficiency, logistics optimization, and customer preferences. The interactive visualizations help identify bottlenecks, optimize inventory, and improve profitability across the supply chain.

## Key Features
- **Product Performance**: Track top-selling SKUs, revenue trends, and stock levels
- **Supplier Analysis**: Compare quality metrics, lead times, and costs by supplier
- **Logistics Optimization**: Evaluate transportation modes by cost and delivery time
- **Customer Insights**: Understand demographic preferences and buying patterns
- **Inventory Management**: Identify stockout risks and overstocked items

## How to Use the Dashboard

### Navigation
1. **Overview Tab**: High-level KPIs and cross-category comparisons
2. **Supplier Performance**: Quality metrics and supplier benchmarking
3. **Logistics Analysis**: Transportation mode efficiency and route optimization
4. **Customer Insights**: Demographic segmentation and product preferences

### Interactivity
- Use **slicers** (top filters) to focus on specific:
  - Product types (haircare, skincare, cosmetics)
  - Time periods
  - Geographic locations
  - Transportation modes
- **Click on visual elements** to cross-filter other components
- **Hover over charts** to see detailed tooltips
- Use **drill-through** by right-clicking data points

### Special Features
- **Stockout Risk Alerts**: Red indicators highlight inventory shortages
- **Efficiency Quadrants**: Visualize cost vs. time tradeoffs in logistics
- **Preference Index**: Shows which demographics over-index on products
- **Dynamic Titles**: Update based on current filters

## Data Sources
- Primary dataset: `supply_chain_data.csv`
- Fields include:
  - Product information (SKU, type, price)
  - Inventory metrics (stock levels, lead times)
  - Supplier details (name, location, defect rates)
  - Logistics data (shipping times, costs, carriers)
  - Customer demographics

## Setup Instructions
1. Clone this repository
2. Open `supply_chain_dashboard.pbix` in Power BI Desktop
3. Ensure your data source path is correctly configured
4. Refresh the data connection if needed

## Requirements
- Power BI Desktop (October 2020 release or later)
- Basic understanding of supply chain metrics

## Troubleshooting
If visualizations don't display properly:
1. Verify all data fields are properly mapped
2. Check for filters that may be hiding data
3. Ensure all DAX measures calculate without errors

## Contributing
To suggest improvements:
1. Fork this repository
2. Create a feature branch
3. Submit a pull request with clear documentation

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
