# Theory : 

Detector : Submarine
Elements to detect : Rocks , Mine

Flow of work : THe submarine sends ultrasonic wave which collide with the element and reflects to the submarine.The submarine receives the wave and predict whether the element is rock or mine.

## Workflow
sonar data ( from rock and metal cylinder ) -> data preprocessing -> train/test/split -> machine learning model( logistic regression model)

Q. Why use logistic regression model as the main machine learning model?
-> The logistic regression model works great with the binary data i.e. 0 and 1 . Here we are going to predict whether it is rock or mine as same as 0 or 1.

Logistic Regression model - supervised learning model
