# Machine Learning Trading Bot

### Purpose
In this challenge I was assume the role of a finanical adviors at one of the top 5 finanical advisory firms in the world. My goal is to enhance the exisiting trading signals by implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.Adjust the input parameters to optimise the trading algorithm and train a new machine learning model and compare its performance to that of a baseline model. I will go about this by establishing a baseline performance and tune the basline trading Algorithm.

### Report Findings

#### Comparing SVM Model to predict Cumulative Returns:
![SVM Plot](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/SVM%20Plot.jpg?raw=true)
![SVM DF](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/SVM%20DF.jpg?raw=true)
![SVM Classification](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/SVM%20Classification%20Report.jpg?raw=true)

The provides SVM provided a 54% accuracy score but a high recall 91% when buying and a low recall 0.08% when selling. Which indicated the model is preforms extremly well when determining when to enter a position.

In conclusion the model did a great job predicting the returns. Regardless of the loss from 2017 - 2018, you would have bigger profit from 2019 to 2021. Therefore the model could be improved by increasing the timeframe. 


#### Tune the Basline Trading Algorithm

#### Adjusting the Time Peroid to 6 Months

![6 Months Classfication Report](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/CF%206%20Months.jpg?raw=true)
![6 Months Plot](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/6%20Months%20Plot.jpg?raw=true)


#### Adjusting the Rolling Windows

![RW Classfication Report](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/Step%202%20CF.jpg?raw=true)
![RW Plot](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/step%202%20plot.jpg?raw=true)

### Choosing Best Parameters
![Step 3 Classfication Report](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/Ste%203%20CR.jpg?raw=true)
![Step Plot](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/Step%203%20Plot.jpg?raw=true)


    
#### Evalutae a New Machine Learning Classifer
Using OG parameters and apply them to the performance of a second machine learning model

- Choosing: AdaBoost, DecisionTreeClassifer LogisticRegression

Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your README.md file. Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

#### Create an Evaluation Report
In the previous sections, you updated your README.md file with your conclusions. To finish this section, add a summary evaluation report at the end of the README.md file. For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created.


### Report Findings

![LRM Plot](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/LRM%20Plot.jpg?raw=true)
![LR Classfication Report](https://github.com/jlaomoc/machine_learning_trading_bot/blob/main/Photos/Logistic%20Regression%20Classifcation%20Report%20.jpg?raw=true)



- Comparing the performance of the machine learning models based on trading predictions that each makes and the resulting cumulative strategy returns. 




