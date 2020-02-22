# Title

Is there any relation amongst US population socioeconomic level and some of the most common diseases related with sedentary life style and junk food consumption like cardiovascular deaths, diabetes, heart attacks, high blood pressure and obesity?

# Team Members

* Juan Pablo Sada
* Adriana Fajardo
* Erick Castillo
* Pablo Beitman

# Hypothesis

People with high socioeconomic level get less diseases/illnesses related with sedentary life style and junk food consumption because they have more health education due to more opportunities and greater access to information.

# Description

Cardiovascular and high blood pressure diseases are among the leading causes of global mortality and is expected to rise over the next few decades, mainly due to aging. Eventhough a clear relation exists, other factors are also affecting growth rates. The hypothesis states a relation between low socioeconomic level (income) and higher rates of diseases, supposing the population is less educated on health topics.
The United Stes is one of the Top countries being consistently affected during the last years by both, aging and disparity of income between the extreme edges of the economically active population.
As the income gap between rich and poor widens, the importance of monitoring health disparities across the income spectrum rises, and the debated amount of appropriate government spending on health care makes income-related health inequality an even more relevant subject to study.
This excercise is seeking to answer the following questions, clarifying the current trends and behaviours of this disases through the income spectrum from 2015 to 2018.

# Variables and maps

* Income
* Obesity %
* Diabetes %
* Heart attack diseases ratio
* High blood pressure %
* Cardiovascular death ratio

#Variable description

High blood pressure: Percetage of adults who reported bieng told by a health professional that they have high blood pressure.
Diabetes: Percentage of adults who reported being told by a health professional that they have diabetes (excluding prediabetes and gestional diabetes).
Cardiovascular deathts: Number of deaths due to all cardiovascular diseases including heart disease and stroke pre 100,000 population (3-year estimate age-adjusted to mid-year).
Hear attack: Percentage of adults who reported being told by a health professional that they had a heart attack (myocardial infarction). Obesity: Percentage of adults with a body mass index of 30 or higher based on reportes height and weight.

# Questions

1. Does the median household income has increased through time?
2. What conlusions can we infer about the median household income data?
3. Do the data sets behave as normal distribution? If not, how should these datasets be analyzed?
4. Is there any correlation between income and cardiovascular deaths, diabetes, heart attacks, obesity and high blood pressure?
5. Is there any correlation between cardiovascular deaths, diabetes, heart attacks, obesity and high blood pressure?


# Datasets and Databases

https://www.americashealthrankings.org/explore/annual
https://www.census.gov/library/stories/2019/09/us-median-household-income-up-in-2018-from-2017.html

# Tasks

1. Define topic and formulate questions
2. Obtain data - obtain the data needed from available data sources.
3. Scrub data (organize and tidy) - clean, filter, consolidate, extract, replace, split, merge, extract data.
4. Explore data - compute desriptive statistics -.describe()- to test significant variables and extract singiciant features, EDA (exploratory data analysis) - insights and results.
5. Model data - reduce datasets dimensionalty, linear regressions, graphs,
6. Data interpretation
7. Presentation

# Data Analysis

Data sets shows mixed results, even when median household income (by state) has significantly increased during the analized four year period. Each state was categorised in 5 regions according to its median household income (Region 1-> <$50,000, Region 2-> $50,000 -$54,000, Region 3-> $55,000 - $59,999, Region 4-> $60,000 - $69,999 and Region 5-> >= $70,000).

The barplot shows that Region 1 and Region 2, which are the states with the lowest Median Household Income, have decreased considerably being in 2018 only 5 states compared to the 11 states in 2015. Region 5 presents the states that have the highest Median Household Income. It is clear that the tendency is increasing year by year. In the case of Region 3, in 2015 was the region with the highest number of states belonging to this classification. However, it shows a considerably decreased, but recovered in the following 2 years.

Continuing with the analysis, in the Median Household Income histograms, all the datasets may present a normal behavior. The median of each year is close to 60,000 USD yearly. However, 2017 and 2018 have the major variance compared to 2015 and 2016. No outliers are present. This may suggest that there are some states in which the median household income increased considerably compares to the previous years, and there are few states that remain with a low median household income. No radical changes in the dara distributios are observed. The normality test was accepted in all the years.

High Blood Pressure and Cardiovascular Deaths rates behave stable in terms of total range and median. In High Blood Pressure, it is clear that it is the variable that has more outliers compared to the rest the variables to be analyzed. All years have a bias to the right side due to the outliers, represented by the states of West Virginia, Alabama, Arkansas and Louisiana. The normality test was accepted in all the years.

Heart Attack percentage behaves stable and most of the states are concentrated between the fiest and second quartile. The normality test was only accepted by years 2016 and 2018.

Diabetes distribution is clear that varies from yeart to year. There is a slightly biase to the right side. The year that has the lowest variance compared to the rest of the years is 2015. The years 2017 and 2018 have an outlier each one, which are represented in both cases by the state of West Virginia. The normality test was accepted in all the years.

Obesity is by far the disease with the highest incremental rate. Between the 75 to the 100% of the population have high body mass indexes. And an outlier is present in 2015, represented by the state of HAwaii being the one with the lowest percentage of population declared with obesity. The normality test was accepted in all the years.

Correlation Diseases vs Median Household Income

All the variables (Cardiovascular Deaths, Diabetes, Heart Attack, Obesity and High Blood Pressure) have a negative correlation with Median Household Income. This means that higher the median household income, less percentage of people with Diabetes, Heart Attacks, high body mass index, High Blood Pressure and the amount of Cardiovascular deaths.

However, more variables need to be considered in order to have bigger picture of the behaviour among Median Household Income and Diseases. A proposal of variables to be included are education, health policies, kunk food consumption and exercise time.

# Conclusions

As a general overview, this analysis represents a good first approach to undestand how annual household income is strongly related to each variable. A question that must be answer is if more variables are needed to be included a deeper study? The answer is absolutely yes as it was discusses in the above. The following questions that came out during the development of this study are: is there a considerable increase of junk food consumption despite the? US people just do not want it? 

Why informative campaings are not the banner of any goverment or administraton? Are the subsides from the goverment to the corn and wheat affect US population healty?
All these questions are now on the table waiting to be answered in further analysis.
