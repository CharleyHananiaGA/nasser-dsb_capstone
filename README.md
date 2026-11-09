## DSB CAPSTONE PROJECT
**Project Title: Irregular Migration Across the Western Balkan Route, impact on Montenegro and prediction of the number of illegal migrants by month in 2027**

This project provides a comprehensive data science approach to understanding irregular migration dynamics along the southern branch of the Western Balkan Route (WBR), with a specific focus on Montenegro as a one of the key transit hub to the Europan Union (EU). Utilizing public datasets from the International Organization for Migration (IOM) Displacement Tracking Matrix (DTM) - Dataset: 
1)Europe — Mixed Migration Flows to Europe, Quarterly Overview (April - June 2026).
The above database that I treat includes data for the period from 2016 and the first quarter of 2016.
The project builds an end-to-end data pipeline.
The workflow encompasses data ingestion, data manipulation, exploratory data analysis (EDA), and predictive modeling. 

**DataSets 1 = 'im1'**
I downloaded the dataset from the official UN International Organization for Migration (IOM) website - link: https://dtm.iom.int/global-overview-of-migration-routes-portal/eastern-mediterranean-and-western-balkans.
The dataset contains data related to several migrant routes: "Eastern Mediterranean Route = EMR", "Western African Atlantic Route = WAAR",
"Central Mediterranean Route = CMR", "Western Mediterranean Route = WMR". 
During my Capstone I will focused the on the EU Others rout what is = Eastern Mediterranean Route (EMR) and Western Balkan Route (WBR). The data show as encompasses land and sea migration flows to Greece, Cyprus, and Bulgaria, predominantly departing from Turkiye, with Libya emerging more recently as a key departure point. Past trends also show migrants departing to a lesser extent from Lebanon and the Syrian Arab Republic (hereafter Syria). This route is primarily travelled by people from Afghanistan, Sudan, Egypt, Bangladesh, Syria, Iraq, Somalia, Yemen and Eritrea fleeing wars, political instability, economic hardship, and restrictive asylum policies in neighboring countries.
Source of data which are in the datasets are official data from - DTM Europe from national authorities: Albania, Bosnia and Hercegovina, Croatia, Romania, North Macedonia, Montenegro, Kosovo, Slovenia, Serbia.
Datasets is in excel and have 9 but I will focus on 5 main sheets.
The names of the datasets 9 sheets are: 'About','Summary','First_Arrival_Countries_Monthly','Other_Countries_Areas_Monthly','First_Arrival_Countries_CoO','Others_Countries_CoO','All_Migrant_Presence','Sources','ISO3'. 
My focus will be on 5 sheets: 'First_Arrival_Countries_Monthly','Other_Countries_Areas_Monthly','First_Arrival_Countries_CoO','Others_Countries_CoO','All_Migrant_Presence', which I will investigate and analyze in detail in order to see what and how to implement in order to answer my Data question - Predict the number of migrants who could potentially come to Europe - Montenegro in the coming period - by months in 2027.

**Data type** is text / numerical.

**DS problem** is Linear Regression, because I want to make prediction of illegal migration arrivals in the EU / Montenegro months by months in 2027.

**The Problem at Hand**

Unregulated mixed migration flows through the Western Balkan route (WBR) pose critical security, humanitarian and border management challenges. In Q1 2026, despite a 38% drop in overall regional arrivals, security risks escalated. Smugglers used deadlier tactics, causing over 990 Mediterranean fatalities. Montenegro faces high transit pressure, primarily handling vulnerable sudden influxes from conflict zones like Sudan (71% of local arrivals).

**The Solution**

A data-driven monitoring repository that structures and visualizes IOM Displacement Tracking Matrix (DTM) intelligence. This project processes raw transit data from key Montenegrin checkpoints (such as Božaj, Rožaje, and Pljevlja). By automating trends analysis and demographic profiling, it provides actionable insights into migrant routes security challenges, immediate humanitarian needs, and shifting nationalities.

**Potential Impact**

• Optimized resource allocation and faster security and humanitarian response at Montenegrin reception centers.
• Predictive tracking of shifting migrant patterns across the country broader on the Western Balkan route.

**Where am I now**

So far I have downloaded data sets, checked source validation, and through data manipulation and EDA familiarized myself with the data.
I plotted some data, in order to see the trends and now I am trying to concretize my activities on the conception of concrete actions syntax that would help me to get the answer to my DataScience question.

**Next steps**
I will make several models where I will do a test and training to find the best model for prediction. I am going to us the Decision tree, Random forest, Clustering, In order to make as good prediction as possible for the potential number of illegal migrants per month in 2027.

