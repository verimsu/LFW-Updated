# LFWA-Updated

LFWA (Huang et al. 2007) is a widely used face attribute dataset; however it contains some labelling mistakes.

We relabelled the test portion of the dataset in order to obtain more reliable results in comparing different face attribute learning algorithms. 
Note that the relabelling of test set directly affects the quality of the estimated error, while errors in the training set may be tolerated to some extent by a robust model. 
We share the results as modifications denoting all changes made so that it can be verified, as well as the updated file (label_Updated.mat).

We relabeled the training set for one attribute (Male) as well, so as to measure the effect of training set errors on performance. 
This attribute was also selected because gender classification is an important problem.

In summary, 15 attributes were relabelled. The attributes were selected such that they would be easy to relabel unambiguously and label change was done only when the label error was clear.
