This was a contest by techniche, technical festival of IIT Guwahati which was conducted by company Head digital works.
I have uploaded the notebook and the final PDF of the PPT our team submitted.

Dataset contains:   
 Provided feature space contains 22 variables spanning across multiple aspects of customer behavior.
 Temporal variation is captured by a numbered sequence of entries for each customer.
 The goal is to predict Y1 & Y2 which represent customer value and temporal extrapolation respectively.
 Each customer can have N sequenced entries as input and only one set of (Y1, Y2) is expected as output.

And we used Deep Learning and then We have trained two models out of which model(1) had  y1 as target and model2  had both y1 and y2 as their targets.
When generating the prediction for test we considered prediction for y1 from model(1) and prediction for y2 from model(2).
The reason for doing this, we observed higher mse when model for predicting  Y2 was trained alone , but observed lower mse when both y1 and y2 were trained together.

Some Results that we obtained were:
 When Y1 was trained alone approximate MSE value was 3025
 When Y2 was trained alone approximate MSE value was 1122123
 When both Y1 and  Y2 was trained simultaneously approximate MSE value was 556693 
 Due to this we considered  Y2 from the combined model and  Y1 from the stand-alone model for prediction of the test data
 Using the above techniques, we achieved an RMSE of 67.85363

