# MNIST-w-SVM---High-Accuracy
Jupyter notebook running SVM (RBF kernel) w/ data augmentation (using scipy's ndimage) to classify handwritten digits. A OneVsRest classifier were used to allow multi-class classification and a Bagging classifier was added to improve generalization. Validation was used for hyperparameter tuning. High accuracy (~98%) was achieved on the test set.

What makes this model unique is that it achieves high accuracy even with an SVM classifier, by (a) using an RBF kernel, (b) data augmentation (shift only, but others can be added) and (c) an ensemble (bagging) approach.
