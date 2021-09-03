# Invasive-Species-Location-Prediction
This classification model is used to predict what group of invasive species are inhabiting a geographical location in British Columbia Canada. Keep in mind that the dataset only measures 20% of all invasive species in British Columbia. The Classification model we decided to use was the XGB classifier and then used SKlearn in python to train, test and validate data. We used a 60% train, 20% test and 20% validate with a learning rate of 0.1 for 100 epochs. It should be noted that we used 4 features for prediction in the cleaned dataset with the target column being "TAXON_GRP".

![bullfrog_1](https://user-images.githubusercontent.com/81518926/132046825-663471e6-5683-4d8b-b950-3cd8e6eae08c.jpg)
# Instructions for use
You should find 2 csv files, the one labelled FSHQTCNVSV.csv which is the original uncleaned dataset that has multiple features that if you choose to create your model it is open ended. Meanwhile the other labelled invasive_species_data.csv is our cleaned dataset which you can use to run the python notebook labelled invasive_species_Prediction model. The other notebook file was just a test notebook to help us pick our features.
