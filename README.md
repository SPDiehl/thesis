# Heat Check: Reframing the Hot Hand Fallacy by Incorporating Holistic Performance

The goal of this project was to incorporate the performance psychology concept of "Flow" into an analysis of the "Hot Hand Fallacy."
<br>
The Hot Hand Fallacy proposes that although basketball players and coaches believe a series of consecutive made field goals translates into a higher chance of making the next field goal attempt, this belief is a social cognitive bias attributed to a misunderstanding of the statistics driving streaks and runs. Indeed, in the initial academic study and in multiple follow-up studies, an analysis of field goal percentage after a streak of makes was no different than an analysis of field goal percentages after streaks of misses. 
<br>
The performance psychology concept of "Flow," on the other hand, proposes that humans can enter into a state of heightened performance and productivity - if they meet specific criteria. Many athletes questioned have reported similar feelings associated with being "Hot" on the court as those most commonly associated with entering into a state of "Flow"
<br>
Statisticians, who, presumably, have never felt like they can't miss, have been asking the wrong question. Getting hot was never about a rigid analysis of streaks. Its about playing well, and feeling good about playing well, and entering into a flow state where you can be expected to continue to perform well.
<br>
Thus, the inspiration of this project was to understand whether or not a holistic analysis of players production on the court - not just shooting stats, but incorporating assists, blocks, steals, and rebounds - might provide a proxy metric for determining players who have entered into a flow state. Statisticians, who, presumably, have never felt like they can't miss, have been asking the wrong question. 
<br>
The goal was to prove that players who have entered into a flow state can be expected to make their field goals at a higher percentage than those who have not entered into a flow state, and to prove that holistic analysis of actual performance relative to expected performance can provide useful insights to be incorporated into further studies. 
<br>
The proxy for a flow state was calculated by comparing the players' actual holistic performance on the court, across five statistical categories, and subtracting the expected statistics based on the amount of time they have played in the game - compiled into one variable called Heat. Then, this metric was normalized compared to the rest of the league to provide a representation of how many standard deviations away from the average a player was over- or under-performing. 
<br> 
To measure the expected averages, this project used the Simple Projection System statistics provided by Basketball Reference. This methodology for projections does not yield results that you can expect to make you money in Vegas by betting on player props; it does, however, provide an incredibly useful and surprisingly accurate yardstick against which we can measure actual performance. 
<br>
Indeed, projecting accurate per 36 statistics would constitute a thesis in and of itself, and therefore Simple Projections were considered within an acceptable range of error (11% RMSPE) for the purposes of this project. The RMSPE was also influenced in no small part by the fact that per 36 statistics are heavily skewed for players who don't record significant time on the court - for example, Qi Zhou recorded a per 36 statline of all zeros, except for 72 points.
<br>
The statistical analysis performed included filtering all shots made for players with a Heat greater than zero and all shots for players with a Heat less than zero. Then, a hypothesis test for comparing two systems of proportions was used to compare each of these against the totals for the season. 
<br>
Finally, a classification algorithm was used to determine whether or not Heat would provide useful for classifying shots as makes or misses. In other words, whether or not a players actual holistic performance on the court minus their expected holistic performance, relative to the league average, would improve the accuracy of classifying shots as makes and misses. This was simply to provide a litmus test, of sorts, to prove that previous experiences on the court indeed affect future outcomes.
<br>
<br>
<br>

The notebook titled "Heat Check" contains the data methodology and data analysis.
<br>

The notebook titled "Stats Projections" contains some error analysis on the projected statistics I used.
<br>

The projections csv file contains the projected per 36 statistics translated into seconds.
<br>
<br>
I'll be sure to come back and update some of this for readability and add some graphs as well.


