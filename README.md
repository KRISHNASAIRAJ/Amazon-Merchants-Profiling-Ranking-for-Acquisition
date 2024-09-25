# Amazon Merchants Profiling Ranking For Acquisition

* The goal of this analysis is to profile Amazon merchants and develop selection criteria to identify the most promising sellers for acquisition.

![image](https://github.com/user-attachments/assets/22797bbd-ab07-4d68-bdfd-7224c4f7d0f1)

## Introduction
The objective of this analysis is to identify promising Amazon sellers for acquisition by profiling and ranking them based on specific Key Performance Indicators (KPIs). Through a comprehensive data sanitization and analysis process, actionable insights are provided to assist the acquisitions team in targeting high-potential sellers.

## Dashboard Overview
### Dashboard 1: Amazon Sellers Dashboard | Overview
This dashboard presents key performance metrics of Amazon sellers, allowing for a holistic view of their business activities. The metrics displayed are:

* Total Number of Sellers: Displays the total count of profiled sellers.
* Average Seller Rating: Reflects the overall customer satisfaction by averaging ratings across all sellers.
* Seller Snapshot: Provides insights into individual seller performance, including their product count and geographical distribution using map visualizations.

### Key Insights:

* Seller Performance: Offers quick access to sellers' product counts and ratings, helping the acquisitions team assess quality and scale.
* Geographical Distribution: Helps evaluate where sellers are located and how that might impact acquisition strategy.

![image](https://github.com/user-attachments/assets/36ec5521-b7be-403d-beeb-3a1cb411c4e0)


### Dashboard 2: Amazon Merchants Profiling & Ranking for Acquisition
This dashboard dives deeper into merchant profiling and acquisition potential, focusing on:

* Business Name: The seller’s business name.
* Country: The seller's geographical location.
* Contact Information: Displays phone numbers and email addresses for easy outreach.
* Risk Levels: Risk categories (High/Low Risk) help prioritize sellers based on factors like performance and rating.
### Key Insights:

* Risk Assessment: Identifies low-risk sellers for acquisition opportunities.
* Acquisition Readiness: By using the Overall Score Slider, the team can filter and prioritize the most promising sellers.

## Methodology
To profile and rank sellers, we utilized multiple KPIs in Tableau, analyzing key attributes to derive insights into performance, risk, and acquisition potential. The most significant KPIs include:

* Seller Business Name Extraction
Identifies sellers by business name for accurate profiling.

* Country Identification
Categorizes sellers based on location using their business address.

* Email and Phone Number Extraction
Extracts contact details to facilitate direct communication.

* Product Count
Measures inventory size, where higher product counts signal greater market presence.
KPI Example: 5 points for over 20,000 products; 1 point for fewer than 100.

* Positive Rating Percentage
Reflects customer satisfaction, with higher ratings suggesting better seller performance.
KPI Example: 5 points for ≥95% positive ratings; 1 point for <60%.

* Hero Product Rating
Scores sellers based on the popularity of their top products, determined by the number of ratings.

* Overall Score
This comprehensive score incorporates ratings, product counts, risk, and brand diversity to assess acquisition potential.
KPI Example: 25% weight on Positive Rating Score, 25% on Product Count Score, 20% on Negative Rating Score.

![image](https://github.com/user-attachments/assets/b7ac7df5-1855-4e18-b4d1-e686aacb0c2a)


## Key Findings
Seller Performance: Sellers with a high product count and positive ratings are prioritized for acquisition.
Geographical Insights: Sellers from key markets may offer strategic advantages.
Risk Profiles: Sellers with low negative ratings and strong customer feedback present lower acquisition risks.

## Conclusion
By leveraging these dashboards and KPIs, the acquisitions team can efficiently identify, profile, and rank sellers based on their potential. The insights provided allow the team to make informed decisions, focusing on high-value, low-risk acquisition targets.
