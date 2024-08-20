# Project: Evaluate transferability of NIR chemometric model between 2 spectrometers


Data challenge - Information and instructions

The goal of this application is to predict a single numeric continuous response (Y). Here is a description of the dataset provided in csv files:
●	The training set contains 400 samples (rows) and the test set contains 100 samples (rows) for which:
○	The known response value in 1st column
○	The predictors (from 2nd column to the last). The predictors are spectral measurements (interaction of a sample and light). The light wavelengths are reported in the headers of the column.

●	The validation set contains 80 samples for which:
○	Y value is missing, to be predicted 
○	Each sample is named as SXXX (where XXX ranges from 001 to 080)
○	Each sample has 400 measurements identified as SXXX-YYY (where YYY ranges from 001 to 400). For example, S001 has 400 spectrums identified as S001-001 to S001-400.
○	Note that the device used to measure the test samples is different from the one used for the training samples.
