# DataKind

DataKind is a volunteer organization that works with data scientists and leading social change organizations to collaborate on cutting-edge analytics and advanced algorithms to maximize social impact. Our programs build upon one another and are designed to meet organizations where they are. From evening or weekend events to multi-month projects, all are designed to provide social organizations with the pro bono data science innovation team they need to tackle critical humanitarian issues in the fields of education, poverty, health, human rights, the environment and cities.

## DC homelessness
This project is in collaboration with the DC DHS where I am working with Datakind as a volunteer on the challenging social issue related to homelessness. One of the key objectives of this project is to predict the number of shetler beds required during the hypothermia season.

### Data collection
Daily bed availability data from the shelter homes is collected using HMIS system and the collated daily occupancy report are present in excel files for last 5 years (2017-2022). Our goal was to scrape the files (~360 files a year) and then create a single dataframe with the required features to build a time series model. The model will be used to predict the #shelter beds required for coming hypothermia season.

### Data pipeline
As part of the data engineering phase, I needed to scrape through the excel files with varying formats and structure for the past 5 years and extract the important features which will feed as input to the time series model.

Data challenges:

	1. Semi-structured data with logos and some unstructured columns with multiple sub-headers separating data for different categories. The column names split under main and sub-header
	2. Rows with redundant columns and rows
	3. Inconsistent file formatting across different years and some inconsistent formats within a single year
  4. The data started with different row numbers. The column names would be different and in some cases even extra columns (at the end)

