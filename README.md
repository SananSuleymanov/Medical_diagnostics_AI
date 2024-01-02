# AI based medical diagnostics

Django based web application is developed to assist medical institutions in the diagnostics of medical conditions. Currently, it is able to segment cancer area in brain from uploaded MRI image and also, predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status.

MRI cancer area segmentation model is created using UNET architecture and trained on the Kaggle dataset (https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation).
The training notebook of model can be found in train.ipynb.

For the stroke prediction, Logistic Regression model is employed and it is also trained on the Kaggle dataset (https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

You can check how application performs in below-mentioned video. 
Note: The application code is not public.

https://github.com/SananSuleymanov/Medical_diagnostics_AI/assets/92025504/48738c85-434e-4c2a-83dd-118e8886e5f8

