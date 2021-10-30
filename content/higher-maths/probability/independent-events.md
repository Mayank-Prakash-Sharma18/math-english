---
title: Independent Events
linktitle: Independent Events

toc: true
type: docs
date: "2020-11-03T00:00:00+01:00"
draft: false
menu:
  probability:
    parent: Probability
    weight: 21

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 21
---

In this article we will learn about:

* Independent Events &

* Multiplication Theorem of Probability

## Independent Events

Two events are independent if the occurrence of one has no effect on the occurrence of the other.

For example, on rolling a die and tossing a coin together <br>
X : The event that number 3 turns up. <br>
Y : The event that tail turns up. <br>

Both these events are independent.

##### Q. If a dice is rolled and a coin is tossed, then what is the probability that the dice shows an odd number and the coin shows a head?
<pre>(a) 1/2   (b) 3/4    (c) 1/5   (d) 1/4</pre>

Explanation:<br>
<div class="Exp">

Possible events = (1H) (2H) (3H) (4H) (5H) (6H) (1T) (2T) (3T) (4T) (5T) (6T) <br>
∴ Total number of events, n(S) = 12

Let E be the event in which ‘the dice shows an odd number and the coin shows a head’. <br>
So, E = (1H) (3H) (5H) <br>
∴ n(E) = 3

So, required Probability = n(E)/n(S) = 3/12 = 1/4 

Answer: (d)
</div> <br>

Let’s consider one more scenario.

In drawing a card from a well-shuffled pack: <br>
X : Event that first card is drawn. <br>
Y : Event that second card is drawn without replacing the first. <br>
Z : Event that second card is drawn after replacing the first. <br>

X and Y are not independent events, because the first card has not been replaced and so it will affect the probability of drawing the second card. 

But X and Z are independent events, because the first card has been replaced. So, no matter what card was drawn in the first draw, it will have no impact on the card drawn in the second draw. 

{{% alert note %}}
#### Mutually Exclusive Events & Independent Events

If A and B are two mutually exclusive events associated to a random experiment, then only one of them can occur at a time.

So, if A occurs, then P(B) = 0. <br>
And if B occurs, then P(A) = 0.

So, it’s pretty evident that mutually exclusive events associated to a random experiment are not independent and vice-versa (because occurrence of one is impacting the occurrence of the other).
{{% /alert %}}

## Multiplication Theorem of Probability

If events A, B are independent then,

P(X and Y) = P(X) × P(Y)

Or P(X ∩ Y) = P(X) × P(Y)

##### Q. Ayan forgot the last three digits of a 7-digit telephone number. If he randomly dials the last 3 digits after correctly dialing the first four, then what is the chance of dialing the correct number?
(a) 1/1001 <br>
(b) 1/1000 <br>
(c) 1/999 <br>
(d) 1/990

Explanation:<br>
<div class="Exp">

It is given that last 3 digits are randomly dialed.

Then, each of the digits can be selected out of 10 digits in 10 ways, out of which only one will be correct in each case.

∴ Required probability = 1/10 × 1/10 × 1/10 = 1/1000

Answer: (b)
</div> <br>

##### Q. Probability that Ria can solve a problem is 1/2 and the probability that Tina can solve a problem is  2/3. If both attempt a question, then what is the probability that the problem is solved?
<pre>(a) 1/2         (b) 1/6          (c) 2/3         (d) 5/6</pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Method I: <br><br>

Probability that Ria can solve a problem = 1/2 <br>
So, probability that Ria can’t solve a problem = 1 – ½ = 1/2

Probability that Tina can solve a problem = 2/3 <br>
Probability that Tina can’t solve a problem = 1 – 2/3 = 1/3

There are 3 possible cases: (Ria solves and Tina doesn’t solve) OR (Ria doesn’t solve and Tina solves) OR (Both Ria and Tina solve it).  

∴ Probability that the problem is solved = (1/2 × 1/3) + (1/2 × 2/3) + (1/2 × 2/3) = 1/6 + 2/6 + 2/6 = 5/6

Answer: (d)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Method II: <br><br>

Probability that Ria can solve a problem = 1/2 <br>
So, probability that Ria can’t solve a problem = 1 – ½ = 1/2

Probability that Tina can solve a problem = 2/3 <br>
Probability that Tina can’t solve a problem = 1 – 2/3 = 1/3

Probability that the problem is solved = 1 - Probability that the problem is not solved 
= 1 – (Probability that neither Ria nor Tina solve the problem) = 1 – (1/2 × 1/3) = 1 – 1/6 = 5/6

Answer: (d)
</div><br>

