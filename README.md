# Florida Causes of Death
This repository contains Florida's vital statistics data on a weekly basis, collected since June here: https://github.com/COVID19Tracking/Florida-Causes-of-Death. I pull my data weekly from Florida's vital statistics website, www.FlHealthCharts.com. This repository contains data for three different categories spanning multiple years and stratified by region and demographics.

## Deaths by cause categories

[113 All causes](https://github.com/COVID19Tracking/Florida-Causes-of-Death/tree/master/113%20All%20causes) | all deaths for each of the WHO ICD 113 cause of death categories with subtotals for each bucket from 1970-2021.
-------------- | ---------------------------------------------------------------------------------------------------------------
 race | White, Black, Other, Unknown
 ethnicity | Hispanic, Non-Hispanic, Unknown
	
[113 other and unspecified COVID](https://github.com/COVID19Tracking/Florida-Causes-of-Death/tree/master/113%20other%20and%20unspecified_COVID) | Florida mixes COVID deaths in the "unspecified parasitic infection and their sequelae" category. Sorted by year and county.
------------------------------- | ------------------------------------------------------------------------------------------------
race | White, Black, Other, Unknown
ethnicity | Hispanic, Non-Hispanic, Unknown
age | 5-year age grouping

[113 symptoms signs abnormal](https://github.com/COVID19Tracking/Florida-Causes-of-Death/tree/master/113%20symptoms%20signs%20abnormal) | R00-R99 category from 2010-2021. I began collecting this separately after I noticed the totals far exceeded prior years. Sorted by year and county.
--------------------------- | ------------------------------------------------------------------------------------------------------------------------
race | White, Black, Other, Unknown
ethnicity | Hispanic, Non-Hispanic, Unknown
age | 5-year age grouping
sex | Male, Female, Unknown

## Medical Examiner data
[Medical Examiners Report](https://github.com/COVID19Tracking/Florida-Causes-of-Death/tree/master/Medical%20Examiners%20Report) | Medical Examiner commissioner's report from the Florida Department of Law Enforcement.
-------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------
[COVID-19 (Coronavirus) 20200811](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Medical%20Examiners%20Report/COVID-19%20(Coronavirus)%2020200811.xlsx) | includes demographic data and death narratives for every COVID death up through mid-August, when the Florida medical examines asked to cede jurisdiction over COVID deaths due to lack of processing personnel available. The counties listed represent the deceased's county of death, not residence.
[Florida Medical Examiner Districts](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Medical%20Examiners%20Report/Florida%20Medical%20Examiner%20Districts.pdf)| Florida medical examiner district map per FDLE

## Data documentation and charts

[Data definitions](https://github.com/COVID19Tracking/Florida-Causes-of-Death/tree/master/Data%20definitions) | contains correspondence with FDOH re: data storage categories, race/ethnicity category coding
----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------
[CodebookDEATHQUERY](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Data%20definitions/CodebookDEATHQUERY.pdf) | The FlHealthCharts Death Query system codebook
[Death reporting post August 11](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Data%20definitions/Death%20reporting%20post%20August%2011.png) | Flowchart developed in collaboration with Dr. Nelson, Florida's chief medical examiner, that show the mortality data pipeline for Florida after August 11.
[Death reporting prior to August 11](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Data%20definitions/Death%20reporting%20prior%20to%20August%2011.png) | Flowchart developed in collaboration with Dr. Nelson, Florida's chief medical examiner, that show the mortality data pipeline for Florida prior to August 11.
[Documentation of COVID data storage](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Data%20definitions/Documentation%20of%20COVID%20data%20storage.docx) | FDOH statement on which ICD 11/358 cause categories COVID vital statistics data is stored.
[FDOH morbidity data](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Data%20definitions/FDOH%20morbidity%20data.png) | flowchart for FDOH morbidity data distribution
[Race and ethnicity coding](https://github.com/COVID19Tracking/Florida-Causes-of-Death/blob/master/Data%20definitions/Race%20and%20ethnicity%20coding.docx) | FDOH statement on race and ethnicity coding

## Data notes
- August, 2020: There is a gap in data in August because the Florida Health CHARTS system was taken offline for renovation. For 2 months afterwards, data slicing for race, ethnicity, and age was halted due to the unusuability of the system. It has now been resolved and data is collecting as before.
 
 - Jan 10, 2021 Provisional 2021 data is now displayed. 2020 data is still provisional.
 
 
 
