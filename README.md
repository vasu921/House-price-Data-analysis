# 🏠 House Data Price Analysis Dashboard

An interactive **Power BI** dashboard that analyzes residential house prices and shows how price changes with bedrooms, condition, floors, waterfront access, and location (ZIP code).

---

## 📌 Overview

This project turns raw housing data into a one-page, interactive report. It uses a **star-schema data model** (one fact table and several dimension tables) and DAX measures, so stakeholders can filter the data and see pricing patterns quickly.

**Goals**
- Understand what drives house prices
- Compare average prices across bedrooms, condition, floors, waterfront and ZIP code
- Give buyers, sellers and analysts a quick market snapshot

---

## 📊 Dashboard Features

### KPI Cards
| Metric | Description |
|---|---|
| **Average House Price** | Mean price of the filtered houses |
| **Total House Price** | Sum of all house prices |
| **Minimum House Price** | Lowest-priced house |
| **Total Houses** | Number of houses (count) |
| **Average Living Area** | Mean living area (sq ft) |

### Visuals
| Visual | Insight |
|---|---|
| Clustered column chart | Average price by **number of bedrooms** |
| Clustered bar chart | Total houses by **condition** |
| Clustered bar chart | Average price by **ZIP code** |
| Clustered column chart | Average price by **condition** |
| Pie chart | Maximum house price by **number of floors** |
| Donut chart | Average price by **waterfront** vs non-waterfront |

### Slicers (Filters)
- Bedrooms
- Floors
- Condition

The report page is 1920 × 1080 and uses the **Tidal** theme.

---

## 🗂️ Data Model

Star schema with the following tables:

- **HOUSE DATA FACT TABLE** – main fact table (prices, area, bedrooms, floors, condition, waterfront, etc.)
- **HOUSE DATA DIMENSIONTABLE** – house attribute dimension
- **LOCATION DIMENSION TABLE** – location details (e.g. ZIP code)
- **DIMENSION CONSTRUCTION TABLE** – construction-related details
- **DATE DIMENSION TABLE** – date dimension

### DAX Measures
`AVERAGE HOUSES PRICE` · `TOTAL HOUSE PRICE` · `MINIMUM HOUSE PRICE` · `MAXIMUM HOUSE PRICE` · `TOTAL HOUSES` · `AVERAGE LIVING AREA`

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop**
- **Power Query** – data cleaning and transformation
- **Data modeling** – star schema, relationships
- **DAX** – calculated measures
- **Data visualization** – KPI cards, charts, slicers

---

## 🚀 How to Use

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).
3. Open `HOUSE_DATA__PRICE_ANALYSIS_DASHBOARD__PROJECT_DOCUMENT_1.pbix`.
4. Use the slicers (Bedrooms, Floors, Condition) to explore the data.

---

## 📁 Repository Structure

```
├── HOUSE_DATA__PRICE_ANALYSIS_DASHBOARD__PROJECT_DOCUMENT_1.pbix   # Power BI report
├── README.md
└── screenshots/                                                   # Dashboard preview images (add yours)
```

---

## 🖼️ Preview

> Add a screenshot of your dashboard here:
>
> `![Dashboard Preview](screenshots/dashboard.png)`

---

## 🔍 Key Insights

> Fill these in after exploring your own data, for example:
> - How average price changes as bedrooms increase
> - Which ZIP codes have the highest average prices
> - Price difference between waterfront and non-waterfront houses
> - Effect of house condition on price

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://linkedin.com/in/your-profile)

---

## 📄 License

This project is for learning and portfolio purposes. Add a license (e.g. MIT) if you want others to reuse it.
