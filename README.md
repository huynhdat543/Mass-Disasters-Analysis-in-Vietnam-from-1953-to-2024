# 🌪️ Mass Disasters Analysis in Vietnam from 1953 to 2024
## 📝 Introduction
This project focuses on exploratory data analysis (EDA) on the "Mass Disasters in Vietnam 1953-2024" dataset to identify morphological characteristics and assess the socio-economic damage of disasters in Vietnam. The research team used Python in combination with a visual dashboard on Power BI to extract patterns of natural disaster changes over more than 70 years.

**Executing member**
- Huỳnh Phát Đạt - ISE-UIT
- Bùi Quốc Bảo - ISE-UIT
- Lê Minh Khôi - ISE-UIT

## 📖 Data
[Mass Disaster in Vietnam 1953 - 2024](https://data.vietnam.opendevelopmentmekong.net/dataset/natural-disaster-in-vietnam)
- Source: Extracted from the International Disaster Database (EM-DAT), published by Open Development Vietnam.
- Scale: Initially comprising 335 rows and 46 columns, after processing and streamlining, it was reduced to 21 columns for analysis (7 categorical variables, 14 numerical variables).
- Key characteristics: Disaster group/type, location, contextual factors, number of fatalities, number of affected people, and total economic damage (adjusted for inflation).

## 🛠️ Analysis Process
The implementation team followed a systematic process including the following steps:

**1. Data Cleaning**: Removing columns with 100% missing values, features containing only a single value, or redundant categorical variables.

**2. Feature Engineering**:
- Combining separate Date-Month-Year columns into a datetime format.
- Filling the missing value of 0 for quantitative columns on damage (people and property).
- Using LLM (Gemini) to create a new feature, economic_region, based on geographic location.

**3. Data Exploration (EDA)**: Using trend charts, distributions, and statistical tests to extract hidden information.

## 📊 Results and Valuable Insights

**Link to DashBoard:** [Click Here](https://app.powerbi.com/groups/me/reports/2ae71530-b0aa-471f-8768-ccbd4bb9d7f4/2f0288ae1174d26ec60b?experience=power-bi)

**1. Characteristics of Disaster Morphology**
- Trend: The number of disasters shows a clear long-term upward trend. During the period 1953-1989, the frequency was low (1-3 incidents/year), but after 1990 it exploded to 7-13 incidents/year (peaking at 16 incidents in 2005).
- Seasonality: Disasters are highly concentrated in the latter half of the year (July to November). Storms and floods are the two dominant types of disasters.
- Targeted Areas: The North Central and Central Coastal regions are most severely affected, with over 175 incidents, double the number in the second-ranked region, the Northern Midlands and Mountains.
- Intensity: Floods and storms have a destructive intensity far exceeding that of technical accidents or scattered fires.

**2. Socio-Economic Damage**
- Damage Shift: There has been a clear shift from human losses to economic losses over the decades.
- Peak Decade: Total damage peaked in the 1990s. While mortality rates dominated in the 1960s, economic damage surged and peaked in the 2010s due to urbanization.
- Most Destructive Types: Storms topped all three indicators (deaths, affected people, economic damage). Droughts caused very high economic damage despite low direct casualties.

## 🚀 Conclusion
This project demonstrates the practicality of combining Python and Power BI in disaster risk management. The results of the analysis on seasonality and damage shifts provide an important scientific basis for optimizing the allocation of response resources and infrastructure reinforcement in Vietnam, especially in the central and northern mountainous regions.
