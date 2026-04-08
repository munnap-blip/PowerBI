# 🚗 Insurance Risk & Claims Analysis – Domain Understanding  

---

## 📌 Dataset Overview  

This dataset contains detailed information about **car insurance policyholders, their vehicles, and their claim history**.  

Each record represents an individual customer and includes demographic details such as **birthdate, gender, marital status, education level, household income, and parental status**. These attributes provide a strong foundation for understanding customer profiles and how personal characteristics influence **driving behavior and insurance risk**.  

The dataset also captures detailed **vehicle-related information**, including car make, model, color, year of manufacture, and usage type (personal, commercial, or commuting). When combined with the **coverage zone**, this helps assess environmental and vehicle-based risk factors.  

For example, an older car used for commercial purposes in an urban area may carry a higher risk compared to a new personal car in a rural area.  

From a financial perspective, the dataset includes **claim amount, claim frequency, and household income**, which are critical for evaluating customer value and insurance risk.  

- High claim frequency → Indicates risky behavior  
- High claim amount → Indicates severe accidents or high repair costs  

The **Kids Driving** feature adds another important dimension, as households with multiple young drivers are generally considered higher risk.  

Overall, this dataset provides a **comprehensive 360-degree view** of customers, vehicles, and claims. It can be used for:  

- 📊 Claims Analysis  
- 🎯 Customer Segmentation  
- ⚠️ Risk Profiling  
- 💰 Premium Optimization  

---

## 🧩 Data Dictionary (Numbered)  

### 1️⃣ ID  
- **Definition:** Unique identifier for each policyholder  
- **Type:** Numeric / Text (Primary Key)  
- **Details:** Ensures each record is unique and avoids duplication  
- **Business Use:** Tracks customers across datasets (claims, payments, renewals)  

---

### 2️⃣ Birthdate  
- **Definition:** Date of birth of the policyholder  
- **Type:** Date  
- **Details:** Used to calculate age  
- **Business Use:**  
  - Age segmentation (<25, 25–40, 40–60, 60+)  
  - Risk-based pricing  

---

### 3️⃣ Car Color  
- **Definition:** Exterior color of the car  
- **Type:** Categorical  
- **Details:** May influence visibility and theft probability  
- **Business Use:** Pattern analysis and fraud detection  

---

### 4️⃣ Car Make  
- **Definition:** Vehicle manufacturer (Toyota, Ford, BMW, etc.)  
- **Type:** Categorical  
- **Details:** Different brands have different repair costs and risk levels  
- **Business Use:** Identify high-risk brands and claim trends  

---

### 5️⃣ Car Model  
- **Definition:** Specific model of the vehicle  
- **Type:** Categorical  
- **Details:** Risk varies across models  
- **Business Use:** Compare luxury vs economy vehicles  

---

### 6️⃣ Car Use  
- **Definition:** Purpose of vehicle (Personal / Commercial / Commute)  
- **Type:** Categorical  
- **Details:** Commercial use has higher exposure  
- **Business Use:** Premium differentiation and risk profiling  

---

### 7️⃣ Car Year  
- **Definition:** Manufacturing year of the car  
- **Type:** Numeric  
- **Details:** Used to calculate vehicle age  
- **Business Use:**  
  - Segment: New / Mid / Old  
  - Analyze risk by vehicle age  

---

### 8️⃣ Coverage Zone  
- **Definition:** Geographic risk area (Urban / Rural / Zone-based)  
- **Type:** Categorical  
- **Details:** Location affects accident and theft probability  
- **Business Use:** Regional risk analysis  

---

### 9️⃣ Education  
- **Definition:** Highest education level  
- **Type:** Categorical  
- **Details:** Linked with income and behavior  
- **Business Use:** Customer segmentation and targeting  

---

### 🔟 Gender  
- **Definition:** Gender of policyholder  
- **Type:** Categorical  
- **Details:** Behavioral differences may exist  
- **Business Use:** Demographic analysis  

---

### 1️⃣1️⃣ Marital Status  
- **Definition:** Marital status (Single, Married, etc.)  
- **Type:** Categorical  
- **Details:** Married individuals often lower risk  
- **Business Use:** Risk comparison and pricing  

---

### 1️⃣2️⃣ Parent  
- **Definition:** Whether policyholder has children  
- **Type:** Boolean  
- **Details:** Impacts driving behavior  
- **Business Use:** Household segmentation  

---

### 1️⃣3️⃣ Claim Amount (Claim Amt)  
- **Definition:** Total value of claims filed  
- **Type:** Numeric (Currency)  
- **Details:** Measures total insurance loss  
- **Business Use:** Loss analysis and fraud detection  

---

### 1️⃣4️⃣ Claim Frequency (Claim Freq)  
- **Definition:** Number of claims filed  
- **Type:** Integer  
- **Details:** Indicates risk behavior  
- **Business Use:** Key KPI for risk assessment  

---

### 1️⃣5️⃣ Household Income  
- **Definition:** Annual household income  
- **Type:** Numeric  
- **Details:** Affects affordability and vehicle type  
- **Business Use:** Income segmentation and premium targeting  

---

### 1️⃣6️⃣ Kids Driving  
- **Definition:** Number of kids who are licensed drivers  
- **Type:** Integer  
- **Details:** Higher number = higher risk  
- **Business Use:** Family risk profiling  

---

## 📈 Business Impact  

This dataset helps insurance companies to:  

- Design **fair pricing strategies**  
- Identify **high-risk customers**  
- Detect **fraudulent claims**  
- Improve **customer targeting and marketing**  

---

!Screenshot 2026-04-07 135543.png
