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

