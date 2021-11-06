---
title: Types of Probability Questions
linktitle: Probability Question Types

toc: true
type: docs
date: "2021-11-03T00:00:00+01:00"
draft: false
menu:
  probability:
    parent: Probability
    weight: 23

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 23
---

In previous articles we have already understood the basic concepts of Probabilty, and have also see some very basic question types. 

In this article, we are going to have a look at some other kinds of questions formed on the topic of Probabilty. 


## Type 1: Probability in Selection

##### Q. A committee of two members is to be chosen from a group of 5 men and 4 women. Out of the 9 people, there is one couple. What is the probability that the committee has one male and one female member if the couple cannot be in the committee simultaneously?
<pre>(a) 5/18   (b) 19/36    (c) 21/36   (d) 1/20</pre>

Explanation:<br>
<div class="Exp">

Number of ways of choosing a committee of two members = $C^9_2$ = (9 × 8)/2 = 36

Number of ways of choosing a committee of one male and one female members = 5 × 4 = 20 <br>
Number of ways of choosing a committee such that the members are the couple = 1 <br>
Number of ways of choosing the committee of one male and one female such that the couple is not in the committee simultaneously = 20 – 1 = 19

So, Required probability = 19/36

Answer: (b)
</div> <br>


## Type 2: Probability in Arrangement

##### Q. Four boys and eight girls are sitting in a row. What is the probability that all the girls are sitting together?
(a) 4!/8! <br>
(b) (6! × 8!)/12! <br>
(c) (5! × 8!)/12! <br>
(d) 5!/12!

Explanation:<br>
<div class="Exp">

Total number of arrangements possible = 12!

Eight girls can sit together if they are considered as a block. Number of ways of such arrangement = (4 + 1)! = 5! <br>
Number of ways in which those 8 girls can sit among themselves = 8! <br>
Hence, number of ways in which 4 boys and 8 girls sit such that all girls sit together = 5! × 8!

Required probability = (5! × 8!)/12!

Answer: (c)
</div> <br>

