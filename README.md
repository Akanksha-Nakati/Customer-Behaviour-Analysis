# 📺 Netflix Customer Behaviour Analysis

> A comprehensive analysis of Netflix's userbase focusing on customer behavior patterns, subscription preferences, revenue generation, and user retention — visualized through interactive Tableau dashboards.

![Netflix Dashboard](Netflix%20user.png)

---

## 📌 The Problem

Netflix operates across multiple subscription tiers and a highly competitive streaming market. Retaining customers and maximizing revenue requires a deep understanding of *who* the users are, *how* they engage with the platform, and *what* drives them to stay or leave.

This project analyzes demographic and behavioral data to answer: *which users are most valuable, which are at risk of churning, and what can Netflix do about it?*

---

## 🔍 What This Project Covers

### 📊 Analysis Areas

- **Revenue Generation** — How subscription type preferences (Basic, Standard, Premium) impact overall revenue
- **User Retention** — Identifying patterns in customer tenure and payment history to flag churn risk
- **User Engagement** — How device type (Smartphone, Laptop, Smart TV) influences plan choice and content consumption
- **Demographic Segmentation** — Cross-analysis of age, gender, and country against subscription behavior

### 🗂️ Dataset Fields Used

| Field | Purpose |
|---|---|
| `Subscription Type` | Segment users by plan tier (Basic / Standard / Premium) |
| `Monthly Revenue` | Measure revenue contribution per user |
| `Join Date & Last Payment Date` | Calculate tenure and identify churn risk |
| `Country`, `Age`, `Gender` | Demographic profiling |
| `Device Type` | Understand engagement patterns across devices |

---

## 💡 Key Findings

- 💳 **Premium Plans** drive the highest revenue, especially among middle-aged users (35–45)
- 📱 **Basic Plans** are most popular with users under 30, particularly in the US and Germany
- 📺 **Smart TV & Laptop users** show longer tenures and higher engagement than smartphone users
- 🌍 **Premium plans dominate** in the US and Canada; Germany skews heavily toward Basic
- 📉 **Smartphone users** tend toward shorter-term, lower-tier subscriptions — a potential churn risk segment

---

## 🎯 Strategic Recommendations

1. **Target smartphone users** with upgrade incentives or mobile-optimized content to drive higher-tier adoption
2. **Run regional campaigns** for Basic and Standard plans in markets like Germany where those tiers are most popular
3. **Promote larger screen consumption** (Smart TV bundles, device partnerships) to boost engagement and reduce churn
4. **Flag churn-risk users** based on tenure length and gaps in payment activity for proactive outreach

---

## 🛠️ Tools & Technologies

| Tool | Role |
|---|---|
| **Tableau Desktop** | Interactive dashboard development and visualization |
| **Microsoft Excel** | Source dataset (`Netflix Userbase.xlsx`) |

---

## 📂 Repository Structure

```
├── Netflix Userbase.xlsx                    # Source dataset
├── Customer Behaviour Analysis(Tableau).twb # Tableau workbook with all dashboards
├── Netflix user.png                         # Dashboard preview image
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Akanksha-Nakati/Customer-Behaviour-Analysis.git
   ```

2. **Open the Tableau workbook**
   - Requires [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/)
   - Open `Customer Behaviour Analysis(Tableau).twb` to explore all interactive dashboards

3. **Explore the dataset**
   - Raw data is in `Netflix Userbase.xlsx` — open with Excel or any spreadsheet tool

---

> **Note:** This project uses a publicly available Netflix userbase dataset for analytical and educational purposes.

