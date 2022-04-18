## histeo_cancer 

Hello, this is an old repository that I had hidden; it contains only a simple notebook with a simple conv net that I did way back. It simply creates a binary classification on a Kaggle dataset. 

The dataset is a computer vision dataset that can be seen in:  
https://www.kaggle.com/c/histopathologic-cancer-detection

#### Code base 
The code was written entirely in PyTorch and is honestly nothing special. 

#### dataset location
The dataset should be placed in assets, and all cells should be easy enough to re-run. To download the dataset, please use the Kaggle API and run:

```kaggle competitions download -c histopathologic-cancer-detection```


#### Sharing results

If you downloaded the dataset, then taking a look into the model should look something like this. 
![Screenshot](/assets/readme_info/samples.png)


Given the fixed random seed, if you choose to retrain the model or use the model uploaded to Kaggle, you should see 95%+ accuracy.
 
![Screenshot](./assets/readme_info/acc.png)
