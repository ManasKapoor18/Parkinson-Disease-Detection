
# Parkinson Disease Detection

A Machine Learning based model to predict if the patient is suffering from Parkinson or not.


## About Dataset: 

This dataset is composed of a range of biomedical voice measurements from 31 people, 23 with Parkinson's disease.

### Atributes:
name - ASCII subject name and recording number  
MDVP:Fo(Hz) - Average vocal fundamental frequency  
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency  
MDVP:Flo(Hz) - Minimum vocal fundamental frequency  
MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency  
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude  
NHR, HNR - Two measures of the ratio of noise to tonal components in the voice  
status - The health status of the subject (one) - Parkinson's, (zero) - healthy  
RPDE, D2 - Two nonlinear dynamical complexity measures
DFA - Signal fractal scaling exponent  
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation


## Results
Training data and test data was split in 80:20 ratio.  

Accuracy Score of training data:  0.8846153846153846  
Accuracy Score of test data:  0.8717948717948718  

With the increase in data set the accuracy can be improved further.

