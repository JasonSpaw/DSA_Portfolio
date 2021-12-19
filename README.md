# Data Science and Analytics Portfolio

- Jason Spaw
- jp_spaw@outlook.com
- (573) 528-2447

# [Project 1 - Starcraft 2 Performance Storytelling](https://github.com/JasonSpaw/SC2StoryProject)

- In this project I examined the dataset SkillCraft1_Dataset.csv used in a research study performed at Simon Fraser University in British Columbia, Canada <https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0075129>.  Mark Blair, one of the researchers in the study posted the dataset on data.world, where it could be shared for free.  The data was collected from ladder players submitting their replays, which also carry the game stats of the match being replayed, to an online site.  Then game stats where then parsed and stored into one dataset.  Replays on pro players were colllected from various sites that contained databases of profession matches.  The story I am attempting to tell using this dataset is what attributes to skill level, league ranking, in

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

# [Project 4 - Computational Linguistics over Reddit Data](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data)

- For this project, pull Reddit subposts from 5 programming related subreddits into a PostGres database, created triggers to implement vector models to aid in search queries, and analyzed sentiment across subreddits from different fields/job titles related to computer programming, such as datascience, machinelearning, dataanalytics, gamedev (wanted to compare field that might attract more artistic applications), and robitics (to compare a field that might attract those that like to tinker with mechanical engineering side while also applying programming/machine learning). The goal is simple, to observe sentimental trends and see if the users utilizing the subreddits, assuming those posting on the subreddits are working or studying those fields, enjoy their field more than others enjoy theirs as a whole, or perhaps there is very little to no deviation between the fields in which case it is all relative to the individuals. I also looked at topic and phrase modeling to support my claims.

Sentiment Analysis of Programming Subreddits:

![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/DMIR%20Final%20Comp%20Scores.png)

- DataScience appears to have the highest compound score on average, meaning it carries the highest amount of positive sentiment, followed by gamedev and MachineLearning. Not as much enthusiasm in robotics.  As a whole, none of the subreddits experienced any real negativity, with most submissions primarily carrying high neutral sentiment scores meaning that these subreddits are likely more informative and a place for users to help one another with programming related issues and questions.

Topic Modeling:

- I used Non-negative Matrix Factorization to obtain and observe the top ten topic models for each subreddit to visualize what is primarily being discussed in the subreddits.

For datascience:

- Topic  0 data science product scientists years know analyst use like manager
- Topic  1 salary senior month level year median responsibilities years offer couple
- Topic  2 file files access sample number approach second memory _getitem id
- Topic  3 explanatory time models variables customer churn looking user prediction frequency
- Topic  4 different data file way column image proper folder drive text
- Topic  5 like job working work feel role data months break people
- Topic  6 recall user precision data model specific low high set instances
- Topic  7 excel data dashboard help steps qlik like need sql guys
- Topic  8 research papers learning ml week trying like reading think paper
- Topic  9 ve project just work python new use lot methods cool

For MachineLearning:

- Topic  0 space boundaries samples decision label training layer neural output input
- Topic  1 ve learning job position machine engineer experience role ml small
- Topic  2 data feature mlp image tabular learning think extractor trained pre
- Topic  3 spin model vector attention statistical partition mechanics transformer differentiable transformers
- Topic  4 pytorch docker template use source version universal cudnn increase using
- Topic  5 point camera image novel rendering differentiable cloud rasterization neural network
- Topic  6 like voice good sound person data specific ones know make
- Topic  7 data method research nlp readiness academic researchers stakeholders academia projects
- Topic  8 transformer audio representation task speech representations quantized latent model exactly
- Topic  9 3d data vision models computer learning used like world understanding

For dataanalytics:

- Topic  0 omnisci analytics data using aws platform solutions nvidia scaling laptop
- Topic  1 number calls customer customers employees service feature 10 total just
- Topic  2 data analytics masters job help learn sql courses want business
- Topic  3 omnisci data use cns network sites make new ll performance
- Topic  4 event sales data prediction curve fitting weeks events forecast looking
- Topic  5 ibcs company report data reports deliver business think look want
- Topic  6 data science career 000 job analytics openings field technology 2020
- Topic  7 x200b did test using spss expert modeler values acf arima
- Topic  8 health program care course currently appreciate start working year analyst
- Topic  9 analytics ve data thanks problem platforms post responses field research

For gamedev:

- Topic  0 game people lot time nbsp make don job good idea
- Topic  1 game trailer views day know posted people ll twitter things
- Topic  2 game x200b people just blocks games make minecraft like really
- Topic  3 int frame thread lua coroutine scripting java print game using
- Topic  4 server player game new client doing position players connected packets
- Topic  5 items array item tab going displays use window inventory way
- Topic  6 x200b levels short decided make game level stuff finally im
- Topic  7 like game want ve don make use just know art
- Topic  8 object dof matrix need affine regular relative ve seesaw launch
- Topic  9 service cloud provider team shared plan game goes title happens

For robotics:

- Topic  0 robot mm need ready software used controller know fully 250
- Topic  1 engineering program department home computer courses ae ms robotics working
- Topic  2 x200b robotic don place engineer help know year months core
- Topic  3 like start parts pla really buy best white remember black
- Topic  4 problem robot cylinder simulation conveyor robotics help looking kind want
- Topic  5 team foxglove share layouts studio feedback app organization teammates robotics
- Topic  6 robots stacking simple job various deepmind researchers new robotics need
- Topic  7 servo arm little base robot motor gripper add ll just
- Topic  8 control 12v remote pid reverse momentary switch actuators forward moving
- Topic  9 leg battery lift walker raising weight body working help using

Phrase Analysis:

- In this section I combined all post strings into one combined string to analyze the subreddits as a whole. I observed the frequency of individual tokens, as well as the frequency of bi-grams and tri-grams for each subreddit.

For datascience:

![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/datascience%20word.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/datascience%20bigram.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/datascience%20trigram.png)

For MachineLearning:

![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/machinelearning%20word.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/machielearning%20bigram.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/machinelearning%20trigram.png)

For dataanalytics:

![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/dataanalytics%20word.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/dataanalytics%20brigram.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/dataanalytics%20trigram.png)

For gamedev:

![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/gamedev%20word.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/gamedev%20bigram.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/gamedev%20trigram.png)

For robotics:

![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/robotics%20word.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/robotics%20bigram.png)
![](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/robotics%20trigram.png)

Conclusion:

- When comparing the mean sentiment scores across the subreddits, DataScience appears to have the highest compound score on average, meaning it carries the highest amount of positive sentiment, followed by gamedev and MachineLearning, while there was not as much enthusiasm in robotics.  As a whole, none of the subreddits experienced any real negativity, with most submissions primarily carrying high neutral sentiment scores meaning that these subreddits are likely more informative and a place for users to help one another with programming related issues and questions.  Topic models appear to confirm this as they seem to all depict either instructions or what would appear to be news related to that field.  This is even further confirmed when observing the most frequent words, bi-grams and tri-grams, as they are all either related to the field of study or are words, bi-grams or tri-grams that would either indicate a request for help or instructions in response to a request for help on a particular issue, along with common programming commands that might be referred to. Examples that are observed across all subreddits would be data, question, education,  _getitem, get, job, help, need, would, want, know, [would, want], [would, want, know], [try, make], [want, make, sure].  The other high frequency words and n-grams are related to the subject of that particular subreddit. For example, the subreddit datascience contained bi-grams such as [data, science], [data, scientist], [data, analyst], [Data, science].

- Queries performed on Subreddits are found in task 7 of [final-project-p2.ipynb].

Code:

- [final-project-p1.ipynb](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/final-project-p1.ipynb)
- [final-project-p2.ipynb](https://github.com/JasonSpaw/DMIR-Final-Project---Computational-Linguistics-over-Reddit-Data/blob/main/final-project-p2.ipynb)

# [Project 5 - Frequent-Itemset-Mining-Apriori-Alternatives](https://github.com/JasonSpaw/Frequent-Itemset-Mining-Apriori-Alternatives)

This project demonstrates my abilities to perform Frequent Itemset mining using Apriori.

- [Code here](https://github.com/JasonSpaw/Frequent-Itemset-Mining-Apriori-Alternatives/blob/main/alt-itemset-mining-ex.ipynb)

# [Project 6 - Rise in Anti-Vax and Mumps Choropleth Analysis](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps-Choropleth-Analysis)
This was the Final Project I submitted for my Geospatial Engineering Course. 

# Rise in Anti-Vax and Mumps Choropleth Analysis

- Measles, mumps, rubella have been making a comeback in the recent years.  The story I am attempting to uncover is whether the number of cases is correlated with the number of people refusing to vaccinate their children, with recent conspiracy hypes.

- My sources of data can be found at these links.  I primarley webscraped data from charts on the CDC website.

  - https://wonder.cdc.gov/nndss/nndss_annual_tables_menu.asp
  - https://www.cdc.gov/vaccines/imz-managers/coverage/schoolvaxview/data-reports/index.html?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fvaccines%2Fimz-managers%2Fcoverage%2Fschoolvaxview%2Fdata-reports%2Fexemptions-trend%2Findex.html
  - https://www2.census.gov/geo/tiger/GENZ2016/shp

- The audience I wish to reach are who might wish to know whether more concern should be raised over recent numbers of mumps cases, or to give a sight for those who may need to convince a spouse to vaccinate their child.

![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/geo%20mean%20cases.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/geo%20delta%20mean%20cases.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/geo%20delta%20mmr%20coverage.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2011_12.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2012.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2012_13.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2013.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2013_14.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2014.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2014_15.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2015.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2015_16.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2016.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2016_17.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2017.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2017_18.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2018.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2018_19.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2019.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Exempt_Est%20(%25)_2019_20.png)
![](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/cum_mumps_2020.png)

- Conclusion:

Measles mumps rubella vaccine has been a standard vaccination requirement before children entering Kindergarden, triggering an immune response allowing the body to develope anti-bodies and lasting resistance for life.  When comparing the mean number of cumulative mumps out breaks across the nation to the mean percent of population utilizing exemptions by state over time there did not seem to be a clear trend between the two, and perhaps a reverse trend through some time spans.  When comparing the percent of the state population utilizing exemptions to the number of annual cumulative cases of mumps reported there seems to be the same reverse trend for individual states.

These results are not what I expected but could perhaps be explained by some other factor such as travelers bringing mumps from foriegn lands, although the number of people unvaccinated does not help.  The reverse trend in exemptions maybe be do to a lag effect as people are reacting to the news, much like the stock market.  As new cases rise more people may become fearful and vaccinate themselves and their children (especially if a case is witnessed first hand).  As precautions are put in place, the numbers drop and thoughts of conspiracy begin once again.

For my final conclusion, I would have to say that the results are inconclusive and would require a more extensive analysis.  However, I would speculate that the number of people utilizing exemptions might be a response to number of mumps cases, rather than the root cause, although it surely does not help.

- [Code here](https://github.com/JasonSpaw/Rise-in-Anti-Vax-and-Mumps/blob/main/Final_Project_Story%20(1).ipynb)
