# 📊 Meta Ad Performance Analytics

An interactive **Power BI dashboard** that analyzes and compares advertising performance across **Facebook** and **Instagram** (Meta platforms). It turns raw campaign data into actionable insights on reach, engagement, conversions, and budget efficiency.

---

## 🎯 Project Objective

Marketing teams often struggle to compare ad performance across platforms, formats, and audiences. This dashboard provides a single view to:

- Track key campaign KPIs at a glance
- Compare Facebook vs. Instagram performance
- Identify the best-performing ad formats, audiences, regions, and time windows
- Support data-driven budget and targeting decisions

---

## 🧩 Dashboard Structure

| Page | Description |
|------|-------------|
| **Facebook** | Performance overview for Facebook ad campaigns |
| **Instagram** | Performance overview for Instagram ad campaigns |
| **Calendar Tooltip** | Hidden tooltip page showing details on hover over the calendar |

Users switch between platforms using the **Facebook / Instagram navigation buttons** in the side panel.

---

## 📈 Key Metrics (KPIs)

**Volume metrics:** Impressions, Clicks, Shares, Comments, Purchases, Engagements

**Rate and budget metrics:**
- **CTR** (Click-Through Rate)
- **Engagement Rate**
- **Conversion Rate**
- **Purchase Rate**
- **Total Budget**
- **Average Budget per Campaign**

### Snapshot

| Metric | Facebook | Instagram |
|--------|----------|-----------|
| Impressions | 216K | 124K |
| Clicks | 25K | 15K |
| CTR | 11.76% | 11.86% |
| Engagement Rate | 13.56% | 13.60% |
| Conversion Rate | 5.21% | 4.82% |
| Purchase Rate | 0.61% | 0.57% |

---

## 🔍 Visualizations & Features

- **KPI Cards:** 12 color-coded cards for instant performance reading
- **Dynamic Measure Selector:** switch all visuals between metrics (Impressions, Clicks, Shares, etc.) using a field parameter
- **Demographics:** donut chart (gender) and column chart (age distribution)
- **Geographic Analysis:** bubble map showing performance by country
- **Time Analysis:**
  - Weekly trend (stacked column chart)
  - Hourly trend (area chart)
  - Monthly calendar view with month slicer and custom tooltip
- **Ad Type Matrix:** Image, Carousel, Video, and Stories compared by IMPR, CLKS, CTR, PR, ER, and CR with conditional formatting
- **Interactive Slicers:** Name, Target Interest, and Month filters
- **Custom Navigation:** platform toggle buttons with Meta branding

---

## 💡 Key Insights

- Facebook delivers significantly higher volume (216K vs. 124K impressions), while Instagram matches it on CTR and engagement rate.
- Facebook has a slightly higher conversion rate (5.21% vs. 4.82%).
- Stories and Image formats lead in impressions on Facebook; Carousel leads on Instagram.
- Engagement rates stay consistent (~13.4% to 13.9%) across all ad formats.
- Audience reach spans North America, Europe, Asia, South America, and Australia.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX** (measures, field parameters, calculated KPIs)
- **Power Query** (data cleaning and transformation)
- **Data Modeling** (relationships, date table)

---

## 📁 Repository Structure

├── Meta_Ad_Performance_Analytics.pbix
├── dataset/
│ └── ad_campaign_data.csv
├── screenshots/
│ ├── facebook_dashboard.png
│ └── instagram_dashboard.png
└── README.md


---

## 🖼️ Screenshots

### Facebook Dashboard
<img width="1322" height="741" alt="image" src="https://github.com/user-attachments/assets/8aa97f58-9b5b-49cb-90d4-59a4fca2cc74" />


### Instagram Dashboard
<img width="1380" height="742" alt="image" src="https://github.com/user-attachments/assets/7f11700d-3a78-469d-8de1-505c7bca8c6b" />


---

## 🚀 How to Use

1. Clone this repository:
```bash
   git clone https://github.com/your-username/Meta-Ad-Performance-Analytics.git
```
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted, refresh the data source path.
4. Use the side-panel buttons and slicers to explore the dashboard.

---

## 🔮 Future Improvements

- Add budget vs. ROI analysis
- Include campaign-level drill-through pages
- Add forecasting for impressions and conversions
- Publish to Power BI Service with scheduled refresh

---

## 👤 Author

**Sharini G**

- 💼 LinkedIn: [linkedin.com/in/sharini-g-571546382](https://www.linkedin.com/in/sharini-g-571546382)
- 📧 Email: [g.sharini1601@gmail.com](mailto:g.sharini1601@gmail.com)
- 🐙 GitHub: [github.com/sharini16173](https://github.com/sharini16173)

⭐ If you found this project useful, consider giving it a star!
