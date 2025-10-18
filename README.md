## 🎯 **1. Project Title / Headline**

**FLAM AR Campaign Analytics Dashboard – QR to AR Journey Performance Tracker**

A data-driven Power BI dashboard designed to visualize end-to-end user engagement across AR-based marketing campaigns powered by Flam, tracking sessions from QR scan to retention and conversions.

---

## 📌 **2. Short Description / Purpose**

This dashboard provides real-time insights into campaign performance by tracking user journey metrics such as scans, AR load success, engagement timings, share actions, drop-off stages, and retention. It enables marketing and product teams to optimize AR experiences and improve user scalability across regions and devices.

---

## 🧠 **3. Tech Stack**

The dashboard was built using the following technologies:

* **📊 Power BI Desktop** – Core platform for interactive visual reporting.
* **🧩 Power Query (M Language)** – Used for data cleaning, transformation, and shaping AR session logs.
* **📐 DAX (Data Analysis Expressions)** – Created calculated KPIs such as Retention Rate, Engagement Score, FPS-based segmentation, and Drop-off probabilities.
* **🎨 Custom Visuals & UX Layer** – Includes KPI cards, funnel visualization, donut breakdown, filled map, slicers, and anomaly detection indicators.

---

## 📂 **4. Data Source**

* Contains **~5000 session records** with fields including:

  * `session_id`, `device_type`, `region`, `fps_capability`, `engagement_seconds`, `qr_scan_time`, `ar_load_time`, `share_clicked`, `retention_day_7`, `dropoff_stage`
* Preprocessing included timestamp conversion, FPS classification, engagement segmentation, and retention flag normalization.

---

## 🚀 **5. Features / Highlights**

### 🧩 **Business Problem**

AR campaigns often generate high scan activity but suffer from poor engagement, slow AR load times, and device-based performance variations. Marketing teams lack granular insights on **WHERE users drop off and WHICH devices/regions deliver highest conversions**.

### 🎯 **Goal of the Dashboard**

To create an interactive analytics layer that:

* Tracks **user journey from Scan → Load → Engage → Exit**
* Identifies high-performing campaigns and regions
* Detects **drop-off spikes and FPS-based device behavior**
* Provides **retention and share conversion intelligence** for product iteration

---

### 🧭 **Walkthrough of Key Visuals**

| **Visual**                                    | **Purpose**                                                                                                            |
| --------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **KPI Tiles (Top Row)**                       | Highlights Total Sessions (5000), Avg Engagement (153 sec), Retention %, Share Conversion, AR Load Success, Drop-off % |
| **Funnel – User Journey**                     | Visualizes step-wise journey with **percentage drop-off labels**                                                       |
| **Engagement by Device (Bar Chart)**          | Compares Android vs iOS vs WebQR engagement trends                                                                     |
| **Campaign Performance Leaderboard**          | Ranks campaigns by performance score / engagement                                                                      |
| **Geo Heatmap – Region & Retention**          | Shows retention distribution across major Indian cities                                                                |
| **Time Series – Month-over-Month Engagement** | Tracks engagement performance trend (Sep vs Oct)                                                                       |
| **Donut Chart – Drop-off Segmentation**       | Breakdown of user exits at Scan, Load, Engage, Exit stages                                                             |
| **FPS Slider & Anomaly Slicer**               | Enables analysis of device capability-related engagement patterns                                                      |

---

## 💡 **Business Impact & Insights**

* **Campaign Optimization:** Identified that **Android contributes highest engagement (316K seconds)** → prioritize Android device tuning.
* **Performance Leak Detection:** **30% drop-off occurs at Scan stage** → QR landing experience needs improvement.
* **Geographic Targeting:** Regions like **Bangalore and Mumbai show stronger retention** → refine ad budget distribution.
* **High-FPS Device Opportunity:** Users with **FPS ≥ 60 show 40% higher engagement** → optimize for high-end experience.
* **Retention Trigger:** AR load success strongly correlates with **Day-7 retention**, indicating first 5 seconds of AR load determine success.

---

## 📸 **6. Dashboard Preview**

![image alt](https://github.com/MohanS-2009/Augmented-Reality-Campaign-Data/blob/main/Flam%20Ar%20Campaign%20Data.jpg)
