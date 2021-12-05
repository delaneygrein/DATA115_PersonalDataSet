# DATA115_PersonalDataSet

# Motivation
With everything going on in the world today, I wanted to look at happiness levels around the world. There are many factors that affect happiness like freedom, GDP, support, life expectancy, generosity, and perceptions of corruption. I wondered what the relationships were between the happiness score and each factor and which factor was most closely correlated to the happiness score. 

# Data Process
When I started looking for data on this subject, I found a website dedicated to statistics about happiness around the world called the [World Happiness Report](https://worldhappiness.report/). As I went through the data, it had a lot of extra factors that I did not need for the purposes of this project. I found another data source which combined data from the World Happiness Report and data from the [Gallup World Poll](https://www.gallup.com/analytics/349487/gallup-global-happiness-center.aspx) to look at the factors that affect happiness and the overall happiness scores given to each country. As for cleaning the data, there wasn't a whole lot of processing that needed to be done. The data was already neatly organized and there were no values that were concerning enough to take out or change. 

# Visualization 
![Happiness score vs. view on people's freedom to make life choices](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/Visualization_HappinessReport.png)
![Happiness score vs. GDP per Capita](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/GDP.png)
![Happiness score vs. Generosity](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/generosity.png)
![Happiness score vs. Life Expectancy](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/life%20expectancy.png)
![Happiness score vs. Perceptions of Corruption](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/perceptions%20of%20corruption.png)
![Happiness score vs. Social Support](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/social%20support.png)

I chose to create scatterplots comparing each factor that affects happiness to the happiness score to look at the relationships between each. Some of the factors were more closely correlated to the happiness score than others and there were some outliers present.

# Analysis 
I decided to look more closely at the correlations between the variables by creating a correlation table with all of the factors and their correlation values. This table does also show correlation between the factors as well, but I primarily focused on the correlation values between the happiness score and each factor. Somewhat suprisingly, the GDP per capita was the factor most closely correlated to happiness score with a correlation value of 0.794. On the other hand, generosity was least correlated to happiness score with a correlation value of 0.076. 

![Correlation table](https://raw.githubusercontent.com/delaneygrein/DATA115_PersonalDataSet/main/correlation%20table.png)
