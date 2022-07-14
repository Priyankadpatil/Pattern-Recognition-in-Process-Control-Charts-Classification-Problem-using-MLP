# Non-Separable Classification using MLP: Pattern Recognition in Process Control Charts – (Classification Problem) 

## Problem Statement 
Evaluate the performance of MLP networks on the problem of pattern recognition in 
process “location” control charts. 

In particular, the neural network is expected to automate the implementation of the run 
rules for control charts based on X-Chart (that plots individual observations across time). 
A process is declared to be out of statistical control when: 
1. A point falls beyond the control limits, usually set at ± three standard deviations 
2. Two out of three consecutive points fall beyond the same ± two standard deviation 
band 
3. Four out of five consecutive points fall beyond the same ± one standard deviation 
band 
4. A run of seven consecutive points falls: 
 a. Above the centerline 
 b. Below the centerline 
5. A run of seven consecutive points falls: 
 a. In a continuous upward pattern 
 b. In a continuous downward pattern 
6. Nine out of ten points fall within the ± one standard deviation band 
Evaluation criteria would include the generalization capability of the neural network and 
the rationale behind the construction of an "optimal" neural network. 
The number of inputs per pattern is 10 (to accommodate runs rule #6) and the number 
of outputs per pattern are 7 (to accommodate a process in control (the first output) and 
each of the 6 runs rules violations). 

## Dataset 
The training data set is made up of 2500 patterns (1000 patterns representing a process in the control and 250 patterns representing each of the six rule violations) 
The testing data set is made up of 250 patterns (100 patterns representing a process in control and 25 patterns representing each of the six rule violations) 

## Methodology 
The following steps are followed to address each problem using MLP: 
1. Data Reviewing 
2. Data Preprocessing 
3. Build a baseline model and optimize parameters 
4. Build and Train Model using optimized parameters 
5. Model Evaluation is done by checking accuracy. 
6. Conclusion 
