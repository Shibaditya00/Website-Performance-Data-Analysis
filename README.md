# Website Performance Data Analysis

This project focuses on analyzing website performance metrics across various marketing channels in domains such as E-commerce, Finance, and Healthcare. Using real-world web analytics data, we explore user behavior, engagement trends, and traffic dynamics to extract actionable insights for improving website performance and user experience.

---

## 📊 Project Overview

As of 2025, the total number of websites on the internet is estimated to be around 110–120 crores (1.1–1.2 billion), and over 60% of web traffic comes from mobile devices. With increasing digital presence, it’s crucial for organizations to understand how users interact with their websites and how different channels contribute to overall performance.

This project answers key business questions by analyzing user sessions, engagement metrics, and traffic sources using Python and Pandas.

---

## 📁 Dataset

<a href="https://github.com/Shibaditya00/Website-Performance-Data-Analysis/blob/main/data-export%20(1).csv">Dataset Link</a>

The dataset contains website performance data with the following columns:
- Channel Group
- DateHour
- Users
- Sessions
- New Users
- Engaged Sessions
- Average Engagement Time (s)
- Engagement Rate
- Event Count

---

## 🔍 Business Questions & Analysis

1. ❓ **What patterns or trends can you observe in website sessions and users over time?**
   - We analyze time-series trends to detect spikes, drops, or seasonal behavior in traffic.

2. 📈 **Which marketing channel brought the highest number of users to the website? How can you use this insight to improve traffic from other sources?**
   - "Organic Social" has brought the highest number of users to the website. Identifying top-performing acquisition channels helps allocate marketing budget effectively.

3. ⏱️ **Which channel has the highest average engagement time? What does that tell us about user behaviour and content effectiveness?**
   - "Organic Video" has the highest average engagement time. Understanding which channels result in longer user engagement reveals content effectiveness and audience relevance.

4. 📊 **How does engagement rate vary across different traffic channels?**
   - Comparing engagement rates helps identify which sources deliver more qualified traffic.

5. 💡 **Which channels are driving more engaged sessions compared to non-engaged ones? What strategies can improve engagement in underperforming channels?**
   - "Organic Social" channel drives more engaged sessions compared to non-engaged ones. Evaluating the quality of traffic by measuring how often users actively interact with the site.

6. 🕒 **At which hours of the day does each channel drive the most traffic?**
   - Time-based channel analysis aids in optimizing content scheduling and campaign timing.
   - Based on the heatmap titled “Traffic by Hour and Channel” from your notebook screenshot, we can identify the hours of peak traffic for each channel group. Here's a summary of when each channel drives the most traffic:

### 🔍 Peak Traffic by Channel:

| Channel Group  | Peak Hour(s) of Day                      | Observations                                                                                                                      |
| -------------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------|
| Direct         | 23:00 (2581 sessions)                    | Late night is the busiest time for direct traffic, showing strong user intent.                                                    |
| Email          | 17:00–20:00 (max around 9 sessions)      | Email traffic remains consistently low throughout the day.                                                                        |
| Organic Search | 18:00–21:00 (around 1884–1900+ sessions) | Users are actively searching in the evening hours.                                                                                |
| Organic Social | 18:00–20:00 (3400+ sessions)             | This channel has the highest peak traffic during evening hours, indicating strong engagement with social platforms post-work |hours. 
| Organic Video  | 18:00–20:00 (up to \~1400+ sessions)     | Engagement through video rises significantly during the evening.                                                                  |
| Referral       | 14:00–18:00 (up to \~1700+ sessions)     | Referral traffic peaks slightly earlier than organic channels.                                                                    |
| Unassigned     | 17:00–20:00 (peak 34 sessions)           | Small in volume, but still peaks in the evening.                                                                                  

### ⏰ Insights:

* Most traffic across all channels spikes between 17:00 and 21:00.
* Organic Social and Organic Search are the most dominant sources during peak hours.
* Direct traffic stays strong even late into the night (23:00), suggesting brand-aware or returning users.

7. 🔄 **Is there any correlation between high traffic (sessions) and high engagement rate over time?**
   - Understanding this relationship helps improve content and landing pages for high-traffic periods.
   - There appears to be little to no direct correlation between spikes in sessions (blue line) and increases in engagement rate (green line).

---

## ⚙️ Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Visualizations using Matplotlib & Seaborn
4. Insights and Strategic Recommendations

---

## 📌 Tools & Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Key Outcomes

- Identified top-performing marketing channels by users and sessions.
- Analyzed engagement metrics to uncover areas of improvement.
- Recommended strategies to boost performance in underperforming channels.

---

## 🧠 Conclusion

Understanding user behavior and channel effectiveness is key to optimizing website performance. Through this project, we provide data-driven insights to support strategic digital marketing decisions and improve user engagement across digital platforms.

---
