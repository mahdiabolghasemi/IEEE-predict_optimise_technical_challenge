# IEEE-predict_optimise_technical_challenge

This repository contains the forecasting models used to forecast the solar power and buildings power in the IEEE-predict+optimise technical challenge (You can find it at https://ieee-dataport.org/competitions/ieee-cis-technical-challenge-predictoptimize-renewable-energy-scheduling).

To run the script, you would need to install and load the required packages as outlined in the R markdown. 
All the required data are stored in Data Folder in this repositoty.
The script contains some exploratory analysis which is not necessary for running the models but it helps in understanding the dataset.
There are two type of LightGBM models developed in this script including daily and hourly models. Daily LightGBM models uses only daily weather features and hourly LightGBM models uses only hourly weather features. 

Note: most of the preprocessing and exploratory analysis has been removed here for simiplicity. If you need more info, feel free to reach out at m.abolghasemi@uq.edu.au. 
