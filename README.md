# DeepLearning_Project

Use the yml file to create environment. 

Recommended step :  get all the files from google drive, unzip zip files in the root directory of this repo. (https://drive.google.com/drive/folders/1EiFT7ZjsaKea1Hw-8eZwtyVO1ShS5Fh3?usp=sharing)

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



In short the steps are:
1. create environment using .yml file.
2. Access files from google drive, unzip the zip files in root directory.
3. Run data_prep.ipynb ( you can skip image generation block).
4. Run modeling.ipynb.
