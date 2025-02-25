# Excel-Insurance-Data-Analysis-Dashboard

## **1. Background and Overview**
Insurance underwriting plays a critical role in assessing policyholder risk, optimizing premium pricing, and managing claims. This project analyses customer data, policy attributes, and claim patterns to identify key trends and support **data-driven decision-making**.  

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
![Dashboard](https://github.com/MichellePuiKa/Excel-Insurance-Data-Analysis-Dashboard/blob/main/Dashboard.PNG)

This project analyses personal auto insurance data to uncover key insights related to distribution channels, time-to-conversion, claim frequency, and severity across different demographics and regions. The findings aim to support data-driven decision-making for optimizing sales strategies, risk management, and customer engagement.

### **Key Findings:**
- Distribution Channels: Online is the most dominant channel, contributing 60% of policy sales, followed by agents (30%) and referrals (10%)
- Time-to-Conversion: Agents show slightly higher average time-to-conversion compared to Online and Referral channels
- Claim Frequency by Region & Age Group: Urban regions have the highest claim frequency, making up 49% of total claims.  The 35-44 age group in urban areas reports the highest number of claims, peaking at 400 claims under Full Coverage
- Regional Variations in Claims: Urban regions have the highest claim frequency, followed by suburban (30%) and rural (20%)
- Claim Severity: The majority of claims fall under low severity, followed by medium and high severity


## **4. Insights Deep Dive**

![Donut Chart](https://github.com/MichellePuiKa/Excel-Insurance-Data-Analysis-Dashboard/blob/main/Distribution%20Channels.PNG)

- **Three Distribution Channels:** Agent, Online & Referral
- **Key Insight**: Online is the primary distribution channel, accounting for 60% of total policies, while Agent and Referral contribute 30% and 10%, respectively


![Column Chart](https://github.com/MichellePuiKa/Excel-Insurance-Data-Analysis-Dashboard/blob/main/Comparison%20of%20Average%20Conversion%20Rates.PNG)

- Analyzed time-to-conversion for both insurance types across all 3 distribution channels
- **Key Insight**: The Agent channel had a slightly higher average time-to-conversion rate compared to Online and Referral channels


![Stacked Column](https://github.com/MichellePuiKa/Excel-Insurance-Data-Analysis-Dashboard/blob/main/Average%20of%20Claims%20Frequency%20Per%20Age%20Groups%20with%20Regions.PNG)

- **Regions**: Urban, Suburban & Rural
- **Key Insight**: The 35-44 age group had the highest average claim frequency, with those living in Urban areas accounting for 49% of total claims within this group. Meanwhile, individuals in the same age group residing in Suburban and Rural areas contributed to 30% and 20% of the claims, respectively


![Column Chart](https://github.com/MichellePuiKa/Excel-Insurance-Data-Analysis-Dashboard/blob/main/The%20Highest%20Claim%20Frequency%20Per%20Regions.PNG)

- Categorised by Policy Types and Regions
- **Key Insight**: For Full Coverage policies in Urban region, the highest claim frequency was observed, with the 35-44 age group reporting the most claims, reaching 400. Liability-Only policies in Urban region had the second-highest claim frequency, with the 25-34 and 35-44 age groups showing nearly identical claim counts of 224 and 226, respectively


![Stacked Bar Chart](https://github.com/MichellePuiKa/Excel-Insurance-Data-Analysis-Dashboard/blob/main/Claim%20Frequency%20and%20Severity%20Breakdwon%20by%20Age%20Group%20%26%20Policy%20Type.PNG)

- Categorised by Age Group and Policy Types with Low, Medium and High Severity
- **Key Insight**: Overall, most claims fall under the low severity category, followed by medium severity, with high-severity claims being the least common


## **5. Recommendations**

- **Optimize Digital Marketing:** Since Online is the primary distribution channel, enhancing digital marketing efforts can drive higher engagement and conversions.
- **Improve Agent Efficiency:** Streamlining the agent sales process through better tools and training could reduce time-to-conversion.
- **Adjust Premium Pricing for High-Risk Segments:** The 35-44 age group in urban areas shows the highest claim frequency, suggesting a need for risk-based pricing adjustments.
- **Strengthen Referral Programs:** With referrals contributing only 10%, incentives can be improved to increase customer acquisition through word-of-mouth.
- **Implement Risk Mitigation Strategies:** For urban policyholders, promoting safer driving initiatives or telematics-based insurance could help manage claim risks.


## **💡 Connect & Feedback**
Have suggestions or feedback? Feel free to **open an issue**!  



