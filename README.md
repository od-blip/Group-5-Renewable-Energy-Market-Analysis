
# **Renewable Energy Marketplace Development Survey Analysis**


## **Table of Contents**
1. [Data Cleaning](#data-cleaning)
2. [Data Transformation](#data-transformation)
3. [Analysis & Visualization](#analysis-and-visualization)
4. [Key Insights & Recommendations](#key-insights-and-recommendations)
5. [Conclusion](#conclusion)

---

## **Project Overview**
### Main Dashboard
![image](https://github.com/user-attachments/assets/440b64ba-2b45-4b00-b563-d64b42ad00fa)

This project analyzes survey data to provide insights into potential users' preferences, needs, and budget constraints for a renewable energy marketplace. The analysis aims to guide the development of a platform tailored to consumer demands and marketplace trends in the renewable energy sector.

### Subsequent Dashboard
![image](https://github.com/user-attachments/assets/0617b3bd-3ee3-4f15-8df8-597689a33601)


---
## **Data Cleaning**

### Steps Taken:
1. **Removed Duplicates**: Identified and removed any duplicate entries to ensure each response was unique.
2. **Standardized Column Values**: For open-ended responses, standardized answers using **Replace Values** to create consistent entries and replaced any blank spaces with "No Response" for completeness.
3. **Renamed Columns**: Simplified column names to make the dataset more readable and easier to reference in analysis steps.

---

## **Data Transformation**

### Steps Taken:
1. **Split Multiple-Selection Columns**: Used **Split by Delimiters** to separate multiple-selection (checkbox) answers into individual columns. Null cells were replaced with `0` for consistency, and all newly created columns were appropriately renamed for clarity.
2. **Converted Rating Scales**: Transformed qualitative ratings (e.g., "Not Important" to "Very Important") into numerical values ranging from **1–5** for easier aggregation and analysis of importance factors.

---

## **Analysis and Visualization**

### Methods and Techniques:
1. **Counting Checkbox Data**:
   - Used `COUNTIF` in Excel to count occurrences in multiple-selection columns, including:
      - Preferred Products
      - Expected Support Options
      - Additional Feature Preferences
   - Created three charts based on these counts to visualize preferences for products, support options, and valued features.

2. **Budget Range Analysis**:
   - Created a **Pivot Table** to calculate and display the percentage distribution of each budget range, allowing us to gauge pricing expectations across respondents.

3. **Consumer Demographics**:
   - Analyzed the **Age Group** and **Consumer Type** fields using pivot tables to determine the frequency of each category and calculate the percentage share of each group.

4. **Transaction Preferences and Challenges**:
   - Used pivot tables to display preferences for payment methods and document the main challenges faced by respondents, giving insight into common pain points.

5. **Trend Analysis for Age Group and Consumer Type**:
   - Analyzed the **frequency trends** within both the age group and consumer type categories to understand the dominant consumer profiles.

---

## **Key Insights and Recommendations**

### Insights:
- **Consumer Base**: Primarily individual consumers, mostly young adults aged 25–34, with limited budgets.
- **Top Products**: Solar panels, inverters, and batteries.
- **Challenges**: Quality trust, high costs, and long shipping times.
- **Preferred Support**: 24/7 support, installation, and technical assistance.
- **Desired Features**: Customer reviews, energy cost calculators, and subscription options.

### Recommendations:
- Emphasize affordable, high-quality solar solutions.
- Implement robust support and an accessible 24/7 helpdesk.
- Include customer reviews, cost calculators, and comparison tools to build trust and aid decision-making.

---

## **Conclusion**

The survey analysis provides critical insights into potential users' preferences and pain points in the renewable energy market. By focusing on these areas, the renewable energy marketplace can effectively cater to consumer needs, promote energy-efficient solutions, and foster a trustworthy platform aligned with user expectations.
