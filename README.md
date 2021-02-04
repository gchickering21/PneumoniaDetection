# Detecting Pneumonia within CT Scans Using Convolutional Neural Networks

To view the actual report, go to [report.pdf](https://github.com/gchickering21/Pneumonia_Detection/blob/main/report/report.pdf) file

### Prerequisites

Packages that need to be downloaded

```
library(tensorflow)
library(reticulate) 
library(tfdatasets)
library(keras)
library(tidyverse)
library(ggplot2)
library(tfruns)
```

### Setup Instructions

Due to the size of the data that I was working with in this project, I did not upload the data directly to Github. Therefore in order for the extra files in this project to run, one needs to follow the instructions below to set up this project. 

1) While the actual data comes from https://data.mendeley.com/datasets/rscbjbr9sj/3, the best source to download the data comes from https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia. Once on this site, please click the "Download (2 GB) " button that is located on the page. 
2) Once downloaded, please move the data into the report/setup/images folder. This will allow all files within the report folder to properly run and execute. 


### Setup Instructions with Google Cloud Storage

If one wishes to learn how to download the data from Google Cloud Storage to work with their R Studio Account, please go to report/setup/Google_Cloud_Setup_Instructions and follow the list of instructions within this folder. 


### Extra files

Beyond the report itself, one can go to report/setup and view the Convolutional_Neural_Net.pdf file to see further information on how to setup and train a convolutional neural network.

