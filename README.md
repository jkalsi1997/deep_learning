# Deep learning

Module 21 challenge

1.	What variable(s) are the target(s) for your model? 
The target variable for this model was the ‘IS_SUCCESSFUL’ column. 

2.	What variable(s) are the features for your model?
All the other columns in the dataset, excluding the ‘IS_SUCCESSFUL’, ‘EIN’, and “NAME’ were features in the dataset. 

3.	What variable(s) should be removed from the input data because they were neither targets nor features? 
Both ‘EIN’ and ‘NAME’ were dropped as they were not required. 

4.	How many neurons, layers, and activation functions did you select and why? 
The choices for each figure were made randomly. 
For all the datasets the cut-off values for the application and classifications were the same. 
For the first and third model the random state was 85 whereas the second model was 75. 
The first model had two hidden values defined as 9 and 19 and processed using the rectified liner unit (ReLu) function. The data was trained at 100 epochs and produced a final accuracy reading of 73.66%. 
The first model also had two hidden nodes valued at 7 and 10 and processed via the ReLu function at 100 epochs resulting in a slightly higher accuracy reading of 73.77%. 
The final model had three hidden nodes valued at 10, 8 and 6 and processed using the LeakyReLu function and ran at 60 epochs. This was the least accurate amongst the three models as the model accuracy was 73.61%

5.	Were you able to achieve the target model performance? 
No, unfortunately all the models produced values under 75%. 

6.	What steps did you take to increase model performance? 
The random state, hidden nodes, and epoch values were changed through a series of trial-and-error experiments to obtain the closest value to the target model performance. 

![image](https://github.com/jkalsi1997/deep_learning/assets/141664737/9c127478-9419-4a2c-b43c-d2225cf71806)
