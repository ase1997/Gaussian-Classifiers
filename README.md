# Gaussian-Classifiers

## Type: Academic Individual Project

## Project Description
NCSU ECE 759 (Pattern Recognition & Machine Learning) Software Project
  - Implement a single-Gaussian classifier and a Gaussian-mixture classifier from scratch and analyze their performance
  - The above models classify 10x10 images of face or non-face from the FDDB datatset

## Dependencies
  - See **environment.yaml** in **/code** directory for complete list of dependecies  
  - Anaconda on Windows 10 Education -> Jupyter Notebook
  
## About the Repo.
  - The FDDB dataset is included in this repository.  Details about the dataset can be found in [X].
  - **models.ipynb** in **/code** is the Jupyter Notebook that contains the Python implementation of the two models.  The notebook shows how to run each of the models to get the results and plots
  - **data_extracter.ipynb** in **/code** extracts the images from the original FDDB in dataset to **/FDDB** under **negImages** and **posImages**.  The extracted images are then manually picked and divided into training and test set in **/dataset**
  - Final report details the implementations of the functions in this project along with the results + analysis

## Authors
Khoa Do

## Reference
[1]  D. Recchia, “Scale Invariant Blob Detection,” Recchia's Portfolio. [Online]. Available: https://www.drecchia.ca/scale-invariant-blob-detection. [Accessed: 30-Nov-2021].

[2] “DSP Tricks: Computing Inverse FFTs Using the Forward FFT,” Embedded.com, 16-Nov-2010. [Online]. Available: https://www.embedded.com/dsp-tricks-computing-inverse-ffts-using-the-forward-fft/. [Accessed: 30-Nov-2021].

[3] https://github.com/scikit-image/scikit-image/blob/main/skimage/feature/blob.py#L401-L564.

## Additional Notes
N/A
