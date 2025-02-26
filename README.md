# p4score

This is a repository used for explaining how to create a python package and publish it on GitHub.
The whole tutorial can be found at: https://medium.com/@thomas.vidori/eebc78b2a12d

This repository is a screenshot of the original repository: https://github.com/TVidori/p4score before it got versioned.
It is purely used to illustrate the tutorial, the original repository should be used if you want to use the package.

### Purpose

This package allows you to calculate the p4-score of a machine learning model prediction. See my tutorial about what the p4-score is at https://medium.com/@thomas.vidori/903242e9545b or the Wikipedia page at https://en.wikipedia.org/wiki/P4-metric.


### Installation

Run the command:
`pip install git+https://github.com/TVidori/p4_score_pre_verioning.git`


### Usage

A quick example displaying how to import and use the package:
````python
import p4score

p4score.calculate_p4score(85, 10, 1, 4)
````