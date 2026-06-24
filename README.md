# PitchSide Pro — Executive Revenue Report
 
> A 5-page Power BI executive dashboard analyzing what drives revenue change over time for PitchSide Pro, a global football-merchandise e-commerce retailer, and where the business should focus to sustain growth.
 
![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811)
![Type](https://img.shields.io/badge/Type-Executive%20Report-16335C)
![License](https://img.shields.io/badge/License-MIT-blue)
 
---
 
## Project Overview
 
This is a **5-page executive Power BI report** built for PitchSide Pro, a fictional global football-merchandise e-commerce retailer. Designed for an **executive leadership audience** who skim in under 60 seconds and make decisions rather than explore, the report leads with the answer first and lets detail sit one layer down.
 
The report answers a single executive question:
 
> **What is driving revenue change over time, and where should the business focus to sustain growth?**
 
*Built as a data-visualization contest entry and portfolio piece.*
 
---
 
## The Thesis
 
**Growth is structural, not rented, and our customers are loyal. The two real levers are converting the traffic we already have (conversion has been flat at 3.24% for five years) and working the growth engine harder. The risk to manage is product concentration, not churn.**
 
The report opens with a starting hypothesis that growth is *rented from football moments* and the priority is converting one-time event buyers then tests it page by page. The data overturns it: tournaments barely move revenue, margins are healthy everywhere, and customers are already loyal. The honest, evidence-led conclusion replaces the hunch and that "hypothesis tested, then revised" arc is the spine of the report.
 
---
 
## Key Findings
 
- **Growth is owned, not rented** — football tournaments drive only ~5% of revenue. The real engine is everyday trading (~48%) plus a commercial calendar the business controls — kit launches and holiday gifting (~38%). Dependence on events is flat-to-falling, and 2025's growth came from the baseline (+23.3%).
- **Margins are healthy and uniform** — 52.8% overall, holding in a tight 48–58% band across every region, channel, and product category. The business is *not* trading profit for volume, the real exposure is **product concentration — Kits + Footwear make up 78.6% of revenue.**
- **Customers are loyal — the leak is conversion** — event-acquired buyers return at 85.7% vs 88.9% for everyone else (a trivial gap), and within-year repeat rate is *rising* (25.5% → 33.2%). Meanwhile site conversion has been stuck at **3.24% for five years**, with 85% of sessions never reaching the cart.
---
 
## Recommendations
 
1. **Fix the funnel** *(primary lever)* — tied to conversion flat at 3.24% for 5 years, enables a quantified **+$1.73M** prize from a +0.5pt conversion lift, from traffic already paid for.
2. **Make the loyalty programme earn its cost** — tied to members repeating identically to non-members (87.7%); enables a decision to redesign or retire the spend.
3. **Work the calendar we control** — tied to ~38% of revenue from kit launches + holiday gifting (vs ~5% from tournaments), enables planning inventory and marketing around owned moments.
4. **Grow high-margin lines, ease concentration** — tied to Limited Edition (5.2% of revenue at 56.2% margin) and 78.6% concentration in two categories, enables expanding the high-margin range.
---
 
## Report Structure (5 Pages)
 
| Page | Executive Question | Headline Insight |
|------|--------------------|------------------|
| 1 | Summary - how are we performing? | Revenue is growing and the growth is increasingly structural; the everyday baseline now carries it. |
| 2 | What's really driving our growth? | Only ~5% rides on tournament outcomes; ~38% is a commercial calendar we control. |
| 3 | Where does revenue come from, and at what margin? | Margins are stable at 52.8% across every region/channel; 78.6% of revenue is concentrated in two categories. |
| 4 | Do event buyers come back, and does traffic convert? | Retention is a strength; the real leak is the funnel conversion flat at 3.24% for five years. |
| 5 | Where to focus next? | Fix the funnel first a +0.5pt conversion lift is worth +$1.73M. |
 
---
 
## Tools & Technologies
 
- **Microsoft Power BI Desktop** — Report development and visualization
- **Power Query (M Language)** — Data modeling and transformation
- **DAX (Data Analysis Expressions)** — Measures, time intelligence, and event/cohort analysis
---
 
## Design System
 
**Audience:** Executive leadership — daily skim, decision-focused, expects precision and trust.
 
**Brand Palette:**
 
| Color | Hex | Use |
|-------|-----|-----|
| Navy | `#16335C` | Primary text / headers / structural series |
| Green | `#0F8A4D` | Positive values only (positive deltas) |
| Gold | `#E6B84F` | Highlights / "the moments" / KPI callouts |
| Slate | `#5E7088` | Secondary text / baseline / neutral series |
 
**Design Principles:**
- Top-line answer first, drill-down second
- Every page ends in a "so what," not just a chart
- Plain business language no jargon or DAX talk on the canvas
- Exact numbers with a clear "data as of" date
- Branded, consistent header across all pages
- Same colour = same meaning on every page
---
 
## Repository Structure
 
```
pitchside-pro-report/
├── README.md                         
├── report/
│   └── PitchSide_Pro_Report.pbix      
└── screenshots/
    ├── 01_overview.png
    ├── 02_products.png
    ├── 03_regions_channels.png
    ├── 04_customers.png
    └── 05_recommendations.png
```
 
---
 
## Report Preview
 
<!-- Add your screenshots or demo video here -->
<!-- To embed a video: drag the .mp4 into the GitHub README editor and it auto-embeds -->
 
*Screenshots / demo coming soon.*
 
---
 
## How to Use
 
### Prerequisites
- Power BI Desktop (free from Microsoft)
### Setup
1. Clone or download this repository
2. Open `report/PitchSide_Pro_Report.pbix` in Power BI Desktop
3. Explore the report using the navigation and slicers
---

## Data Source
   Dataset and starter file provided by the Microsoft Fabric Community 
   Contest (Power BI Dataviz World Champs, Barcelona 2026).
   Source: https://github.com/shannonlindsay/FabricCommunityContests

## About Me
 
**Bedoor Ayadh Almareni**
Computer Science Graduate (AI Specialization) | Aspiring Data Analyst, Jeddah Saudi Arabia
 
I turn complex data into clear, actionable insights using Power BI, Power Query, SQL, and Python.
 
**Connect with me:**
- Email: Bedooralmareni@gmail.com
- LinkedIn: [Bedoor Almareni](https://www.linkedin.com/in/bedoor-alsulami)
---
 
## License
 
This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details. 

 
*Last updated: June 2026*
