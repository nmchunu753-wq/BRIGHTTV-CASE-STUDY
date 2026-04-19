# BRIGHTTV-CASE-STUDY
BrightTv case study focusing on finding insights and cleaning data to get what is the reasons for things that are happening and insights and recommendations on how to fix problems.
***

# BrightTV Viewership Analysis: CVM Growth Strategy

## Project Overview
To view PDFs and pictures, they have to be downloaded.

## Project Overview
This project was developed for the **Customer Value Management (CVM)** team to assist the CEO in growing the BrightTV subscription base. By analyzing a sample of subscriber demographics and viewership patterns, this study identifies key factors influencing content consumption and provides strategic recommendations for market expansion.

## Tools Used
*   **SQL:** Data cleaning and table joining (FULL OUTER JOIN).
*   **Excel:** Initial analysis, pivot tables, and graphing.
*   **Miro:** Project flowchart and logic mapping.
*   **Excel:** Interactive dashboarding for stakeholder presentation.
*   **Canva and PowerPoint:** Final executive presentation.

## Data Processing & Methodology
*   **Data Integration:** A **FULL OUTER JOIN** was performed to merge `USERPROFILES` and `VIEWERSHIP` tables, resulting in a comprehensive dataset of **11,295 rows** representing **5,375 distinct users**.
*   **Timeframe:** The analysis covers data from **01 January 2016 to 01 April 2016**.
*   **Localization:** All timestamps were converted from UTC to **South African Standard Time (SAST)** to ensure viewership peaks accurately reflected local consumer behavior.
*   **Handling Nulls:** The analysis accounted for **1,049 viewers** with missing provincial data and **235 viewers** with unspecified racial data to maintain statistical integrity.

## Key Insights

### 1. Geographical Dominance
*   **Gauteng** is the primary market with **3,786 viewers**, largely due to its high population density of approximately 16 million people.
*   **Northern Cape** represents the smallest market segment with only **236 viewers**.

### 2. Demographic Trends
*   **Race:** The majority of the viewer base identifies as **Black (4,516 viewers)**.
*   **Age:** There is a clear **inverse correlation** between age and viewership; as age increases, TV consumption decreases.
*   **Adults vs. Teens:** While **Adults** lead consumption (4,991 views), **Teenagers** account for only **181 views**, likely because their viewing is restricted to weekends due to school commitments.

### 3. Temporal Viewing Patterns
*   **Monthly Volatility:** **March** saw a peak of **4,816 viewers** driven by high interest in sports content. Conversely, **April** saw a drastic decline to **5 viewers**, suggesting a massive shift toward digital/social media or outdoor activities during improved weather.
*   **Daily Peaks:** The **afternoon slot (3,734 viewers)** is the most active as students and workers return home to relax. 
*   **Late Night/Midnight:** Late night viewing is lowest (561) due to age-restricted content, while midnight viewing (1,295) is surprisingly high, attributed to night-shift workers and insomnia.

## Strategic Recommendations
*   **Digital Integration:** To combat the "April Slump," BrightTV should integrate digital and social media offerings to retain users who are moving away from traditional broadcast formats.
*   **Senior Engagement:** Develop "Senior-Friendly" content or interfaces (addressing weak eyesight) to stabilize the viewership decline in older demographics.
*   **Gauteng Expansion:** Focus marketing spend on Gauteng to capitalize on the existing high-density user base.
*   **Youth Weekend Blocks:** Curate high-impact content for teenagers on weekends to maximize their limited viewing windows.

## Repository Structure
*   `/Data`: Raw CSV viewership and profile data.
*   `/SQL`: `.sql` file containing the FULL OUTER JOIN and time conversion queries.
*   `/Analysis`: Excel files containing pivots and trend graphs.
*   `/Presentation`: Final PDF/PPT presentation and dashboard links.
*   `/Planning`: Miro flowchart and Project Gantt Chart.

*** 
**Author:** Andiswa Asanda Mchunu
