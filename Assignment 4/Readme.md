

 I am giving you a dataset that contains 70 judgments a subject has made
 about the size of hypothetical people based on their weight (in kilos)
 and height (in inches). The subject has categorized people into three categories - 
 small, average and large. 

The dataset X.csv contains the 70 actual judgments made by the subject as a 70x
3 matrix. The first column contains weights, the second contains heights.
The third column contains the category label assigned by the subject (small = 1, average = 2, large = 3).

I am also giving you a test set y.csv of 10 more weight-height combinations as
a 10x2 matrix (same column interpretations). I want you to tell me what a
generalized context model would predict this subjects' category labels to
be, assuming 

(i) he is polite, and is far more likely to call someone big average than
large
(ii) He is more likely to use weight than height to make category
judgments about size.


Q1. (30 points)

Implement a GCM encoding these assumptions and give me quantitative predictions on
the test set. Submit both code and category responses for the data points. 

Q2. (40 points) I am also sharing with you, John McDonnell's python implementation of Anderson's
 Rational Model of Categorization (rational.py). Modify the code to obtain category predictions for 
the data I have shared with you. 

Q3. (30 points) For both GCM and RMC, show empirically using the dataset I've shared that both models
assume exchangeability of data, viz. the order in which data enters the model does not affect the category
labels of the model for any given subset of data. 
