# timelines


Then dropping the Validation set with ‘val_idx = [0]’ for final training of the model.

00:32:30 How to create our Deep Learning algorithm (or model), using ‘ColumnarModelData.from_data_frame()’
Use the cardinality of each variable to decide how large to make its embeddings.
Jeremy’s Golden Rule on difference between modern ML and old ML:
“In old ML, we controlled complexity by reducing the number of parameters.
In modern ML, we control it by regularization. We are not much concerned about Overfitting because we use increasing Dropout or Weight-Decay to avoid it”

00:39:20 Checking our submission vs Kaggle Public Leaderboard (not great), then Private Leaderboard (great!).
Why Kaggle Public LB (LeaderBoard) is NOT a good replacement to your own Validation set.
What is the relation between Kaggle Public LB and Private LB ?

00:44:15 Course review (lessons 1 to 12)
Two ways to train a model: one by building a tree, one with SGD (Stochastic Gradient Descent)
Reminder: Tree-building can be combined with Bagging (Random Forests) or Boosting (GBM)

00:46:15 How to represent Categorical variables with Decision Trees
One-hot encoding a vector and its relation with embedding

00:55:50 Interpreting Decision Trees, Random Forests in particular, with Feature Importance.
Use the same techniques to interpret Neural Networks, shuffling Features.

00:59:00 Why Jeremy usually doesn’t care about ‘Statistical Significant’ in ML, due to Data volume, but more about ‘Practical Significance’.

01:03:10 Jeremy talks about “The most important part in this course: Ethics and Data Science, it matters.”
How does Machine Learning influence people’s behavior, and the responsibility that comes with it ?
As a ML practicioner, you should care about the ethics and think about them BEFORE you are involved in one situation.
BTW, you can end up in jail/prison as a techie doing “his job”.

01:08:15 IBM and the “Death’s Calculator” used in gas chamber by the Nazis.
Facebook data science algorithm and the ethnic cleansing in Myanmar’s Rohingya crisis: the Myth of Neutral Platforms.
Facebook lets advertisers exclude users by race enabled advertisers to reach “Jew Haters”.
Your algorithm/model could be exploited by trolls, harassers, authoritarian governements for surveillance, for propaganda or disinformation.

01:16:45 Runaway feedback loops: when Recommendation Systems go bad.
Social Network algorithms are distorting reality by boosting conspiracy theories.
Runaway feedback loops in Predictive Policing: an algorithm biased by race and impacting Justice.

01:21:45 Bias in Image Software (Computer Vision), an example with Faceapp or Google Photos. The first International Beauty Contest judged by A.I.

01:25:15 Bias in Natural Language Processing (NLP)
Another example with an A.I. built to help US Judicial system.
Taser invests in A.I. and body-cameras to “anticipate criminal activity”.

01:34:30 Questions you should ask yourself when you work on A.I.
You have options !
