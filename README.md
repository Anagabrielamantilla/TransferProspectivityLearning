# Mineral prospectivity mapping with imbalanced data via prior geological transfer learning

## Repository description 📋

Mineral prospectivity mapping is crucial for identifying areas with economically valuable minerals. Therefore, several methods based on machine learning have been applied to predict the likelihood of mineral occurrences, especially deep learning (DL), which provides a flexible and precise approach to the use of continuous data. It allows the approximation of predictive variables with probability values related to new ore targets. However, in the early stages of mineral exploration, DL-based methods face a challenge related to class and sampling imbalance due to scarce mineral deposits, resulting in a lack of enough samples to train, limiting the model’s predictive ability. This work proposed a detailed and systematic framework to address imbalanced data issues with prior geological transfer learning and a weighted loss function. We exploited the abundant pixel information of input variables to develop a pretext geological classification and a feature data extraction task as an initializer for the trainable variables of the neural network. The proposed workflow was tested in a porphyry-rich Yukon (Canada) region and overperformed other state-of-the-art classification algorithms such as random forest, support vector machines, and logistic regression. Moreover, our results were contrasted against different geological reports, where our mineral prospectivity map was coherent with regional and local potential assessments of porphyry-type mineral occurrences. The quantitative metrics with a validation dataset suggested that the proposed method can effectively predict mineral prospective areas in different imbalanced data scenarios.

<p align="center">
<img src="https://github.com/Anagabrielamantilla/TransferProspectivityLearning/blob/main/GraphicalAbstract.png" width="900">
</p>

## Database 📋

The data used in this study is protected under an open-access license and is published on the platform of the Yukon Geological Survey (https://data.geology.gov.yk.ca/) and the Government of Canada (https://www.canada.ca/en.html). Data are organized as follows:

* **01_Train_VO.csv**: values of predictive variables X1-X7 at training data points labeled with 0 (non-occurrence) and 1 (occurrence).

* **02_Train_PCA.csv:** values of transformed predictive variables with Principal Component Analysis (PCA). These are called PC1-PC7 and are labeled with 0 (non-occurrence) and 1 (occurrence). 

* **03_Train_Pretext.csv:** values of transformed predictive variables PC1-PC7 at 500 random points labeled with 1 (plutonic), 1 (sedimentary/volcanic), 2 (volcanic), 3 (sedimentary) and 4 (metamorphic). 

* **04_Validation_Points.csv:** values of transformed predictive variables PC1-PC7 at validation points labeled with 1 (occurrence).

## Models 📋

The weights of each trained model were saved in .h5 format.


## How to cite ✒️
Mantilla-Dulcey, A., Goyes-Peñafiel, P., Baez-Rodríguez, R., & Khurama, S. (2024). Porphyry-type mineral prospectivity mapping with imbalanced data via prior geological transfer learning. Gondwana Research.

You can found the details of the research in our paper: https://doi.org/10.1016/j.gr.2024.09.004 

## How to contact me? ✒️
* **Ana Gabriela Mantilla:** anagmd2019@gmail.com </br> <a href="https://www.linkedin.com/in/ana-gabriela-mantilla-24377a21a/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="HTML tutorial" style="width:30px;height:30px;">
</a> </br> 
