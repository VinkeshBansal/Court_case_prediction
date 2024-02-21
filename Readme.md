# PreCog Recruitment Task
This is the Readme file for the PreCog Recruitment Task and is divided into two major categories namely Court Cases Analysis and Bonus Task.

Most of the work is done on Kaggle and can be run on the same by importing the required datasets given in the notebooks in proper folders. However, Jupyter Notebooks from Anaconda Navigator might also be used to run the notebooks for files requiring higher memory access.

**Detailed Report of the Analysis and Classification is given separately as a pdf file.**

## Sections

- [Task](#task)
- [Libraries and Frameworks and Resources used](#libraries-and-frameworks-and-resources-used)
- [Analysis](#analysis)
    - [Judge Gender Position](#judge-gender-position)
    - [Caste Crimes](#caste-crimes)
    - [State Analysis](#state-analysis)
    - [Gender Crimes](#gender-crimes)
    - [Duration Analysis](#duration-analysis)
- [Classifier](#classifier)
    - [Classifier Outcome](#classifier-outcome)
    - [Classifier Duration](#classifier-duration)
- [Report](#report)
- [Bonus Task](#bonus-task)
- [Bibliography](#bibliography)

---

## Task

The task PDF with requirements and details as well as the links to the dataset.

* Precog_Recruitment_Task.pdf

---

## Libraries and Frameworks and Resources used

* Pandas
* Matplotlib
* Seaborn
* NumPy
* Dython
* Scikit-Learn
* Yellobrick
* IPython
* Population Dataset of Indian States for 2011
* Geopandas
* Shapefile

---

## Analysis

### Judge Gender Position

This contains the analysis to answer the question -

**Is there any discrimination in appointing females to high positions in the court? And if yes, then in which all states its more?**

> Contents

* judge-analysis.ipynb - python notebook to clean, filter the dataset and give necessary plots.

* judge_gender.png - Strip Plot for the analysis

---

### Caste Crimes

This contains analysis to the question - 

**Which states have the highest number of cases filed on Caste Atrocities and Crimes? And what has been their trend over the years?**

> Contents

* 2016
    * caste_crimes_without_outlier.png - Distribution of cases in various states for the year 2016.

* 2017
    * caste_crimes_with_outlier.png - Distribution of cases in outlier states for the year 2017.
    * caste_crimes_without_outlier.png - Distribution of cases in non-outlier states for the year 2017.

* 2018
    * caste_crimes_with_outlier.png - Distribution of cases in outlier states for the year 2018.
    * caste_crimes_without_outlier.png - Distribution of cases in non-outlier states for the year 2018.
    * caste-crimes.ipynb - Python notebook for cleaning, filtering the dataset and plotting the necessary plots. (Dataset can be loaded for the years 2017 and 2016 to get the outputs for other years in the same notebook).

---

### State Analysis

This contains analysis to the question - 

**Which states have higher number of cases filed than the others over the years? It also analyses the same after normalizing the dataset with population of each state.**

> Contents

* 2010
    * state_2010.csv - This contains the dataset of the cases filed in different states in 2010 after pre-processing.
    * state_2010.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2010.png - This is the bar graph for the cases filed in 2010 v/s the states.
    * state_map_2010.png - This is the visualization of the bar plot on the map of India

* 2011
    * state_2011.csv - This contains the dataset of the cases filed in different states in 2011 after pre-processing.
    * state_2011.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2011.png - This is the bar graph for the cases filed in 2011 v/s the states.
    * state_map_2011.png - This is the visualization of the bar plot on the map of India

* 2012
    * state_2012.csv - This contains the dataset of the cases filed in different states in 2012 after pre-processing.
    * state_2012.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2012.png - This is the bar graph for the cases filed in 2012 v/s the states.
    * state_map_2012.png - This is the visualization of the bar plot on the map of India

* 2013
    * state_2013.csv - This contains the dataset of the cases filed in different states in 2013 after pre-processing.
    * state_2013.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2013.png - This is the bar graph for the cases filed in 2013 v/s the states.
    * state_map_2013.png - This is the visualization of the bar plot on the map of India

* 2014
    * state_2014.csv - This contains the dataset of the cases filed in different states in 2014 after pre-processing.
    * state_2014.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2014.png - This is the bar graph for the cases filed in 2014 v/s the states.
    * state_map_2014.png - This is the visualization of the bar plot on the map of India


* 2015
    * state_2015.csv - This contains the dataset of the cases filed in different states in 2015 after pre-processing.
    * state_2015.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2015.png - This is the bar graph for the cases filed in 2015 v/s the states.
    * state_map_2015.png - This is the visualization of the bar plot on the map of India


* 2016
    * state_2016.csv - This contains the dataset of the cases filed in different states in 2016 after pre-processing.
    * state_2016.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2016.png - This is the bar graph for the cases filed in 2016 v/s the states.
    * state_map_2016.png - This is the visualization of the bar plot on the map of India


* 2017
    * state_2017.csv - This contains the dataset of the cases filed in different states in 2017 after pre-processing.
    * state_2017.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2017.png - This is the bar graph for the cases filed in 2017 v/s the states.
    * state_map_2017.png - This is the visualization of the bar plot on the map of India


* 2018
    * state_2018.csv - This contains the dataset of the cases filed in different states in 2018 after pre-processing.
    * state_2018.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis.
    * state_bar_2018.png - This is the bar graph for the cases filed in 2018 v/s the states.
    * state_map_2018.png - This is the visualization of the bar plot on the map of India

* cummulative analysis
    * state_cum_trend.png - The trend of cases filed over the years.
    * state_cumm_trend_withpop_withMaha.png - The trend of cases filed over the years normalized with population with outlier.
    * state_cumm_trend_withpop_withoutMaha.png - The trend of cases filed over the years normalized with population without outlier.
    * state_pop.csv - Population dataset of 2011 used to normalize. (Values in thousands) 
    * state-cumm.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis. 
    * state-cumm-pop.ipynb - This is the python notebook for pre-processing and generating the required plots for the analysis which is normalized with population.

---

### Gender Crimes

**Gender Crimes refer to the crimes involving Dowry, Gender Discrimination, Matrimonial Issues and Domestic Violence.**

This contains the analysis to the following questions -

**1. What is the State Wise Distribution of the cases involving gender crimes over the years?**

**2. Which gender is more likely to be the alleged in such cases and what is its trend over the years?**

**3. Which gender is more likely to file the case in such cases and what is its trend over the years?**

**4. What is the usual outcome of such cases or what is the verdict distribution of such cases?**

> Contents

* 2013
    * fdef_2013.csv - Processed Dataset for gender distribution in defendants for 2013.
    * fpet_2013.csv - Processed Dataset for gender distribution in petitioners for 2013.
    * gender-crimes-2013.ipynb - Python Notebook for cleaning, filtering the dataset, generating the CSV file.

* 2014
    * fdef_2014.csv - Processed Dataset for gender distribution in defendants for 2014.
    * fpet_2014.csv - Processed Dataset for gender distribution in petitioners for 2014.
    * gender-crimes-2014.ipynb - Python Notebook for cleaning, filtering the dataset, generating the CSV file.

* 2015
    * fdef_2015.csv - Processed Dataset for gender distribution in defendants for 2015.
    * fpet_2015.csv - Processed Dataset for gender distribution in petitioners for 2015.
    * gender-crimes-2015.ipynb - Python Notebook for cleaning, filtering the dataset, generating the CSV file.

* 2016
    * fdef_2016.csv - Processed Dataset for gender distribution in defendants for 2016.
    * fpet_2016.csv - Processed Dataset for gender distribution in petitioners for 2016.
    * gender-crimes-2016.ipynb - Python Notebook for cleaning, filtering the dataset, generating the CSV file.

* 2017
    * fdef_2017.csv - Processed Dataset for gender distribution in defendants for 2017.
    * fpet_2017.csv - Processed Dataset for gender distribution in petitioners for 2017.
    * gender-crimes-2017.ipynb - Python Notebook for cleaning, filtering the dataset, generating the CSV file.

* 2018
    * fdef_2018.csv - Processed Dataset for gender distribution in defendants for 2018.
    * fpet_2018.csv - Processed Dataset for gender distribution in petitioners for 2018.
    * gender-crimes-2018.ipynb - Python Notebook for cleaning, filtering the dataset, generating the CSV file.

* outcome_2018
    * outcome_2018.png - Pie Chart for representing various outcomes of such cases for the year 2018.
    * outcome-2018.ipynb - Python Notebook for cleaning, filtering the dataset and generating the required plot.

* petitioner_defendant
    * fdef.png - Double bar graph for gender distribution in defendants in such cases over the years.
    * fpet.png - Double bar graph for gender distribution in petitioners in such cases over the years.
    * gender-crime-pet-def.ipynb - Python Notebook for cleaning and merging the datasets from the previously generated CSV files and generating the required plots.

* State_Wise
    * 2010
        * gender_state_2010.csv - State Wise distribution of filing of such cases in 2010.
        * gender_state_map_2010.png - Visualization of the dataset after processing on the Map of India.
    * 2011
        * gender_state_2011.csv - State Wise distribution of filing of such cases in 2011.
        * gender_state_map_2011.png - Visualization of the dataset after processing on the Map of India.
    * 2012
        * gender_state_2012.csv - State Wise distribution of filing of such cases in 2012.
        * gender_state_map_2012.png - Visualization of the dataset after processing on the Map of India.
    * 2013
        * gender_state_2013.csv - State Wise distribution of filing of such cases in 2013.
        * gender_state_map_2013.png - Visualization of the dataset after processing on the Map of India.
    * 2014
        * gender_state_2014.csv - State Wise distribution of filing of such cases in 2014.
        * gender_state_map_2014.png - Visualization of the dataset after processing on the Map of India.
    * 2015
        * gender_state_2015.csv - State Wise distribution of filing of such cases in 2015.
        * gender_state_map_2015.png - Visualization of the dataset after processing on the Map of India.
    * 2016
        * gender_state_2016.csv - State Wise distribution of filing of such cases in 2016.
        * gender_state_map_2016.png - Visualization of the dataset after processing on the Map of India.
    * 2017
        * gender_state_2017.csv - State Wise distribution of filing of such cases in 2017.
        * gender_state_map_2017.png - Visualization of the dataset after processing on the Map of India.
    * 2018
        * gender_state_2018.csv - State Wise distribution of filing of such cases in 2018.
        * gender_state_map_2018.png - Visualization of the dataset after processing on the Map of India.
        * gender-crime-state-2018.ipynb - Python Notebook for cleaning, filtering the dataset and generating the required plots. (Dataset can be loaded for the other years to get the outputs for other years in the same notebook).
    * cummulative trend
        * gender_state_cumm_trend.csv - Collective dataset of number of cases filed for such crimes for the states over the years, generated after processing.
        * gender_state_cumm_trend.png - Line graph for the cases filed over the years for the states
        * gender-state-cumm-trend.ipynb -  Python Notebook for generating the plots after filtering and cleaning and merging the datasets from CSV files.

---

### Duration Analysis

This is the analysis for the question -

**How many judges are efficient enough to close the case within 1 year and how many take 5 years to close one?**

> Contents

* case_close_0_1.png - Number of Judges v/s percentage of closed within 1 Year
* case_close_0_5.png - Number of Judges v/s percentage of closed within 5 Years
* duration.ipynb - Python Notebook for filtering, cleaning and generating a dataFrame to visualize the required information as cumulative histogram.

---

## Classifier

Two Classifiers have been made for the following purposes - 

**1. To predict the Outcome/Verdict of the cases based on the input features.**

**2. To predict the Number of Years the case will take to close based on input featues.**

<br>

### Classifier Outcome

Uses Test/Train Split and Random Forest Classifier to predict the outcome of the cases. Description in report.

> Contents 

* classify-outcome-exp.ipynb - Python Notebook to make the classifier
* heat_map_outcome.png - Heatmap for the dataset
* Labels.png - Labels for the categories in target variable
* matrix_f.png - Confusion Matrix for the model results on the Test Set.
* pre-processing-1.ipynb - Python Notebook to pre-process the dataset to make it suitable for the classifier.
---


### Classifier Duration

Uses Test/Train Split and Random Forest Classifier to predict the outcome of the cases. Description in report.

> Contents 

* cduration-classify-exp.ipynb - Python Notebook to make the classifier
* heatmap.png - Heatmap for the dataset
* matrix_f.png - Confusion Matrix for the model results on the Test Set.
* pre-processing_2_a.ipynb - Python Notebook to pre-process the dataset to make it suitable for the classifier.
* pre-processing_2_b.ipynb - Second Python Notebook to pre-process the dataset obtained from previous notebook to make it suitable for the classifier.

---

## Report

A report has been prepared to summarize and explain all the findings of the analysis and the classifier for the user to read.

* Court_Case_Report.pdf

---

## Bonus Task

A report on the research paper given to analyse with findings, strengths and weaknesses described.

* Paper_Report.pdf

---

## Bibliography

- [Judicial Dataset Explanation](https://www.devdatalab.org/judicial-data)
- [Information about Gender Bias in Indian Judiciary](https://shrug-assets-ddl.s3.amazonaws.com/static/main/assets/other/India_Courts_In_Group_Bias.pdf)
- [State Population Dataset](https://kaggle.com/datasets/4787368868b955e15cbc878cdf88eb65921df90fbab353a51a44b77f0da51dc7)
- [Plotting Indian Map with Data](https://towardsdatascience.com/mapping-with-matplotlib-pandas-geopandas-and-basemap-in-python-d11b57ab5dac)

---