## DSB Capstone
**Project Title: Irregular Migration Across the Western Balkan Route: The Case of Montenegro (2016–2026)**

This project provides a comprehensive data science approach to understanding irregular migration dynamics along the southern branch of the Western Balkan route, with a specific focus on Montenegro as a one of the key transit hub to the Europan Union. Utilizing public datasets from the International Organization for Migration (IOM) DTM - Datasets: 
1)Europe — Mixed Migration Flows to Europe, Quarterly Overview (April - June 2026) 
2)Europe — Mixed Migration Flows to Europe, Quarterly Overview (January - March 2026)
The project builds an end-to-end data pipeline. 
The workflow encompasses data ingestion, exploratory data analysis (EDA) using Pandas, Seaborn, and Matplotlib, and predictive modeling. 

**DataSets 1 = 'im1'**
I downloaded the dataset from the official UN International Organization for Migration (IOM) website - link: https://dtm.iom.int/global-overview-of-migration-routes-portal/eastern-mediterranean-and-western-balkans.
The dataset contains data related to the Eastern Mediterranean Route (EMR) and Western Balkan (WBR) - encompasses land and sea migration flows to Greece, Cyprus, and Bulgaria, predominantly departing from Türkiye, with Libya emerging more recently as a key departure point. Past trends also show migrants departing to a lesser extent from Lebanon and the Syrian Arab Republic (hereafter Syria). This route is primarily travelled by people from Afghanistan, Sudan, Egypt, Bangladesh, Syria, Iraq, Somalia, Yemen and Eritrea fleeing wars, political instability, economic hardship, and restrictive asylum policies in neighbouring countries.
Source of data which are in the datasets are official data from - DTM Europe from national authorities: Albania, Bosnia and Hercegovina, Croatia, Romania, North Macedonia, Montenegro, Kosovo, Slovenia, Serbia.
wich have 9 but I will fokus on 5 main sheets
This datasets have 9 sheets: 'About','Summary','First_Arrival_Countries_Monthly','Other_Countries_Areas_Monthly','First_Arrival_Countries_CoO','Others_Countries_CoO','All_Migrant_Presence','Sources','ISO3'. My fokus will be on 5 sheets: 'First_Arrival_Countries_Monthly','Other_Countries_Areas_Monthly','First_Arrival_Countries_CoO','Others_Countries_CoO','All_Migrant_Presence', which I will investigate and analyze in detail in order to see what and how to implement in order to answer my Data question - Predict the number of migrants who could potentially come to Europe - Montenegro in the coming period.

**Data type** is text / numerical.

**DS problem** is Regression, because I want to make prediction of illegal migration arrivals in the EU / Montenegro.

**The Problem at Hand**

Unregulated mixed migration flows through the Western Balkan route pose critical security, humanitarian and border management challenges. In Q1 2026, despite a 38% drop in overall regional arrivals, security risks escalated. Smugglers used deadlier tactics, causing over 990 Mediterranean fatalities. Montenegro faces high transit pressure, primarily handling vulnerable sudden influxes from conflict zones like Sudan (71% of local arrivals) and Egypt.

**The Solution**

A data-driven monitoring repository that structures and visualizes IOM Displacement Tracking Matrix (DTM) intelligence. This project processes raw transit data from key Montenegrin checkpoints (such as Božaj, Rožaje, and Pljevlja). By automating trends analysis and demographic profiling, it provides actionable insights into migrant routes security challenges, immediate humanitarian needs, and shifting nationalities.

**Potential Impact**

• Optimized resource allocation and faster security and humanitarian response at Montenegrin reception centers.
• Predictive tracking of shifting migrant patterns across the broader Western Balkan route.

**Where am I now**

So far I have downloaded data sets, checked source validation, and through data manipulation and EDA familiarized myself with the data.
I plotted some data, in order to see the trends and now I am trying to concretize my activities on the conception of concrete actions syntax that would help me to get the answer to my DataScience question.
