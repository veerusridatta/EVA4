Model -1:
Targets:
Base model and working code

Results:  
Number of Parameters = 122,256
Best Train Accuracy = 99.41
Best Test Accuracy = 99.06

Analysis:
No overfitting as gap between train and test accuracy is less.
We can push this model to increase accuracy.
Reduce number of parameters

File Link:
https://github.com/veerusridatta/EVA4/blob/master/Session_5/Assignment_5_1.ipynb


Model -2:
Targets: Add Batch Normalization to increase model efficiency.

Results:  
Number of Parameters = 9,752
Best Train Accuracy = 99.62
Best Test Accuracy = 99.29

Analysis:
Batch Normalization has improved the model efficiency
This model can be pushed further to improve efficiency,

File Link:
https://github.com/veerusridatta/EVA4/blob/master/Session_5/Assignment_5_2.ipynb

Model -3:
Targets: Image augmentation to transofrm the images with rotation of +-20 degree.

Results:  
Number of Parameters = 9,752
Best Train Accuracy = 99.03
Best Test Accuracy = 99.43

Analysis:
Train accuracy is reduced.
Model is overfitting/good

File Link:
https://github.com/veerusridatta/EVA4/blob/master/Session_5/Assignment_5_3.ipynb

Model -4:
Targets: Image aumentation with StepLR to adjust Learning Rate

Results:  
Number of Parameters = 9,752
Best Train Accuracy = 99.03
Best Test Accuracy = 99.42, 41, apperaed more times

Analysis:
Train accuracy is less compared to test accuracy due to transformation images in train dataset
Benchmark appered for mutliple epochs 

File Link:
https://github.com/veerusridatta/EVA4/blob/master/Session_5/Assignment_5_3.ipynb

Model -5:
Targets: Image aumentation with Dropout and ADAM optimizer 

Results:  
Number of Parameters = 9,752
Best Train Accuracy = 98.71
Best Test Accuracy = 99.40

Analysis:
Model is working well
Model still have capacity to push further to improve efficiency

File Link:
https://github.com/veerusridatta/EVA4/blob/master/Session_5/Assignment_5_5.ipynb





