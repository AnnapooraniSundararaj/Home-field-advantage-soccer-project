# Home-field-advantage-soccer-project

When it comes to sports, specifically soccer, home and away advantage can be a big factor on many outcomes and statistics during a match. For example, a home team might have home advantage and the referee might be in favor of them and that could lead to less fouls and cards called against them and more for the away team. Many athletes, like ourselves at some point, have stated that they rather play at home due to the atmosphere and not having to worry about traveling and getting exhausted of going to an away field.
“Home field advantage” is a concept in sports that has ties to emotions of the fan base and anecdotal support. I want to be able to report whether data supports this effect, but also which statistics are predictive of this difference to point a casual fan’s eye towards a data-based “why.” This also could help advise folks on when to tune into a team they might only casually support. If this difference is pronounced enough, a fan could be advised to avoid watching matches in which Liverpool is playing away - since results would be negative, and thus less enjoyable for that fan.
This project will investigate whether or not there is an advantage to playing at home or away for the European soccer team Liverpool. Specifically I hope to answer an experimental question with a null hypothesis that models return home statistics when Liverpool are playing home that are equal to away statistics when Liverpool is away, with an alternative hypothesis that my models return home statistics that are better than away statistics for a variety of response variables.

I will be using a combination of datasets provided by Footy Stats that has collected stats from soccer matches dating all the way back to the 2007/2008 season to the end of the 2020/2021 season. These data came in several separate .csv files that have been combined and gone through a processing stage, leaving us with 36 variables, 32 of which are numeric, 4 of which are categorical or descriptive (i.e. “team name”) and 532 rows. Those rows are individual observations of Liverpool matches only. The unprocessed data (which some may return to) has 65 variables and 5320 rows.
Using the EPL Matches data, I hope to answer several questions regarding the relationship between home field advantage or away field disadvantage and goals scored per match. I also want to look at other variables affecting the total goal count for example: attendance and total goal count, Liverpool corner count home and away, Liverpool fouls home and away, Liverpool possession home and away. Using the Liverpool Matches data, I hope to
answer the following questions:
● What kind of impact do referees have for Liverpool when the team is at home and
away?
○ Fouls afford and against them
○ Total yellow and red cards given
● How did the PPG change from playing home and away?
● What was their goal count at home? Away goal count?
● What was the possession at home vs away?

