# Flight Price & Cancellation Analysis Dashboard (Power BI)

## Overview
This project presents an interactive **Power BI dashboard** analyzing domestic flight data with a focus on **ticket pricing behavior and cancellation trends**.  
The analysis highlights how **prices increase as departure dates approach**, how pricing varies across **airlines and departure times**, and introduces **flight cancellation percentage** as an operational reliability indicator.

The dashboard is designed to support **data-driven decision making** for travelers and analysts by combining **cost and risk (cancellation)** perspectives.

---

## Key Insights
- **Flight prices rise sharply as days left before departure decrease**, confirming last-minute booking premiums.
- **Afternoon and morning flights** tend to be more expensive than night and late-night flights.
- Airlines follow **distinct pricing strategies**, leading to consistent average price differences.
- Prices are generally **lower and more stable when booked 20–50 days in advance**.
- The **cancellation rate (~0.5%)** is low overall but provides important context when comparing airlines and routes.

---

## Dashboard KPIs
- **Cancelled %** – Percentage of flights cancelled
- **Average Duration** – Mean flight duration (hours)
- **Total Flights** – Number of flights analyzed
- **Average Price** – Mean ticket price

---

## Visualizations Included
- Average ticket price by airline
- Average ticket price by departure time
- Price trend vs days left before departure
- Interactive slicers for:
  - Source city
  - Airline
  - Destination
  - Departure time

---

## Tools & Technologies
- **Power BI Desktop**
  - Data modeling
  - DAX measures
  - Interactive visual analytics
- **Power Query**
  - Data cleaning and transformation
- **CSV Dataset**
  - Flight pricing and scheduling data

---

## Dataset Description
The dataset includes the following fields:
- Airline
- Flight number
- Source and destination
- Departure and arrival time
- Stops
- Ticket class
- Duration
- Days left before departure
- Price
- Cancellation status

---

## Files in This Repository
- `Flight_Price_Analysis.pbix` – Power BI dashboard file
- `flight_data.csv` – dataset used for analysis
- `screenshots/` – dashboard preview images
- `README.md` – project documentation

---

## How to Use
1. Download the `.pbix` file.
2. Open it using **Power BI Desktop**.
3. Use slicers to explore pricing and cancellation patterns.
4. Interpret insights directly from the visualizations.

---

## Project Purpose
This project was built to:
- Analyze **real-world flight pricing behavior**
- Understand the impact of **time-to-departure on cost**
- Incorporate **operational reliability (cancellations)** into analysis
- Strengthen a **data analytics portfolio** for internships and placements

---

## Author
**Sumit Singh**  
B.Tech CSE (Data Science)  
GitHub: https://github.com/Sumitsingh39499
