[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents


## Changed my project from predicting MLB games to predicting NBA players salaries based on their stats
### Completed an initial look at the data and found that we can see correlation with points, assists, and rebounds
I then created new features based on these so I didn't have to deal with large totals of these I created per game stats. It increasses the data's readability and easier to understand. 


### Started to do linear regression and predictions
Based on simple predictions we can get almost 70% of the predicted value determined by the input. This is very promising for the future of the project and making actual predictions in the future.

### Classifying data using decision tree and SVM
First I had to classify my Y category which is salary in my case. I chose to categorize it by low medium and high salaries. I saw overfitting when using the decision tree so that was not very useful but when using the SVM I found the accuracy of my model sitting at around 75%. This is promising to the future of my project but if I were to do this again I would probably add more categories even though it might lower my accuracy.

### Final Tries and Conclusions
After all my efforts stated above and moving on to unsupervised models such as random forrests this project has settled into being very unpredictable. Finishing with scores of around 50% I am not happy with it but it has taught me a few things.
1. Find data with more entries. This dataset only had 199 entries and I think more data and even historical data over the last few years would have been very beneficial to my project.
2. Outside factors. For this project I only used stats on individual players when there are wya more factors that can play into contract negotiations. A couple examples would be team needs and the athlete's popularity. Both things that the player cannot necessarily control and have a stat on.
