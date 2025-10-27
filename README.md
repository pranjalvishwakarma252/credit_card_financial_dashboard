 📌 **Dashboard Overview**
- **Purpose**: Designed to analyze credit card customer behavior and transaction trends across demographics, card categories, and usage types.
- **Data Source**: Connected directly to a SQL database for real-time data extraction and refresh.
- **Structure**: Split into two main views—Customer Report and Transaction Report—each offering granular insights.


 🧮 **Data Modeling & Measures**
- Created **custom measures** for revenue, interest earned, transaction volume, and customer segmentation.
- Built **calculated columns** to categorize age groups, income levels, education tiers, and card usage types.
- Applied **DAX logic** to enable dynamic filtering and comparative analysis across quarters and customer segments.


 📊 **Customer Report Highlights**
- **Quarterly Revenue & Interest**: Visualized trends across Q1–Q4 with total revenue of ₹55M and interest of ₹8M.
- **Demographic Breakdown**:
  - Age groups 40–50 and 50–60 are top contributors to revenue.
  - Gender split shows slightly higher revenue from male customers.
  - Education level and income group visuals highlight high-value segments (e.g., graduates and high-income earners).
- **Geographic Insights**: Top contributing states include TX, NY, CA, FL, and NJ.
- **Customer Job Analysis**: Businessmen and white-collar professionals generate the highest revenue and interest.


💳 **Transaction Report Highlights**
- **Card Category Performance**:
  - Blue cards dominate with ₹46M revenue and highest transaction volume.
  - Silver and Gold follow with moderate usage and revenue.
- **Transaction Channels**:
  - Swipe transactions lead with ₹35M revenue, followed by chip (₹17M) and online (₹3M).
- **Expenditure Type Analysis**:
  - Bills, entertainment, and groceries are top spending categories.
  - Travel and fuel show moderate engagement, useful for targeted offers.


 🧠 **Interactivity & Usability**
- Enabled **slicer filters** for card type, gender, education, and income group.
- Designed for **executive-level storytelling** with clean layout and intuitive navigation.
- Supports **drill-through** for deeper exploration of customer segments and transaction behavior.


 🛠️ **Technical Highlights**
- Used **Power Query** for data transformation and cleanup.
- Leveraged **SQL joins and filters** to optimize data before loading into Power BI.
- Ensured **data integrity** with consistent formatting and validation checks.
