# Reading material:
## general
- https://towardsdatascience.com/python-for-finance-stock-portfolio-analyses-6da4c3e61054
- https://pandas-datareader.readthedocs.io/en/latest/remote_data.html#iex
- https://ntguardian.wordpress.com/2016/09/19/introduction-stock-market-data-python-1/
## confusion matrix
- https://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/
## backtesting
- https://www.quantstart.com/articles/backtesting-systematic-trading-strategies-in-python-considerations-and-open-source-frameworks
- https://machinelearningmastery.com/backtest-machine-learning-models-time-series-forecasting/

# Project 2 Goals
 
Decision support for trading
The grade is based on the accomplished tasks below and the presentation. Read 
https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0194889

• **Grade 1**: You need to calculate errors for regression forecast of three models, using sMAPE and MASE. Plot in a table and compare models. 

• **Grade 2**: Create a decision, state clearly in the notebook what the strategy is about. The decision taken should be the same as what you describe. Compare decision to optimal decision, present some statistical evidence, e.g hit rate.

• **Grade 3**: Visualize the decision on the price graph, different color each decision. Use an interactive graph. Create a confusion matrix for the decision outcomes.

• **Grade 4**: Calculate the quality of the decision by determining the return on investments (P/L account). Visualize in a graph how the P/L account changes over time. For this grade you may use a library for back - testing if you like.

• **Grade +1**: Choose your own improved model or output. E.g. an ensemble, several outputs and so on. Use this in the above and compare the difference to a baseline.

# Jupyter Notebook

## packages:
- datetime
- numpy
- math
- 
- pandas
  - **from** pandas_datareader.data -- DataReader
- sklearn
  - **from** sklearn.linear_model -- LinearRegression
  - **from** sklearn.model_selection -- train_test_split
- matplotplib.pyplot
