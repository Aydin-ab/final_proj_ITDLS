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



## References
Impact of JPEG 2000 compression on deep convolutional neural networks for metastatic cancer detection in histopathological images
https://www.spiedigitallibrary.org/journals/journal-of-medical-imaging/volume-6/issue-02/027501/Impact-of-JPEG-2000-compression-on-deep-convolutional-neural-networks/10.1117/1.JMI.6.2.027501.full?SSO=1

Keeping the Bad Guys Out: Protecting and Vaccinating Deep Learning with JPEG Compression
https://www.semanticscholar.org/paper/Keeping-the-Bad-Guys-Out%3A-Protecting-and-Deep-with-Das-Shanbhogue/8ab5d59c6534039e6854cdb60a8519e0e96bde03

Difference between JPEG and PNG
https://www.tutorialspoint.com/difference-between-jpeg-and-png#:~:text=JPEG%20and%20PNG%20both%20are,is%20present%20in%20PNG%20format.

Does repeated JPEG compression ruin images?
https://blog.kasson.com/the-last-word/does-repeated-jpeg-compression-ruin-images/

Compression in the ImageNet Dataset
https://towardsdatascience.com/compression-in-the-imagenet-dataset-34c56d14d463
