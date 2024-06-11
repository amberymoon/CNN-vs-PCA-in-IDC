# CNN vs PCA in IDC detection
Extracting meaningful information from images is a fundamental challenge in machine learning. 
Convolutional neural networks (CNNs) have proven particularly effective in this task, but face significant challenges due to high-dimensional data. 
Principal Component Analysis (PCA) is a commonly used technique to reduce dimensionality. 

In the field of image-based medical diagnosis, dimensionality reduction without loss of critical information could improve the efficiency of machine learning models. This project explores the use of PCA for the analysis and classification of microscopic tissue images and compares its performance with that of CNNs. 

For the CNN, the ResNet18 model was used with the addition of fully connected layers, while for PCA, the data were compressed into different principal components, and a shallow network was then used for training. 
The results show that while the CNN maintains overall higher accuracy, the use of PCA with significant reduction of the principal components results in a relevant decrease in training time without a drastic loss of performance. However, differences in precision and recall metrics suggest that CNN is more reliable for identifying areas of diseased tissue, although PCA offers significant computational efficiency advantages.
