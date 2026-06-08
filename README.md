# RideFast Business Intelligence Analysis

Business Intelligence analysis of RideFast ride-sharing operations using Python, Pandas, and Tableau to identify operational challenges, customer retention issues, ride fulfillment bottlenecks, and strategic growth opportunities.

---

## Project Overview

RideFast is a ride-sharing platform facing several operational and business challenges affecting customer satisfaction, ride fulfillment, and long-term growth. This project analyzes ride, user, driver, and support ticket data to uncover key business problems and provide data-driven recommendations.

The analysis combines Exploratory Data Analysis (EDA) in Python with an interactive Tableau dashboard to identify trends, operational inefficiencies, customer behavior patterns, and regional performance gaps.

---

## Dashboard Preview

### Interactive Tableau Dashboard

View the live dashboard:

https://public.tableau.com/app/profile/md.adnan.parvez/viz/Book1_17798090269510/Dashboard3

### Dashboard Screenshot

![RideFast Dashboard](https://raw.githubusercontent.com/mdadnanparvez/ridefast-business-intelligence-analysis/main/Dashboard.png)

---

## Business Objectives

The primary objectives of this project are:

* Analyze ride fulfillment performance
* Identify causes of ride failures and cancellations
* Evaluate promotional campaign effectiveness
* Investigate customer churn behavior
* Assess city-level operational performance
* Generate actionable business recommendations
* Build an interactive dashboard for stakeholder decision-making

---

## Dataset Overview

The project uses four datasets:

### Rides Dataset

Contains ride request information including:

* Ride status
* Fare amount
* Pickup and drop-off times
* Ride ratings
* Surge multipliers
* Vehicle type

### Users Dataset

Contains customer information including:

* User activity
* Wallet balance
* Promotional usage
* Churn indicators

### Drivers Dataset

Contains driver-related information including:

* Driver status
* Acceptance rate
* Cancellation rate
* Ratings
* Monthly online hours

### Support Tickets Dataset

Contains customer support interactions including:

* Ticket category
* Resolution information
* Ride-related complaints

---

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Tableau Public

---

## Key Business Problems Identified

### 1. High Ride Failure Rate

RideFast experiences a significant ride fulfillment problem.

**Key Findings**

* Total Requests: 120,000
* Completed Rides: 97,638
* Completion Rate: 81.37%
* Failed Ride Rate: 18.63%

Nearly one in every five ride requests fails, reducing customer trust and platform reliability.

---

### 2. Driver Cancellation Problem

Driver-side cancellations are a major contributor to failed rides.

**Key Findings**

* Driver Cancellation Rate: 9.26%
* Northgate Driver Cancellation Rate: 12.95%

Driver cancellations account for a significant portion of all ride failures and negatively affect customer experience.

---

### 3. Promotion Inefficiency

Promotional spending is not generating meaningful operational improvements.

| Category        | Requests | Completed Rides | Completion Rate | Average Fare |
| --------------- | -------- | --------------- | --------------- | ------------ |
| Promo Rides     | 18,768   | 15,276          | 81.39%          | $23.30       |
| Non-Promo Rides | 101,232  | 82,362          | 81.36%          | $31.08       |

The completion rates are almost identical despite additional promotional costs.

---

### 4. High User Churn

Customer retention is a major business concern.

**Key Findings**

* Total Users: 35,000
* Churned Users: 27,867
* Churn Rate: 79.62%

A large percentage of users stop using the platform despite maintaining relatively high ride activity.

---

### 5. Northgate Underperformance

Northgate is the weakest-performing city in the network.

**Key Findings**

* Completion Rate: 76.14%
* Driver Cancellation Rate: 12.95%
* Average Rating: 3.97

Northgate consistently underperforms compared to other operational regions.

---

## Tableau Dashboard Features

### KPI Overview

* Total Requests
* Completed Rides
* Completion Rate
* Total Revenue
* Average Fare
* Cancellation Rate

### Demand Analysis

* Monthly Ride Trends
* Hourly Ride Demand Analysis

### Operational Performance

* City Performance Comparison
* Ride Status Distribution

### Customer Support Insights

* Support Ticket Analysis
* Complaint Category Distribution

---

## Recommendations

### Ride Fulfillment Improvement

* Improve ride-driver matching algorithms
* Optimize dispatch efficiency
* Reduce customer wait times
* Enhance ETA accuracy

### Driver Performance Management

* Introduce performance scorecards
* Implement reliability-based incentives
* Reduce excessive pickup distances
* Apply cancellation penalties

### Customer Retention Strategy

* Build churn prediction models
* Launch retention-focused campaigns
* Introduce loyalty and rewards programs
* Improve customer engagement

### Promotional Optimization

* Replace blanket discounting with targeted promotions
* Conduct customer segmentation
* Implement A/B testing
* Continuously monitor campaign ROI

### Regional Performance Improvement

* Increase driver availability in Northgate
* Improve dispatch systems
* Monitor city-level KPIs regularly
* Address operational bottlenecks

---

## Project Structure

```text
ridefast-business-intelligence-analysis/
│
├── data/
│   ├── rides.csv
│   ├── users.csv
│   ├── drivers.csv
│   └── support_tickets.csv
│
├── notebooks/
│   └── RideFast_EDA.ipynb
│
├── dashboard/
│   └── RideFast_Dashboard.twbx
│
├── reports/
│   └── RideFast_BI_Case_Study.pdf
│
├── Dashboard.png
│
└── README.md
```

---

## Results

The analysis revealed several critical operational and business challenges:

* High ride failure rates affecting customer satisfaction
* Significant driver cancellation issues
* Inefficient promotional spending
* Severe customer churn
* Regional underperformance in Northgate

Addressing these issues can improve platform reliability, customer retention, operational efficiency, and overall business growth.

---

## Tableau Dashboard

Interactive Dashboard:

https://public.tableau.com/app/profile/md.adnan.parvez/viz/Book1_17798090269510/Dashboard3

The Tableau dashboard enables stakeholders to explore operational metrics, customer behavior, ride fulfillment trends, and regional performance through interactive visualizations.

---

## Repository

GitHub Repository:

https://github.com/mdadnanparvez/ridefast-business-intelligence-analysis

---

## Author

Adnan Parvez

Business Intelligence Analysis Project

Python | Pandas | Tableau | Data Visualization | Business Analytics
