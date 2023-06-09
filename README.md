# medications-challenge

## Analyzing Anti-Cancer Medications Data
<br/><br/>
This project is about a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

There is a given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The task is to generating all of the tables and figures needed for the technical report of the clinical study. Also,a top-level summary of the study results analyzing the school and test scores data of city's district is needed.

For these analysis a pythin script is created which does the following:

### Prepares the Data
 
* The datasets are merged into a single DataFrame. 
* The number of mice are shown from the merged DataFrame. 
* Each duplicate mice is found based on the Mouse ID and Timepoint.
* A clean DataFrame is created with the dropped duplicate mice.
* The number of mice are shown from the clean DataFrame. 


### Generates Summary Statistics

* The mean of the tumor volume for each regimen is calculated.
* The media of the tumor volume for each regimen is calculated.
* The variance of the tumor volume for each regimen is calculated.
* The standard deviation of the tumor volume for each regimen is calculated.
* The SEM of the tumor volume for each regimen is calculated.
* A new DataFrame is created with using the summary statistics.


### Creates Bar Charts and Pie Charts
* A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated.
* A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated.
* A pie plot showing the distribution of female versus male mice using Pandas is generated
* A pie plot showing the distribution of female versus male mice using pyplot is generated.

### Calculates Quartiles, Find Outliers, and Create a Box Plot
* A DatFrame that has the last timepoint for each mouse ID is created.
* The index of the DataFrame is reset.
* Retrieve the maximum timepoint for each mouse.
* The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list.
* An empty list is created to fill with tumor volume data.
* A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group.
* A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group.

* ### Creates a Line Plot and a Scatter Plot
* A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin.
* A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen.

### Calculates Correlation and Regression
* The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen.


### Written Report


* The written report summarizes the analysis
  
<br/><br/><br/>

### Directory tree
. Pymaceuticals ---> pymaceuticals.ipynb, data( ---> Mouse_metadata.csv, Study_results.csv)

## References
This project is a part of UC Berkeley "Data Analysis and Visualisation" Boot Camp education services.
Data generated by Mockaroo (https://mockaroo.com/ ), LLC (2022). Realistic Data Generator.

In projects' descriptions, some paragraphs are copy/pasted from 'Module 4 Challenge' of UC Berkeley Data Analytics and Visualisation Bootcamp course.
pymaceuticals_starter.ipynb file is used as a tamplate.

Script author - Nazeli Mnatsakanyan
 
Apr-05-2023
# medications-challenge