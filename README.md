# weather_analysis
In this project I build weather analysis forecast model using global weather repository dataset
I used statistical model to foreceast future temperature over period of time
I used ARIMA model to forecast tempererature based past temperatures
I used prophet model to forecast temperature for coming 30 days
i used prophet model to analyzed temperature trends and seasonality and patterns over daily basis, weekly bases, monthly basis and yearly basis
I build an esemble model by computing the average of the ARIMA and Prophet mmodel
These project is mainly implemented in functions to make code reusable since statiscal models are mainly limited to one target columns
I will also use deep learning models like LSTM to predict multiple environmont trends silmultaneously
This code contains a lot of comments because when building statisticalmoels you have to split the target columns into two separate dataset based on date to prevent data leakage. This approach can help you to evaluate your model by training on the train set and evaluating against the test set before making forecasting
by this you will already know how well your model is going to make forecast 
