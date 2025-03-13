# EDA-ASSIGNMENT-1


### **Dataset Analysis Report: Telco Customer Churn**  

#### **Overview**  
- **Rows:** 7,043  
- **Columns:** 21  
- **No missing values**  
- **No duplicate entries**  

#### **Key Findings**  

1. **Customer Distribution**  
   - The dataset contains **7,043 unique customers** (`customerID`).  
   - Gender distribution is fairly balanced: **Male (50.5%) vs. Female (49.5%)**.  
   
2. **Churn Rate**  
   - The majority of customers did **not churn** (73.5%), while **26.5% churned**.  
   - This suggests an **imbalanced dataset**, which may require resampling techniques in predictive modeling.  

3. **Contract and Payment Preferences**  
   - **Majority (55%) are on a month-to-month contract**, which may contribute to higher churn.  
   - Most common payment method: **Electronic check (33.6%)**.  
   - Customers using **automatic payments tend to stay longer**.  

4. **Monthly Charges and Tenure**  
   - Average **Monthly Charges**: **$64.76** (ranging from $18.25 to $118.75).  
   - Customers with **higher monthly charges** have a **higher likelihood of churn**.  
   - **Average tenure is 32 months**, with 25% of customers having tenure below 9 months.  

5. **Internet and Streaming Services**  
   - **Fiber optic internet users are more likely to churn** than DSL users.  
   - Streaming service users **tend to have higher monthly charges**.  

6. **Potential Data Issues**  
   - **TotalCharges column contains blank spaces**, requiring conversion to numerical format.  

#### **Conclusions & Recommendations**  
- **Customer retention strategies** should focus on **month-to-month contract users**.  
- Offer **discounts or promotions** to customers with **higher monthly charges**.  
- Analyze **Fiber optic users** further to improve retention.  
- Convert **TotalCharges** to numeric format for accurate analysis.  

