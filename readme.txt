This script implements supervised learning regression-based models to predict the CO2 saturation levels of 2360 different possible subusurface reservoirs.

The dataset used consists of 59 possible bedform architecture architectures, each with a set of 40 matrix-laminae pairings. This results in a dataset of 2360 entries.
From this dataset, 8 specified bedforms were extracted for testing, and the remaining 51 bedforms were used for training.

The input data consists of both numerical(3) and descriptive(5) features, however this script also allows the use of only numerical features.
The widgets in this script allow the user to test each model with different parameters, and the results of that model are shown with the following:
R2 score, Mean CV score, graph comparing predictions and actual values of the 8 test bedforms.
The feature predicted is 'Saturation' which represents the CO2 saturation capacity for a particular bedform and matrix-laminae pairing (one entry of the 2360 row dataset).

Note: Due to confidentiality, the dataset used for this script cannot be shared, however the "machineLearningOuput.pdf" file found in this repository gives an instance of the script output.