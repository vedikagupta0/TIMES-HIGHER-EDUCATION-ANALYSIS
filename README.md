# 🎓 World University Rankings Analysis

**Dataset:** Times Higher Education (THE) World University Rankings  
**Scope:** 2,191 institutions across 90+ countries  
**Goal:** Identify patterns in global higher education performance and provide strategic insights for institutions and policymakers.

---

## 📋 Analysis Outline

| # | Section | What we answer |
|---|---------|----------------|
| 1 | Setup & Data Loading | Libraries, theme, and raw data |
| 2 | Data Cleaning & Preprocessing | Handling nulls, type-casting, and range score resolution |
| 3 | Country-Level Distribution | Which countries dominate the rankings by volume? |
| 4 | Overall Score Analysis by Country | Which countries score highest and most consistently? |
| 5 | Score Breakdown by Metric | Radar profiles (teaching, research, citations, etc.) |
| 6 | Student Population & Staff Ratio | How institution size and staffing relate to performance |
| 7 | Correlation Analysis | Identifying key factors influencing overall rankings |
| 8 | International Outlook vs Performance | The impact of global integration on rankings |
| 9 | Key Findings & Recommendations | Strategic takeaways for stakeholders |

---

## Key Findings

### Top Countries Overview
* **Dominance:** The United Kingdom and the United States hold the majority of top-ranking universities.
* **Volume vs. Quality:** Countries like the US, India, and Japan are top contributors by volume, but a high number of ranked institutions does not guarantee strong average performance across all metrics.
* **The Singapore Model:** Singapore demonstrates a highly optimized and globally integrated system. Both of its ranked universities perform consistently well across all five scoring dimensions with low score variation.
* **Systemic Inequality:** US and UK universities show a significant spread between their best and worst performers, suggesting internal systemic inequality.

### Who Influences What? (Correlation Analysis)
* **Research & Teaching:** High teaching performance almost always coexists with strong research output.
* **International Outlook:** Higher international student presence strongly aligns with better international outlook scores.
* **Staffing:** Higher student-to-staff ratios are associated with reduced teaching quality due to resource strain.

---

## Recommendations

1. **Focus on Existing Institutions:** Efforts should be prioritized toward upgrading the performance scores of pre-existing universities to help them grow and upskill students.
2. **Student Intake Management:** Defining upper limits on student intake can help prevent quality dilution as institutions grow.
3. **Internationalization:** Actively recruiting international students and faculty is not just a diversity initiative; it has a measurable impact on overall performance.
4. **Resource Allocation:** Reducing the student-to-staff ratio is one of the most actionable levers available to improve teaching scores and overall rankings.
5. **Depth over Breadth:** Maintaining a smaller, elite set of universities with strong international outlook and concentrated research investment is a replicable model for prioritizing depth.

---

## 🛠 Methodology

* **Data Preprocessing:** Cleaned 2,191 records by removing metadata, normalizing numeric strings (e.g., student counts), and converting range scores (e.g., "56.4-58.6") to midpoints.
* **Data Standardization:** Regrouped metrics into logical tiers (identity, scores, stats, dimensions) for consistent analysis.
* **Visualizations:** Utilized bar, range-scatter, radar, histogram, scatter, and heatmap charts to surface patterns.
