# spartan-race-social-media-analytics
Social Media Performance &amp; Content Optimization Case Study analyzing 393 Facebook posts to improve content format mix, posting schedule, and audience engagement.
# Spartan Race: Social Media Performance & Content Optimization

> **📌 Note:** This case study analyzes historical Facebook page performance metrics (**393 posts across 17 variables**) to identify content characteristics associated with stronger audience engagement and propose a data-driven content strategy.

---

## 1. Business Context & Problem Statement

While Spartan Race maintains an established presence on Facebook, post-level engagement fluctuates significantly across formats, topics, and publishing schedules. 

* **Core Business Question:** *How can Spartan Race optimize content formats, thematic pillars, and posting schedules to drive higher, more meaningful audience engagement?*
* **Objective:** Move beyond volume-driven publishing by uncovering engagement patterns, investigating top-performing viral outliers, and translating analytical findings into a structured A/B testing and KPI tracking framework.

---

## 2. Dataset & Analytical Framework

### 2.1. Dataset Overview
* **Scope:** 393 Facebook posts tracked across 17 variables.
* **Core Metrics:** `Reactions`, `Comments`, `Shares`, `Total Engagement`, and format-specific engagement ratios (`Reaction Ratio`, `Comment Ratio`, `Share Ratio`).
* **Dimensions:** `Post Type` (*Video, Photo, Link, Event, Status*), `Content Pillar` (*6 thematic categories*), `Posting Day`, and `Posting Time` (*Morning, Afternoon, Evening, Late Night*).

### 2.2. Analytical Methodology
1. **Performance Baseline:** Evaluated overall averages (`764.67` avg. engagement/post) alongside **Median Engagement** to establish a resilient baseline unaffected by extreme viral spikes.
2. **Dimensional Comparison & Outlier Handling:** Analyzed post volume versus engagement efficiency across formats, schedules, and content pillars. **8 extreme viral outliers** were excluded during day-of-week and pillar comparisons to prevent skewed averages.
3. **Outlier Investigation:** Conducted qualitative content teardowns on top-performing Video and Photo outliers to identify shared narrative drivers.
4. **Actionable Recommendations & KPI Governance:** Designed a pilot testing roadmap and a recurring weekly/monthly KPI tracking structure.

---

## 3. Key Findings & Strategic Recommendations

### Finding 1: Content Format Mismatch (`Volume ≠ Engagement`)
* **Observation:** Videos dominate publishing volume (**50%** of all posts, 195 posts), yet Photos (**40%**, 156 posts) outperform Videos in both **Median Engagement (`562` vs. `454`)** and **Average Engagement (`944.6` vs. `733.7`)**. Meanwhile, Status posts represent only **1%** of volume (2 posts) but exhibit the highest discussion intensity (**38% Comment Ratio**).
* **Recommendation:** Rebalance the format mix by scaling high-performing Photo narratives and running controlled **A/B tests on Status posts** to validate whether text-driven prompts can deepen community discussion at lower production cost.

### Finding 2: Posting Schedule Misalignment
* **Observation:** Publishing peaks mid-week (**Wednesday–Friday**, led by Thursday with 75 posts) and during afternoon/evening hours. However, audience engagement peaks on **weekends (Saturday avg. `848`, Sunday avg. `771`)** and during three specific daily windows: **7:00 AM (`1,465` avg.)**, **12:00 PM (`1,215` avg.)**, and **1:00 AM (`1,679` avg.)**.
* **Recommendation:** Shift posting slots from saturated mid-week afternoons toward high-engagement weekend windows and test scheduled releases at the 7:00 AM, 12:00 PM, and late-night slots against historical baselines.

### Finding 3: Content Pillar & Narrative Drivers
* **Observation:** Race/competition updates account for **83%** of total posts (*56% Race Experience & Course Challenges*, *27% Spartan Championship & Competitions*). Conversely, **Community & Spartan Culture** represents only **6%** of volume but achieves the highest non-outlier average engagement (**`718` engagements/post**). Qualitative analysis of top outliers confirms that **human-centered, emotion-driven stories** (overcoming adversity, race-day proposals, record-breaking feats) consistently outperform purely promotional posts.
* **Recommendation:** Reallocate editorial bandwidth from routine race announcements toward human-centered storytelling—spotlighting community camaraderie, athlete journeys, and coaching insights.

---

## 4. Proposed KPI Tracking Framework

To measure execution impact post-optimization, a recurring Weekly/Monthly Tracker is proposed with format-aligned KPIs:
* **Primary KPI:** `Average Total Engagement per Post` segmented by format (*Photo, Video, Status, Link, Event*).
* **Format-Specific Secondary KPIs:**
  * *Photo & Video:* `Reactions` & `Reaction Ratio` (brand resonance & reach).
  * *Status:* `Comments` & `Comment Ratio` (community discussion depth).
  * *Link & Event:* `Reactions + Shares` (conversion & event amplification).

---

## 5. Repository Structure

```text
├── Spartan_Race_Case_Study.pdf   # Full 17-slide analytical presentation
└── README.md                     # Project summary, methodology & key findings
```
*(Note: Update this tree if raw dataset `.xlsx`/`.csv` or `.pbix` files are uploaded to the repository).*

---

## 6. Limitations & Next Steps

* **Small Sample Sizes in Niche Formats:** `Status` (2 posts) and `Event` (9 posts) have limited historical volume; directional insights require structured A/B testing before full-scale rollout.
* **Reach & Impression Data:** Analysis is based on public engagement interactions (`Reactions, Comments, Shares`); integrating organic reach, click-through rate (CTR), and paid boost flags from Meta Business Suite would further refine efficiency metrics.
