# Title
Is there any relation amongst US population socioeconomic level and some of the most common diseases related with sedentary life style and junk food consumption like cardiovascular deaths, diabetes, heart attacks, high blood pressure and obesity?

# Team Members
- Juan Pablo Sada
- Adriana Fajardo
- Erick Castillo
- Pablo Beitman

# Hypothesis
People with high socioeconomic level get less diseases/illnesses related with sedentary life style and junk food consumption because they have more health education due to more opportunities and greater access to information. 

# Description
Cardiovascular and high blood pressure diseases are among the leading causes of global mortality and is expected to rise over the next few decades, mainly due to aging. Eventhough a clear relation exists, other factors are also affecting growth rates. **The hypothesis states a relation between low socioeconomic level (income) and higher rates of diseases, supposing the population is less educated on health topics.**  

The United Stes is one of the Top countries being consistently affected during the last years by both, aging and disparity of income between the extreme edges of the economically active population.

As the income gap between rich and poor widens, the importance of monitoring health disparities across the income spectrum rises, and the debated amount of appropriate government spending on health care makes income-related health inequality an even more relevant subject to study. 

This excercise is seeking to answer the following questions, clarifying the current trends and behaviours of this disases through the income spectrum from 2015 to 2018. 


# Variables and maps 
  - Income
  - Obesity %
  - Diabetes %
  - Heart attack diseases ratio
  - High blood pressure %
  - Cardiovascular death ratio
  
  
High blood pressure: Percetage of adults who reported bieng told by a health professional that they have high blood pressure.
Diabetes: Percentage of adults who reported being told by a health professional that they have diabetes (excluding prediabetes and gestional diabetes).
Cardiovascular deathts: Number of deaths due to all cardiovascular diseases including heart disease and stroke pre 100,000 population (3-year estimate age-adjusted to mid-year).
Hear attack: Percentage of adults who reported being told by a health professional that they had a heart attack (myocardial infarction).
Obesity: Percentage of adults with a body mass index of 30 or higher based on reportes height and weight.


# Questions
1. What is the correlation between:
      Income and  diabetes, obesity, heart attacks, highblood pressure     	and cardiovascular deaths 

2. Which of the previously explained deseases has the biggest growth            	rate during the last years?
3. According to the analized data,income disparity among US popullation 	is generating poor people to become exposed to sicknesses?
4. What conlusions can We infer about the median household income data?
5. Do the data sets behave as normal distribution? If not, how should these datasets be analized?

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

# Data Interpretation

Data Sets distribution

Data sets shows mixed results, even when median household income has significantly increased during the analized four year period 







Annual Household Income (By region/scale)







The barplot shows that Region 1 and Region 2, which are the states with the lowest Median Household Income, have decreased considerably being in 2018 only 5 states compared to the 11 states in 2015. Region 5 presents the states that have the highest Median Household Income. It is clear that the tendency is increasing year by year.
In the case of Region 3, in 2015 was the region with the highest number of states belonging to this classification. However, it shows a considerably decreased, but recover in the following 2 years.

Continuing with the analysis, by seeing histograms only, all the datasets may present a normal behavior, We can notice concentrating the peak of cases in people aged from 30 to 35 years old and. The median of each year is close to 60,000 USD yearly. However, 2017 and 2018 have the major variance compared to 2015 and 2016. No outliers are present.








Histogram Annual Household income





Through years 2015 to 2018 no radical changes in how data is distributed can be appreciated.

highblood pressure and cardiovascular deaths rate behaved stable in terms of total range and median.
In High Blood Pressure, it is clear that is the variable that has more outliers in compared to the rest the variables to be analyzed. All years have a bias to the right side.


 




Heart attacks rate is  stable but shows a reduction of 1% in the data located al across the  4th quartile during the last two years.
Histogram reflects that most of the cases are located in a range from 4 to 5 % of popullation and apparently a normal behaviour. Normality test shoul be run. Through years 2015 to 2018 no changes in how data is distributed can be appreciated except for obesity graphs where a little trend change is located and can be explained by population aging.



Diabetes data distribution is probably the most inconsistent in terms of distribution, histogram graphs reflect no trends in their behavior but box plot graphs show that either ranges and median is stable through the years.
The year that has the lowest variance compared to the rest of the years is 2015. Nevertheless, it has a slight bias to the right. The years 2017 and 2018 have an outlier each one.

 

Obesity is by far the disease with the highest incremental rate not only by average of people affected but by showing data is located in the 3rd and 4rth quartile 
 


Correlation Desease vs Annual household income and 

Diabetes has negative correlation with a min of -61% during 2018 and a maximun of -77%. That basically means that people with more income is less exposed to get diabetes deseases.

Heart Attack has also a negative correlation with range from -66% to -79% again it confirms low income people es more exposed to heart attacks.

Obesity has a negative dependency to annual household income refleted by a correlation from -59% to -72% during the 4 year analized period. This desease is the one that presentd the lowest correlation factor among all the analized deseases, this result suggest that not only but additional variables are related to this desease.

Highblood pressure shows a negative correlation from -68% to -73%, something  interesting is the fact highblood pressure is the only desease that shows a slightly but consistent reduction of dependency vs anual household income, from -73% in 2016 up to -68% during 2018, is there aditional factors that are helping people to get over HBP? Aditional data and a deep dive may help for better understanding.

Do the 6 variables to study have a normality distribution in order to be analyzed as it?

H0= The data has a normal distribution.
Ha= The data does not have a normal distribution.



The variable Heart Attack in the years 2015 and 2017 reject the null hypothesis with p-values of 0.036112 and 0.012007, respectively and with a significance level of 0.05. The rest of the variable accept the null hypothesis with a significance level of 0.05


# Conclusions

As a general overview, this analysis represents a good first approach to undestand how annual household income is strongly related to each of the variables, is income the only variable? For sure not but is truly one of tha main variables that may suggest how a better dealing with these deseases can be made. Huge questions come to our team like why  with these results, there is no boom of  cheap healthy-industry? US people just do not want it? Or just do not know how harmful their current habbits are?  
Why informative campaings are not the banner of any goverment or administraton?  Are the subsides from the goverment to the corn and wheat affect US population healty?

All these questions are now on the table waiting to be answered in further analysis.

