# LSE_NHS_Diagnostic_Analysis_using_Python
LSE Data Analytics Career Accelerator  Program Course 2: Data Analytics using Python

For Assignment 2 we were given a huge NHS database of GP appointments to analyse using Python. A link to my ipynb file is included here, followed by a summary of my analysis, insights and recommendations.

Context

This is a story of digital disruption. The covid-19 pandemic not only took 205,540 lives and infected 24,315,983 people in the UK (United Kingdom COVID - Coronavirus Statistics, n.d.), it was a catalyst for digital disruption across a whole range of industries, including healthcare. This report explores evidence of changes to the provision of GP services in England from January 2020 to June 2022, and recommends options for the NHS to improve efficient use of its services in the future.

Business objective: to improve efficient use of GP services.

My analytical approach was to carefully import and explore the data so that I could get my head around what questions could be answered with it. I created a csv file of NHS names for regions and ICB locations so I could merge and use these with all the DataFrames (NHS England Names and Codes, 2022). I found 21,604 duplicates in the appointments_regional DataFrame, and decided to remove them, creating an ar_clean DataFrame.

The next steps (Parts 2 and 3) involved establishing time frames for all three DataFrames, and exploring which variables might be important in later analyses. I decided the ar DataFrame would be the most fruitful, as it covers a 30 month period that spanned the covid-19 pandemic in the UK, from January 2020 to June 2022.

In Part 4 I identified seasonal trends. I used the nc DataFrame to explore daily trends, and the ar DataFrame to explore monthly trends. I also looked at regional differences and most of my analyses involved grouping data by one or more variables to count the total number of appointments under different scenarios. Finally I looked at resource utilisation using the 1.2 million appointments a day figure given in the Week 6 assignment.

I also carried out the Twitter analysis using the data provided, but decided against exploring this further as it was not directly relevant to my area of focus.

Please find the 'erdi_ozyurt (AutoRecovered).pdf' for more information.
