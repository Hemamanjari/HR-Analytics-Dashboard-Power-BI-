# HR-Analytics-Dashboard-Power-BI
End-to-end Power BI HR Analytics Dashboard — Turning raw HR data into actionable business insights through DAX, data modeling, and visualization storytelling.

Project Objective
To build an interactive HR Analytics dashboard that provides actionable insights into workforce composition, salary distribution, gender diversity, and employee trends — enabling HR teams to make data-driven decisions in hiring, retention, and compensation management.

                              Business Problem
                The HR department lacked a consolidated view of:
                          •	Headcount and gender distribution across departments
                          •	Salary variations by job title and qualification
                          •	Workforce demographics (age, experience, education)
                          •	Hiring trends and leave patterns
The goal was to design a self-service BI dashboard to replace static reports and improve HR’s ability to analyze workforce trends dynamically.


          Key DAX Measures Created
                        Measure	                                            Description
                Total Headcount	                                    Count of employees
                Avg Salary	                                        Average salary per job title or department
                Min Salary / Max Salary	                            Range analysis per role
                Salary Range = [Max Salary] - [Min Salary]	        Salary gap per role
                Avg Leave Balance	                                  Mean leave days per employee
                Cumulative Headcount	                              Workforce growth trend by date of joining

                          Dashboard Insights
    The Power BI dashboard includes:
                        •	Headcount by Job Title: Identifies the most staffed roles (e.g., Packaging Associate, Production Operator).
                        •	Gender Distribution: Balanced workforce with ~55% female and ~45% male representation.
                        •	Salary Overview:
                        o	Highest average salary — Product Managers & Research Scientists
                        o	Lowest average salary — Packaging Associates
                        •	Age Demographics: Majority of employees between 25–40 years old.
                        •	Qualification vs Salary: Higher education (Master’s Degree) correlates with higher pay.
                        •	Hiring Trend: Consistent growth in workforce from 2018–2023.
                        •	Leave Balance Analysis: Most roles maintain 15–18 average leave days.

                          Key Actions Taken
      1.	Data Cleaning & Preparation
                      o	Handled nulls, removed duplicates, standardized date & salary formats.
                      o	Ensured proper column data types and consistency.
      2.	Data Modeling
                      o	Created a star schema with fact and dimension tables.
                      o	Defined relationships and built calculated columns for job titles, salary categories, and tenure.
      3.	DAX Measures & KPIs
                      o	Designed reusable measures for min/max/avg salaries, headcount, and trends.
                      o	Ensured responsiveness to filters (job title, gender, qualification).
      4.	Dashboard Design & Storytelling
                      o	Applied a clean, consistent layout with intuitive visuals.
                      o	Added slicers and cards for dynamic filtering.
                      o	Focused on insight-first visualization, not just data display.
      5.	Validation & Testing
                      o	Cross-checked salary calculations and headcount totals.
                      o	Tested dashboard under different filters for accuracy and performance.

                        Key Takeaways
                •	Learned to design context-aware DAX measures for flexible analytics.
                •	Strengthened understanding of data modeling and visualization storytelling.
                •	Enhanced ability to turn raw data into executive-level insights.
                •	Reinforced the link between HR data and strategic decision-making.

                        Impact
                •	Empowered HR teams to explore workforce trends without manual reporting.
                •	Improved decision-making by making key HR metrics visible and comparable.
                •	Demonstrated how analytics can bridge HR operations and strategic planning.
               

