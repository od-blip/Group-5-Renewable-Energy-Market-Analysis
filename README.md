
# **Renewable Energy Marketplace Development Survey Analysis (Group 5)**


## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Data Cleaning](#data-cleaning)
3. [Data Transformation](#data-transformation)
4. [Analysis & Visualization](#analysis-and-visualization)
5. [Key Insights & Recommendations](#key-insights-and-recommendations)
6. [Conclusion](#conclusion)

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

Market Insights and Recommendations for Renewable Energy Marketplace Development

1. Consumer Demographics

Insight: The consumer base comprises primarily individual consumers (89%), followed by small businesses (6%) and government organizations (5%).

Recommendation: Tailor the marketplace to cater to individual consumers by focusing on user-friendly, self-service options and educational resources. For small businesses and government entities, consider offering bulk purchase options or customized solutions to support larger projects.


2. Age Group Analysis

Insight: A significant portion of respondents are young adults: 53% are aged 25–34 and 42% are aged 15–24. Only a small percentage (5%) are aged 45–54.

Recommendation: Given the youthful demographic, leverage social media and digital advertising to promote the platform, focusing on platforms popular with young adults. Educational content on renewable energy benefits could increase engagement among younger audiences.


3. Budget Constraints

Insight: Most respondents (61%) indicated they can only spend under ₦500,000, while 22% fall into the ₦500,000–₦1,000,000 range, suggesting that affordability is a priority.

Recommendation: Offer a range of affordable product options and financing plans. Emphasize products like solar panel kits or entry-level inverters that align with these budget limits. Highlight any available government incentives or subsidies to further support affordability.


4. Product Preferences

Insight: The preferred products, based on multiple selections, include solar panels (27 selections), inverters (19), and batteries (13). Electric vehicle chargers (6) and wind turbines (1) received fewer mentions, indicating lower interest.

Recommendation: Focus initial marketplace offerings on solar panels, inverters, and batteries. Consider positioning electric vehicle chargers and wind turbines as niche products, targeting specific audiences with specialized marketing.


5. Challenges and Pain Points

Insight: The biggest challenge for consumers is a lack of trust in product quality (24 responses), followed by concerns over high costs (8 responses) and long shipping times (3 responses).

Recommendation: To build trust, emphasize quality assurance through detailed product descriptions, customer reviews, and certifications. Partner with reputable suppliers and highlight quality standards. Address cost concerns with transparent pricing and explore options to reduce shipping times where possible.


6. Importance Ratings of Purchase Factors

Insight: The most important factors in choosing renewable energy products are Energy Efficiency (4.36 average), followed by Eco-Friendliness and Warranty Period (both 4.03). Cost (3.86) and Brand Reputation (3.58) are rated lower.

Recommendation: Highlight energy-efficient products and provide detailed information on eco-friendliness to appeal to consumer priorities. Offer extended warranty options to increase consumer confidence. Consider introducing a “best value” badge to indicate products that balance efficiency and affordability.


7. Transaction Preferences

Insight: The most preferred payment method is bank transfer (23 respondents), with smaller groups favoring credit cards (8), digital wallets (3), and cryptocurrency (2). No respondents chose PayPal.

Recommendation: Ensure that bank transfers are seamless and secure. Consider offering discounts for this payment method if feasible. Maintain a range of options, but prioritize the most popular ones, as these will likely enhance the user experience.


8. Expected Support Options

Insight: In terms of customer support, 24/7 support (26 selections), installation services (23), and technical support (18) are the most desired options. Warranty handling (15) and product consultation (12) are also valued.

Recommendation: Offer accessible 24/7 support, especially via chat or phone. Provide an option for professional installation services to enhance product usability and offer technical support resources like FAQs or video tutorials. Highlight warranty policies and include expert consultation services for users needing advice on product selection.

9. Additional Feature Preferences

Insights: Respondents showed high interest in customer reviews (20 selections) and energy cost calculators (19), with additional demand for subscription options and a product comparison tool (14 each). Customizable product options (12) were also requested, reflecting a desire for personalized and informative purchasing experiences.

Recommendations: Implement customer reviews to build trust, add an energy cost calculator to highlight potential savings, and provide subscription options for ongoing needs. Offer a product comparison tool to aid decision-making and customizable options for tailored solutions. These features will enhance user satisfaction and support informed choices.

---

## Conclusion

The survey analysis reveals that the primary target market for the renewable energy marketplace consists of budget-conscious, young, individual consumers with a preference for solar energy solutions. They highly value energy efficiency and eco-friendliness and are cautious about product quality and affordability. By focusing on quality assurance, affordable product options, reliable customer support, and targeted digital marketing, the marketplace can effectively attract and serve this audience. These recommendations align the marketplace’s offerings with consumer expectations, fostering a trustworthy platform that caters to the practical needs of the renewable energy community.


---
