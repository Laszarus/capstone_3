# Appleseed 3.0
***
## Introduction
***
My last project ([Appleseed 2.0](https://github.com/Laszarus/capstone_2)) concluded with a CNN that erroneously classified all 
image tiles as "water". In this iteration of Appleseed, my goal was to **remedy this misclassification issue** and **optimize 
the CNN for practical application**. I reached this goal by performing the following steps:

1. Relabeling
2. Restructuring neural network architecture
3. Retraining model
4. Creating output visualization application

## Relabeling 
***
To test my hypothesis that the classification error was due to imbalanced classes, I revamped how I structured my classes. Since the goal of building this network is to identify land available to plant trees, it made sense to re-label all the data as simply "available" or "unavailable" to reduce the complexity of the CNN's task.
