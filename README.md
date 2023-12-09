# Traffic-Accident_analysis

Google Drive Folder: https://drive.google.com/drive/folders/1Wvcwbvk3qNWSDGO8sq9yA6EI__uYEuTS?usp=sharing
- Contains MergedData - The accidents and vehicles dataset merged and cleaned

FARS Data - Crash API: https://crashviewer.nhtsa.dot.gov/CrashAPI

Files:
AccidentsData_2010-2021.zip - This file is the combination of files we got from the API, with only the columns we needed, and an additional st_case_per_year field.
VehiclesData_2010-2021.zip - This file is the combination of files we got from the API, with only the columns we needed, and an additional st_case_per_year field.
PersonsData_2010-2021.zip - This file is the combination of files we got from the API, with only the columns we needed, and an additional st_case_per_year field.

Cleaned_AccidentsData_2010_2021.zip - This file is essentially the AccidentsData_2010-2021 cleaned using Tableau Prep file AccidentsCleanUp.tfl
Cleaned_VehiclesData_2010_2021.zip - This file is essentially the VehiclesData_2010-2021 cleaned using Tableau Prep
Cleaned_PersonsData_2010_2021.zip - This file is essentially the PersonsData_2010-2021 cleaned using Tableau Prep file PersonCleanUp.tfl

Accidents_filteredData_NoOutliers.zip - This file is the final cleaned accident file with all lat/long outliers removed using Mihir's Method

Filtering County Outliers.ipynb - This file has Mihir's and Abhinav's code to help remove outliers based on latitude and longitude
Data Cleaning.ipynb - This file helped combine the original API files and extract required columns
