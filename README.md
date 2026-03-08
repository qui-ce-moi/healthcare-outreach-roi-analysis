# 🏥 Healthcare Tele-Nursing Data Analysis: Impact of Outbound Calls on Patient Screening Rates

## 📖 Project Overview 
Preventive health screenings are critical for early diagnosis and better patient outcomes. However, many patients fail to schedule or attend their required screenings naturally. 

This data analysis project investigates the **return on investment (ROI) and overall effectiveness of an Outbound Call Nursing Team**. By proactively reaching out to patients, we aimed to measure whether a simple phone call intervention significantly increases the likelihood of patients completing necessary health screenings (such as Colonoscopy, Blood Pressure, Breast Cancer Screening, etc.) compared to the natural compliance rate of uncalled patients.

Ultimately, this analysis helps healthcare management and clinic directors to:
* **Target the right patients:** Identify which patient groups need reminders the most.
* **Optimize resources:** Focus nurse call campaigns on the screening types that yield the highest conversion rates.
* **Improve preventive care:** Drive higher completion rates for critical health checks.

## 📊 Key Business Insights & Findings
Our dual-axis analysis and comparative A/B style compliance tracking revealed the following core insights:
1. **Patient Reachability & Conversion:** Quantified the exact number of successful distinct patient engagements out of the total dialed pool.
2. **Compliance vs. Task Load:** Patients with only 1 or 2 required screenings naturally showed higher adherence. However, as the "task load" (required number of screenings) increased, compliance rates fluctuated, highlighting the exact threshold where patients feel overwhelmed and require nurse guidance.
3. **ROI by Screening Type:** By comparing the **Grey Bars (Natural Compliance)** vs. **Red Bars (Post-Intervention Compliance)**, we isolated the true added value of the nursing team. Specifically, the data showed which screening campaigns (e.g., COL vs. OMW) benefited the most from direct human intervention.

## 🛠️ Tech Stack & Methodology
* **Language:** Python
* **Libraries:** `pandas`, `numpy` (for heavy data manipulation and cleaning), `matplotlib`, `seaborn` (for data visualization)
* **Data Processing Steps:**
  * Strict deduplication of patient call logs to avoid overcounting.
  * Handling invalid screening types and standardizing binary (1/0) indicators for call success and completion.
  * Temporal analysis using `datetime` to track the time difference between the call date and the actual screening date.

## 🚀 How to Run the Notebook
*(Yazılım bilmeyenler veya projeyi incelemek isteyen iş analistleri için kısa açıklama: Bu proje Jupyter Notebook üzerinde çalışmaktadır ve analiz adımlarını görsel grafiklerle adım adım anlatmaktadır.)*

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tele-nursing-compliance-analysis.git
