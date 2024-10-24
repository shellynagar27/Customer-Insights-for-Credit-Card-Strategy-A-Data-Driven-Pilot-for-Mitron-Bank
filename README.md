# Customer-Insights-for-Credit-Card-Strategy-A-Data-Driven-Pilot-for-Mitron-Bank
## Mitron Bank Credit Card Analysis Project

## Project Overview
This project was conducted for **Mitron Bank**, a legacy financial institution headquartered in Hyderabad, which plans to introduce a new line of credit cards to expand its product offerings. **AtliQ Data Services** proposed a data-driven solution for this initiative. As part of a pilot project, Mitron Bank provided a sample dataset of 4000 customers across five cities, focusing on their online spending and demographic details. The insights generated from this data will guide the creation of tailored credit card products.

## Problem Statement and Background
Mitron Bank is exploring ways to introduce a new line of credit cards. **Peter Pandey**, a data analyst at AtliQ Data Services, was tasked with analyzing the customer data provided by the bank and delivering key insights to the strategy team. His analysis is crucial for securing the project by providing actionable, data-driven recommendations that demonstrate a deep understanding of the target customers’ needs.

## Key Objectives
The key objectives of this project were:
1. Analyze the spending patterns and demographic information of Mitron Bank's customers.
2. Provide actionable insights to help Mitron Bank tailor credit card offerings to specific customer segments.
3. Identify key customer groups that are most likely to be high-value users of the new credit cards.
4. Present the findings in a clear, visual, and impactful Tableau dashboard.

## Data Description
The project uses two primary data sources provided by Mitron Bank:

- **`dim_customers.csv`**: Contains demographic information about customers, such as:
  - `customer_id`: Unique ID assigned to each customer.
  - `gender`: Gender of the customer (Male, Female).
  - `age_group`: Age groups of customers (e.g., 21-24, 25-34).
  - `marital_status`: Marital status (Single, Married).
  - `city`: Customer's city of residence (e.g., Mumbai, Delhi-NCR).
  - `occupation`: Profession (e.g., Salaried IT Employees, Business Owners).
  - `average_income`: Monthly average income of the customer (in INR).

- **`fact_spends.csv`**: Contains information about customers' online spending across various categories, including:
  - `customer_id`: Unique ID linked to the `dim_customers` table.
  - `month`: Month in which the spending was recorded.
  - `category`: Spending category (e.g., Entertainment, Electronics).
  - `payment_type`: Type of payment used (e.g., Debit Card, Credit Card).
  - `spends`: Total amount spent in the specified category and month.

## Dashboard Description
The Tableau dashboard provides multiple views that help decision-makers at Mitron Bank understand customer behavior and preferences. The dashboard includes the following pages:

1. **Landing Page**: A summary view that provides high-level insights and directs users to specific analysis sections.
2. **Demographics**: A breakdown of customers by gender, age, occupation, and city, helping to understand customer diversity.
3. **Spend Analysis - 1**: A detailed analysis of average customer spending across various factors such as age, category, and occupation.
4. **Spend Analysis - 2**: A more nuanced analysis considering two factors at once, such as category and gender, occupation and age group.
5. **Income Analysis**: An analysis of how income influences spending behavior and credit card usage potential.
6. **Detailed View**: A consolidated view summarizing key findings across all analyses for quick decision-making.

## Approach and Methodology
1. **Data Exploration & Validation**: Used MySQL to explore and validate the data.
2. **Data Relationships**: Established relationships between `dim_customers` and `fact_spends` tables in Tableau.
3. **Calculated Fields & Parameters**: Created calculated fields to track spending, average income, and customer segmentation. Used parameters to activate button functionality for easier dashboard navigation.
4. **Customer Segmentation**: Identified high-value customer segments based on their spending habits, demographics, and financial behavior.
5. **Recommendations**: Provided recommendations on features that should be included in the new credit cards based on customer needs.

## Insights Generated
- **Spending Patterns**: Identified where customers are spending the most (e.g., Electronics, Apparel) and analyzed the effect of demographics (age, occupation, etc.) on spending behavior.
- **Income Utilization**: Analyzed how customers’ average income utilization affects their likelihood of using credit cards.
- **High-Value Segments**: Segmented customers likely to be the most valuable for the new credit card offering, such as IT professionals and business owners in certain age groups.

## Key Learnings
1. **Data Modeling & Cleaning**: Developed proficiency in data modeling and data cleaning using Tableau.
2. **Interactive Dashboard Creation**: Learned how to create professional-level dashboards with features like sheet swapping, navigation buttons, and custom icons.
3. **Advanced Tableau Techniques**: Implemented calculated fields, parameter controls, and action-based interactivity to enhance user experience.
4. **Visual Design**: Designed visually appealing and functional dashboards using customized color palettes and icons.
5. **Data-Driven Insights**: Gained deep insights into how to tailor products (credit cards) based on customer needs, demographics, and spending patterns.
6. **Tooltips**: Customized tooltips to display contextual insights, enhancing user interactivity and understanding of the data

## Technologies Used
- **MySQL**: For data exploration and validation.
- **Tableau**: For data visualization and dashboard creation.
- **Figma & Flaticon**: For designing custom icons and improving dashboard aesthetics.
- **Excel Direct Method**: To enable sheet swapping and button functionalities.

## Conclusion
This project provided actionable insights for **Mitron Bank** to introduce a new line of credit cards tailored to specific customer needs. By analyzing customer demographics, spending behaviors, and income utilization, the project helped identify key customer segments, offering significant value to the bank’s strategy team.

## Future Enhancements
- Incorporating more data from other regions or customer segments to further refine the credit card offering.
- Integrating real-time data analysis for continuous updates and improvements.

---

This README is intended to guide users and stakeholders through the project’s objectives, methodology, and results, demonstrating how data-driven insights can inform business decisions.
