# Customer Engagement

Last week, I got a chance to participate in a data science competiiton organized by a financial services firm. Competition's aim 
was to define an engagement metric for its users and then build models to separate out engaged users from disengaged ones. Best models 
would then be used directly on their marketing platform to improve customer services, to enhance customer retention and to reduce churn.

Given data was organized in four parts:
1. Device information of each user
2. Various notifications being sent to users 
3. Daily transactions on the platform
4. User profile

My approach to solve this problem was to define an engagement metric solely based on daily transactions of all users. Other data will
then be used to create features for modelling the engaged users. 

This was a very interesting problem to work on and I hope this repository can work as a good reference for people aiming to work in 
financial services industry.

Please refer to **[Transaction Exploration](https://github.com/AD1985/Customer-Engagement/blob/master/TransactionsExploration.ipynb)** notebook for understanding the exploratory analysis and/or go to **[Modelling](https://github.com/AD1985/Customer-Engagement/blob/master/Modelling.ipynb)** notebook to 
look into various algorithms being tried to build a good classifier. 

If you are not interested in codes, please download the html files (TransactionExploration and Modelling) to have a gist of all the 
work done.

Some interesting plots from the analysis are:

**Increasing Transaction Volume
!(Trend-Completed%20Transactions.PNG)


Happy coding and Enjoy Data Science!





