# Uber Ride Booking Data Analysis

## 📌 Project Overview

This project performs an end-to-end analysis of Uber ride booking data using Python. The analysis focuses on booking performance, cancellations, vehicle types, ride distance, booking value, customer and driver ratings, payment methods, and time-based booking patterns.

The objective is to transform raw ride-booking data into meaningful business insights that can help understand operational performance and identify areas for improvement.

---

## 🎯 Business Objectives

* Analyze overall booking performance
* Measure completion and cancellation rates
* Understand booking-value and ride-distance patterns
* Compare performance across vehicle types
* Analyze customer and driver ratings
* Identify time-based booking patterns
* Evaluate payment-method and booking-status relationships
* Generate actionable business recommendations

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📊 Dataset

The dataset contains **150,000 ride-booking records** with information related to:

* Booking status
* Vehicle type
* Customer and booking details
* Pickup and drop locations
* Booking value
* Ride distance
* Customer ratings
* Driver ratings
* Payment method
* Cancellation information
* Date and time information

---

## 🔍 Analysis Performed

### 1. Data Understanding

* Dataset shape and structure
* Data types
* Missing-value analysis
* Duplicate analysis
* Unique-value analysis
* Statistical summary

### 2. Data Cleaning

* Missing-value handling
* Duplicate checks
* Data type conversion
* Data consistency checks
* Numerical data validation

### 3. Feature Engineering

Created additional analytical features:

* Hour
* Day of Week
* Day Number
* Month
* Month Number
* Year
* Time Period
* Cancellation Category

### 4. Exploratory Data Analysis

#### Univariate Analysis

* Booking Status
* Vehicle Type
* Payment Method
* Time Period
* Day of Week
* Numerical variable distributions

#### Bivariate Analysis

* Vehicle Type vs Booking Value
* Booking Status vs Ride Distance
* Payment Method vs Booking Value
* Time Period vs Booking Status
* Vehicle Type vs Booking Status
* Ride Distance vs Booking Value
* Driver Rating vs Booking Value
* Customer Rating vs Booking Value
* Hour vs Booking Status
* Day of Week vs Booking Value
* Ride Distance vs Vehicle Type
* Vehicle Type vs Ratings
* Payment Method vs Booking Status

#### Multivariate Analysis

* Correlation Matrix
* Pairplot
* Vehicle Type × Booking Status × Booking Value
* Time Period × Vehicle Type × Booking Status
* Day of Week × Booking Status × Booking Value

---

## 📈 Key KPIs

| KPI                     |       Value |
| ----------------------- | ----------: |
| Total Bookings          |     150,000 |
| Completed Bookings      |      93,000 |
| Completion Rate         |      62.00% |
| Cancelled Bookings      |      37,500 |
| Cancellation Rate       |      25.00% |
| Total Booking Value     | ₹51,846,183 |
| Average Booking Value   |     ₹508.30 |
| Average Ride Distance   |       24.64 |
| Average Driver Rating   |        4.23 |
| Average Customer Rating |        4.40 |

### Booking Status Distribution

* **Completed:** 62%
* **Cancelled by Driver:** 18%
* **No Driver Found:** 7%
* **Cancelled by Customer:** 7%
* **Incomplete:** 6%

Overall, **38% of bookings were not completed**, while 25% were specifically recorded as cancellations.

---

## 🚗 Vehicle Type Performance

| Vehicle Type  | Bookings | Completion Rate | Cancellation Rate |
| ------------- | -------: | --------------: | ----------------: |
| Auto          |   37,419 |          61.88% |            24.92% |
| Go Mini       |   29,806 |          62.23% |            24.92% |
| Go Sedan      |   27,141 |          61.44% |            25.29% |
| Bike          |   22,517 |          62.33% |            25.10% |
| Premier Sedan |   18,111 |          62.13% |            24.94% |
| eBike         |   10,557 |          62.05% |            24.91% |
| Uber XL       |    4,449 |          62.55% |            24.48% |

---

## 💡 Key Business Insights

### 1. High Overall Non-Completion

The dataset shows a **62% completion rate**, meaning a significant **38% of bookings were not completed**.

This indicates that improving booking fulfilment could be an important operational opportunity.

### 2. Auto Has the Highest Booking Volume

**Auto** recorded the highest number of bookings with **37,419 bookings**, making it the largest vehicle segment in the dataset.

### 3. Uber XL Shows the Highest Completion Rate

**Uber XL** has the highest completion rate at **62.55%** among the analyzed vehicle types.

### 4. Go Sedan Has the Highest Cancellation Rate

**Go Sedan** has the highest cancellation rate at **25.29%**.

This segment may require additional investigation into the reasons behind cancellations.

### 5. Vehicle Type Is Not the Main Driver of Booking Success

Completion rates across vehicle types range only from approximately **61.44% to 62.55%**.

Therefore, vehicle type alone does not appear to be the primary driver of booking success. Other operational factors such as driver availability, location, demand, and cancellation reasons may have a stronger influence.

### 6. Strong Average Customer and Driver Ratings

The overall average driver rating is **4.23**, while the average customer rating is **4.40**, indicating generally positive ratings among completed rides.

---

## 🚀 Business Recommendations

### 1. Improve Booking Fulfilment

Investigate the causes behind the **38% non-completed bookings** and focus on reducing failed booking outcomes.

### 2. Investigate Cancellation Drivers

Analyze customer and driver cancellation reasons separately to identify the major operational causes of cancellations.

### 3. Monitor Go Sedan Performance

Since Go Sedan has the highest cancellation rate, its cancellation patterns should be investigated further.

### 4. Maintain High-Performing Vehicle Segments

Uber XL currently shows the strongest completion performance and can be monitored to understand which operational factors contribute to its relatively better performance.

### 5. Focus Beyond Vehicle Type

Since vehicle-level completion rates are relatively similar, operational decisions should also consider:

* Driver availability
* Pickup and drop locations
* Time of booking
* Demand patterns
* Cancellation reasons
* Booking fulfilment

---

## 📁 Project Structure

```text
Uber-Ride-Booking-Data-Analysis/
│
├── Uber_Ride_Booking_Analysis.ipynb
├── README.md
├── requirements.txt
│
└── visuals/
    ├── booking_status.png
    ├── vehicle_type.png
    ├── payment_method.png
    ├── ...
    └── pairplot.png
```

---

## 📊 Visualizations

The project contains **34 visualizations** covering:

* Booking status distribution
* Vehicle type analysis
* Payment method analysis
* Time-period analysis
* Day-of-week analysis
* Booking value distributions
* Ride distance analysis
* Rating analysis
* Cancellation analysis
* Correlation analysis
* Multivariate relationships
* KPI-based business analysis

All generated visualizations are available in the `visuals` directory.

---

## 📌 Project Outcome

This project demonstrates an end-to-end **Exploratory Data Analysis workflow** using Python, starting from raw ride-booking data and progressing through:

**Data Understanding → Data Cleaning → Feature Engineering → EDA → KPI Analysis → Business Insights → Business Recommendations**

The analysis highlights booking performance, operational patterns, vehicle-level performance, customer/driver experience, and potential areas for business improvement.

---

## 👨‍💻 Author

**Abhishek Mishra**

B.Tech Computer Science Engineering

### Skills Demonstrated

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `EDA` `Data Cleaning` `Feature Engineering` `Business Analysis`
