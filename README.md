# Summer Olympics EDA

This repository includes a simple exercise in Exploratory Data Analyis around the Summer Olympics. I used a dataset found on [kaggle](https://www.kaggle.com/the-guardian/olympic-games/data). While the dataset includes both Winter & Summer Olympic Medal Results, I decided to focus on the Summer Olympics as a means of exploring the data and answering some simple questions.

The libraries I used in this project are:

    - Pandas
    - Matplotlib
    - Seaborn
    
## Question 1: What country has won the most medals since 1986 in the Summer Games?

My first question around this data is what country has accumulated the most medals from the summer games? This data runs the course of 130 years - 1896 to 2012 which means it captures 27 summer games. When looking at the top countries, the US has brough home almost 4.6k medals. Russia follows with 2.0k medals. Great Britain, France, Germany, Italy, Australia, Hungary, Sweden and the Netherlands round out the top 10.

Because this was so heavily skewed to the US, I wanted to compare gold medal wins to see if those were a little closer. Again the US was the number one earning country with 2.2k gold medals won. Interestingly, the countries who won the most gold don't follow the same order as the total number of medals. Russia and Great Britan were still the second and third countries in this list, but Italy jumped to the fourth position. Most interestingly East Germany makes an appearance on the top earning gold medal list. They won 329 gold medals when the country existed.

## Question 2: What sport wins the most medals?

I've decided to work with US only data and draw some conclusions. The US as I mentioned has collected nearly 4.6k medals since 1896. Gold makes up the biggest percentage, 49% of the total medal count. Silver represents 27% of the medals and Bronze 24%. When I looked to see where the US earned all these medals, Athletics brought in 994 medals and Swimming won 894 medals. When I think about the nature of these sports, it makes sense. There are a ton of individual and team events that are opportunities for athletes to participate in.

## Question 3: How are team medals accounted for?

I was beginning to wonder how the US amassed *so* many medals compared to other countries. I began to wonder how this dataset accounted for team medals since it lists the individual athletes and the corresponding medal they won. I set about confirming the makeup by checking the 1992 Men's Basketball team, or better known as the Dream Team - I just finished the Last Dance on Netflix so Michael Jordan was top of mind. I filtered my dataset for the year, 1992, and under Discipline, I filtered for Basketball. Up popped all the members of the Dream Team from that fated year. Now the medals were obviously won by the individuals, but when I think about the medal count from watching the games I wouldn't initially think of those as individual medals. Instead I would think of it as one for the US. For this exercise, I'm going to proceed as is. I know the medal count is inflated beyond the number of events at the games, but I can still draw some other conclusions around the data.

## Question 4: How many medals did men win compared to women?

I have gender information so I want to understand how many medals have men won and how many women have for the US. When I look, I see that men have overwhelmingly won the majority of the medals. They've won 3.2k medals where women have won 1.4k. Men have won almost all the medals in Athletics and over half of the Swimming medals. Women on the other hand have won 65% of the Football (Soccer) medals for the US. And interesting shift that I honestly wasn't expecting to see.


## Question 5: Who has won the most medals?

Michael Phelps. I knew that going in but I like to confirm things with my data. I subtotaled each athletes medals to see who has won the most. Phelps came in #1 with 22 medals. The interesting thing I found that the next two athletes who both won 12 medals a piece were also swimmers. Again I think it goes back to the sheer number of events when it comes to swimming. Athletes can participate in individual races as well as relays. There's a lot of room to keep earning those medals.

## Next Steps

This was a really simple exercise in some preliminary EDA. Some of my next steps would be around cleaning the data. I had multiple disciplines that repeated because of certain words being capitalized or the order switched. I should clean my data up and get in deeper. I'd also want to do the tedious but necessary task of separating my individual events from my team events. This way when I'm making my comparisons I'm looking at similiar things.
