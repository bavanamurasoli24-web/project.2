---


## 🖥️ Dashboard Structure

### **Page 1 — Executive Overview**
7 KPI cards (Total Consumed, Avg Efficiency, Total Generated, Avg Utilization, Active Plants, Renewable %, Total Deficit), a donut chart of generation share by source, and a bar chart of generation by region.

### **Page 2 — Generation Dashboard**
A multi-line trend of generation by source over time, a clustered column comparing generation vs. consumption by source, and a bar chart of monthly generation patterns — filterable by Year, Source, and Quarter.

### **Page 3 — Regional Dashboard**
A column chart of total generation by region, a donut chart of efficiency by region, and a plant-level operational status table flagging which plants are running in deficit.

### **Page 4 — Sustainability Dashboard**
A Renewable Contribution % card, a power deficit trend line across years, and a column chart showing generation totals broken down by weather condition.

---

## 🖼️ Dashboard Screenshots

> Stored in the `images/` folder.

| Page | File |
|---|---|
| Executive Overview | `images/page1_executive_overview.png` |
| Generation Dashboard | `images/page2_generation_dashboard.png` |
| Regional Dashboard | `images/page3_regional_dashboard.png` |
| Sustainability Dashboard | `images/page4_sustainability_dashboard.png` |

---

## 🔍 Key Findings

- **Hydro is the leading renewable source**, contributing the largest share of total generation, followed closely by Solar and Wind.
- **Generation is fairly evenly spread across regions** (South, Central, West, East, North), but plant-level data shows individual plants within each region running in deficit (`Is_Deficit = True`).
- **Power deficit is volatile rather than trending** — it fluctuates sharply day to day rather than showing a steady seasonal pattern.
- **Weather conditions visibly affect output** — generation is highest under Sunny/Normal conditions and drops under Stormy, Flood, and Breezy conditions.
- **Overall renewable contribution stands at 100%**, so the focus going forward is on efficiency and reliability rather than the renewable mix itself.

---

## 💡 Recommendations

1. **Target deficit-flagged plants first** using the Page 3 operational status table.
2. **Build weather-aware operational planning** since generation drops under adverse weather.
3. **Diversify source mix** in regions over-relying on a single source to reduce weather exposure.
4. **Investigate deficit spikes as incidents**, not long-term trends, given the volatility pattern.
5. **Track utilization rate alongside efficiency** to spot underused capacity.

---

## 🚀 Future Scope

- Integrate real-time/live data feeds for live monitoring.
- Add ML-based forecasting for generation and deficit prediction.
- Build an automated alerting system for plants entering deficit status.
- Expand the Regional Dashboard with a geographic map visual.
- Add cost/financial metrics tied to operational efficiency.

---

## 🛠️ Tools Used

- **Power BI** — dashboard development, DAX measures, data modeling

---

## 📁 Repository Structure
