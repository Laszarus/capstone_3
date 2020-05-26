# Appleseed 3.0
***
## Introduction
***
My last project ([Appleseed 2.0](https://github.com/Laszarus/capstone_2)) concluded with a CNN that erroneously classified all 
image tiles as "water". I hypothesized this is due to an imbalance of classes. 

## Relabeling 
***
To test this hypothesis, I first plan to revamp how I've structured my classes. Since the goal of building this network is to 
identify land available to plant trees, it makes sense to re-label all the data as simply "available" or "unavailable" to
reduce the complexity of the CNN's task.
