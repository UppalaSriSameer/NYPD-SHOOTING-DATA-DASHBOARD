📊 NYPD Shooting Incident Data Dashboard
This Tableau dashboard visualizes historical NYPD shooting incident data, offering insights into trends and demographics related to shooting incidents in New York City.

🚀 Overview
The dashboard consists of four main sheets, each providing a unique perspective on the data:

Total Shooting Incidents in NYC (2006–2011): A line chart showing the total number of shooting incidents over time, broken down by month and year. This allows for an understanding of temporal trends in shooting incidents.

Geographical Distribution (NYC Map Hotspots): A heatmap visualization on an NYC map, indicating areas with higher concentrations of shooting incidents across different boroughs. This sheet helps identify geographical hotspots.

Victim Demographics: Bar charts showing the distribution of victims by race and sex, allowing for an analysis of demographic patterns among victims.

Sex Distribution – Victim vs Perp: A pie chart comparing the sex distribution of victims versus perpetrators.

📋 Data Source
The dashboard uses the NYPD_Shooting_Incident_Data_Cleaned.csv file, which contains the following key columns:

INCIDENT_KEY: Unique identifier for each incident.

OCCUR_DATE: Date of the incident.

OCCUR_TIME: Time of the incident.

BORO: Borough where the incident occurred.

PRECINCT: Police precinct of the incident.

JURISDICTION_CODE: Jurisdiction code.

STATISTICAL_MURDER_FLAG: Flag indicating if the incident resulted in a murder.

PERP_AGE_GROUP: Age group of the perpetrator.

PERP_SEX: Sex of the perpetrator.

PERP_RACE: Race of the perpetrator.

VIC_AGE_GROUP: Age group of the victim.

VIC_SEX: Sex of the victim.

VIC_RACE: Race of the victim.

X_COORD_CD, Y_COORD_CD: X and Y coordinates.

Latitude, Longitude: Geographical coordinates for mapping.

Calculated fields include:

Year: Extracts the year from OCCUR_DATE.

Month-Year: Truncates OCCUR_DATE to the month.

Time Period: Categorizes OCCUR_TIME into "Morning," "Afternoon," and "Evening."

Total Victims: A count for each incident.

Role: Identifies whether an entry is for a "Victim" or "Perpetrator."

Sex (Role): Combines victim and perpetrator sex based on the Role calculation.

🛠️ Usage
To open and interact with this dashboard:

Ensure you have Tableau Desktop installed (version 2024.2.1 or newer is recommended).

Download both Dashboard.twb and NYPD_Shooting_Incident_Data__Historic__20250729.csv.

Place the NYPD_Shooting_Incident_Data__Historic__20250729.csv file in the same directory as the Dashboard.twb file, or update the data source connection within Tableau Desktop if you place it elsewhere.

Open Dashboard.twb with Tableau Desktop.

Explore the various sheets and use the available filters (e.g., for BORO, Year, Month-Year) to refine your analysis.

📈 Key Insights (Potential)
While specific insights depend on the actual data and your analysis, this dashboard is designed to help answer questions such as:

How have shooting incidents in NYC changed year-over-year?

Which boroughs experience the highest number of shooting incidents?

Are there specific times of day when incidents are more frequent?

What are the predominant age, sex, and racial demographics of victims and perpetrators?

Are there observable differences in sex distribution between victims and perpetrators?
