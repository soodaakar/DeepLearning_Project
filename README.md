# DeepLearning_Project

Use the yml file to create environment. 

This project has 2 main files to run.
1. data_prep.ipynb : - 

Reading data has 2 parts to it.
  1. Reading the csv file which has patients demographic information and diagnostic statements.
  2. Reading the wave form based on the specified sampling frequency, they are storing in signal formats, we use wfdb to read these kind of signals.

After these 2 steps we convert these signals using python library ecg_plot(https://pypi.org/project/ecg-plot/).

The image generation process is quite time consuming, we have already generated them and saved in google drive.
Which can be accessed using https://drive.google.com/drive/folders/1EiFT7ZjsaKea1Hw-8eZwtyVO1ShS5Fh3?usp=sharing.

Copy all of the files from google drive in root directory, unzip the zip files and directly run the modeling code.


2. modeling.ipynb:-

Data preparation step has already added all the required files. 
you can either.
1. Run the model and save .h5 files again or
2. skip directly to load model section of every model, load the model and check the results.
