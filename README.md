# BankNote_Authetication_Naive_Bayes
### Problem Definition
* The task here is to predict whether a bank currency note is authentic or not based on four attributes i.e. variance of the image wavelet transformed image, skewness, entropy, and curtosis of the image

* The dataset used is from the Kaggle. It uses the pywavelets package to gather variance, skewness, curtosis and entropy of each given banknote image. 
* Each image is binarily classified based on these attributes as either real (class = 1) or fake (class = 0).

* About this file Data were extracted from images that were taken from genuine and forged banknote-like specimens. 
* For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels.
* Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained.
