# Projekt zur Daten analyse

Notes on the code:
we are building the model using twi approches :
      1 -VGG16 as features extractor und xgboost as classifier
      2 using CNN
 the first remark on the data that we have unbalanced dataset therfore we used data augmentation 
     * data augmentationt technik that we used is in ppt file
 * Data preprocessing:
    resize  with 224
      why we use 224 ?  because vgg16 take inputs size with 224
  * after extracting the features using vgg16 , we use xgboost for classification
  * xgboost has a bib nammed Gridsearch , we are using this bib for hyperparameters tunning 
  
 
      
   
