

# Fourth Down: Combining NFL data with Statistical Models

## What and Why
Fourth Down will be a website that lets passionate fans and statistics students dive deeper into the NFL by combining sports data with statistical analysis.

Fourth Down will be similar in structure to current NFL databases like Pro Football Reference, but it will build on that data by using various statistical models to analyze relationships in the data. Users will  not only be able to look up data on a certain player or team, but also compare performances across seasons and players, and use the data to gain insight into questions such as what drives offensive success or what factor most affects a quarterback's ability to win games.

Rather than requiring users to understand either coding or statistics to run these models and analyses, our model attempts to ultimately appeal to fans by running that analysis and presenting it through understandable statistics and visuals. For example, when analyzing what makes a successful defense, we can tie data metrics like sacks and interceptions to the site's models to ultimately show what that defense is good at and how historically good their performance in that metric is. 

Ultimately, Fourth Down is valuable because it lets users move beyond looking up statistics and understand what drives those numbers. This website thus gives fans and students a new way to connect with a sport they already enjoy. 

## For whom?

Fourth Down is ultimately designed for NFL fans who may already use databases in the form of websites like Pro Football Reference. While these sites provide metrics and data such as passing yards, they do not necessarily assess the underlying factors behind the data, nor do they inherently provide a point of comparison against the rest of the league. With statistical analysis, fans can gain additional insights and answer questions such as whether a performance is due to a statistical anomaly or a sustained advantage. Ultimately, the app will give fans more evidence-based analysis and let them explore the world of football more deeply. 

It can also provide value to students who are studying statistics. It will provide a real-life example of how statistical concepts are used in the real world and give them more data for possible football-related projects. Ultimately, by using statistical tools this way, we hope to give statistics students even more data to test hypotheses and draw conclusions. In this way, we believe this website would support more advanced NFL analysis. Thus, statistics students would be attracted to a database that applies the methods they are learning in an easily understandable way while also being materially impactful to how they view its effect outside the classroom.

## How?
We will take our NFL data from nflverse. We can simplify access to the database using the nflreadpy wrapper, which saves us from downloading numerous datasets. Thus, we can spend more time curating our data. As an example, we would combine datasets containing base stats like passing yards, completion percentage, and touchdowns, with advanced stat datasets like EPA expected points added) and WPA(win probability added).

We then conduct statistical analysis using a limited set of methods specified by the team. For example, this would include correlation, confidence intervals, statistical regressions, basic descriptive statistics (mean, median, mode, deviation, etc.), trend analysis over time, and hypothesis testing. THis would involved the use of libraries such as scipy and pandas, among others. Ultimately, this reusable analysis 

For now, the team would specify a set of football questions to answer to avoid relying on artificial intelligence or natural language processing. If viable, future developments could implement this feature. By limiting the question scope and the regression scope, the team can successfully map the questions to important variables in the statistical analysis framework. This prevents the team from needing to recalculate statistics for certain questions.

## Scope
Ultimately, this project will be manageable for a whole semester because we already have a sustainable database to pull data from in the nflverse database, rather than pulling data ourselves. In addition, as mentioned above, we can achieve these methods using libraries like pandas and scipy. Saving time on collecting data and implementing calculations can ultimately allow for the time needed to work on integrating it into the website and curating the data as needed.

However, this website will still present some implementation challenges. For example, as mentioned before, while nflverse provides the data needed to sustain our database, we will still need to curate the data in various ways. We will need to combine different data sheets to get a complete list of a player's basic and advanced stats. We might also need to calculate additional metrics we find valuable that aren't already included. 

On the statistical end, the team  will also need to  define certain metrics to answer questions. We must be able to retrieve the correct data sets, apply thresholds and filters, handle incomplete data, run the data through the statistical methods, and ultimately connect it to the same interface as the data. Additionally, the team must present this data in an understandable, user-friendly way. 



