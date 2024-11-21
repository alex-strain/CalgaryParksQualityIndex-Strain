This readme file was generated on [2024-11-20] by [Alex Strain]


# CalgaryParksQualityIndex-Strain



Author Information

Name: Alex Strain

Institution: University of Calgary

Address: Calgary, Alberta, Canada

Date of data collection: 2024-10-01

Data Source(s): 

- City of Calgary Open Data Portal (https://data.calgary.ca/)

- Statistics Canada Census 2021 (https://www150.statcan.gc.ca/n1/en/type/data) 



Project Description:

This project is designed to create a Parks Quality Index (PQI) for all parks within Calgary based on weighted criteria. 
This criteria includes park amenities, park area, presence of park pathways, presence of water bodies, and access to transit stops within 350m of parks. 
These criteria were selected based on what qualities of parks make them more or less usable by the communities they reside in or near. 
Weights for the criteria were determined through the analysis of the priorities of sustainable goals and indicators associated with Sustainable Calgary's 'State of Our City 2020' report.
This PQI was used in conjunction with Census data from Stats Canada 2021 tables based on Average Income, Population Density per Square Kilometer, and the Census Tracts of Calgary. 
This data was spatially joined and analyzed within ArcGIS Pro using the Calgary WGS 1984 3TM W114 projected coordinate system. All datasets and cleaned tables will be provided within the datasets folder which is included below in a CSV table format along with HTML Metadata files. 
The cleaned datasets included below begin with the prefix "Park" and the results that stem from these datasets being spatially joined and manipulated on ArcGIS Pro are the PQI and Census tables. 

Dataset Folder:

- ParksAndCensus_Data:
    - PQI_Table
    - Census_Table
    - Park_Area
    - Park_Equipment
    - Park_Seating
    - Park_WaterBodies
    - Park_Transit
    - Park_Washrooms
    - Park_Pathway
    - Park_SportSurfaces

    
