# Visualizing-Storm-Data
CSCI 627 Data Visualization: Final Project 
Name of Dataset: Storm Events Database

Storm Events Database: https://www.ncdc.noaa.gov/stormevents/ftp.jsp

Attribute Types:
There are three types of files which are linked by event ID number. Details, locations and fatalities.

Details of attribute which used in project.

episode_id:
•	Type: Categorical
•	Semantics: An ID assigned by NWS to denote the storm episode. Episodes may contain multiple events.
event_id:
•	Type: Categorical
•	Semantics: An ID assigned by NWS for each individual storm event contained within a storm episode. It is the primary database key field.
state:
•	Type: Categorical
•	Semantics: The name of the state where the event occurred (in ALL CAPS).
state_fips:
•	Type: Categorical
•	Semantics: A unique number (State Federal Information Processing Standard) assigned to the county by the National Institute for Standards and Technology (NIST).
year:
•	Type: Quantitative
•	Semantics: The four digit year for the event in this record.
event_type:
•	Type: Categorical
•	Semantics: The type of meteorological event leading to fatalities, injuries, damage, etc. 
cz_type:
•	Type: Categorical
•	Semantics: Indicates whether the event happened in a (C) County/Parish, (Z) NWS Public Forecast Zone, or (M) Marine.
cz_fips:
•	Type: Quantitative 
•	Semantics: The county FIPS number (or NWS Forecast Zone Number) for the location of the event.
cz_name:
•	Type: Categorical
•	Semantics: The name of the county, parish, zone, or marine area assigned to the FIPS number or NWS Forecast Zone.
injuries_indirect:
•	Type: Quantitative
•	Semantics: The number of injuries indirectly caused by the weather event.
deaths_direct:
•	Type: Quantitative
•	Semantics: The number of deaths directly caused by the weather event.
deaths_indirect:
•	Type: Quantitative
•	Semantics: The number of deaths indirectly caused by the weather event.
damage_property:
•	Type: Quantitative
•	Semantics: The estimated amount of damage to property incurred by the weather event (in dollars).
damage_crops:
•	Type: Quantitative
•	Semantics: The estimated amount of damage to crops incurred by the weather event (in dollars).
magnitude:
•	Type: Quantitative
•	Semantics: The measured extent of the magnitude type, typically used for wind speeds (in knots) and hail size (in inches).
magnitude_type:
•	Type: Categorical
•	Semantics: Describes the type of magnitude measurement, such as wind estimated gust, estimated sustained wind, measured sustained wind, or measured wind gust.
