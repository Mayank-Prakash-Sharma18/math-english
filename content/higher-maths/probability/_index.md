---
# Course title, summary, and position.
linktitle: Introduction to Probability
summary: This is a basic introduction to Probability.
weight: 3

# Page metadata.
title: Introduction to Probability
date: "2018-09-09T00:00:00Z"
lastmod: "2020-11-03T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  probability:
    name: Overview
    weight: 1
---

Probability - In layman terms, we can say that it is an attempt to <strong>quantify our prediction</strong> about the future events, i.e. it is the estimate of the likelihood of occurrence of an event.

Before we dive into Probability and try to define it in even better terms, we must first learn about the very basic concepts of an event.

## Event - Basic Concepts 

### Random Experiment

* there is more than one possible outcome and all possible outcomes are known.

* the exact output cannot be predicted in advance.

For example, on flipping a coin we know that either head or tail will come. But we cannot predict that in advance. 

### Biased and Unbiased Experiment

* Unbiased experiment - all possible outcomes are equally likely to occur.

* Biased experiment - all possible outcomes are not equally likely to occur.

For example:

When we throw a die, if the likelihood of getting one or more numbers is more than that of the other  numbers, we say it is a biased die. If all the six numbers are equally likely, then we call it an unbiased die. 

Similarly, a coin will be an unbiased or a biased coin depending on whether the head and tail are equally likely or not. 

Unless otherwise specified a coin or a die is considered as unbiased.

##### Q. The probability of a dice showing a 6 on being rolled is 1/6. If the first 5 rolls of this dice have brought 1, 2, 3, 4 and 5 respectively, then which of the following is correct with regard to the sixth roll of the dice?
(a)	The dice would certainly show a 6. <br>
(b)	The chances of a 6 coming up has increased. <br>
(c)	The chances of a 6 coming up remains the same. <br>
(d)	Both (a) and (b)

Explanation:<br>
<div class="Exp">

Subsequent rolls of a dice are independent of the previous outcomes. The probability of 6 coming on any roll of the dice remains the same, i.e. 1/6. 

Answer: (c)
</div> <br>

### Elementary Event and Sample Space

* Elementary Event  - each possible outcome in a random experiment. 

* Sample Space (denoted by symbol S) - The set of all possible elementary events (outcomes) of a random experiment is called the sample space associated with the experiment. 

For example:

When we roll a die, the possible outcomes of this experiment are 1, 2, 3, 4, 5, or 6. Each one of these is an elementary even associated with this experiment. 

The set of possible outcomes {1, 2, 3, 4, 5, 6} is the sample space of the experiment.

Let’s see one more example:

Consider the experiment of tossing two coins together (or a single coin twice). 

Four possible elementary events (outcomes) associated with the random experiment are:

Heads on both coins – HH <br>
Tails on both coins – TT <br>
Head on first & Tail on second – HT <br>
Tail on first & Head on second - TH <br>

The associated sample space , S = {HH, TT, HT, TH}

### Favourable Elementary Events

Favourable Elementary Events – All those elementary events, the occurrence of anyone of which will ensure the happening of the desired event.

Let’s see one example:

Desired event - occurrence of exactly one head when two coins  are tossed. 

So, HT and TH are the only elements of S (sample space) corresponding to the occurrence of our desired event. 
So, set of favourable elementary events = {HT, TH}

Note that such a set of favourable elementary events will always be a subset of the sample space S. 
For example, {HT, TH} is a subset of {HH, TT, HT, TH}. 

## Definition of Probability

If there are X elementary events associated with a random experiment that are equally likely to occur (i.e. number of elements in the sample set are X) 

AND

Out of them there are Y favourable elementary events (i.e. the events, the occurrence of anyone of which will ensure that our desired event, say A, takes place), then

probability of occurrence of the desired event, P(A) = Y/X <br>
(i.e. P(A) = Number of favourable elementary events / Total elementary events )

For example:

Desired event - occurrence of exactly one head when two coins are tossed

So, set of favourable elementary events = {HT, TH}, i.e. 2 possible favourable elementary events, and

Sample space S = {HH, TT, HT, TH}, i.e. a total of 4 possible elementary events.

Hence, probability of occurrence of the desired event, P(A) = Y/X =  2/4 = 1/2

That is, 50% probability or chance of occurrence. 

Note that, 0 ≤ Y ≤ X

So, 0 ≤ P(A) ≤ 1

* In case of a certain event: P(A) = 1 
For example, what is the probability that on tossing a coin either head or tail will come?

* In case of an impossible event: P(A) = 0 
For example, what is the probability that on rolling a dice a face with the digit 7 will come?

The probability of event A not occurring, denoted by P (not A), is given by P (not A) or P(Ā) = 1 – P(A)

##### Q. If monthly salary of a person is Rs. 10,000 and the monthly expenditure has a uniform probability of falling anywhere in the range of Rs. 4,000 to Rs. 6,000. Then, what is the probability that in a given month he will make a saving of Rs. 5,500 or above.
<pre>(a) 1/4   (b) 1/3    (c) 1/2   (d) 3/4</pre>

Explanation:<br>
<div class="Exp">

The monthly expenditure has a uniform probability of falling anywhere in the range of Rs. 4,000 to Rs. 6,000. The probability that the expenditure lies between Rs. 4,000 to Rs. 6,000 is 1.

For saving to be Rs. 5,500 or above, the expenditure must lie between Rs. 4,500 and Rs. 4,000. (Note that he cannot save more than Rs. 6,000).

The probability that the expenditure lies between Rs. 4,001 to Rs. 4,500 = (4500-4000)/(6000-4000) = 500/2000 = 1/4.

Answer: (a)
</div> <br>

