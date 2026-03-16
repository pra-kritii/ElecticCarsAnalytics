# 🚗 Electric Vehicle Analytics Using Tableau

##  FInd the link below

---

# Problem Statement

With the rapid growth of electric vehicles, it is important to analyze EV data to understand:

- Vehicle efficiency and performance
- Charging infrastructure availability
- Cost comparison of EV models
- Driving range and battery performance

Raw EV datasets are complex and difficult to interpret directly. Therefore, **data analytics and visualization tools** are required to transform raw data into meaningful insights.

The goal of this project is to analyze EV datasets and build **interactive dashboards and stories** that help users explore EV data and make informed decisions.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Collect and analyze electric vehicle datasets
- Clean and prepare EV data for analysis
- Create visualizations representing EV performance metrics
- Build an interactive Tableau dashboard
- Create a Tableau story explaining insights step-by-step
- Integrate Tableau visualizations into a website

---

# 📊 Data Collection & Extraction

The project uses **four EV datasets in CSV format.**

---

## 1️⃣ EVIndia Dataset

Contains information about electric vehicles available in India.

**Columns**

- Car – Car brand and model  
- Style Range – Vehicle style range  
- Transmission – Transmission type  
- VehicleType – Type of vehicle  
- PriceRange (Lakhs) – Price range  
- Capacity – Battery capacity  
- BootSpace – Boot space  
- BaseModel – Base model name  
- TopModel – Top model name  

---

## 2️⃣ Electric Vehicle Charging Station List

Provides information about EV charging stations.

**Columns**

- Region – Charging station region  
- Address – Station address  
- Aux Address – Additional address details  
- Latitude – Geographic coordinate  
- Longitude – Geographic coordinate  
- Type – Charging station type  
- Power – Charging power  
- Service – Service type  

---

## 3️⃣ ElectricCarData_Clean Dataset

Contains detailed EV specifications.

**Columns**

- Brand  
- Model  
- AccelSec – Acceleration time  
- TopSpeed_KmH – Maximum speed  
- Range_Km – Driving range  
- Efficiency_WhKm – Energy efficiency  
- FastCharge_KmH – Fast charging speed  
- RapidCharge – Rapid charging availability  
- PowerTrain – Powertrain type  
- PlugType – Charging plug type  
- BodyStyle – Vehicle body style  
- Segment – Vehicle segment  
- Seats – Seating capacity  
- PriceEuro – Vehicle price  

---

## 4️⃣ Cheapestelectriccars-EVDatabase Dataset

Contains information about affordable EV models.

**Columns**

- Name  
- Subtitle  
- Acceleration  
- TopSpeed  
- Range  
- Efficiency  
- FastChargeSpeed  
- Drive  
- NumberofSeats  
- PriceinGermany  
- PriceinUK  

---

# 🧹 Data Preparation

Before analysis, the datasets were cleaned and prepared.

## Data Cleaning

- Removed duplicate records  
- Handled missing values  
- Standardized column names  
- Converted numerical values into correct formats  
- Removed unnecessary columns  

## Data Transformation

- Standardized vehicle categories  
- Converted price columns to comparable units  
- Organized data for visualization  

After preprocessing, the datasets were ready for **Tableau analysis**.

---

# 📈 Data Visualization

Data visualization helps convert complex datasets into understandable insights.

In this project, **Tableau Public** was used to create visualizations including:

- Bar charts comparing EV models
- Scatter plots showing efficiency vs range
- Price comparison charts
- Performance comparison graphs
- Maps showing EV charging station locations

These visualizations help identify **trends, patterns, and comparisons between EV models.**

---

# 📊 Tableau Dashboard

An interactive Tableau dashboard was created to present EV insights.

### 🔗 Dashboard Link

https://public.tableau.com/app/profile/prakriti.kesharwani/viz/EVanalyticsDashboard/Electriccarsanalytics

### Dashboard Insights

- Electric vehicle model comparison  
- Range and efficiency analysis  
- Price comparison across EV brands  
- Acceleration and performance metrics  
- EV segment analysis  

Users can interact with filters such as:

- Brand  
- Vehicle segment  
- Price range  
- Vehicle type  

This enables **dynamic exploration of EV data.**

---

# 📖 Tableau Story

The Tableau Story presents a step-by-step analysis of electric vehicle data and charging infrastructure in India.

### 🔗 Story Link
https://public.tableau.com/app/profile/prakriti.kesharwani/viz/EVanalytics/StoryofelectriccarsinIndia

## Story Title
**Story of Electric Cars in India**

The story explains different aspects of EV adoption and infrastructure through multiple visualizations.

---

## 1️⃣ Charging Stations in India

This section shows the distribution of electric vehicle charging stations across India.  
It highlights how charging infrastructure is expanding to support the growing number of EV users.

Insights include:

- Total charging stations available
- Distribution across different regions
- Growth of EV infrastructure

---

## 2️⃣ Charging Stations by Region and Type

This visualization analyzes charging stations based on:

- Geographic region
- Charging station type
- Charging power

It helps identify which regions have better charging infrastructure and the types of charging facilities available.

---

## 3️⃣ Price by Brand

This section compares electric vehicle prices across different brands.

Insights include:

- Price differences between EV manufacturers
- Brand positioning in the EV market
- Identification of affordable and premium EV brands

---

## 4️⃣ Different Brand and Model Numbers

This visualization compares various EV brands and their available models.

Insights include:

- Number of EV models offered by each brand
- Brand diversity in the EV market
- Popular manufacturers contributing to EV adoption

---

The story helps users understand **EV infrastructure, pricing trends, and brand distribution in India** through interactive visual analysis.

---

# ⚙️ Performance Testing

Performance testing ensured that the dashboard works smoothly.

### Tests Performed

- Verified dataset loading  
- Tested dashboard filters and interactions  
- Ensured Tableau visualizations load properly  
- Checked responsiveness in the web interface  

The dashboards performed efficiently with smooth interaction.

---

# 🌐 Web Integration

The Tableau visualizations were integrated into a website using **HTML, CSS, and Bootstrap**.

### Website Pages

- Home Page  
- Dashboard Page  
- Story Page  
- Contact Page  

The Tableau dashboards were embedded using **Tableau embed code**, allowing users to interact directly with the visualizations.

---

# 🎥 Project Demonstration

Project workflow:

1. Data collection from EV datasets  
2. Data cleaning and preparation  
3. Data visualization using Tableau  
4. Dashboard development  
5. Story-based analysis  
6. Web integration  

The project enables users to explore **EV performance, efficiency, and charging infrastructure insights.**

---

# 🏁 Conclusion

Electric vehicles are becoming a key part of **sustainable transportation**. Data analytics helps understand EV performance, infrastructure needs, and consumer behavior.

This project demonstrates how **Tableau dashboards and stories can transform EV datasets into meaningful insights.** Interactive visualizations make it easier for users to analyze data and make informed decisions.

---

# 🔮 Future Scope

Possible future improvements include:

- Integrating real-time EV charging data  
- Adding battery health datasets  
- Developing machine learning models for EV range prediction  
- Creating advanced predictive dashboards  

These improvements can further enhance **EV analytics and decision-making.**
