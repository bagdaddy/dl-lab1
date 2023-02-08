### 1 individual task
#### Order

**The deadline for the settlement of the first task for the maximum score is March 15.**

(Plan your time, don't leave tasks for the last weeks, it is possible to apply for the maximum score in the week when the presentation started.)
The presentation sequence and the week when presentations begins are fixed
by the time the task was uploaded to the Github environment.
**Each task must have a solution implemented with clearly named variables and documented.**
At the beginning of the assignment, there must be information with the author's name, surname and LSP number and variant.

Each decision is evaluated according to the evaluation of the task the specified number of points.
During the presentation, the teachers of the exercises may ask for a comment or
change the program.
**Maximum evaluation of the task (without additional points) - 2 points.**
The task can be revised during the semester. The version of the task is written at the top of the document, and potential changes are noted.

#### Evaluation

The first task can be scored without additional points up to 1 point, with additional points up to 1.2 points.

Evaluation components:

| | Requirement | maximum rating |
|---|---|---|
| $A$ | Correct operation of the program, commenting on the program and answers to questions, modification of the program during checkout, | 2.0 |
| $P_1$ | Bonus point: Checkout early | 0.2 |
| $B$ | **Total** | 2.2 |



The final assessment score of the task is formed by:

$$
B = A + P_1
$$

Additional score $P_1$ for the earlier submission week:



| Week | February 22 | March 1 | March 8/15 | March 22 |
|---|---|---|---|---|
| Extra/Penalty Point | 0.2 | 0.1 | 0 | -0.5 |


At the submission of deadline week half of the maximum rating remains - 0.5 points. 6-16 weeks Task 1 is no longer available for presentation.

#### Task

The first task will require the realization of:
* usage of existing pre-trained (pre-trained) image classification model adaptation to new task using **few-shot**,**one-shot** and **zero-shot** learning. 
* calculate accuracy, precision, recovery and F1 statistics for selected new class on unseen 1000 images from [OpenImages](https://storage.googleapis.com/openimages/web/index.html),
* to implement threshold value (_threshold_) change, enabling classification of images for each assigned class by changing $T \in [0,1]$. Statistics must be recalculated after changing the threshold value.

Students themselves choose new class for which the model will be adapted and statistics will calculate.


At presentation, the exercise instructor will send test images with which you will need to demonstrate how the model you used works.
