# Situational Awareness Assisted MmWave Vehicular Beam Training

Data and codes for journal paper **"MmWave Vehicular Beam Training with Situational Awareness Using
Machine Learning"** submitted to IEEE Access. 

The code assumes Python 3. 

## The dataset 
 
We simulate and collect the data in Ray tracing simulation in an urban canyon. An example is given in Fig. 2 and Fig. 3 in the paper. 
The dataset includes the features (defined situational awareness vector of a certain receiver) and the beam RSRP for different beam pairs
used. DFT beam codebook is deployed at the transmitter and receiver. 

### Noisy situational awareness features

In the paper, we consider several different sources of noise for situational awareness. We include the dataset with localization error, 
different connecting rates, and different location reporting frequencies. 

### Channel statistics with UPAs of different sizes  

The dataset includes the channel information with 4x4, 4x8, 16X16 UPA deployed.

To limit the size of data which includes 16^4 = 65536 beam RSRP of over 100K samples, we only include the information of the top 100 beams (including the beam power and the beam pair index) in the data. The beam index file can be found in "beam_index_nx_XXX_ny_XXX. csv" and the corresponding beam RSRP is in "channel_power_nx_XXX_ny_XXX.csv". 

Due to the size limit of uploaded data in github, the data can be retrieved from **Google Drive** through the following link. 

https://drive.google.com/drive/u/0/folders/1v8TmiMa2ATYmFxn2nB9sGDS5e3UcCk_B

## The codes 
The codes include different classification models we apply and the hyperparameters of the models.

# Reference 

If you use any data or code, please cite: "MmWave Vehicular Beam Training with Situational Awareness Using
Machine Learning", Yuyang Wang, Aldebaro Klauta, Monica Ribero, Anthony C.K. Soong and Robert W. Heath Jr., submitted to IEEE Access 2019. 

>Bibtex entry:
```
 @inproceedings{wang19,
 author    = {Yuyang Wang and Aldebaro Klautau and Monica Ribero and Anthony C.K. Soong and Robert W. Heath Jr.},
 title     = {MmWave Vehicular Beam Training with Situational Awareness Using Machine Learning},
 booktitle = {submitted to IEEE Access},
  year      = {2019},
  url       = 
}
```

