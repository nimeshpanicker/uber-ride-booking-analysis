# 🚗 Uber Ride-Booking Performance Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-green)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-Portfolio-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

> An interactive Power BI and Excel analytics project analysing ride-booking
> performance, completed and lost bookings, revenue, vehicle types,
> cancellations, locations, ratings, payment methods, and operational trends.

# 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Booking Requests | **150,000** |
| Completed Bookings | **93,000** |
| Lost Bookings | **57,000** |
| Completion Rate | **62.0%** |
| Revenue | **₹51.85M** |
| Total Distance | **2.51M km** |
| Average Distance | **24.64 km** |
| Customer Rating | **4.40 / 5** |
| Driver Rating | **4.23 / 5** |

> **Revenue definition:** The reported Revenue KPI includes Booking Value
> from both Completed and Incomplete trips, covering 102,000 records. It is
> therefore not strictly revenue from successfully completed rides only.

---

# 📈 Key Findings

## 🚕 Booking Performance Analysis

| Booking Outcome | Bookings | % of Total |
|---|---:|---:|
| Completed | **93,000** | **62.0%** |
| Lost / Unfulfilled | **57,000** | **38.0%** |
| Total | **150,000** | **100%** |

The dataset contains **150,000 booking requests**, of which **93,000 were
completed** and **57,000 were lost or not completed**.

The completion rate was **62.0%**, leaving **38.0% of total booking demand**
unfulfilled.

---

## 📅 Monthly Booking & Revenue Analysis

| Month | Completed Bookings | Revenue |
|---|---:|---:|
| January | **8,189** | **₹45.26L** |
| February | **7,130** | **₹39.71L** |
| March | **7,954** | **₹45.68L** |
| April | **7,632** | **₹42.54L** |
| May | **7,905** | **₹43.21L** |
| June | **7,757** | **₹43.26L** |
| July | **7,926** | **₹43.66L** |
| August | **7,780** | **₹42.44L** |
| September | **7,542** | **₹41.91L** |
| October | **7,905** | **₹44.17L** |
| November | **7,659** | **₹43.43L** |
| December | **7,621** | **₹43.20L** |

Monthly completed bookings remain within a relatively narrow range of
approximately **7,130 to 8,190 bookings**.

**January** recorded the highest completed-booking volume with **8,189**,
while **February** recorded the lowest with **7,130**.

Revenue followed a similar pattern, reaching its highest monthly value in
**March at ₹45.68 lakh** and its lowest in **February at ₹39.71 lakh**.

Because February has fewer calendar days, its lower total should not
automatically be interpreted as weaker daily demand.

---

## 🚘 Vehicle Type Performance Analysis

| Vehicle Type | Bookings | Revenue | Share of Revenue |
|---|---:|---:|---:|
| Auto | **37,419** | **₹1,28,78,422** | **24.84%** |
| Go Mini | **29,806** | **₹1,03,38,496** | **19.94%** |
| Go Sedan | **27,141** | **₹93,69,719** | **18.07%** |
| Bike | **22,517** | **₹78,37,697** | **15.12%** |
| Premier Sedan | **18,111** | **₹62,75,332** | **12.10%** |
| eBike | **10,557** | **₹36,18,485** | **6.98%** |
| Uber XL | **4,449** | **₹15,28,032** | **2.95%** |

**Auto** is the largest vehicle category by booking volume and revenue.

Auto, Go Mini, and Go Sedan together account for **62.85% of total revenue**.

Uber XL and eBike together contribute less than **10% of total revenue**.

The dashboard report notes that the lower contribution of these categories
cannot by itself distinguish between lower demand and limited vehicle
availability.

---

## ❌ Cancellation & Lost Booking Analysis

| Booking Outcome | Count | % of Total Requests |
|---|---:|---:|
| Cancelled by Driver | **27,000** | **18.0%** |
| Cancelled by Customer | **10,500** | **7.0%** |
| No Driver Found | **10,500** | **7.0%** |
| Incomplete | **9,000** | **6.0%** |

Driver cancellations represent the largest individual lost-booking
category at **27,000 bookings**, or **18.0% of all booking requests**.

The total of cancelled, no-driver-found, and incomplete bookings accounts
for **57,000 lost bookings**, representing **38.0% of total demand**.

---

## 🚨 Cancellation Reason Analysis

### Driver Cancellation Reasons

| Reason | Count |
|---|---:|
| Customer related issue | **6,837** |
| Customer was coughing/sick | **6,751** |
| Personal & car related issues | **6,726** |
| More than permitted people in the car | **6,686** |

### Customer Cancellation Reasons

| Reason | Count |
|---|---:|
| Wrong address | **2,362** |
| Change of plans | **2,353** |
| Driver not moving towards pickup location | **2,335** |
| Driver asked to cancel | **2,295** |
| AC is not working | **1,155** |

A notable data-quality observation is that **"Driver asked to cancel"**
appears under customer cancellation reasons.

The report identifies **2,295 such cases**, meaning some driver-attributable
cancellations may be classified under customer cancellations.

---

## 📍 Location Performance Analysis

The dataset contains **176 distinct pickup locations** and **176 distinct
drop locations**.

### Top Pickup Locations

| Pickup Location | Completed Bookings |
|---|---:|
| Khandsa | **600** |
| Barakhamba Road | **594** |
| Subhash Chowk | **582** |
| Madipur | **579** |
| Mehrauli | **574** |

### Top Drop Locations

| Drop Location | Completed Bookings |
|---|---:|
| Ashram | **592** |
| Preet Vihar | **589** |
| Sultanpur | **584** |
| Noida Extension | **579** |
| Narsinghpur / Dwarka Mor | **574** |

Demand is distributed across a broad network rather than being heavily
concentrated in a small number of locations.

---

## ⭐ Ratings & Service Quality

| Metric | Result |
|---|---:|
| Average Customer Rating | **4.40 / 5** |
| Average Driver Rating | **4.23 / 5** |

Ratings are available for **Completed bookings only**.

The average customer rating is higher than the average driver rating,
providing an opportunity for further analysis by vehicle type, cancellation
history, and other operational segments.

---

## 💳 Payment Method Analysis

| Payment Method | Transactions | Share |
|---|---:|---:|
| UPI | **45,909** | **45.01%** |
| Cash | **25,367** | **24.87%** |
| Uber Wallet | **12,276** | **12.04%** |
| Credit Card | **10,209** | **10.01%** |
| Debit Card | **8,239** | **8.08%** |

**UPI** is the most frequently recorded payment method, accounting for
**45.01%** of transactions.

---

# 💡 Business Insights

## 1. Significant Unfulfilled Demand

**57,000 of 150,000 booking requests**, or **38.0%**, were not completed.

Driver cancellations represent the largest individual loss category at
**18.0% of all requests**.

This makes cancellation and non-completion analysis an important area for
operational investigation.

---

## 2. Revenue Is Concentrated Across Three Vehicle Types

Auto, Go Mini, and Go Sedan together contribute **62.85% of total revenue**.

Auto alone contributes **24.84%**.

This makes these vehicle categories important segments for monitoring
booking demand and revenue performance.

---

## 3. Monthly Performance Is Relatively Stable

Completed bookings remain between approximately **7,130 and 8,190 per
month**.

The dataset does not show a strong growth or decline pattern across the
2025 period.

February has the lowest total, although its shorter calendar length should
be considered before interpreting the result as weaker daily demand.

---

## 4. UPI Is the Dominant Payment Method

UPI accounts for **45.01%** of recorded payment transactions, significantly
higher than Cash at **24.87%**.

This indicates that digital payment behaviour is an important component of
the observed booking activity.

---

## 5. Demand Is Broadly Distributed Across Locations

The platform operates across **176 pickup and 176 drop locations**.

No single location dominates the completed-booking network, suggesting a
broad geographic distribution of demand.

---

## 6. Customer Ratings Exceed Driver Ratings

The average customer rating is **4.40**, compared with an average driver
rating of **4.23**.

Further segmentation could help determine whether this difference is
associated with particular vehicle types, cancellation patterns, or other
operational factors.

---

## 7. Revenue Includes Incomplete Trips

The dashboard Revenue KPI includes Booking Value from both Completed and
Incomplete trips.

Incomplete trips account for **9,000 bookings** and contribute partial
Booking Value.

Therefore, the current Revenue KPI should be clearly labelled when used
for stakeholder reporting.

---

# 📋 Business Recommendations

## 🚕 Reduce Driver-Initiated Cancellations

Investigate the causes behind the **27,000 driver cancellations** and
identify operational factors contributing to the highest cancellation
categories.

---

## 🔎 Review Cancellation Classification

Audit the **"Driver asked to cancel"** reason currently recorded under
customer cancellations.

Improving classification can provide a more accurate view of
driver-attributable lost demand.

---

## 💳 Maintain UPI Payment Reliability

Given that UPI represents **45.01%** of recorded transactions, monitor
payment reliability and investigate potential friction in the digital
payment experience.

---

## 🚘 Investigate Vehicle Availability

Further investigate whether the lower revenue contribution from **eBike**
and **Uber XL** is driven by lower customer demand or limited vehicle
availability.

The current dataset does not contain sufficient fleet-availability data to
distinguish between these explanations.

---

## 📊 Improve Revenue KPI Definition

Add a separate **Revenue — Completed Only** KPI alongside the current
inclusive Revenue measure.

This would allow stakeholders to distinguish between total recorded
Booking Value and value generated from successfully completed rides.

---

## 🧹 Improve Data Quality

Address the following issues identified during the project:

- Add the missing **eBike** row to the vehicle-image lookup table.
- Correct duplicated booking-status icon mappings.
- Review the **non-unique Booking ID** issue before using Booking ID as a
  primary or join key.
- Review cancellation reason classification.

---

# 📊 Dashboard

The Power BI dashboard provides an interactive operational overview
containing:

- KPI cards
- Completed booking trend
- Revenue trend
- Vehicle-type revenue analysis
- Pickup location analysis
- Drop location analysis
- Customer rating
- Driver rating
- Booking status indicators
- Month slicer
- Quarter slicer
- Vehicle-type visual navigation

The dashboard is designed to provide a quick operational view of booking
volume, revenue, vehicle performance, locations, and service quality.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Dataset review, data-quality analysis and validation |
| **Power BI Desktop** | Interactive dashboard and data visualization |
| **Power BI Visuals** | KPI cards, charts, tables and interactive filters |
| **Data Analysis** | Trend, cancellation, vehicle, location and service analysis |
| **Business Intelligence** | Operational KPI monitoring and decision support |

---

# 📁 Project Structure

```text
uber-ride-booking-analysis/
│
├── README.md
│
├── data/
│   └── uber.csv
│
├── dashboard/
│   └── Uber_Dashboard.pdf
│
└── reports/
    └── Uber_Ride_Booking_Performance_Report.pdf
