# Introduction, Regression Analysis, and Gradient Descent

Applications of machine learning include
* Search
* Photo tagging
* Spam filters

Examples:
 * Applications that cannot be programmed by hand
  * Autonomous helicopter
  * Handwriting recognition

Definition

Machine learning: "Field of study that gives computers the ability to learn without being explicitly programmed"

Several types of learning algorithms
* Supervised learning

    Teach the computer how to do something, then let it use it;s new found knowledge to do it
* Unsupervised learning

  Let the computer learn how to do something, and use this to determine structure and patterns in data
* Reinforcement learning
* Recommender systems

## Supervised learning

How do we predict prices of houses?
![](source\01_02_Introduction_regression_analysis_and_gr_files\Image.png)

Problem: How to estimate 750 squere feet price?

Straight line or polynomial? This type of problem is regression problem - predict continuous valued output.

![](source\01_02_Introduction_regression_analysis_and_gr_files\Image [1].png)
Problem finding whether cancer is malignant or benign based on tumor size:
Classification problem - you have discrete classes

For multi-dimension
![](source\01_02_Introduction_regression_analysis_and_gr_files\Image [3].png)


## Unsupervised learning
* In unsupervised learning, we get unlabeled data

### Clustering algorithm
Example Google news
 * Groups news stories into cohesive groups

### Cocktail party algorithm

 Lots of overlapping voices - hard to hear what everyone is saying

Two people talking, microphones at different distances from speakers

 ![](source\01_02_Introduction_regression_analysis_and_gr_files\Image [5].png)

 The problem is to seperate two clean sources of speakers. Easy to do in MATLAB or Octave.

## Linear Regression
Notation (used throughout the course)
m = number of training examples
x's = input variables / features
y's = output variable "target" variables
(x,y) - single training example
(xi, yj) - specific example (ith training example)
i is an index to training set
