## House Sales USA Analysis
House Sales in the USA: an Exploratory Analysis using Python as the main programming language to understand some trends and correlations between prices, client satisfaction, houses' size, and location. This work is based on an academic exercise taken from a university course.
It's aimed at people who want to understand how some Python libraries can be helpful when doing exploratory data analysis and to extract some useful insights from data.

## Authors
- @Karen-Benites
- @hittheflash

## Key Findings and lessons learned
- There is a huge difference between the most expensive (USD  7700000.0) and the cheapest house (USD  75000.0), and these values are quite far from the average price (USD  540182.16). This affirmation is supported by the standard deviation value calculated (USD  367362.23). 
- There is an important number of people that are not fully satisfied with the house they bought. Indeed, most of them gave a review of 3-4, according to the following graph:
- A difference of 6.73 % between property surface area in and outside Seattle can be seen little at the beginning, but in the real state business, this can be an alarming value.
- We can reduce significantly the number of code lines by knowing the appropriate functions when performing data cleaning and organization. For example, to categorize variables and add another column to the data frame, we could write some if and for lines, or we can do the exact same calculation with a single line of code using a pandas function.
- There is a slight difference between property surface area in and outside Seattle. Big houses tend to be a little bigger outside Seattle, whereas small and medium houses have a little more surface area inside Seattle. However, this difference is so small according to the graph, that houses can be considered the same size regardless of their location relative to Seattle.
- When building a graph comparing the cheapest houses according to house size, at first glance, it seems a bit suspicious that a small house has a higher price than a large one in this latter graph. However, it is essential to remember the context of the data. This graph does not take into account the location of the houses; therefore, a possible explanation for this phenomenon is that houses located within a city tend to be more expensive and smaller, while larger houses are typically found outside the city, which could lower their selling price. Thus, this small house with a price above a large house might be situated in a luxurious location within a city, whereas the large house may be located outside a city, leading to a lower sale price.
- When comparing client's average review score (satisfaction level) with house size, there was no difference between the average review score and house size. Thus, there is no relation between client's satisfaction and house size. Client's satisfaction level is influenced by other factors.
- According to the graph, the most expensive houses are in Medina and Mercer Islan. The chapest houses are in Kent and Federal Way.
- Visually, we can see (in the graph below) that there is some correlation between house size, location and price. Houses outside Seattle tend to be more expensive than those inside; and the bigger the house, the more expensive and the farther they are from Seattle. This hypothesis is confirmed later with a statistical hypothesis test.
  
## Further improvements
To improve this analysis, we suggest:
- Considering the outliers in the dataset. Outliers have not been removed because that aspect was not contemplated in the original academic task
