

# Fourth Down: Combining the NFL data with Stastical Models

## What and Why
Fourth Down will be a website that allows users to combines  passionate fans a deeper look into the NFL by combining sports data with the field of statistical analysis.

It will be similar to current NFL databases like Pro Football Reference in structure but will deepen that data through the use of various statistical models for analyzing relationships in data. Users will  not only be able to look up data on a certain player or team, but they can also compare performances across seasons, across players, and use the data to gain insight on questions such as what drives offensive success, or what factor most affects a quarterbacks ability to win games.

Rather than requiring users to understand either coding or statistics to run these models and analysis, our model attempts to ultimately appeal to fans by running that analysis, and presenting it through understandable statistics and visuals. For example, when analyzing what makes a successful defense, we can tie data metrics like sacks and interceptions to the site's models to ultimately show what that defense is good at and how historically good their performance in that metric is. 

Ultimately, Fourth Down is valuable because it allows users to move beyond looking up statistics and provide them with a way to understand why and what impacts those numbers. Ultimately,this website gives those fans a new way to connect to a sport they already enjoy. 

## For whom?

Fourth Down is ultimately designed for NFL fans who may already use databases in the form of websites like Pro Football Reference. While these sites provide the metrics and data such as passing yards, they do not necessarily assess underlying factors contributing to the data, nor do they inherently provide a point of comparison against the rest of the league. Using statistical analysis, the fan can gain additional insights and answer certain questions such as whether their performance is due to statistical anomaly or a sustained advantage. Ultimately the app will provide fans with more evidence based analysis and allow them to explore deeper into the world of football. 

It can also provide value to students who are studying statistics. It will provide a real life example of how statistical concepts are used in the real world and provide them with even more data to use for possible football related projects. Ultimately, by using statistial tools in this way, we hope to provide statistic students with even more data to test hypothesises and gain conlcusions from. In this manner, we feel this website would help lead to more advanced analysis of the NFL. THus, statistics students would be attracted by a database that implements the methods they are learning in an easily understandable manner while also being materially impactful to how they view its effect outside the classroom.

## How?
We will take our NFL data from nflverse. We can simplify access to the database using the nflreadpy wrapper, which prevents us from having to download all the numerous datasets. Thus we can spend more time curating our data. As an example, we would combine datasets containing base stats like passing yards, completion percentage and touchdowns, with advanced stat datasets like EPA( expected point added) and WPA(win probability added).

We then conduct statistical analysis using a limited set of methods specified by the team. For example this would include correlation, confidence intervals, statistical regressions, the base descriptive data of a dataset(mean,median,mode,deviation etc), trend analysis over time and hypothesis testing. THis would involved the use of libraries such as scipy and pandas, among others.Ultimately this reusable analysis 

As of right now, the team would specify a certain set of football questions to answer, so as not to rely on artificial intelligence or natural language processing. If viable , future developments could see this feature implemented. By limiting the question scope and the regression scope, the team can successfully map the questions to important variables in the statistics analysis framework. This prevents the team from needing to recalculate statistics for certain questions.

## Scope
Ultimately, this project will most important be a manageable undertaking for a whole semester because we already have a sustainable database to pull data from in the nflverse database, rather than pulling data ourselves. In addition as mentioned above,  These methods can be achieved through use of libraries like pandas and scipy. Saving time on collecting data and implementing calculations can ultimately allow for the time needed to work on integrating it in the website and curating the data as needed.

However, this will still sustain enough of a challenge and most importantly has a broad range of potential statistical methods that can be added to make the project more robust. As mentioned before, while nflverse provides the data needed to sustain our database, we will still need to curate the data in various ways. We will need to combine different data sheets to get a complete list of a player's basic and advanced stats. We might also need to calculate some additional metrics we find valuable that are not already added . 

On the statistical end, the team  will also need to  define certain metrics to answer questions. We must be able to retrieve correct sets of data, apply certain thresholds and filters, handle incomplete data, pass the data through the statistical methods and ultimately connect it to the same interface as the data. Additionally, the team must work on presenting this data in an understandable user friendly way. 



