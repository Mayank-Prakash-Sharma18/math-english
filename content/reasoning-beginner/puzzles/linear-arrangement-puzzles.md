---
title: Linear Arrangement Puzzle Questions
linktitle: Linear Arrangement Puzzle Sets
toc: true
type: docs
date: "2021-06-30T00:00:00+01:00"
draft: false
menu:
  puzzles:
    parent: 4. Seating arrangement Puzzles
    weight: 19

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 19
---

In this article, we will have a look at the various types of Linear Arrangement Puzzles that you may encounter in an aptitude examination. 

But before we do so, let us categorize the kind of information/data we will find in such questions. 

## Types of Information

### Absolute Information

Absolute information provides us the hinge (starting point), from where we can start unwrapping the puzzle. 

An example of absolute information would be - A is on the extreme left of the line, or B is at one of the extreme ends, or C is at the middle. 

So, an absolute information is something that we can directly put down in the diagram of a linear arrangement. 

{{% alert note %}}
If a puzzle set has a lot of absolute information, then that set is bound to be easier to crack. 

So, apart from checking out the dimensions in a puzzle set, you should also check out the kind of information given. It will help you identify the easier sets, even before attempting them. This is what will make you a topper. 
{{% /alert %}}

### Relative Information

Relative information is with relation to each other. It's something we generally cannot fill in the linear arrangement diagram, as we do not know where to place it. 

For example, a question may say A is 3rd to the right of B, C is on the immediate left of D etc. All these are relative information (i.e. they give positions with repect to each other).

{{% alert note %}}
Relative Information may further be categorized into:
* Positive Relative Information - E.g. A is sitting next to B.
* Negative Relative Information - E.g. A is ***not*** sitting next to B. 

Negative Relative Information generally does not help us much in the initial stages. But it may come handy in the end, when we want to eliminate some of the possible cases. 
{{% /alert %}}


## Type 1: Some absolute information given

In some questions, some absolute information is given (along with relative information). 

##### Q. Five people A, B, C, D and E are sitting on a bench. A is sitting second from left end of the bench and is adjacent to B. D is sitting in between A and C. Who is sitting at the right end of the bench?
<pre>(a) B   (b) E    (c) C   (d) Can’t be determined</pre>

Explanation:<br>
<div class="Exp">

The puzzle is one-dimensional (1-D): Only sitting arrangement has to be handled. So, it must be easy to crack. 

Let the positions on the bench be represented by dashes.
<img src="../../../media/puzzles/linear-arrangement-puzzle-questions-1.png" alt="puzzles" style="width:72%;height:72%;">

A is sitting second from left end of the bench and is adjacent to B. So, two cases are possible:

Case I:
<img src="../../../media/puzzles/linear-arrangement-puzzle-questions-2.png" alt="puzzles" style="width:72%;height:72%;">
Case II:
<img src="../../../media/puzzles/linear-arrangement-puzzle-questions-3.png" alt="puzzles" style="width:72%;height:72%;">

{{% alert note %}}
Absolute Information - ***A is sitting second from left end of the bench***. 

This is something, we can directly fill in the diagram, as we did above. This provided us with a good starting point to solve he puzzle. 
{{% /alert %}}

However, D is sitting between A and C. This is possible only in case I. Hence we arrive at the following arrangement:
<img src="../../../media/puzzles/linear-arrangement-puzzle-questions-4.png" alt="puzzles" style="width:72%;height:72%;">
The last vacant position must be occupied by E. Hence option (b) is correct.

Answer: (b)
</div> <br>


## Type 2: No absolute information given

In some questions only relative information is given, i.e. no absolute information is provided. 

##### Q. Five flowering plants are planted in a row. Rose is to the right of Lily, while Tulip is to the left of Lotus and to the right of Rose. Lily is to the right of Marigold.

Which of the flowering plant is in the middle?
<pre>(a) Lily   (b) Marigold    (c) Tulip   (d) Rose</pre>

Explanation:<br>
<div class="Exp">

The puzzle is one-dimensional (1-D): Only sitting arrangement has to be handled. So, it must be easy to crack. 

Let Rose, Lily, Tulip, Lotus and Marigold be represented by R, L, T, Lo and M.

As per 1st statement: L - R

Now, as per the 2nd statement, Tulip is to the left of Lotus and on the right of Rose. Thus, both Tulip and Lotus are to the right of Rose: L - R - T - Lo

As Lily is to the right of Marigold, the final picture that emerges may be represented as follows: M - L - R - T - Lo

It's evident in the above sequence, that Rose is in the middle.

Answer: (d)
</div> <br>


