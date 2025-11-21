📊 **NYC Transportation Project**


📘 **Project Overview** 

This project analyzes New York City’s bus transportation performance by exploring delay times, day-of-week travel patterns, and common causes of delays or breakdowns. The dataset, split into multiple sheets, provides insights into how bus companies perform across boroughs, how travel demand fluctuates throughout the week, and which operational issues most frequently disrupt service.
The goal is to transform these raw tables into actionable insights that support data-driven decision-making for improving service reliability and customer satisfaction.

🧩 **Business Problem** 

NYC’s bus network faces consistent challenges involving delays, breakdowns, and uneven performance across boroughs and time periods. These issues directly impact:

- Passenger satisfaction
- Operational efficiency
- Cost management
- Service reliability and scheduling


💻 **Tech Stack** 

- Microsoft Excel

**Data Cleaning and Transformation:** 

- Broke a full date column by the =WEEKDAY formula.
- Data Normalization.
- Splitted data into multiple columns.
- Deleted outliers rom the dataset (dates of 1900).
- Created Pivot Tables and Pivot Charts.

**1. What are the most common reasons for delays and breakdowns?** 

Graph used: Clustered Bar
- Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:

- **Breakdown:**
The majority of breakdowns are occuring due to Mechanical Problems or "Wont Start" which also 
seems to be a mechanical problem.
Recommendation: More precautionary maintenance done to prevent mechanical problems. Potentially 
have buses serviced monthly or quarterly to reduce this.

- **Reasons for Delay:**
Overwhelmingly, the main cause of delays is traffic.
Potential Solution: Have buses pick up majority of students at non-high traffic times.
Note: There are almost 14k delays due to Mechanical issues. This could be resolved with
the plan for breakdowns in servicing the vehicles regularly.

**2. How do delay times vary by bus company and borough?** 

Graph used: Clustered Bar
- Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:

- **Largest Delay Times for Bus Companies:**
There are the top 10 companies with the highest delay times.
Recommendation: Use this to compare to # of delays, boros, and total number of trips.
Could be mechanical issues - fix with regular maintenance OR we need to fire them.

- **Longest Delay Times Per Boro:**
The boros with the highest delay times are the main areas of NYC. These are the areas with the
highest concentration of people and vehicles  which would account for the longer delays.
Conclusion: This is accurate to what I would have hypothesized.

**3. Is there a correlation between specific days of the week and the frequency of breakdowns or delays?** 

Graph used: Line Charts
- Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:

- **Running Late:**
Spike in Delays on Monday and a decrease in delays on Fridays.
Conclusion: Since the majority of delays are caused by traffic, we can assume the decrease in delays
on Friday are caused by less people going into work or driving on that day.

- **Breakdown:**
There is a gradual decrease in breakdowns throughout the week. Higher percentage of breakdowns 
happening on Monday and decreases throughout the week.
Recommendation: Schedule Maintenance over weekends to help with breakdowns.

--------------------------------------------------------------------------------------------------------------------------

📊 **US Debt Tracker Project** DONE

📘 **Project Overview** DONE

The US Debt Tracker Project is designed to analyze, monitor, and forecast the growth of the United States national debt. Using multiple datasets containing historical monthly values, yearly percentage changes, and projected future trends, this project provides a structured analytical framework to understand how federal debt evolves over time.
The purpose of the project is to transform raw economic data into meaningful insights that highlight long-term financial risks, growth patterns, and key inflection points. By combining descriptive analytics with forward-looking projections, the project supports data-driven decision-making for analysts, financial agencies, and policy researchers.

🧩 **Business Problem** DONE

The United States’ national debt continues to rise, creating significant long-term challenges related to federal budgeting, inflation management, interest obligations, and economic stability.

The business problem this project addresses is:
“How can we better understand, monitor, and forecast U.S. debt growth to support transparent financial planning and risk assessment?”

To solve this, the project focuses on answering core analytical questions:

**1. What was the Yearly Debt Percentage Increase for each year compared to the previous year?** DONE
   
- The Yearly Debt Percentage Increase will show how fast the total U.S. debt has grown from one year to the next. Typically, national debt increases most years, often ranging from 2% to 10% annually, depending on economic conditions, federal spending, and major events. The final dataset will show the exact percentage increase for each individual year.

**2. Which months historically have seen the highest/lowest increases in Total debt?** DONE
   
- Some months tend to show larger increases in debt due to seasonal spending patterns (e.g., fiscal year boundaries, stimulus disbursements, or budget cycles).
The highest-increase months are often tied to periods of higher federal budget activity, while the lowest-increase months may reflect periods of reduced spending or stabilizing debt accumulation. Exact monthly trends will be identified once the dataset is analyzed.

**3. What is the projected growth of the publicly held debt in the next few years?** DONE

- The projected growth will depend on the model used in the dataset. Generally, U.S. publicly held debt is expected to continue rising each year, often at a steady or accelerating pace depending on economic forecasts. The projection sheet in the dataset will provide the specific forecasted values over the next several years.

💻 **Tech Stack** DONE

- Microsoft Excel

**Data Cleaning and Transformation:** DONE

- Deleted BLANKS and NULL values.
- Applied Data Formats from Scientific to Number
- Added Puntuation
  


**1. What was the Yearly Debt Percentage Increase for each year compared to the previous year?**

Graph used: Line Charts, Yearly Debt Percentage Increase.
- Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:
  
- Overall Trends and Key Observations
Across all three debt categories, the chart shows relatively steady, moderate growth from 2016 to 2019, followed by:
A massive spike in 2020. This corresponds to the economic impact of COVID-19 stimulus spending, emergency federal programs, large-scale borrowing to stabilize the economy, then a sharp decline in growth in 2021 and 2022, returning closer to pre-pandemic levels.

- Debt Held by the Public (Blue Line)
  
This category shows the most volatility and the largest spike in 2020. 
From 2016–2019 it was moderate, steady increases, generally ranges between 5%–10% annual growth, suggests normal federal borrowing patterns. 
In 2020 we see a dramatic surge (~25–30%) with the highest point on the entire graph, this reflects unprecedented borrowing during the pandemic; indicates heavy reliance on public investors, Treasury bonds, and external financing.
2021–2022 we see a sharp correction downward growth falls back to around 5%, similar to pre-pandemic levels. This indicates emergency borrowing slowed significantly once the crisis passed.

Interpretation:
Debt held by the public expanded aggressively during crisis conditions, then stabilized. This category was the primary driver of total debt growth.

- Intragovernmental Holdings (Orange Line)

This line is much flatter and does not show dramatic spikes.
Consistent, low growth (2016–2019) and  slight increases each year. Represents internal borrowing between government agencies (e.g., Social Security Trust Fund, Medicare).
In 2020 Uptick we see a noticeable increase but not nearly as dramatic as public debt, this suggests some internal borrowing adjustments due to economic pressures.
In 2021–2022 returns to normal. We see growth stabilizes back to low levels, this indicates intragovernmental transfers did not drive total borrowing.

Interpretation:
Intragovernmental debt behaves more steadily because it is tied to trust fund operations, not market borrowing. It is less sensitive to economic shocks.

- Total Public Debt Outstanding (Gray Line)

This line combines the previous two categories and reflects the overall national debt growth rate.
In 2016–2019 we see a gradual upward trend that slightly increasing year-to-year. This indicates steady borrowing as part of routine fiscal operations.
In 2020 we see a pronounced spike (Mirrors the public debt surge). Total debt growth jumps significantly higher than any other year (Confirms 2020 as an exceptional event in fiscal history).
In 2021–2022 we see a sharp return to moderate growth. Quickly falls back down toward ~5% this shows stabilization after emergency spending phases ended.

Interpretation:
The total debt pattern is heavily driven by the public debt spike. The system corrected itself once fiscal pressures eased.

**Final Summary**

The graph shows that:

- Debt growth was modest and stable from 2016–2019.

- 2020 produced an unprecedented spike, driven almost entirely by Debt Held by the Public.

- Intragovernmental debt remains the most stable, least volatile component.

- Total debt growth mirrors public borrowing behavior.

- By 2021–2022, debt growth returns to near-normal levels, but the long-term upward trend persists.


**2. Which months historically have seen the highest/lowest increases in Total debt?**
**3. What is the projected growth of the publicly held debt in the next few years?**
















