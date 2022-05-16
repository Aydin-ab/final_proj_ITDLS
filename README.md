# Final Project ITDLS
Final Project for the ITDLS course

The notebook serves as a report for the 2 main experiments of this project.


## Description of the project


Computer Vision focus on image and video analysis and some tasks need tremendous amount of images and video data to train deep learning models. Thus, dataset size can be an issue in the scaling and deployment of such systems. The project's idea is to see if data compression can help to ease this constraint without losing too much on the system's performance.

The project's goal is to analyze, describe and interpret the influence of different compression algorithms on the performance of Computer Vision systems.
We study the effect of JPEG compression (lossy compression) and WebM compression (lossless compression) on the CIFAR-10 dataset for a classification task using a Convolutional Neural Network.

## Description of the repository and code structure
The repository is only composed of a notebook which you can run to obtain every result of the project. The code is divided in 2 main experiments : the JPEG compression and the WebM compression. I have implemented special code to launch the training jobs on Greene (which is where the plots are from) but they are similar to the notebook. It was not possible to run the entire notebook on Greene since the jobs kept being cancelled due to low GPU usage (~30%)

## Example commands to execute the code         
No example commands to execute the code, just run the notebook

## Results (including charts/tables) and your observations  
Results and observations are available in the notebook and it would have been redundant to put them here all over again
