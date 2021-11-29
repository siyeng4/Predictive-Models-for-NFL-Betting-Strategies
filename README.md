# Predictive-Models-for-NFL-Betting-Strategies
DSC 478(Programming Machine Learning Applications) Final Project 

Online sports betting is becoming legalized and more ubiquitous in many states. Unlike many other forms of betting (ex. poker, blackjack, roulette, craps, etc.), sports betting isn’t predicated on pre-defined and well known probabilities/odds. The inspiration for this project is to assess if through the use of machine learning there are any interesting findings that could lead to successful betting strategies for NFL game betting. We will attempt to accomplish this by leveraging the "NFL Scores and Betting Data" data set on Kaggle found here, https://www.kaggle.com/tobycrabtree/nfl-scores-and-betting-data. To give this a real world goal and metric to compare against we'll also perform a comparison on expected returns our models could have versus major stock indices like the S&P 500, Dow Jones, and NASDAQ to give a sense of opportunity cost.

To try to answer these questions, we first used clustering in order to see if there were any interesting groups in the data. As it turned out, most of the data clustered in one big blob, leading to poor clustering results. This poor result somewhat indicated that we would see less than stellar results from our next task, which was applying supervised learning techniques. The supervised learning methods we attempted were k-nearest neighbors, decision trees, and logistic regression. From all three of those methods, we saw rather poor performance, which the classifiers being roughly the same as random chance. We did see some elevated performance from predicting specific cases, such as looking at only the predictions for bets of the over-under being over. Though, the overall poor performance does not instill a lot of confidence in using these models widely.

While in the scope of our project, we found poor results, there are further avenues to explore that could lead to more fruitful results. One of the major additions would be to add more variables, specific variables relating to team performance, to the dataset. We saw in our analysis that the four variables that related to team performance were in important to many models. Other learning techniques could be tried, such as SVM or even ensemble techniques that leverage multiple models.
