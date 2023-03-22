# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2023

+ Team # 3
+ Team members
	+ Kaitlyn Brown
	+ Jinghan Huang
	+ Zhi Huang
	+ Chenghao Lu
	+ Denise Rahmadina
	+ Mingze Xu

+ Project summary: In this project, we created two versions of a model to perform image classification given training data with noisy labels and a baseline logistic regression model with a 24% accuracy. In our first model, we ignore the issue of noisy labels and implement a convolutional neural network that is able reach validation accuracies in the 40-50% range. In our second model, we use weakly supervised learning techniques to first address the issue of noisy labels. We are given 10,000 data points with labels that are known to be clean and use those data points to train a convolutional neural network. We then run our remaining training data with potentially noisy labels through that convolutional neural network and output new labels for those data points. Those data points and their new labels are then used as the input training data for the first model (also a convolutional neural network). The second model is able to reach validation accuracies in the 70-80% range.
	

**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. Denise, Chenghao, and Jinghan worked on model one. Kaitlyn, Zhi, and Mingze worked on model two.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
