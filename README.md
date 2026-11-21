# Sales Intelligence & UX-Driven Dashboard  — Power BI

> An interactive Power BI dashboard that turns 16 months of raw financial data into clear, fast, decision-ready insights — built with a focus on **backend engineering and UX**, not just visuals.

---

## Project Overview

| Attribute | Details |
|---|---|
| **Data Period** | September 2021 → December 2022 (16 months) |
| **Financial KPIs** | Net Sales, Units Sold, Profit, Discounts |
| **Analysis Dimensions** | Customer Segment, Country, Product, Time |
| **Tool** | Power BI |

---

## Analysis Scope

- **Overall Performance** — Sales and profit trends over time, highlighting growth and decline patterns
- **Geographical Analysis** — Country-level performance to identify the most profitable markets
- **Segmental Analysis** — Customer segment breakdown to guide targeted strategic decisions
- **Product Analysis** — Top-selling and highest-margin products, including the impact of discounts on volume and profit

---

## Dashboard Engineering & UX

Most dashboards stop at visuals. This one was designed from the backend to deliver a fast, clean experience.

### Bookmarks & Selections
- **Bookmarks + Selection Pane** create dynamic visual layers instead of multiple pages
- Elements show/hide instantly based on user context, with no page reloads
- Each analysis view is a *state*, not a page, which keeps navigation fast and the report light

### Dynamic Navigation Buttons
- Dedicated buttons for each analysis dimension (Products, Countries, Segments, Time Periods)
- **Dynamic formatting** (Active / Inactive states) so the user always knows which view they are in

### Custom Tooltip Pages
- Hovering over key data points opens **custom-designed tooltip pages** instead of default tooltips
- Shows granular detail (exact discount breakdowns, monthly profit margins) without cluttering the main canvas

**Result:** Zero page reloads · Minimal click-paths · Maximum analytical depth

---

## Key Insights

<!-- Fill these in from your own findings. Keep each one specific and numeric. -->
- **Most profitable country:** _[name + figure]_
- **Best-performing segment:** _[name + figure]_
- **Highest-margin product:** _[name + figure]_
- **Discount impact:** _[what you observed, e.g. discounts vs. margin by segment]_
- **Underperforming area:** _[e.g. segment or product with low or negative profit, and why]_

---

## Business Value

| Use Case | Impact |
|---|---|
| **Performance Monitoring** | One view of sales, profit, units, and discounts across all dimensions |
| **Strategic Decisions** | Quickly identifies the strongest markets, segments, and products |
| **Discount Policy Review** | Shows how discounts relate to volume and profitability |
| **Executive UX** | Bookmark-based design minimizes click-paths and saves management time |

---

## Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI** | Data modeling, DAX measures, interactive dashboard |
| **Bookmarks & Selection Pane** | Dynamic navigation and visual layers |
| **Custom Tooltips** | Contextual detail on hover |

---
