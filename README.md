# Student-Performance-in-Virtual-Learning-Environment
This assignment explores the idea of predicting student performance for a hypothetical university module based on data describing student activity on a Virtual Learning Environment (VLE). It uses two files: log.csv and grades.csv. The first one has the activity log of the student captured on the virtual learning platform and grades.csv has the final grades of the students. I have peformed data characterisation, ABT creation with newly extracted features and classification and evaluation on three different classifiers. In addition to this, I extracted the best features using permutation importance methodology.

# Key Results:
SVM gives a better overall accuracy and F1 score across all labels vs RandomForest and kNN. Predicting Class 3 (distinction) accurately was a problem for all the classifiers. Class balancing and resampling is recommened in such cases.
