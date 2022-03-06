# DataKind

DataKind is a volunteer organization that works with data scientists and leading social change organizations to collaborate on cutting-edge analytics and advanced algorithms to maximize social impact. Our programs build upon one another and are designed to meet organizations where they are. From evening or weekend events to multi-month projects, all are designed to provide social organizations with the pro bono data science innovation team they need to tackle critical humanitarian issues in the fields of education, poverty, health, human rights, the environment and cities.

## DC homelessness
This project is in collaboration with the DC DHS where I am working with Datakind as a volunteer on the challenging social issue related to homelessness. One of the key objectives of this project is to predict the number of shetler beds required during the hypothermia session.

### Data collection
Daily bed availability data from the shelter homes is collected using HMIS system and the collated daily occupancy report are present in excel files for last 5 years. Our goal was to scrape the files (~360 files a year) and then create a single dataframe with the required features to build a time series model. The model will be used to predict the #shelter beds required for coming hypothermia season.
