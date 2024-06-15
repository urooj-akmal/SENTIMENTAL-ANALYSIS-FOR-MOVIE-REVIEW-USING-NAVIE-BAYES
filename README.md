# NAVIE-BAYES
Bayes Theorem is named for English mathematician Thomas Bayes, who worked extensively in decision theory, the field of mathematics that involves probabilities.

Bayes Theorem is also used widely in machine learning, where it is a simple, effective way to predict classes with precision and accuracy. The Bayesian method of calculating conditional probabilities is used in machine learning applications that involve classification tasks.

A simplified version of the Bayes Theorem, known as the Naive Bayes Classification, is used to reduce computation time and costs. In this repository, we take you through these concepts and discuss the applications of the Bayes Theorem in machine learning. 
Got it! Let's create the **Usage** section from the perspective of potential users who might find your script helpful for verbal interactions with GPT-3.

---

# NAVIE BAYES THEOREM:

Bayes Formula:
![](https://miro.medium.com/max/804/1*6dmvRYysiU5PwWIcHRdKVw.png)

Let’s Look into the terms:

P(C | x) = Probability of event C happening given that event x happened
P(x | C) = Probability of event x happening given that event C happened
P(C) = Probability of event C happening
P(x) = Probability of event x happening

The Bayes Theorem thus gives us a way to find the Conditional Probability . Bayes Theorem lies in the heart of the Naive Bayes theorem.

---

# How to Apply Bayes Theorem in Machine Learning: 

The Naive Bayes Classifier, a simplified version of the Bayes Theorem, is used as a classification algorithm to classify data into various classes with accuracy and speed. 

Let’s see how the Naive Bayes Classifier can be applied as a classification algorithm. 

- Consider a general example: X is a vector consisting of ‘n’ attributes, that is, X = {x1, x2, x3, …, xn}.

- Say we have ‘m’ classes {C1, C2, …, Cm}. Our classifier will have to predict X belongs to a certain class. The class delivering the highest posterior probability will be chosen as the best class. So mathematically, the classifier will predict for class Ci iff P(Ci | X) > P(Cj | X). Applying Bayes Theorem:

P(Ci | X) = [P(X | Ci) * P(Ci)] / P(X)

- In this formula, P(X) is the condition-independent entity, which means it will be constant throughout the classes. It won’t change the value whenever the classes change. Therefore, to maximize P(Ci/X), which can also be termed as the precise answer to be derived, we will have to maximize the P(X/Ci) * P(Ci) value.

- With n number classes on the probability list let’s assume that the possibility of any class being the right answer is equally likely. Considering this factor, we can say that : P(C1)=P(C2)-P(C3)=P(C4)=…..=P(Cn).

---

# Advantage, DisAdvantage of Navie- Bayes Classifier:

## Advantage: 

- It is easy and fast to predict the class of the test data set. It also performs well in multi-class prediction.

- When assumption of independence holds, a Naive Bayes classifier performs better compare to other models like logistic regression and you need less training data.

- It perform well in case of categorical input variables compared to numerical variable(s). For numerical variable, normal distribution is assumed (bell curve, which is a strong assumption).

## Disadvantage: 

- Naive Bayes is also known as a bad estimator, so the probability outputs are not to be taken too seriously.

- Another limitation of Naive Bayes is the assumption of independent predictors. In real life, it is almost impossible that we get a set of predictors which are completely independent.
  
