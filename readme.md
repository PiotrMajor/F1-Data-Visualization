# Formula 1 Data Exploration
## by Piotr Majorkowski


## Dataset

### Context
Formula One (also Formula 1 or F1 and officially the FIA Formula One World Championship) is the highest class of single-seat auto racing that is sanctioned by the Fédération Internationale de l'Automobile (FIA). The FIA Formula One World Championship has been one of the premier forms of racing around the world since its inaugural season in 1950.

### Content
This dataset contains data from 1950 all the way through the 2018 season, and consists of tables describing constructors, race drivers, lap times, pit stops and more.

### Acknowledgements
The data was downloaded from http://ergast.com/mrd/.


## Summary of Findings

In the exploration, I found that there are only a few drivers in history who won over 20 GPs in their careers. Most drivers who ever won a GP, came first in a race only 1 - 2 times. Additionally, I saw that there were some drivers who completely dominated F1 racing and won over 50 GPs in their careers. The most successful driver is Michael Schumacher with 91 wins. Lewis Hamilton and Sebastian Vettel won 73 and 52 GPs respectively. These two drivers are still active; therefore, they could potential stop Schumacher's domination. I saw a similar pattern in the constructors' chart. There were a few teams that completely dominate the sports, while most teams won only a handful of GPs in their history. The most successful team is Ferrari with 236 GP wins. Next, we have McLaren with 178 wins and Williams with 114 victories.

Next, I investigated whether the speed of the cars changed over the years. In general, the average fastest lap decreased from year 2004 to 2015 for allmost all circuits. From 2015 onwards, the speed started to come back again to the values from 2004. I also saw that the speed is very different on each track. For instnance, the Italian GP is the fastest race in the calendar with average speed exceeding 240 km/h. On the other hand, Monaco is the slowest race with average speed below 160 km/h. This was expected, as Monaco GP takes place on the narrow streets of a city.

Finally, I analyzed the difference in speeds by teams in Mozna (Italian GP) and Monaco. Overall, I didn't notice a lot of difference in performace on different tracks by major teams. Seems like, if a car is fast in a high-speed race like Italy, then it should also be fast on a more technical track, like Monaco. For example, McLaren was one of the fastest cars in both Italy and Monaco from 2005 to 2011. On the other hand, Red Bull which completely dominated the sport in seasons 2010 - 2013 (https://en.wikipedia.org/wiki/Red_Bull_Racing), was not very fast in Italy in these years; however, in highly technical Monaco, it was the fastest car on track. One reason that can explain this, is the fact that certain drivers prefer one track over the other; hence, they perform better on their favorite tracks. Another reason can be the fact that these two GPs are a few months apart from each other; therefore, engineers have a lot of time to improve the cars between the races.

I also noticed that Monaco GP had some oddly slow lap speeds which were not present in Italy. I suspect that these were caused by the drivers who did not finish the race due to accidents. This makes sense because the Monaco track has a very small marging for error; therefore, drivers are more likely to crash and not finish the race than in races where the track is wider, like Italy.