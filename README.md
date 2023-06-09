# I70TrafficPredictor
# Problem and Goal
The problem that our group would like to solve is related to the increase in traffic that can be seen on I70 over the weekends and other popular days in the Winter due to skiing. We hope to be able to predict how many cars will pass certain points on I70 each hour. We will focus on the stretch from stations to 205-260 (Golden to Silverthorne). Our goal is to measure this number with an accuracy of 80%.

# Dataset
Our main dataset comes from the Colorado Department of Transportation’s OTIS (Online Transportation Information System). This dataset contains hourly counts of cars passing by specific stations along I70. Our predictor variables will be: Route Capacity, V/C Ratio, Precipitation, and date/hour. Our outcome is the cars passed each hour.

# Planned Approaches
Our planned approach is to use the traffic data as well as data about snow and road conditions to predict the amount of cars that will pass by the monitoring stations along I70. 
The first approach we are going to use is the k nearest neighbors algorithm. Then, we will use a decision tree algorithm, and finally a random forest and compare. If none of these methods provide accurate results, we may move on to adaboosting.

# Previously Completed Research
This differs from research in the field because the majority of predictions made are yearly predictions of overall traffic congestion. There are some daily predictions, but the predictions are based almost entirely on what the traffic was at this time last year. The site https://goi70.com/travel shows some of these predictions. We would differ from this in that we are using actual machine learning to predict an hourly count of cars, which would hopefully be more accurate.

# Stretch Goal
Our stretch goal is to measure the number of cars to an accuracy of 90%. It is likely that we would need to find datasets with more information to better predict the totals.
