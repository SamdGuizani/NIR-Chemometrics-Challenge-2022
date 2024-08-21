# Project: Transferability of NIR chemometric model between two spectrometers


In the frame of Process Analytical Technology (PAT) applications, it is likely that the model development and its routine use are done on different instruments. 

**Question**: Are the models developed based on data from a given spectrometer applicable "as-is" to a data from a new spectrometer? If not, what solution can be used without redeveloping a model for the new instrument?

## Description of the datasets

The training set contains 400 samples (rows), and the test set contains 100 samples (rows) for which:
- The known response value in 1st column
- The predictors (from 2nd column to the last). The predictors are spectral measurements (interaction of a sample and light). The wavelengths are in the headers of the column.
- Note that a first spectrometer was used to obtain the data for model training and testing. 

The validation set contains 80 samples for which:
- Each sample is named as SXXX (where XXX ranges from 001 to 080)
- Each sample has 400 measurements identified as SXXX-YYY (where YYY ranges from 001 to 400). For example, S001 has 400 spectrums identified as S001-001 to S001-400.
- Note that the device used to measure the validation samples is different from the one used for the model training/testing samples.
