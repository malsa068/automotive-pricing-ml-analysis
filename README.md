# 🚗 Automotive Pricing Analysis with Machine Learning

A comprehensive machine learning project that predicts vehicle retail prices using multiple linear regression. This analysis examines 389 vehicles to identify the key factors that drive pricing decisions in the automotive market.

## 📊 Project Overview

This project demonstrates end-to-end machine learning workflow including:
- Exploratory data analysis and statistical insights
- Multiple linear regression modeling
- Feature engineering with polynomial terms and interactions
- Business-focused strategic recommendations

**Key Achievement:** 74% R² score explaining vehicle price variation

## 🎯 Key Findings

- **Horsepower** is the strongest pricing driver ($218 per HP)
- **Sports car classification** adds a $21,000 premium
- **Engine size** shows non-linear effects on pricing
- Performance features deliver 3x higher ROI than fuel efficiency

📊 Model Performance
MetricInitial ModelImproved ModelR² Score0.7250.739Adjusted R²0.7190.735Features96

**Key Variables**

Dependent Variable:

Retail Price ($)

Independent Variables:

Engine displacement (L)
Horsepower (HP)
City MPG
Vehicle class (Sedan, SUV, Sports, etc.)
Derived features (Engine², HP×Sports interaction)

💡 Business Recommendations

Focus on horsepower optimization - delivers the highest pricing leverage
Target 250-350 HP range - optimal value without diminishing returns
Premium positioning for the sports segment - $21K+ price advantage
Data enrichment opportunities - add luxury features & regional data for 8-13% improvement

📝 Dataset
The analysis uses automotive sales data with the following features:

Retail: Vehicle retail price
Dealer: Dealer cost
Engine: Engine displacement in liters
Cylinders: Number of cylinders
Horsepower: Engine horsepower
CityMPG: City fuel efficiency
HighwayMPG: Highway fuel efficiency
Class: Vehicle category (Sedan, SUV, Sports, Wagon, Minivan)
