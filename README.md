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
  - The FDDB dataset is included in this repository.  Details about the dataset can be found in [1].
  - **models.ipynb** in **/code** is the Jupyter Notebook that contains the Python implementation of the two models.  The notebook shows how to run each of the models to get the results and plots
  - **data_extracter.ipynb** in **/code** extracts the images from the original FDDB in dataset to **/FDDB** under **negImages** and **posImages**.  The extracted images are then manually picked and divided into training and test set in **/dataset**
  - Final report details the implementations of the functions in this project along with the results + analysis

## Authors
Khoa Do

## Reference
[1]  Vidit Jain and Erik Learned-Miller. FDDB: A Benchmark for Face Detection in Unconstrained Settings. Technical Report UM-CS-2010-009, Dept. of Computer Science, University of Massachusetts, Amherst. 2010.

[2]  A. Singh, “Build Better and Accurate Clusters with Gaussian Mixture Models,” Analytics Vidhya, 31-Oct-2019. [Online]. Available: https://www.analyticsvidhya.com/blog/2019/10/gaussian-mixture-models-clustering/. [Accessed: 11-Apr-2022].

[3]  Prince, S.J., 2012. Computer vision: models, learning, and inference. Cambridge University Press.

[4]  A. Rosebrock, “Intersection over union (IOU) for object detection,” PyImageSearch, 07-Nov-2016. [Online]. Available: https://pyimagesearch.com/2016/11/07/intersection-over-union-iou-for-object-detection/. [Accessed: 11-Apr-2022].

## Additional Notes
N/A
