# Predict-Student-Performance-from-Game-Play

For each <session_id>_<question #>, you are predicting the correct column, identifying whether you believe the user for this particular session will answer this question correctly, using only the previous information for the session.

The timeseries API presents the questions and data to you in order of levels - level segments 0-4, 5-12, and 13-22 are each provided in sequence, and you will be predicting the correctness of each segment's questions as they are presented.

Performed cleaning and processing, as well as feature engineering, on a large time series dataset of 5GB.
Developed MLP, CNN, and RNN models for question segment accuracy prediction, achieving an overall F1 score of 0.7917. The enhanced MLP model achieved an improved F1 score of 0.8112.
