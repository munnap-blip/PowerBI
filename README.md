📌 Project Description

This project is based on an Insurance Risk & Claims Analysis dataset, which contains detailed information about car insurance policyholders, their vehicles, and their claim history.

Each record represents an individual customer and includes demographic attributes such as birthdate, gender, marital status, education level, household income, and parental status. These features provide a strong foundation for understanding customer profiles and how personal characteristics influence driving behavior and insurance risk.

In addition, the dataset captures detailed vehicle-related information, including car make, model, color, manufacturing year, and usage type (personal, commercial, or commuting). When combined with the coverage zone, these attributes help assess environmental and vehicle-based risk factors. For example, an older commercial vehicle operating in an urban area typically carries a higher risk compared to a new personal vehicle in a rural location.

From a financial perspective, the dataset includes claim amount, claim frequency, and household income, which are critical for evaluating both customer value and insurance risk. High claim frequency may indicate risky driving behavior, while high claim amounts may reflect severe accidents or costly repairs.

Another important feature is Kids Driving, which represents the number of young drivers in a household. Households with multiple young drivers are generally considered higher risk due to increased exposure.

Overall, this dataset provides a comprehensive 360-degree view of customers, vehicles, and claims. It is highly suitable for building Power BI dashboards and performing:

Claims analysis
Customer segmentation
Risk profiling
Premium optimization

The insights derived from this project can help insurance companies:

Design fair pricing strategies
Identify high-risk customers
Detect potential fraud
Improve targeted marketing
🧩 Data Dictionary & Business Understanding
🆔 ID
Definition: Unique identifier for each policyholder
Type: Numeric / Text (Primary Key)
Use: Ensures data integrity and links records across datasets
🎂 Birthdate
Definition: Customer’s date of birth
Type: Date
Use:
Calculate age
Segment customers (<25, 25–40, 40–60, 60+)
Risk-based pricing
🎨 Car Color
Definition: Exterior color of the vehicle
Type: Categorical
Use:
Pattern analysis
Fraud detection insights
🏭 Car Make
Definition: Vehicle manufacturer (Toyota, Ford, BMW, etc.)
Type: Categorical
Use:
Compare claim trends by brand
Identify high-risk manufacturers
🚙 Car Model
Definition: Specific vehicle model
Type: Categorical
Use:
Compare luxury vs economy vehicles
Perform detailed risk analysis
🔄 Car Use
Definition: Purpose of vehicle (Personal / Commercial / Commute)
Type: Categorical
Use:
Commercial vehicles → higher risk
Supports premium differentiation
📅 Car Year
Definition: Manufacturing year of the car
Type: Numeric
Use:
Calculate vehicle age
Segment into New / Mid / Old categories
🌍 Coverage Zone
Definition: Geographic risk area (Urban / Rural / Zone-based)
Type: Categorical
Use:
Analyze regional risk
Urban → higher frequency
Rural → lower frequency but higher severity
🎓 Education
Definition: Highest education level
Type: Categorical
Use:
Customer segmentation
Marketing strategy insights
🚻 Gender
Definition: Gender of policyholder
Type: Categorical
Use:
Behavioral analysis
Demographic insights
💍 Marital Status
Definition: Customer marital status
Type: Categorical
Use:
Compare risk between single vs married
Support pricing decisions
👨‍👩‍👧 Parent
Definition: Whether customer has children
Type: Boolean
Use:
Household-based segmentation
Combined analysis with Kids Driving
💸 Claim Amount (Claim Amt)
Definition: Total value of claims filed
Type: Numeric (Currency)
Use:
Loss calculation
Identify high-cost claims
Fraud detection
🔁 Claim Frequency (Claim Freq)
Definition: Number of claims filed
Type: Integer
Use:
Risk behavior indicator
KPI for insurance analysis
🏠 Household Income
Definition: Annual household income
Type: Numeric
Use:
Income segmentation
Premium targeting strategies
👶 Kids Driving
Definition: Number of licensed young drivers in household
Type: Integer
Use:
Higher value → higher risk
Family risk profiling
📊 Business Impact

This project enables:

📊 Data-driven decision making
⚠️ Accurate risk profiling
💰 Optimized premium pricing
🔍 Fraud detection
🎯 Targeted customer segmentation
🛠️ Tools Used
Power BI
Excel / CSV Dataset
Python (Optional for preprocessing)
