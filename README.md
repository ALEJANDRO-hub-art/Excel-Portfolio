📘 **Project Overview** DONE

This project analyzes New York City’s bus transportation performance by exploring delay times, day-of-week travel patterns, and common causes of delays or breakdowns. The dataset, split into multiple sheets, provides insights into how bus companies perform across boroughs, how travel demand fluctuates throughout the week, and which operational issues most frequently disrupt service.
The goal is to transform these raw tables into actionable insights that support data-driven decision-making for improving service reliability and customer satisfaction.

🧩 **Business Problem** DONE

NYC’s bus network faces consistent challenges involving delays, breakdowns, and uneven performance across boroughs and time periods. These issues directly impact:

- Passenger satisfaction
- Operational efficiency
- Cost management
- Service reliability and scheduling


💻 **Tech Stack** DONE

- Microsoft Excel

**Data Cleaning and Transformation:** DONE

- Broke a full date column by the =WEEKDAY formula.
- Data Normalization.
- Splitted data into multiple columns.
- Deleted outliers rom the dataset (dates of 1900).
- Created Pivot Tables and Pivot Charts.

**1. What are the most common reasons for delays and breakdowns?** DONE

Graph used: Clustered Bar
Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:

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

**2. How do delay times vary by bus company and borough?** DONE

Graph used: Clustered Bar
Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:

Largest Delay Times for Bus Companies:
There are the top 10 companies with the highest delay times.
Recommendation: Use this to compare to # of delays, boros, and total number of trips.
Could be mechanical issues - fix with regular maintenance OR we need to fire them.

Longest Delay Times Per Boro:
The boros with the highest delay times are the main areas of NYC. These are the areas with the
highest concentration of people and vehicles  which would account for the longer delays.
Conclusion: This is accurate to what I would have hypothesized.

**3. Is there a correlation between specific days of the week and the frequency of breakdowns or delays?** DONE

Graph used: Line Charts
Based on the Pivot Tables and the Pivot Charts for this question our findings were the following:

Running Late:
Spike in Delays on Monday and a decrease in delays on Fridays.
Conclusion: Since the majority of delays are caused by traffic, we can assume the decrease in delays
on Friday are caused by less people going into work or driving on that day

Breakdown:
There is a gradual decrease in breakdowns throughout the week. Higher percentage of breakdowns 
happening on Monday and decreases throughout the week.
Recommendation: Schedule Maintenance over weekends to help with breakdowns.


