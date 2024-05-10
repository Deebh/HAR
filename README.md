HAR
Human Activity Recognition using Smartphone Data

Utilizes machine learning to classify physical activities based on smartphone sensor data.
Conducted with 30 volunteers aged 19-48, performing six activities.
Activities include: WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING.
Data collected from Samsung Galaxy S II smartphones worn on the waist.
Captures 3-axial linear acceleration and angular velocity at 50Hz.
Experiments video-recorded for manual data labeling.
Dataset randomly partitioned into 70% training and 30% test sets.

Data Pre-processing:

Sensor signals (accelerometer and gyroscope) pre-processed with noise filters.
Sampled in fixed-width sliding windows (2.56 sec, 50% overlap).
Body motion and gravitational components separated using a low-pass filter.
Features extracted from time and frequency domains.

Machine Learning Model Training:

Objective: Train a model to classify activities accurately.
Features extracted from pre-processed data.
Models: Decision tree, random forest, support vector machine, neural network.
Performance evaluated on a separate test dataset to assess generalization.

