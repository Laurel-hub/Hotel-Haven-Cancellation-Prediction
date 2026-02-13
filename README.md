# 🏨 Hotel Haven Booking Cancellation Prediction  
### A Data-Driven Approach to Proactive Revenue & Capacity Planning

**Author:** Oghenevurie Lauretta  
**Tools:** Python, Google Colab, Pandas, NumPy, Scikit-learn, Matplotlib  
**Project Type:** Applied Machine Learning | Predictive Analytics

---

## Project Overview

Hotel booking cancellations present a significant operational and financial challenge in the hospitality industry. High cancellation rates lead to lost revenue, inefficient capacity planning, and suboptimal resource allocation.

This project develops a **predictive machine learning solution** to identify bookings at risk of cancellation at **Hotel Haven**, using historical booking data. The objective is to support **proactive intervention**, improve planning accuracy, and enable data-driven decision-making.

---

## Project Objectives

- Analyse booking and customer characteristics associated with cancellation behaviour  
- Build predictive models to classify whether a booking will be cancelled  
- Compare multiple machine learning models to identify the most effective approach  
- Translate analytical findings into actionable business recommendations  

---

## Dataset Overview

The dataset consists of historical hotel booking records containing features such as:

- Lead time  
- Average daily price  
- Booking timing and seasonality  
- Market segment  
- Length of stay  
- Special requests  
- Customer engagement indicators  

The target variable is **booking status** (Cancelled vs Not Cancelled).

---

## Data Preparation

- Verified data quality and corrected inconsistencies  
- Handled missing values and ensured appropriate data types  
- Prepared the dataset for modelling and analysis  

---

## Feature Engineering & Preprocessing

- Separated input features from the target variable  
- Encoded categorical variables appropriately  
- Scaled numerical features where required  
- Split the dataset into training and testing sets (80/20) to ensure reliable evaluation  

---

## Predictive Modelling Approach

Multiple machine learning models were trained and evaluated to assess performance and robustness. Model comparison focused on achieving a balance between:

- Accurate identification of cancellations  
- Minimising false positives  
- Practical usability in a real operational environment  

Ensemble-based approaches demonstrated strong predictive performance.

---

## Key Insights

- **Lead time** is the strongest predictor of cancellation, with longer lead times showing significantly higher risk  
- **Higher booking prices** are associated with increased cancellation likelihood  
- **Seasonality and booking timing** influence cancellation patterns  
- **Lower engagement signals**, such as fewer special requests, correlate with higher cancellation probability  

---

## Model Performance Summary

- Successfully identified a large proportion of cancelled bookings, enabling early intervention  
- Retained most non-cancelled bookings, reducing unnecessary operational actions  
- Demonstrated that booking cancellations can be predicted reliably using historical data  

---

## Business Recommendations

Insights from this model can be used to:

- Flag high-risk bookings early for targeted retention strategies  
- Adjust pricing and deposit policies for long lead-time bookings  
- Improve staffing and capacity planning  
- Reduce revenue loss from last-minute cancellations  

---

## Limitations

- Predictions are based solely on historical booking patterns  
- External factors such as economic conditions or travel disruptions are not explicitly captured  
- More complex models introduce interpretability trade-offs  

---

## Future Work

- Integrate real-time booking behaviour and customer interaction data  
- Apply model explainability techniques such as SHAP values  
- Deploy the model as part of a live decision-support system  
- Extend the approach to demand forecasting and revenue optimisation  

---

## 📁 Repository Structure

