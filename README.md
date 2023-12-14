# Mineral prospectivity mapping with imbalanced data via prior geological transfer learning

## Repository description 📋

We present a methodology to address deep learning with imbalanced data using transfer learning to enhance the initialization weights of the classification network. Moreover, we included two additional improvements based on bias initialization and weighted loss to increase the performance during the training.

## Database 📋

The data used in this study is protected under an open-access license and is published on the platform of the Yukon Geological Survey (https://data.geology.gov.yk.ca/) and the Government of Canada (https://www.canada.ca/en.html). Data are organized as follows:

* **01_Train_VO.csv**: values of predictive variables X1-X9 at training data points labeled with 0 (non-occurrence) and 1 (occurrence).

* **02_Train_PCA.csv:** values of transformed predictive variables with Principal Component Analysis (PCA). These are called PC1-PC9 and are labeled with 0 (non-occurrence) and 1 (occurrence). 

* **03_Train_Pretext.csv:** values of transformed predictive variables PC1-PC9 at 500 random points labeled with 1 (plutonic), 1 (sedimentary/volcanic), 2 (volcanic), 3 (sedimentary) and 4 (metamorphic). 

* **04_Validation_Points.csv:** values of transformed predictive variables PC1-PC9 at validation points labeled with 1 (occurrence).

* **01_VO.tif:** raster composed of 9 bands, each corresponding to a predictive variable (X1-X9). You can find it in the following link: https://drive.google.com/drive/folders/1Tzrwo7I5K2xme8V4gTtiNTsujbVZHICD?usp=sharing

* **01_VO.tif:** raster composed of 9 bands, each corresponding to a transformed predictive variable (PC1-PC9). You can find it in the following link: https://drive.google.com/drive/folders/1Tzrwo7I5K2xme8V4gTtiNTsujbVZHICD?usp=sharing

## Models 📋

The weights and biases of each trained model were saved in .h5 format.


## Créditos ✒️

* **Ana Gabriela Mantilla:** anagmd2019@gmail.com </br> <a href="https://www.linkedin.com/in/ana-gabriela-mantilla-24377a21a/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="HTML tutorial" style="width:30px;height:30px;">
</a> </br> 
* **Paul Goyes:**   goyes.yesid@gmail.com </br> <a href="https://www.linkedin.com/in/paul-goyes-0212b810/">
  <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="HTML tutorial" style="width:30px;height:30px;">
</a>

## Cómo citar ✒️

* X.

Este código se encuentra protegido bajo una licencia de libre acceso que tiene las siguientes condiciones: 

- Se requiere la preservación de los avisos de derechos de autor y licencia
- Se prohibe el uso de estos códigos con fines lucrativos
- Los autores no se hacen responsables del uso de los códigos por parte de terceros
- En caso de modificaciones al código, deben especificarse en un apartado donde se cite la fuente original de este: https://github.com/Anagabrielamantilla/MineralProspectivityPrediction 
- No se permite la publicación de este código en otras plataformas bajo ninguna circunstancia sin consentimiento de los autores

**Los autores prohiben eliminar, borrar o modificar este apartado**
