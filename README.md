# Arun_Puri_Intern_Project
This is an intern Project done for Tabi Ai where we have done Basic EDA and Feature Engineering

<h2>Objective :</h2>

The task is to conduct exploratory data analysis on the provided vehicles dataset. By analysing the dataset, aim is to gain insights into various aspects of vehicles attributes and trends. The analysis will help to understand the data better and identify potential areas for further investigation.

<h3>Task To Perform:</h3>
<ul>
<li>Data loading and preparation.</li>
<li>Data cleaning and preprocessing.</li>
<li>Exploratory data analysis.</li>
<li>Feature Engineering.</li>
<li>Insights and Recommendations.</li>
</ul>

<h2>Approach For Solution:</h2>

The vehicle data has total of 1834 rows and 144 columns at start and they are further broken down as float-122, int-13, object-16.
To get insights from the data we have used the following approach to do the analysis.

<ul>
<li>Step1: Data loading and preparation.
To start with the analysis first we have imported the important libraries into our project. Like- Numpy, Pandas, Seaborn, Matplotlib and SkLearn.
Then we have read the data set into the jupyter notebook and assign it to the variables.
Basic Exploratory work is performed like-first few rows of the data set, identifying types of variables, size of the data set, missing values and irregularities.
</li>

<li>Step2: Cleaning Of Data Set.
Missing values were identified and were imputed with median values.
Columns having all the NAN were removed to reduce the memory space of the data set and total 0f 6 columns having same values throughout were also removed.
All the categorical column which was not useful was dropped and our total columns were than reduced from 144 to 24.
Then we have removed the outliers from the column ‘Fuel Efficiency’ as we have taken it as a dependent variable in our analysis.
Duplicates were check and found no duplicate values.
Further we have done a correlation heatmap on the numerical features of our data set to get a deep knowledge about how they are corelated the different features.
</li>

<li>Step3: Exploratory data analysis (EDA):
First, Univariate analysis was done on categorical features where we have created a count plot with different categorical features such as – torque Mode, Break Clutch.
Then we have done univariate analysis on different numerical features and made some of the plots like – kde plot, histogram plot, boxplot. With that we were able to find the extreme values, outliers and their distribution.
After, that we have done bivariate analysis on different features taking categorical and numerical features and plotting various charts such as – swan plot with torque mode and fuel economy, barplots, scatterplots, and Line graph.
</li>
<li>Step4: Feature Engineering:
In this we have created a new feature out of current feature that is Percentage change in engine torque and demand of driver torque with respect to engine torque
</li>
<li>Step5: Standardization:
As we could see our data was not distributed normally which result in lot of skewedness to deal with it we have standardized our data so that our data can get fit with different machine learning models properly if needed.
</li>
</ul>
