### Comparing-Healthcare-Resources-and-Health-Outcomes-at-Country-and-Regional-Level
##### An analysis of the health expenditure and health outcomes at country and regional level to create a country level composite indicator of healthcare utilization efficiency.

All data files are in the data folder. No download necessary

TO INSTALL DEPENDENCIES :

---

uncomment and run the first code cell in the first notebook, 01_data_load.ipynb


TO OBTAIN DATA FILES :

---

1. UN Personnel File [HealthPersonnel.csv] - 

Link below will initiate download.

https://data.un.org/_Docs/SYB/CSV/SYB65_154_202209_Health%20Personnel.csv

2. UN Expenditure File [HealthExpenditure.csv] -

Link below will initiate download.
https://data.un.org/_Docs/SYB/CSV/SYB65_325_202209_Expenditure%20on%20health.csv

3. UN HDI File [HDR21-22_Composite_indices_complete_time_series.csv] -

Link below will initiate file download.

https://hdr.undp.org/sites/default/files/2021-22_HDR/HDR21-22_Composite_indices_complete_time_series.csv

4. UNSDG File [UNSDG.csv]- 

Access Swagger page here - https://unstats.un.org/SDGAPI/swagger/

There is a POST endpoint under the goals section - POST /v1/sdg/Goal/DataCSV. In the parameter goal, provide 3.  Click 'Try it out!' button. After request finishes, click on the csv file under Response Body to download.

5. UN Region File [UNSDRegions.csv]- 

Click CSV button at link below, download will begin 
https://unstats.un.org/unsd/methodology/m49/overview/

6. WHO GHED File [GHED_data.xlsx]- 

There is a link on the bottom left of the site linked below that says Download all data in XLSX format'.  Click that. Download should start.
https://apps.who.int/nha/database/Select/Indicators/en

7. WHO GHO dataframe - 

API request built in a loop in the code, no key necessary






