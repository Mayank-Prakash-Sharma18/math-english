---
title: Geometric Probability
linktitle: Geometric Probability

toc: true
type: docs
date: "2020-11-03T00:00:00+01:00"
draft: false
menu:
  probability:
    parent: Probability
    weight: 24

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 24
---

If the total number of outcomes (elementary events) of a trial in a random experiment is infinite, then the traditional definition of the probability of occurrence of an event is not sufficient. 

For example, if we have to find the probability of hitting the innermost circle (i.e. bullseye) in a dart game. 
<img src="../../../media/probability/geometric-probability.png" alt="probability" style="width:45%;height:45%;">
In such cases, the probability of occurrence of an event, <br>
p = $\frac{Measure \hspace{1ex} of \hspace{1ex} the \hspace{1ex} specified \hspace{1ex} part \hspace{1ex} of \hspace{1ex} the \hspace{1ex} region}{Measure \hspace{1ex} of \hspace{1ex} the \hspace{1ex} whole \hspace{1ex} region}$ 

Here 'measure' means length, area or volume of the region if we are dealing with one, two, or three dimensional space respectively.

In our example of dart game, it will be $\frac{Area \hspace{1ex} of \hspace{1ex} the \hspace{1ex} innermost \hspace{1ex} circle}{Area \hspace{1ex} of \hspace{1ex} the \hspace{1ex} whole \hspace{1ex} dart \hspace{1ex} board}$ <br>
(given that the dart never misses the board in any case)

##### Q. A dart board has dimensions of 4 m × 4 m. What is the probability that a person can hit within a circle of radius of 2 m at the centre of the board, if the probability of hitting the dart board is:
A. 1 <br>
B. 0.70

Explanation:<br>
<div class="Exp">
If the dart hits within the board, then the probability of the dart hitting within the circle = $\frac{Area \hspace{1ex} of \hspace{1ex} circle}{Area \hspace{1ex} of \hspace{1ex} dart \hspace{1ex} board}$ = $\frac{π r^2}{(l × b)}$ = $\frac{π 2^2}{(4 × 4)}$ = $\frac{π}{4}$ <br><br>

A. Probability of hitting the dart board = 1 (i.e. a definite hit) <br>
So, required probability = $\frac{π}{4}$ × 1 = $\frac{π}{4}$ = $\frac{11}{14}$     (as π = $\frac{22}{7}$)

B. Probability of hitting the dart board = 0.70 (i.e. a definite hit)<br>
So, required probability = $\frac{π}{4}$ × 0.70 = $\frac{22}{40}$ = $\frac{11}{20}$    (as π = $\frac{22}{7}$)
</div> <br>