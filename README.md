# Situational Awareness Assisted MmWave Vehicular Beam Training

Data and codes for journal paper "MmWave Vehicular Beam Training with Situational Awareness Using
Machine Learning" submitted to IEEE Access. 

The code assumes Python 3. 

## The dataset 
 
We simulate and collect the data in Ray tracing simulation in an urban canyon. An example is given in Fig. 2 and Fg. 3 in the paper. 
The dataset includes the features (defined situational awareness vector of a certain receiver) and the beam RSRP for different beam pairs
used. DFT beam codebook is deployed at the transmitter and receiver. 

### Noisy situational awareness features

In the paper, we consider several different sources of noise for situational awareness. We include the dataset with localization error, 
different connecting rates, and different location reporting frequencies. 

### Channel statistics with UPAs of different sizes  

The dataset includes the channel information with 4x4, 4x8, 16X16 UPA deployed. 

## The codes 
The codes include different classification models we apply and the hyperparameters of the models.


