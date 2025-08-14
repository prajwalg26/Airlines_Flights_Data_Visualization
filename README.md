# Airlines Flights Data Visualization — Python EDA & Insights

## Project Overview
This project explores and visualizes a large dataset of **300,000+ flight records** to analyze:
- **Pricing trends** over time
- **Peak travel periods**
- **Route-based price differences**
- **Effects of booking lead-time**
- **Airline, travel class, and time-of-day impacts on pricing**

The project uses **Python** with **Pandas**, **Matplotlib**, and **Seaborn** for data preprocessing, exploratory analysis, and creating **publication-quality visualizations**.

---

## Objectives
- Perform **EDA** to understand flight pricing dynamics.
- Identify **optimal booking strategies** using lead-time analysis.
- Compare **airlines, travel classes, and routes** for price optimization.
- Detect **seasonal and time-of-day patterns**.
- Present **insights visually** to inform airline pricing and marketing strategies.

---

## Dataset
- **Source**: Airlines flight bookings dataset (public/sample data)
- **Size**: 300K+ flight records
- **Key Columns**:
  - `Airline`
  - `Flight Route` (Source → Destination)
  - `Travel Date`, `Booking Date`
  - `Price`
  - `Class` (Economy, Business, etc.)
  - `Departure Time Category` (Morning, Afternoon, Evening, Night)
  - `Duration`

---

## Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Handled missing `Price` and `Class` fields.
- Converted date columns to datetime format.
- Derived **`Lead_Time`** feature = *Travel Date - Booking Date*.
- Standardized airline and route names.

### 2️⃣ Exploratory Data Analysis
- Summary statistics on price distribution across airlines, routes, and classes.
- Grouped visualizations for route-class combinations.
- Correlation analysis between lead-time and price.

### 3️⃣ Data Visualization
Using **Matplotlib** & **Seaborn**:
- **Line Charts** — Price change over months and weeks.
- **Box Plots** — Price variation by class and airline.
- **Bar Charts** — Peak travel periods & busiest routes.
- **Heatmaps** — Correlations between price, lead-time, and schedule.
- **Facet Grids** — Time-of-day vs price range comparisons.

---

## Key Insights
- **Peak pricing** during holiday seasons; off-peak discounts in mid-week months.
- **Booking 30–45 days in advance** yields best price savings.
- **Business class** prices vary more sharply with lead-time than economy.
- Certain **routes maintain stable prices** year-round, others are highly seasonal.
- Evening departures on short-haul routes tend to be **cheaper**.

---

## Tools & Technologies
| Tool / Library   | Purpose |
|------------------|---------|
| **Python**       | Core programming for analysis |
| **Pandas**       | Data loading, cleaning, transformation |
| **Matplotlib**   | Static visualizations |
| **Seaborn**      | Statistical visualizations |
| **Google Collab** | Interactive analysis |

---

## Visualization Samples
<img width="1690" height="510" alt="image" src="https://github.com/user-attachments/assets/515da1aa-c549-4b35-ac05-0a7102d65b12" />


---


