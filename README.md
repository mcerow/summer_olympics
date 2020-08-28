# Summer Olympics EDA

This repository includes a simple exercise in Exploratory Data Analyis around the Summer Olympics. I used a dataset found on [kaggle](https://www.kaggle.com/the-guardian/olympic-games/data). While the dataset includes both Winter & Summer Olympic Medal Results, I decided to focus on the Summer Olympics as a means of exploring the data and answering some simple questions.

The libraries I used in this project are:

    - Pandas
    - Matplotlib
    - Seaborn
    
## Question 1: What country has won the most medals since 1986 in the Summer Games?

My first question around this data is what country has accumulated the most medals from the summer games? This data runs the course of 130 years - 1896 to 2012 which means it captures 27 summer games. When looking at the top countries, the US has brough home almost 4.6k medals. Russia follows with 2.0k medals. Great Britain, France, Germany, Italy, Australia, Hungary, Sweden and the Netherlands round out the top 10.

Because this was so heavily skewed to the US, I wanted to compare gold medal wins to see if those were a little closer. Again the US was the number one earning country with 2.2k gold medals won. Interestingly, the countries who won the most gold don't follow the same order as the total number of medals. Russia and Great Britan were still the second and third countries in this list, but Italy jumped to the fourth position. Most interestingly East Germany makes an appearance on the top earning gold medal list. They won 329 gold medals when the country existed.

## Question 2: How are team medals accounted for?


