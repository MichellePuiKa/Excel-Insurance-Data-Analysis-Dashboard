# Excel-Insurance-Data-Analysis-Dashboard

## **1. Background and Overview**
Insurance underwriting plays a critical role in assessing policyholder risk, optimizing premium pricing, and managing claims. This project analyzes customer data, policy attributes, and claim patterns to identify key trends and support **data-driven decision-making**.  

This analysis is done in **Microsoft Excel**, leveraging **pivot tables, calculated fields, and interactive charts** to present actionable insights.  



## **2. Data Source & Structure**
### **2.1 Data Source**
This dataset was obtained from **[Kaggle - Insurance Dataset Based on Real-World Statistics](https://www.kaggle.com/datasets/samialyasin/insurance-data-personal-auto-line-of-business)**.
The original dataset was created by **Mark Otto and Andrew Fong** and is used here for **educational and analytical purposes**.
The data has been **cleaned, processed and visualised** in Excel to showcase underwriting insights.

### **2.2 Data Structure Overview**
The dataset contains **customer demographics, policy details, claims history, and conversion metrics**. Below are the key fields analysed:
| **Category**          | **Fields** |
|----------------------|----------------------------------------------------------------|
| **Customer Profile** | `Age`, `Marital_Status`, `Region`, `Credit_Score` |
| **Policy Details**   | `Policy_Type`, `Premium_Amount`, `Total_Discounts` |
| **Claims Analysis**  | `Claims_Frequency`, `Claims_Severity (Low/Medium/High)`, `Claims_Adjustment` |
| **Conversion Metrics** | `Source_of_Lead`, `Time_Since_First_Contact`, `Conversion_Status` |
| **Premium Adjustments** | `Prior_Insurance_Premium_Adjustment`, `Premium_Adjustment_Credit`, `Premium_Adjustment_Region` |

Data cleaning steps include **removing duplicates, handling missing values, and creating calculated fields** for age groups and discount impact.



## **3. Executive Summary**
### **Key Findings**
✔ **Young policyholders (Under 25) had the highest claims frequency**, while **middle-aged customers (35-44) showed lower risk profiles**  
✔ **Higher credit scores correlated with lower claims severity** and **lower premium adjustments**  
✔ **Bundling policies (multi-policy discounts) led to increased customer retention and lower claims frequency**  
✔ **Online leads converted faster than broker-referred customers**, indicating a shift in distribution trends

These insights help **optimise underwriting strategies, pricing models, and marketing efforts** to enhance profitability.



## **4. Insights Deep Dive**
### **📊 Claims Analysis by Age Group & Severity**
- **Stacked Bar Chart**: Age groups are divided into **Low, Medium, and High claim severity**.
- **Key Insight**: **Older customers (45+) had fewer but higher-severity claims**, affecting underwriting risk.

### **📈 Premium Adjustment Analysis**
- **Combo Chart**: Premium adjustments vs. prior insurance and credit scores.
- **Key Insight**: Customers with **prior insurance** and **higher credit scores** received more **favorable premium adjustments**.

### **📉 Customer Conversion Trends**
- **Pivot Table & Line Chart**: Analyzed time-to-conversion by source.
- **Key Insight**: **Online inquiries had a 20% faster conversion rate** compared to traditional broker leads.



## **5. Recommendations**
🚀 **Enhance Pricing Strategies**: Adjust premium structures for younger policyholders based on risk segmentation.  
📢 **Optimize Digital Lead Generation**: Invest more in online acquisition channels due to faster conversion rates.  
🔄 **Encourage Multi-Policy Bundling**: Further promote bundling to increase policyholder retention and reduce claims frequency.  
📊 **Expand Risk-Based Underwriting**: Use more granular data points (such as driving history) to refine underwriting decisions.  



## **💡 Connect & Feedback**
🔗 Have suggestions or feedback? Feel free to **open an issue**!  
📜 License: This project is for **educational and demonstration purposes**.  



