# 🌍 Global Sustainable Energy Analytics (2000–2020)

**Microsoft Elevate – AICTE Internship Capstone Project** *Built by Hridesh Maithani*

Welcome to my project repository! This dashboard is the culmination of my 4-week internship. As a BCA student specializing in Data Science and Machine Learning, I wanted to build a tool that doesn't just display numbers, but actually uncovers the hidden story of how our world is transitioning to green energy.

![Dashboard Preview](Insert_Link_To_A_Screenshot_Of_Your_Dashboard_Here.png)

## ❓ The Problem

If you look at raw global energy data from the last 20 years, it’s honestly a mess. The data is massive, fragmented, and hard to interpret. We all know the world needs to "go green," but it’s incredibly difficult to see the exact relationship between a country’s economic wealth (GDP), its population, and its actual progress in adopting renewable energy. 

Without a clear way to visualize these connections, it's almost impossible to see which sustainability policies are actually working.

## 💡 The Solution: A Data-Driven Command Center

I built an end-to-end interactive Business Intelligence dashboard in Power BI. Instead of static charts, this acts as an analytical "Command Center" where users can:
* **Travel through time:** Watch the energy mix shift year by year from 2000 to 2020.
* **Correlate Wealth and Sustainability:** Instantly see if richer countries are actually greener.
* **Drill Down into Emissions:** Start from the global CO2 total and click down to see exactly which regions and nations are the biggest contributors.

## 🛠️ The Tech Stack (Under the Hood)

* **Tool:** Microsoft Power BI Desktop
* **Data Processing (ETL):** Power Query (Handled missing values, normalized data types, and cleaned financial flow metrics).
* **Data Modeling:** Built a highly optimized **Star Schema** with a central Fact Table connected to dedicated Geography and Date dimension tables.
* **Calculations:** Custom DAX measures for dynamic aggregations and year-over-year comparisons.
* **UI/UX Design:** Designed with a modern **"Glassmorphism"** theme (dark backgrounds, glowing accent borders, and custom page navigation) to make it feel like a premium software application.

## 🧠 AI & Advanced Analytics

I wanted to push beyond basic reporting, so I integrated Power BI's built-in Machine Learning visuals:
1. **Key Influencers:** AI-driven analysis that discovered GDP and population density are the strongest predictors of a country's renewable energy capacity.
2. **Decomposition Tree:** A root-cause analysis tool that lets users dynamically break down global emission totals.
3. **Smart Narrative:** Automated natural language summaries that write out key findings in plain English based on the filtered data.

## 📊 Key Discoveries

After building and analyzing the dashboard, a few major insights stood out:
* **The 2010 Acceleration:** There was a massive spike in green energy adoption starting around 2010, heavily driven by falling tech costs.
* **The "Leapfrogging" Effect:** While there is a strong link between high GDP and renewables, several developing nations are successfully "leapfrogging" traditional fossil fuel grids and going straight to solar/wind.
* **The Efficiency Gap:** We are producing more green power than ever, but global "Energy Intensity" remains high. This shows we need to focus on using power more efficiently, not just generating it cleanly.

## 🚀 Future Scope (IoT & Predictive ML)

This project currently looks at historical data, but the next phase is taking it into the future:
* **Real-Time IoT Integration:** I plan to connect this dashboard to live IoT sensors on solar grids via Azure IoT Hub, moving from annual reporting to real-time monitoring.
* **Predictive Analytics:** Integrating Python/Machine Learning models directly into Power BI to forecast energy trends for 2030 (aligning with UN Sustainable Development Goals).

## 📂 How to Use This Repository

1. Clone the repository or download the `.zip` file.
2. Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
3. Open the `renuble energy.pbix` file.
4. The cleaned raw dataset is also available in the repository as a CSV file if you want to inspect the data model.

## 📚 References
* **Dataset:** Global Data on Sustainable Energy (2000-2020) via Kaggle & The World Bank.
* **Documentation:** Microsoft Power BI & DAX Reference Guide.
* **Framework:** UN Sustainable Development Goal 7 (Affordable and Clean Energy).

---
*If you have any questions or feedback about the data model or the UI design, feel free to reach out or open an issue!*