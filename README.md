# London Housing Analysis Project

**London Housing Analysis Project** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The dataset is sourced from Kaggle. It displays a variety of information regarding average house price, total crimes and total houses sold for a variety of boroughs of London. It provides this information for every month between 01/01/95 to 01/01/20. 

## Business Requirements
* London City Council requires an analysis of the London housing market for the past 20 years and how crime may have affected it. The council requires to understand crime's impact and how each borough fares in comparison to other boroughs in the region.


## Hypothesis and how to validate?
* Hypothesis 1: In areas of high crime, there will be less houses sold
* Hypothesis 2: In areas of high crime, the average house price will be lower
* Hypothesis 3: When crime increases, houses sold will reduce and when crime decreases, houses sold will increase
* Hypothesis 4: When crime increases, average house prices will reduce and when crime decreases, average house prices will increase

All the hypotheses will be validated via visualising the data in graphs to compare the stats.

## Project Plan
1) ETL - the data must be cleaned and transformed removing all null values, all data that is not relevant for this project so that it can be analysed accurately.
2) Visualisation - the clean data will now be visualised using a variety of libraries including Matplotlib, Seaborn and Plotly.
3) Conclusion - the visualisations will be used to draw conclusions against the data which will then be compared to the hypotheses derived earlier in the project.

## The rationale to map the business requirements to the Data Visualisations
* The requirements were to understand how crime may affect London housing markets and house prices.
* Against the hypotheses we can draw the following conclusions:
    * Hypothesis 1: Failed. In areas of high crime, more houses were sold.
    * Hypothesis 2: Passed. In areas of high crime, the average house price was lower, however, there are still the odd anomaly boroughs (such as Westminster), where house prices were high yet crime rates also remaind high.
    * Hypothesis 3: Failed. There was no definitive correlation between house sales and crime rates.
    * Hypothesis 4: Failed. There was a clear correlation between average house price and crime rates but not in the way of the hypothesis. In areas of high crime, average house prices remained low and vice versa (low crime areas = higher average house price). However, we could see that all boroughs had a consistent increase in average house price with crime rates not causing them to decrease but just helping define how high the average price will reach.

## Analysis techniques used
* The different data analysis techniques used were as follows:
    * Matplotlib - It was difficult to derive correlations directly so more complex techniques were required.
        * Bar charts
    * Seaborn - More complex analysis tools were used and this allowed to do a more detailed analysis however, all data was completely separated and required switching between different visualisations.
        * Facet Grid with line plots
        * Heat maps
        * Scatter plots
        * Facet Grid with scatter plots and linear regression
    * Plotly - This allowed for using one visualisation to compare many different types of data
        * Scatter graph with sizing and colour of points to indicate data 
* I structured the data analysis techniques in order of complexity. This helped show the development of the visualisations and the analysis from Basic to Complex. This also helped show the process in which conclusions were drawn and how basic visualisations may not provide the full picture.
* The data did limit me in some senses such as the crime rates. Through my data analysis I determined that crime rates can't be considered as general categories and need further in depth analysis to draw more accurate conclusions. I analysed the data and made sure to document this so that future analysis can be done with this in mind.
* I used ChatGPT to help aid me in code optimisation and in helping me decide what graphs I wanted to create to visualise the data accurately. I was careful not to rely on ChatGPT completely and made sure I made the decisions myself using AI only as a guide while also making sure I understood every bit of code I wrote and why I wrote it.

## Ethical considerations
* The issue with my data is that it was very basic in terms of analysing how the housing market in London was impacted. Crime is one issue but even that needs an in depth analysis into the types of crime. For example, do areas with high rates of violent crime have less houses sold than areas with high crime but less violent crime?
* As well as this it is important to consider other socio-economic variables when doing a study of any housing market. It can not be trivialised to purely crime impacting it.



## Unfixed Bugs
* For gaps in my knowledge I would use a variety of resources including:
    * Code Institute LMS
    * ChatGPT
    * StackOverflow
    * GeeksforGeeks
    * W3Schools
    * Youtube

## Development Roadmap
* In my next project experience I definitely want to incorporate some Machine learning (such as feature engine) as I would like to do predictive analytics.




## Main Data Analysis Libraries
* The Libraries I used were as follows:
    * Pandas - Data cleaning and visualisation (creating variables to help with visualisation)
    * Matplotlib - Basic Data Visualisation
    * Seaborn - Complex Data Visualisation
    * Plotly - Interactive Data Visualisation


## Credits 

* I got my dataset from Kaggle.


## Acknowledgements (optional)
* Firstly, thank you to God for everything.
* Thank you to my parents and my wife who have supported me throughout this project and in my career and life in general.
* Thank you Vasi for his support throughout this project.