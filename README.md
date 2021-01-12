# Portfolio
Data Science Portfolio

# [Project 1 - Starcraft 2 Performance Storytelling](https://github.com/JasonSpaw/SC2StoryProject)

- In this project I examined the dataset SkillCraft1_Dataset.csv used in a research study performed at Simon Fraser University in British Columbia, Canada <https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0075129>.  Mark Blair, one of the researchers in the study posted the dataset on data.world, where it could be shared for free.  The data was collected from ladder players submitting their replays, which also carry the game stats of the match being replayed, to an online site.  Then game stats where then parsed and stored into one dataset.  Replays on pro players were colllected from various sites that contained databases of profession matches.  The   The story I am attempting to tell using this dataset is what attributes to skill level, league ranking, in

- The purpose for of the project was for school and also to determine the most imparitive areas to focus on for anyone who plays Starcraft 2 and wants to improve
  their ranking on the ladder.

- Visualizations:

![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2_Correlation_Plot.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot1.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot2.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot3.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot4.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot5.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot6.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot7.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot8.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot9.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot10.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot11.png)
![](https://github.com/JasonSpaw/SC2StoryProject/blob/main/SC2%20-%20plot12.png)

- Conclusion:

After visualizing the data its clear to say that most of the variables examined did show a correlation with the league the players played in with the exception of a few like UniqueUnitsMade or UniqueHotKeys, which had no correlation at all with league placement.  What is important to keep in mind is the grouping and range of the datapoints for each league.  For example, you may notice that the data points plotted for Action Latency along bronze league may range 50 to 200, while the range is about 30 to 125 for Platinum, and while professionals range from 25 to 50 milliseconds. Alough, a Bronze player might have a an Action Latency of 50 it does not mean that he is quick to respond, it likely means he is quick to panic and his actions might not be as efficient as a pro.  These instances of panic can be btter observed in the last three graphs comparing APM vs NumberofPACs, ActionInPAC vs NumberOfPACs, and APM vs ActionLatency, all of which have LeaguePlacement encoded for color.  When observing the last three graphs it is easy to see that even gold players can have an APM above 200 and some even having a ActionLatency (average latency to first reaction in PAC) as low as around 40 miliseconds.  As impressive as that may sound when looking at APM vs NumberofPACs and ActionInPAC vs NumberOfPACs we see that there is much fewer NumberOfPacs utilized by these players, meaning that lower level players with high APM and low ActionLatency are likely spamming out of panic or over microing one area of the map, likely focusing too much on a single harrassment or engagement, while neglecting game nessecities such as expanding to more resources or increasing their production or tech while engaging their opponent.  With this being said it is important to take that even though one player may be strong in on aspect or variable they may be weak in others causing them to be ranked lower.  On the flip side, one player may be weak in one area but strong in others causing them to be ranked higher.  What is consistant is that we can observe the ranges of these values narrow as players go up in rank showing that it becomes more of a necessity for a player to hone that skill and become more well rounded.

Although, their is a correlation for most variables, the ones that seem to have the strongest impact on league placement are Actions Per Minute (APM), Action Latency, Number Of PACs, and Select By Hotkeys.  When observing the correlation matrix you can see that these variables are also strongly correlated with each other, showing that improving in one skill will aid in your improvement in the others.  When you take a closer look at these variables it is clear why they would contribute to one another.  NumberOfPACs is the number of PACs per minute.  A PAC is a Perception-Action-Cycle, which takes place whenever a player relocates his/her camera to another location on the map resulting in a perception in which the player has to anylize and react to.  Thus, the greater the number of PACs the more the player is multitasking across the map.  Action Latency is the mean latency (in milliseconds) to the first action within a PAC.  Thus, ActionLatency measures how fast the player reacts once he/she has moved to a new camera loction.  SelectByHotKeys is how many times per minute a player selects units through assigned hotkeys.  Thus, SelectByHotkeys can be seen as a means to measure the efficiency in which a player selects units to command.   APM stands for actions per minute which is self explanatory.  It is just the number of commands per minute.  It is clear to see how a player who is able to multitask (NumberOfPACs), respond quickly (ActionLatency), select desired units or structures as efficiently as possible would be able to achieve a high APM.  What this story truely tells us is that league placement is most correlated with multitasking, effieciency, but most importantly responsiveness, of which ActionLatency narrows the most at the professional level as opposed to bronze compared to other variables showing it becomes more essential at higher ranks.

I correlated age to the size factor in the plots.  It is interesting to see that most players in Grandmater are below the age of 30.

# [Project 2 - Factors on Student Grades Infographic Storytelling](https://github.com/JasonSpaw/EduFactors_Vis)

- The purpose for of the project was for school and also to determine the main contributing factors to students' performance.

- Data used for this project was found on Kaggle at <https://www.kaggle.com/uciml/student-alcohol-consumption> 

- The factors that made the most impact in student performance was found to be the school they attended and their availability of internet which would allow access to a limitless number of resources to pull from.

- Infographic:

![](https://github.com/JasonSpaw/EduFactors_Vis/blob/main/Data%20Vis%20Final%20revised.png)

# [Project 3 - Chicago Crimes Database Design and Implementaion](https://github.com/JasonSpaw/Chicago_Database)

- The purpose for of the project was for school and also to design and create a database containing crime data of Chicago from the year 2012 and then query tables from the database to depict crime in Chicago.

- ERD:
![](https://github.com/JasonSpaw/Chicago_Database/blob/main/DB%20Final%20Project%20ERD.png)

- [Queries ran on database here](https://github.com/JasonSpaw/Chicago_Database/blob/main/Final-Project-Part-III.ipynb)
