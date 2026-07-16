# hvac-fault-detection-ml
MSc Project: Fault Detection in HVAC Systems using Machine Learning
Abstract: 
Building managers deal with the problem of fan coil unit (FCU) failure in HVAC (heating, 
ventilation, and air conditioning) systems in buildings. Because of these flaws, buildings lose 
15–30% of the energy that the FCUs use. This thesis looks at fault detection and diagnostics to 
pinpoint the precise fault in the FCU unit to prevent energy waste. After pre-processing and 
data transformation when the data was finally ready, machine learning algorithms that 
attempted to find faults included K-nearest neighbour (KNN), support vector machine (SVM), 
(MLP)multilayer perceptron, and deep multilayer perceptron (DEEP MLP). This model used 
several splits, such as 70-30 % and 80-20 %, to verify the results of all of the models. But in 
order to prevent the model from over-fitting, the term "label noise" was included in the present 
case. As a result, the model operates both with and without label noise. Additionally, 
experiment with a different kernel and optimizer to get better results. All of these models were 
evaluated using the confusion matrix, F1 score, recall and precision. Among all these models, 
the MLP model was the most established since it consistently achieved high testing and training 
accuracies of 0.99 with and without noise 80-20% sample split. This model's robustness in 
recognising intricate patterns in the data while maintaining its capacity to generalise to new 
cases was demonstrated by its low training and testing losses. Moreover, the addition of the 
Adam optimizer and two hidden layers enhanced the MLP's precision in distinguishing 
between fault and non-fault instances. Consequently, the analysis indicates that the MLP model 
is the most effective choice for fault identification. 
