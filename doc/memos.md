### 2018_07_10

the architectuer of the network should be checked in the following time.



### 2018-07-16

analysis of normal distribution

memorization: remembering the difference from other samples

data augmentation


工程中一个神经网络往往是train好了的，现实中人类的大脑是可以学习新的事物的，并且不影响原有的知识


### 2018-07-17


做一些测试  在data augmentation的时候，测试是否的确破坏了原有的概率分布

这个需要找一个有明确分布的数据集，比如一个uniform分布  在被“正态”移动之后，他的分布是不是被破坏了

### 2018-07-18

ordinary encoding of labels rather than one-hot encoding,

`mean-squared` rather than `cross-entropy` :

a small network does generalize, with an accuracy of 66%.

next step:

we use techniques from `data augmentation`, while we don't generate new samples(will be explained later).

mathematical explaination(proof).

goal: break distribution of inputs while protect patterns.

### 2018-07-19

finished:

TensorFlow with CUDA support on windows 10.

Intellij Idea Develop environment configuration.


### 2018-07-26

test tflearn first time failed.

works with tensorflow example

differentiating between test error and validation error.

**EX1**

Given the following property of conditional probability:

Additional formula for conditional probabilities:

P(A∪B|X) = P(A|X) + P(B|X) when A and B are disjoint event.

If we split the A into A1 and A2 randomly, A1 and A2 are not disjoint event. From human’s aspect of view, A1 and A2 are same event.

P(A1∪A2|X) = P(A1|X) + P(A2|X) when A and B are not disjoint event.

We want to test will the network fit and their confidence on unseen data.



### 7-30

given two distributions 

say normal distribution and polynomial distribution

when we do MLE, what we get based on statistical procedures?