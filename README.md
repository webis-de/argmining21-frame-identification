# Frame Identification Shared Task
## Overview
In the frame identification shared task, we seek systems that are able to choose the "primary frame" of a given argument from a set of provided candidate frames. 
## Data
The training data is a subset of the Webis-argument-framing corpus. The corpus contains 12 326  arguments that have been extracted from the debate platform 'debatepedia.com'. Each argument is labeled with its primary frame, where the labels (the names of the frames) are derived from the platform's debate structure. The corpus covers 465 controversial topics with altogether 1623 different primary frames. The dataset used in the shared task contains 2786 arguments on 107 topics and covers the 111 most frequently used frames. For each argument, two frames are sampled as random as negative labels, hence, resulting in 2786 * 3 = 8358 arguments in the training dataset

## Evaluation
The evaluation of the submitted systems will be based on F1 score measure.

## Submission
Submission of the systems will be on www.tira.io
