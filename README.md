# Crime-Against-Women-2001-2021---Power-BI-Project
Two decades of data (2001–2021) mapping crimes against women in India. Built with Power BI to explore regional distributions, historical timelines, and shifting trend dynamics.

## 📌 The Core Thesis: The Post-2012 Paradox
A central focus of this analytical report is the historical timeline featured on Slide 2. 

Following the watershed events of 2012, public policy shifted, legal frameworks tightened, and societal outrage peaked. Yet, the data reveals a counterintuitive trend: **reported violent crimes and sexual abuse surged drastically rather than declining.** This dashboard visualizes this trajectory, forcing stakeholders to confront a critical analytical question: *Does a spike in data points reflect an increase in actual violence, or a hard-fought increase in the courage to report it?*

---

## 🛠️ The Data & Analytics Pipeline

### 1. Data Transformation (Power Query)

* **Ingestion & Normalization:** Processed 20 separate annual government datasets, rectifying structural shifts in reporting methodologies across two decades.
* **Fact/Dimension Modeling:** Restructured flat tabular data into normalized tables optimized for analytical scanning.

### 2. Data Modeling & DAX Engine

* **Schema Design:** Implemented a robust **Star Schema** architecture to decouple dimensions (Time, Geography, Crime Type) from historical crime counts, ensuring highly performant filter propagation.
* **Advanced DAX Metrics:** Developed custom measures to compute:
  * Year-over-Year (YoY) percentage changes across volatile crime categories.
  * Regional crime distribution index weights.
  * Rolling 3-year averages to smooth out reporting anomalies.

### 3. UI/UX & Sentiment Design

* **Custom Theme Engineering:** Utilized a tailored JSON theme configuration to dictate a somber, clinical, yet highly professional interface.
* **Cognitive Load Management:** Intentionally isolated high-density trend lines with deliberate spatial layouts, ensuring the grim reality of the data remains objective, clear, and readable without becoming visually chaotic.

---

## Key Analytical Visualizations

### Slide 1: Regional Landscapes

* National KPI cards tracking total case volumes and macroeconomic growth vs. crime growth rates.
* Geographic choropleth maps identifying high-density reporting zones vs. silent zones.

### Slide 2: Chronological Trends & Categorical Spikes

* **The Primary Visual:** A deep-dive time-series line chart mapping the 2001–2021 timeline. This highlights the post-2012 structural break, isolating sexual assault to see how it affects macro-level spikes.
* Key influencers

### Slide 3 and 4: Drill-through page for deep diving state level data and Tooltips page for Slide 1.

---

## 🚀 How to Run and Interact with the Dashboard

1. **Prerequisites:** You will need [Power BI Desktop](https://powerbi.microsoft.com/) installed on your machine.
2. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/crime-against-women-india.git](https://github.com/YOUR_USERNAME/crime-against-women-india.git)
