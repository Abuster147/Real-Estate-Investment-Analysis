# Real Estate Investment Analysis

## Overview
This project focuses on analyzing real estate investments by calculating return on investment (ROI) and evaluating potential risks. Various financial metrics like cash flow, Net Present Value (NPV), and Internal Rate of Return (IRR) are used to assess profitability across multiple real estate properties. The project also includes investment risk analysis through sensitivity analysis, stress testing, and scenario modeling, and it provides insights into market trends using economic indicators and real estate data.

## Key Features
- **ROI Calculation**: Calculate ROI for different real estate properties using cash flow, NPV, and IRR.
- **Risk Assessment**: Perform sensitivity analysis, stress testing, and scenario modeling to assess investment risks.
- **Market Trend Analysis**: Analyze regional market trends using property prices, rental yields, and economic indicators.
- **Comparative Analysis**: Identify profitable opportunities through metrics such as price per square foot, cap rate, and occupancy rate.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/username/real-estate-investment-analysis.git
   cd real-estate-investment-analysis
   pip install -r requirements.txt
   from real_estate_analysis import calculate_roi

    property_data = 'data/properties.csv'
    roi_metrics = calculate_roi(property_data)
    print(roi_metrics)

