DIABETIC RETINOPATHY

The CNN model built using Keras attempts to classify Diabetic Retinopathy by employing transfer
learning and hybrid methodology. The project also employes ensemble modelling 
to further increase the accuracy. 

Model 1 - Inception V3 for feature extraction and Logistic Regression for classification

Model 2 - Xception for feature extraction and Logistic Regression for classification

Model 3 - MobileNet for feature extraction and Logistic Regression for classification

Ensembling based on Mode.


Further, a web application has been built.

Step 1 - Keras model deployed to a flask web-service.

Step 2 - Accessing the CNN deployed to flask over HTTP.


The simple web application accepts the Retinal fundus image from the user and respondes
back with the grade/ predictions.
