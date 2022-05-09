# Gaussian-Classifiers

## Type: Academic Individual Project

## Project Description
NCSU ECE 759 (Pattern Recognition & Machine Learning) Software Project
  - Implement a single-Gaussian classifier and a Gaussian-mixture classifier and analyze their performance

## Dependencies
  - See **environment.yaml** in **/code** directory for complete list of dependecies  
  - Anaconda on Windows 10 Education -> Jupyter Notebook
  
## About the Repo.
  - kddo_dfmunoz_code contains **main.py** that are carefully commented.  The algortihm developed is LoG/SIFT.  The input image's size stay constant and is convoled with a Guassian kernel at different sizes. The 2-D convolution is modifed to perform computation in frequency domain using 2-D FFT and iFFT functions using in **ECE 558 (Digital Imaging Systems) Project 1**
  - Final report details the implementations of the functions in this project along with the results + analysis

## Authors
Khoa Do

## Reference
[1]  D. Recchia, “Scale Invariant Blob Detection,” Recchia's Portfolio. [Online]. Available: https://www.drecchia.ca/scale-invariant-blob-detection. [Accessed: 30-Nov-2021].

[2] “DSP Tricks: Computing Inverse FFTs Using the Forward FFT,” Embedded.com, 16-Nov-2010. [Online]. Available: https://www.embedded.com/dsp-tricks-computing-inverse-ffts-using-the-forward-fft/. [Accessed: 30-Nov-2021].

[3] https://github.com/scikit-image/scikit-image/blob/main/skimage/feature/blob.py#L401-L564.

## Additional Notes
N/A
