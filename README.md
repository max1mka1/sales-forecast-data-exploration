# sales-forecast-data-exploration
Data preparation for forecasting task. Project for Jovian cource "Data Analysis with Python: Zero to Pandas". Course Project Final Submission.
This dataset was a test task for building a sales forecast for the month (March 2020). 
We have historical data for 2 full years, as well as 1 quarter of 2020. 
The dataset was provided by "Zolotoe Yabloko" store and shows sales for two brands across three stores.

# Context

In this test task, you need to build a sales forecast for the month (March 2020).
You have historical data for 2 full years, as well as 1 quarter of 2020.
The dataset shows sales for two brands across three stores.
Content

There are 4 files in a dataset:

    sales_train - sales for the period from 2018.01.01 to 2019.03.31
    Items - this table contains common information on brands
    stock - this file contains count of days with zero balance for items
    test_submission - a sample of what the final file should look like.

# Acknowledgements

Thanks to "Zolotoe Yabloko" company for the data provided specially for Zero to Pandas course from Jovian.ml
Inspiration

This task is a forecasting task. The expected content item:
• Carry out preprocessing of data (search for anomalies, removal / cut of outliers, etc.). Conduct time series analysis (graphical presentation, descriptive statistics).
• Summarize the results of the cleaning, data preprocessing. Draw conclusions based on your analysis.
• Feature engineering
• Which of the algorithms is better suited. What data do you think you need to enrich the current dataset for more accurate, effective sales forecasting.
• Construction of a forecast and its assessment. Please comment on your chosen metric to evaluate the forecast. MAE, RMSE, etc? and why. Is it necessary to use CV in this example? Will it give the best result.

# References and Future Work

## TODO - Write some explanation here: ideas for future projects using this dataset, and links to resources you found useful.

For future projects using this dataset, we can predict sales for March of 2020, according to previous sales, that is to make time series analysis: Forecasting-task Kaggle dataset, tasks, information and more (https://www.kaggle.com/maxinstellar/forecasting-task)

Fore time series forecasting exists a lot of solutions, from statistical ones to deep learning methods. You can start from pytorch-forecasting library with neural networks. (https://pypi.org/project/pytorch-forecasting/)

You also can take a try in LSTM time series prediction. It looks very interesting. (https://stackabuse.com/time-series-prediction-using-lstm-with-pytorch-in-python/)

And, if you want to have a good understanding of time series analysis, try to read a book Forecasting principles and practice.(https://otexts.com/fpp2/)

Also, I want to thank the team of Jovian.ml (https://jovian.ml/) for participation in "Data Analysis with Python: Zero to Pandas" project. (https://jovian.ml/learn/data-analysis-with-python-zero-to-pandas). It was very interesting and informative.
