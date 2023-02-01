# Learning Bayes [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://github.com/hchiam/learning-bayes/blob/main/LICENSE)

Just one of the things I'm learning. https://github.com/hchiam/learning

## intuition and explanation:

How to use Bayes's rule to update beliefs when given new evidence (hint: ratios): 

https://brilliant.org/courses/knowledge-and-uncertainty/bayesian-thinking/bayes-rule/1/

## backups of some of my old diagrams:

<hr>

## A indep B ⇒ p(A & B) = p(A) \* p(B):

![0.5*0.5=0.25 with overlapping circles, since you don't know the state of the other when one is true](indep.png)

<hr>

## A not indep B ⇒ p(A & B) = p(A if B) \* p(B):

![0.5*0.5=0.25 with one circle enclosed in the other circle, not two separate circles](indep_not.png)

<hr>

## A xor B ⇒ p(A or B) = p(A) + p(B):

![0.5+0.5=1 with two squares taking up the whole space and not overlapping, since they're mutually exclusive](xor.png)

<hr>

## A not xor B ⇒ p(A or B) = p(A) + p(B) - p(A: & B)

![0.75+0.75-0.5=1 with overlapping squares since they're not mutually exclusive and you could have both true at the same time](xor_not.png)
