---
title: Input-Output Coding
linktitle: Input-Output Coding
toc: true
type: docs
date: "2021-03-19T00:00:00+01:00"
draft: true
menu:
  coding-decoding:
    parent: Coding-Decoding
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

Input Output Coding is a question type, where the candidate is given some kind of word and number arrangement, i.e. Input, to be fed into a machine, the intermediate steps and the final output. 

With each subsequent operation, the arrangement of the words and numbers changes. These operations are performed until a final arrangement is reached or is performed in loop. 

<img src="../../../media/coding-decoding/coding-decoding-10.png" alt="Coding Decoding" style="width:90%;height:90%;">

You are expected to find out what processing is being done and predict the intermediate or final Output of another Input given to you.  

There are various possible cases based on the manner in which the rearrangement is done. 

Let’s see…

### Case I: Rearrangement based on Ordering

* Words are arranged alphabetically (forward or reversed), while numbers are arranged in ascending/descending order, without changing the order of the remaining words/numbers.

* Both words and numbers could be arranged individually or simultaneously in each step. 

* The rearrangement can start from the leftmost side or the rightmost side of the sentence and sometimes even simultaneously from both the ends.

Let's consider an example:

<img src="../../../media/coding-decoding/coding-decoding-11.png" alt="Coding Decoding" style="width:99%;height:99%;">

Here, Step III is the final step and the rearrangement is done simultaneously from both front and back ends. 

The numbers are arranged in ascending order one by one from the left end, with the next biggest number being added to the right of the previous number. 

The words are arranged in forward order one by one, with the last word in the dictionary going to the rightmost end, and earlier entries in the dictionary getting added in subsequent steps to the left of that word.

### Case II: Rearrangement based on Interchanging the Positions of Words/Numbers

* We either start from the leftmost or rightmost position and keep on arranging the items in the required order, one position at a time. 

* Positions of only two words/numbers are interchanged in each step. The positions of all others remain unchanged.

* Unlike element based ordering, in position based ordering once an element is arranged in a position it remains there in all the subsequent steps. 

Let's consider an example:

<img src="../../../media/coding-decoding/coding-decoding-12.png" alt="Coding Decoding" style="width:99%;height:99%;">

Step VII is the final step of the input. 

The underlined words are used to indicate the words that will be interchanged in the next step.

Here we started from the leftmost position. In step 1, the first position was taken care of, i.e. appropriate word/number was placed in position 1 and then so on for other positions. In case the position is already having appropriate item, then we skip it and move on to the next position. 
