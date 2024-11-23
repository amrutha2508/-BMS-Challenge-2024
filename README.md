# BMS-Challenge-2024
### Abstract
Bristol Myers Squibb (BMS) has over 100 years of history and is one of the earliest adopters of electronic systems to record our data and go paperless. The historical data and prior knowledge are of tremendous value, especially when it comes to leveraging the massive amount of existing data to feed into AI/ML models to gain more insights, enable predictive power, and eventually empower reliable data-driven decisions. However, over the decades, industrial standards/systems and regulatory requirements on electronic data have been evolving significantly along with the rapid development of technologies and digitalization. Although implemented standards to collect data in the electronic systems for many years, various data issues (e.g., inconsistency, typos, etc.) were observed  across products, studies, etc. The historical data need to be cleaned and aligned to enable reliable and meaningful data-driven decisions by leveraging AI/ML models.

This project focuses on cleaning and aligning attribute names across two datasets — bms_data and Standard Names — to ensure consistency and improve data quality. The goal is to map each pair of Analysis and Attribute in the bms_data dataset to a corresponding Standard Name in the Standard Names dataset. A Python script is developed to automate this mapping process by comparing the columns Analysis and Attribute in both datasets. The output of this script is three datasets:

1.	Mapped Data: Contains records successfully mapped to a Standard Name.
	
2.	Junk Data: Contains records with no clear relation to any standard name.

3.	Indecisive Data: Contains records requiring manual review due to ambiguity or alternative term usage.

This solution streamlines the standardization process, providing a robust method for handling complex mappings and ambiguous data.
