Abstract
--------

This paper provides a systematic approach of calculating the effectiveness of a 
Haar Cascade model for detecting objects in a 2d space, in an attempt to 
construct a relationship between the accuracy and training stage. During the 
investigation, we used a set of 2000 positive and 1000 negative images to train
17 stages of a Haar Cascade model, which we then processed through an algorithm
to calculate the accuracy for each stage of the model. We later recognized a 
flaw within our accuracy calculations that undervalued the effectiveness of 
detection in the primitive stages and readjusted our algorithm to include a 
weighted detection rating. This new algorithm provided a more intrinsic, 
truthful dataset that more closely represented the real values. Analyzing the
data produced from both algorithms, we were able to make two major 
observations. Firstly, there lies a critical point, in which the rate of perfect
detections jumps abnormally from 0% to 60~70% within one stage. Moreover, there 
exists a second critical point that occurs after the first, in which the 
accuracies start to diminish as stages progress rather than correlating 
positively with the stages. Using these critical points in conjunction with our
findings, we were able to conclude that the accuracy of the training model 
increases approximately exponentially until it reaches a critical point in which
the accuracy starts to decline. Additionally, there exists an optimal stage 
somewhere between the two critical points that provides the maximum detection 
accuracy.


Work Period
-----------

Start Date: 2019-09-09 


End Date: 2020-06-04


Data and Source Code
--------------------

`Data and source code used to conduct the research is available on request`
