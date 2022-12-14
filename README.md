# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2022

+ Team 2
+ Projec title: Learning fair representations (LFR) vs Maximizing fairness under accuracy constraints (gamma and Fine-gamma)

+ Team members
	+ Ahmad, Zeya za2291@columbia.edu
	+ Kamal, Samira sk4176@columbia.edu
	+ Li, Shuangxian sl4978@columbia.edu
	+ Wang, Weijia ww2589@columbia.edu
	+ Zhang, Yudan yz4346@columbia.edu

+ Project summary:  Our project implements the algorithms described in the given paper Learning fair representations (LFR) and Maximizing fairness under accuracy constraints (gamma and Fine-gamma). To implement the LFR algorithm, we transfered variables to dummy variables, splited data into 2 groups: sensitive group and nonsensitive group and then divided the dataset into training, validation and testing set by 0.6, 0.2 & 0.2 respectively. Eventually, achieved the overall accuracies for training, validation and testing 0.85, 0.57 & 0.56 approximately.

**Contribution statement**: 

Shuangxian Li: She implented to A1 (LFR) and tried to  reduce the training time on a small training set in order to get good result. She also implemented the algorithms described in the (A3)Maximizing fairness under accuracy constraints (gamma and Fine-gamma) and participate in doing presentaion file.

Yudan Zhang: Assisted in the implement of the initial version of A1 (LFR) algorithm, improved the final LFR algorithm, organized & edited Github files, researched on LFR & assisted in PPT. 

Weijia Wang: Researched and helped to write the initial version of A1 (LFR) algorithm. Implemented the algorithm and helped to debug. Edited readme file, uploaded and organized files in GitHub repo.

Samira Kamal: Researched A1 and A3 algorithms, as well as implemented A3 algorithm on COMPAS dataset. Edited Powerpoint and presented our research/code.

Zeya Ahmad: Researched and implemented the A3 algorithm-Maximizing Fairness under Accuracy Constraints on the Bank dataset and the Compas dataset. Edited readme file, uploaded and organized files in our  GitHub repo.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
????????? lib/
????????? data/
????????? doc/
????????? figs/
????????? output/
```

Please see each subfolder for a README file.
