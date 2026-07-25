# 🚕 Ola Bookings — Power BI Dashboard

An interactive Power BI dashboard analyzing a month of Ola ride-booking data, covering overall booking trends, vehicle-type performance, revenue, cancellations, and customer/driver ratings.

## Overview

The report is built as a 5-page interactive dashboard on top of a single ride-bookings table, with a date slicer on every page so metrics can be filtered to any time window. Navigation between pages is handled through in-report action buttons.

## Dashboard Pages

| Page | What it shows |
|---|---|
| **Overall** | Total Bookings and Total Booking Value KPI cards, a Ride Volume Over Time trend line, and a Booking Status Breakdown pie chart |
| **Vehicle Type** | KPI cards broken out by vehicle category (e.g. Mini, Sedan, Prime, Auto, Bike), letting you compare volume/value across vehicle types |
| **Revenue** | Revenue by Payment Method and Ride Distance Distribution per day column charts, plus a Top 5 Customers table |
| **Cancellation** | Cancelled Rides by Customers and Cancelled Rides by Drivers pie charts, alongside Total, Succeeded, and Cancelled Booking counts and the overall Cancellation Rate |
| **Ratings** | KPI cards summarizing customer and driver rating metrics |

## Tech Stack

- **Power BI Desktop** (`.pbix`)
- DAX measures for KPI cards (bookings, revenue, cancellation rate)
- Built-in Power BI visuals: line chart, pie chart, column chart, table, cards, slicer

## Repository Contents

| File | Description |
|---|---|
| `Ola.pbix` | The full Power BI report — data model, DAX measures, and all 5 report pages |
| `README.md` | Project documentation |

## Getting Started

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows only).
2. Clone the repository:
   ```bash
   git clone https://github.com/NaveenK9959/Ola-Bookings.git
   ```
3. Open `Ola.pbix` in Power BI Desktop.
4. Use the **Date** slicer on any page to filter the dashboard, and the navigation buttons to move between Overall, Vehicle Type, Revenue, Cancellation, and Ratings pages.

## Key Insights the Dashboard Surfaces

- Booking volume and value trends over time, and how bookings split across status (completed, cancelled, etc.)
- Which vehicle types drive the most bookings and revenue
- Revenue breakdown by payment method and how ride distance is distributed day to day
- Who's cancelling more — customers or drivers — and the overall cancellation rate
- Rating patterns across customers and drivers

## Author

**Naveen Kumar**
- GitHub: [@NaveenK9959](https://github.com/NaveenK9959)
- LinkedIn: [naveen-kumar-934858289](https://linkedin.com/in/naveen-kumar-934858289)
