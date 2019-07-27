# Deep-Learning-Lie-Detection
# Using machine learning models to detect lies based solely on acoustic speech information

Current methods of lie detection are highly inaccurate and dependent on physiological and behavioral patterns. Less research has focused on creating a computational model to automate lie detection. Here I train several machine learning models and a sequential neural network using solely acoustic features in speech for lie detection. Mel-frequency cepstral coefficients (MFCC), energy envelopes, and pitch contours are generated from a balanced dataset of deceptive and non-deceptive speech recordings collected from a 2-person lying game. Predictions on a single audio file were binary, classified as either a truth or a lie.

The best model presented is a majority-voting ensemble learning classifier constructed from a Gradient Boosting Classifier (GBC), Support Vector Machine (SVM), and Stochastic Gradient Descent (SGD) trained on MFCC and energy features. The maximum accuracy for lie detection achieved using this model is 55.8%, which outperforms the baseline chance accuracy of 50% and human accuracy of 48%. These results achieve an incremental improvement on a task which has monumental applications ranging from criminal investigations to national security. 

