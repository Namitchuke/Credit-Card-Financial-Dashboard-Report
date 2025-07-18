# Credit Card Financial Dashboard - Power BI Project

## 1. Project Overview

This project presents a comprehensive Credit Card Financial Dashboard designed to provide actionable insights into credit card transactions, customer behavior, and business performance metrics. The dashboard analyzes credit card data across multiple dimensions including customer demographics, transaction patterns, revenue generation, and operational efficiency.

The project encompasses two main analytical views:
- **Transaction Report**: Focuses on revenue analysis, transaction volumes, and expense categorization
- **Customer Report**: Analyzes customer demographics, income groups, and behavioral patterns

### Key Performance Indicators (KPIs)
- **Total Revenue**: $55.3M
- **Total Transaction Amount**: $44.5M  
- **Total Interest Earned**: $7.8M
- **Transaction Count**: 655.7K transactions
- **Customer Satisfaction Score**: 3.19/5.0

The dashboard serves as a strategic tool for financial institutions to understand their credit card portfolio performance, identify growth opportunities, and optimize customer acquisition strategies.

## 🛠️ Tools & Libraries

### Data Storage & Processing
- **PostgreSQL**: Primary database for storing and processing credit card and customer data
- **SQL**: Complex queries for data aggregation, KPI calculations, and business intelligence

### Visualization & Analytics
- **Power BI Desktop**: Interactive dashboard creation and data visualization
- **DAX (Data Analysis Expressions)**: Advanced calculations and measures
- **Power Query**: Data transformation and cleaning

### Data Sources
- **CSV Files**: Raw transaction and customer data
  - `credit_card.csv`: Transaction details and card information
  - `customer.csv`: Customer demographics and profile data
  - `cc_add.csv` & `cust_add.csv`: Additional weekly data updates

### Development Environment
- **Git**: Version control and project management
- **Markdown**: Documentation and reporting

## Analysis Overview

### Data Architecture
The analysis is built on a robust two-table structure:

**Credit Card Details (`cc_detail`)**
- Transaction-level data including amounts, categories, and payment methods
- Card category information (Blue, Silver, Gold, Platinum)
- Time-based data for trend analysis
- Interest and fee calculations

**Customer Details (`cust_detail`)**
- Demographic information (age, gender, education, marital status)
- Geographic data (state, zipcode)
- Financial profile (income, job category)
- Satisfaction metrics

### Analytical Dimensions

**1. Temporal Analysis**
- Quarterly performance trends (Q1-Q4)
- Weekly revenue patterns
- Seasonal transaction behaviors

**2. Customer Segmentation**
- Income-based groups (High, Medium, Low)
- Age demographics (20-30, 30-40, 40-50, 50-60, 60+)
- Education levels (Graduate, High School, Post-Graduate, etc.)
- Professional categories (Business, White-collar, Government, etc.)

**3. Product Performance**
- Card category analysis (Blue, Silver, Gold, Platinum)
- Payment method preferences (Swipe, Chip, Online)
- Credit utilization patterns

**4. Geographic Intelligence**
- State-wise revenue distribution
- Regional performance comparison
- Market penetration analysis

**5. Expense Category Analysis**
- Transaction categorization (Bills, Entertainment, Fuel, Grocery, Food, Travel)
- Spending behavior patterns
- Revenue contribution by category

### Key Analytical Metrics

**Revenue Metrics**
- Total revenue by various dimensions
- Interest earned calculations
- Transaction volume analysis

**Customer Metrics**
- Customer satisfaction scoring
- Income analysis and segmentation
- Demographic performance indicators

**Operational Metrics**
- Card utilization ratios
- Customer acquisition costs
- Transaction frequency patterns

## Key Insights & Conclusion

### 🎯 Strategic Insights

**1. Revenue Performance**
- **Q2 Leadership**: Q2 generated the highest revenue at $14.2M, indicating strong mid-year performance
- **Blue Card Dominance**: Blue cards contribute 83% of total revenue ($46M out of $55.3M), showing mass market success
- **Bills Category**: Bills transactions generate the highest revenue ($14M), indicating utility and essential payment preferences

**2. Customer Behavior Patterns**
- **Graduate Advantage**: Graduate customers contribute $22M (40%) of total revenue, highlighting the importance of educated customer segments
- **Professional Focus**: Business professionals generate $17M, followed by white-collar workers at $10M
- **Age Sweet Spot**: 40-50 age group shows highest engagement, suggesting prime earning years drive credit card usage

**3. Payment Method Preferences**
- **Swipe Dominance**: Traditional swipe transactions lead with $35M (63% of revenue)
- **Chip Adoption**: Chip transactions contribute $17M, showing security-conscious behavior
- **Digital Gap**: Online transactions only $3M, indicating potential for digital payment growth

**4. Geographic Concentration**
- **State Leaders**: TX, NY, CA represent top revenue states, aligning with population and economic centers
- **Market Opportunity**: Significant revenue concentration suggests expansion opportunities in underserved states

### 🔍 Operational Insights

**Customer Satisfaction**
- Average satisfaction score of 3.19/5.0 indicates room for improvement
- Focus needed on customer experience enhancement

**Income Segmentation**
- High-income customers show strong engagement
- Medium-income segment presents growth potential
- Low-income customers require tailored product offerings

**Transaction Patterns**
- 655.7K transactions indicate high customer activity
- Strong transaction-to-revenue conversion rate

### 📈 Strategic Recommendations

**1. Product Strategy**
- **Blue Card Optimization**: Enhance blue card offerings given their revenue dominance
- **Premium Card Development**: Develop strategies to increase Gold and Platinum card adoption
- **Digital Payment Push**: Invest in online payment infrastructure and incentives

**2. Customer Acquisition**
- **Graduate Targeting**: Focus marketing efforts on graduate populations
- **Professional Segments**: Develop specialized offerings for business professionals
- **Geographic Expansion**: Consider expansion strategies for underperforming states

**3. Revenue Optimization**
- **Bills Category Enhancement**: Strengthen utility payment partnerships
- **Cross-selling Opportunities**: Leverage high-performing segments for additional services
- **Satisfaction Improvement**: Implement customer experience initiatives to improve satisfaction scores

### 🎯 Conclusion

The Credit Card Financial Dashboard reveals a robust credit card portfolio with strong performance in traditional segments while highlighting opportunities for digital transformation and geographic expansion. The $55.3M revenue demonstrates solid business performance, with clear opportunities for growth through strategic focus on high-performing customer segments and payment method diversification.

The analysis provides a foundation for data-driven decision making, enabling stakeholders to optimize product offerings, enhance customer experience, and drive sustainable revenue growth in the competitive credit card market.

**Next Steps:**
1. Implement customer satisfaction improvement initiatives
2. Develop digital payment adoption strategies  
3. Create targeted marketing campaigns for high-potential segments
4. Expand geographic presence in underperforming markets
5. Enhance product portfolio based on customer preferences
