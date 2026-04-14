# PredictingMarchMadness

# Group Members
Riley and Johnson


# Abstract
Our project aims to develop a model that predicts March Madness games with more accuracy compared to traditional intuition-based brackets. To do this, we plan to implement multiple different ML algorithms for classification and find one that works best. In addition to quantifying our success rate in predicting games, we would like to generate full brackets for tournaments in our validation set and compare our models performance to human-made brackets (brief overview of typical scores for past years here: https://www.ncaa.com/news/basketball-men/bracketiq/2021-02-12/heres-how-your-march-madness-bracket-will-do-if-you-only-pick-better-seeded).



# Motivation and Question
For both of us, March Madness is a fun part of every spring. With the large amount of data recorded on basketball teams, it is reasonable to suspect that ML algorithms could make fairly accurate predictions for games. The primary use for this project is to make more accurate March Madness brackets, but if it’s successful it could also provide broader insight into which types of teams (ie. playstyles) are more and less effective in the tournament.


# Planned Deliverables

Full Success: We implement a few different classification algorithms and find at least one which works really well for making predictions. The scope of our data also allows for a number of meaningful extensions, such as predicting final scores should we move faster than expected. 

Partial Success: We implement at least one advanced classification algorithm that is able to predict game outcomes with some degree of accuracy. As an aside, determining an acceptable level of accuracy here is relatively difficult. While anything over 50% would represent an improvement over random guessing, the disparity between college basketball teams is really large, and anyone even slightly informed could likely predict results at a rate better than 50%. 



# Resources Required

We have access to a very large dataset containing lots of data on D1 college basketball games (linked here: https://github.com/kim3-sudo/march_madness_data/tree/main/DataFiles) (documentation here: https://march-madness-data.readthedocs.io/en/latest/usage/variables.html#). From this dataset, we can gather pretty much anything we would want to know about. This dataset includes the winner of each game among other things, so we have both feature and target data. The datasets are also segmented by regular season and march madness. To replicate the situation of a bracket, we can use regular season data as features and March Madness game outcomes as targets. This separation will also make it easy to ensure that we are only using features that we have access to before the game we are trying to predict


# What You Will Learn

Johnson: I intend to continue to learn and practice good version control practices. I’ve had some experience using version control through CSCI 0312 Software Development with Professor Andrews, but I’m excited to use version control more during this project. I also plan to practice teamwork effectively by, for example, communicating with Riley, doing my share of the work, being prepared to work on the project, etc. With respect to project material, I’m excited to use deep learning/neural networks because I don’t have a lot of experience with them. I also want to use the correct evaluation metrics for this project (e.g., are true negatives, false positives, false negatives, or true positives most important?).
Riley: As a non-CS major, this is going to be my first major coding project, which I am excited about. In particular, I’m excited to get more practice with version control, as it’s not something I have a ton of experience with. I’m also excited to learn about some more advanced classification models like random forest, as this project will provide the perfect opportunity to do so. 

# Risk Statement

One risk is the unpredictability of March Madness, so even with a lot of data, our model may not perform that much better than a basic strategy like guessing “win” 50% of the time (and, therefore, “lose” 50% of the time). March Madness’ one-game eliminations and the upsets that come with it can make it hard for patterns in the data to consistently translate into accurate predictions. Another risk is dealing with the size/structure of the dataset. The data may take a lot of time to clean everything into a usable format. This could limit how much time we have to test or tune different models.

# Ethics Statement

If our project were successful and deployed, March Madness could be more engaging for fans because predicting brackets would be more informed and data-driven instead of relying purely on intuition and “ball knowledge.” Gamblers have the potential to benefit the most because a model that hypothetically predicts March Madness brackets correctly 100% of the time would give gamblers huge payouts and a lot of money to be made. In contrast, people who don’t have access to machine learning/artificial intelligence models are excluded from the benefits, and gamblers could also be harmed because a successful model would encourage gambling. It could also spoil the fun of March Madness a bit by devaluing people's ability to effectively compete with their friends. We think that the world would become an overall better place under the following two assumptions: 1) increasing the accuracy of predictions in sports could propel the development of those sports, and 2) users will use the model as a tool to support bracket decisions instead of blindly trusting it. With respect to algorithmic bias, our model could be biased toward historically strong teams because of the data. This would then undervalue underdog teams.

# Tentative Timeline
While our dataset is quite large here, the data is split across a number of files, each containing specific information. I expect it to take some time to get our dataset into a usable form containing all of the information we want. Additionally, we’ll need to do some additional research to determine which classification models we want to use. After two weeks, we hope to have our data pipeline in place and a good understanding of the algorithms we plan to implement. Best case scenario would be to have one new algorithm up and running by this point. This will set us up perfectly to implement, tune, and evaluate multiple models over the next week or so, providing us with everything we need to assemble our presentation and finalize other deliverables in the final week.

