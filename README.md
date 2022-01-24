# Handwritten_Digit_Recognition_with_SVM+Ensemble
Jupyter notebook running SVM (RBF kernel) w/ data augmentation (using scipy's ndimage) to classify handwritten digits from the MNIST dataset. A OneVsRest classifier were used to allow multi-class classification and a Bagging classifier was added to improve generalization. Validation was used for hyperparameter tuning. High accuracy (~98%) was achieved on the test set.

What makes this model unique is that it achieves high accuracy and good generalization even with an SVM classifier by using (a) data augmentation (shift only, but others can be added) and (b) an ensemble (bagging) approach. The power of data augmentation in improving generalization is also seen in the neural network model built subsequently.
