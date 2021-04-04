# Pharmaceutical Treatment Results Analysis

The goal of this project was to calculate and display various performance metrics for four pharmaceutical cancer treatments (Capomulin, Infubinol, Ketapril, Placebo) on test mice over a 45 day treatment period. Since the baseline data was provided in CSV format, Python with Pandas, Numpy, and Matplotlib (through Jupyter Notebooks) was used to clean and process the data, as well as calculate and display the desired outputs.

---
## Datasets
* https://github.com/Emily-Keymon/Pharmaceutical-Treatment-Results-Analysis/blob/master/data/Mouse_metadata.csv
* https://github.com/Emily-Keymon/Pharmaceutical-Treatment-Results-Analysis/blob/master/data/Study_results.csv


---
## Tools Used
*  Jupyter Notebook
*  Python - Matplotlib, Pandas, Scipy


---
## Tasks
### Tumor Response to Treatment
1.  Import the mouse data and clinical data CSV files as individual Pandas data frames.
2.  Merge the individual data frames into a combined data frame based on the unique mouse identification numbers.
3.  Split the combined data frame into groups by treatment and time index.
4.  Calculate the average mean tumor volume for each treatment at each time index.
5.  Calculate the tumor volume standard error for each treatment at each time index.
6.  Create individual data frames for the average volume and standard error data.
7.  Plot the average volume data versus time with error bars defined by the standard error data.

### Metastatic Spread During Treatment
1.  Split the combined data frame into groups by treatment and time index.
2.  Calculate the average number of metastatic sites for each treatment at each time index.
3.  Calculate the metastatic site standard error for each treatment at each time index.
4.  Create individual data frames for the average metastatic site and standard error data.
5.  Plot the average metastatic site data versus time with error bars defined by the standard error data.  

### Survival During Treatment
1.  Split the combined data frame into groups by treatment and time index.
2.  Calculate the number of surviving mice for each treatment at each time index.
3.  Create a data frame for the survivng mice data.
4.  Plot the surviving mice data versus time.

### Tumor Change over 45 Day Treatment
1.  Calculate percent change in average tumor volume data over the full length of the treatment period.
2.  Plot the percent change data for each treatment.

---
## Observations
* Capomulin and Ramicane had the most data points in the study and the greatest reduction in tumor volume. While, Ketapril had the least effect on tumor growth.
* Infubinol's data had a potential outlier. One mouse showed a decrease in tumor volume while the rest showed an increase.
* There seems to be a direct correlation between a mouse's weight and the size of the tumor. This is indicative that the mouse's weight has an impact on the drug's effectiveness.
* Overall, Capomulin treatments on mouse b128 reduced the tumor volume. The most dramatic reduction occured between 25 and 35 days on the treatment. Capomulin proved to be the best drug to reduce tumor growth.

---
## Statistics
![summary_statistics](https://user-images.githubusercontent.com/64673015/113496016-1fe79d00-94bb-11eb-9a2e-d013d98ee2be.PNG)

---
## Bar Chart
![bar_chart](https://user-images.githubusercontent.com/64673015/113495890-380aec80-94ba-11eb-85c2-099ca3a2f2a8.PNG)

---
## Pie Chart
![pie_chart](https://user-images.githubusercontent.com/64673015/113495910-5cff5f80-94ba-11eb-85e6-74ec15aef4f6.PNG)

---
## Box Plot
![box_plot](https://user-images.githubusercontent.com/64673015/113495923-72748980-94ba-11eb-9123-50526ed7b548.PNG)

---
## Line Plot
![line_plot](https://user-images.githubusercontent.com/64673015/113495944-81f3d280-94ba-11eb-94f9-6e8de717b9eb.PNG)

---
### Scatter Plot
![scatter_plot](https://user-images.githubusercontent.com/64673015/113495961-b2d40780-94ba-11eb-9f31-d44d226b7544.PNG)

---
### Correlation and Regression
![correlation_plot](https://user-images.githubusercontent.com/64673015/113495975-cd0de580-94ba-11eb-8a4b-21f529fe173d.PNG)

---


