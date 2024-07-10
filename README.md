# Mineral prospectivity mapping with imbalanced data via prior geological transfer learning

## Repository description 📋

We present a framework to address deep learning with imbalanced data using transfer learning to enhance the initialization weights of the classification network. Moreover, we included an additional improvement based on a weighted loss function to increase the performance during the training.

## Database 📋

The data used in this study is protected under an open-access license and is published on the platform of the Yukon Geological Survey (https://data.geology.gov.yk.ca/) and the Government of Canada (https://www.canada.ca/en.html). Data are organized as follows:

* **01_Train_VO.csv**: values of predictive variables X1-X7 at training data points labeled with 0 (non-occurrence) and 1 (occurrence).

* **02_Train_PCA.csv:** values of transformed predictive variables with Principal Component Analysis (PCA). These are called PC1-PC7 and are labeled with 0 (non-occurrence) and 1 (occurrence). 

* **03_Train_Pretext.csv:** values of transformed predictive variables PC1-PC7 at 500 random points labeled with 1 (plutonic), 1 (sedimentary/volcanic), 2 (volcanic), 3 (sedimentary) and 4 (metamorphic). 

* **04_Validation_Points.csv:** values of transformed predictive variables PC1-PC7 at validation points labeled with 1 (occurrence).

## Models 📋

The weights of each trained model were saved in .h5 format.


## Créditos ✒️

* **Ana Gabriela Mantilla:** anagmd2019@gmail.com </br> <a href="https://www.linkedin.com/in/ana-gabriela-mantilla-24377a21a/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="HTML tutorial" style="width:30px;height:30px;">
</a> </br> 
* **Paul Goyes:**   goyes.yesid@gmail.com </br> <a href="https://www.linkedin.com/in/paul-goyes-0212b810/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="HTML tutorial" style="width:30px;height:30px;">
</a>
