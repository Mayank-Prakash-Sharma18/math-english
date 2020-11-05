---
title: Mutually Exclusive Events
linktitle: Mutually Exclusive Events

toc: true
type: docs
date: "2020-11-03T00:00:00+01:00"
draft: false
menu:
  probability:
    parent: Probability
    weight: 18

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 18
---

In this article we will learn about:

* Mutually Exclusive Events &

* Addition Theorem of Probability

## Mutually Exclusive Events

Mutually exclusive events (or disjoint events) – those events that cannot occur simultaneously. If one occurs, the other won’t and vice versa. 

For example, on rolling a die: <br>
X : The event that the number is odd, i.e. 1, 3, 5. <br>
Y : The event that the number is even, i.e. 2, 4, 6. <br>
Z : The event that the number is a multiple of three, i.e. 3, 6. <br>

Events X and Y are mutually exclusive – i.e. only one of them can occur at a time. Both even and odd numbers cannot come up when we roll a die. 

But the events X and Z are not mutually exclusive since they may have common outcomes, e.g. when 3 comes up.

Let’s see another example:

In drawing a card from a deck of 52 cards. <br>
X : The event that it is a spade, 13 possible elementary events.<br>
Y : The event that it is a club, 13 possible elementary events.<br>
Z : The event that it is a king, 4 possible elementary events (including two kings of spade and club).<br>

Events X and Y are mutually exclusive, as a card drawn cannot be of spade and club simultaneously. 

But the events X and Z are not mutually exclusive since they may have common outcomes, e.g. when a kind of spade is drawn.

## Addition Theorem of Probability

* If the events are not mutually exclusive, then: <br>
<img src="../../../media/probability/addition-theorem.png" alt="probability" style="width:54%;height:54%;">
P(X or Y) = P(X) + P(Y) - P(X and Y together) <br>
Or P(X ∪ Y) = P(X) + P(Y) - P(X ∩ Y) <br><br>
Similarly, P (neither X nor Y) = 1 - P(X or Y).
<img src="../../../media/probability/addition-theorem2.png" alt="probability" style="width:54%;height:54%;">

* If X and Y are two mutually exclusive events (i.e. X and Y are disjoint sets), then, P(X ∩ Y) = 0
<img src="../../../media/probability/addition-theorem1.png" alt="probability" style="width:54%;height:54%;">
So, the probability that either event X or event Y will occur in a single trial is given by :
P(X or Y) = P(X) + P(Y)

##### Q. A warehouse contains 20 fans and 60 bulbs. Half of the fans and half of the bulbs do not work. If one item is chosen at random, then what is the probability that it is a non-working item or a bulb?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1:  <br><br>

Let P(X) be the probability that a non-working item is chosen and P(Y) be the probability that a bulb is chosen.

So, P(X) = $\frac{40}{80}$ = $\frac{1}{2}$ (as half of the items do not work) <br>
And P(Y) = $\frac{60}{80}$ = $\frac{3}{4}$ <br>
Now, the probability that a non-working bulb is chosen, i.e. P(X ∩ Y) = $\frac{30}{80}$ = $\frac{3}{8}$ <br>

So, the probability that the chosen item is a non-working item or a bulb, P(X ∪ Y) = P(X) + P(Y) - P(X ∩ Y) = $\frac{1}{2}$ + $\frac{3}{4}$ - $\frac{3}{8}$ = $\frac{(4 + 6 - 3)}{8}$ = $\frac{7}{8}$
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Number of non-working items = $\frac{20}{2}$ + $\frac{60}{2}$ = 10 + 30 = 40

Number of working bulbs = Number of bulbs - Number of non-working bulbs = 60 - $\frac{60}{2}$ = 30

So, the probability that the chosen item is a non-working item or a bulb = $\frac{(40 + 30)}{80}$ = $\frac{7}{8}$
</div><br>

## Collectively Exhaustive Events

Collectively Exhaustive events - Events that together cover all the possible occurrences of an experiment.

For example, on rolling a die: <br>
X : The event that the number is odd, i.e. 1, 3, 5. <br>
Y : The event that the number is even, i.e. 2, 4, 6. <br>
Z : The event that the number is a multiple of three, i.e. 3, 6. <br>

The events X and Y are collectively exhaustive events. That is, X ∪ Y = S 

The events X and Z are not collectively exhaustive events, as they do not cover 2 and 4, even when seen together.

## Mutually Exclusive & Collectively Exhaustive Events

If we have a set of events (say A and B) which are both mutually exclusive and collectively exhaustive, then 

the sum of the probabilities of such events = 1.

Or P(A) + P(B) = 1

For example: <br>
Probability of getting an even number on rolling a dice = $\frac{3}{6}$ = $\frac{1}{2}$ <br>
So, Probability of getting an odd number on rolling a dice = 1 – $\frac{1}{2}$ = $\frac{1}{2}$  <br>






