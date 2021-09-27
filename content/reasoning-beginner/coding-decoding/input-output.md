---
title: Input-Output Coding
linktitle: Input-Output Coding
toc: true
type: docs
date: "2021-03-19T00:00:00+01:00"
draft: false
menu:
  coding-decoding:
    parent: Coding-Decoding
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

## What is Input Output Coding?

Input Output Coding is a type of coding-decoding question, that is often asked in Banking examinations. 

Here, some sort of input (e.g. word, symbol or number arrangement) is fed into a virtual machine, which starts processing the input based on some logic. So, it produces a sequence of intermediate steps and then a final output. 
<img src="../../../media/coding-decoding/coding-decoding-10.png" alt="Coding Decoding" style="width:90%;height:90%;">

Sometimes, there is no final output. Rather the processing keeps ongoing in a loop. 

We have to decipher the underlying logic and based on that predict an intermediate step, or the output. 

{{% alert note %}}
#### Tips and Concepts regarding Steps in Input-Output Coding

* If there are ‘n’ elements (words, numbers. etc.) in the input, then we need a maximum of 'n - 1' steps to rearrange it completely and get the output.

* Number of elements arranged/changed until a certain step ≥ The step number of that step. It means that, at least one element should be arranged/changed per step. Sequences in no two steps will look exactly the same. 

* Generally, we cannot move backwards in Input-Output. That is, we cannot find out a previous step from the subsequent step. For example, we cannot determine input from the sequence in the first step, we cannot determine the first step from the sequence in the second step, etc. 
{{% /alert %}}


## Approach to solve Input-Output Coding Questions

Let's generalize the approach that we are going to adopt while solving such questions. 

* **Identify the Logic/Pattern**: The first thing we should do in Input-Output Coding questions is to identify the underlying logic or pattern. The best way to do so is to have a look at the final output (if it has been given), or the last given step.

* **Find out the changes per Step**: Compare subsequent steps to find out how many changes are being brought about in each step, and from where. Are changes being made one at a time, or two at a time, from the righmost or the leftmost side, or from inside out. 

* **Start writing all the Steps**: Once you know the logic/pattern being used, start writing all the steps, starting from the input. Stop when the output is achieved. 

{{% alert note %}}
**Some tips to fasten up the process**

We can adopt some shortcut methods to save some of our precious time in the exam.

* Write only a few initials of the word, rather than writing the full word again and again. But make sure that you are able to identify it clearly. 

* In each step, just write the elements that are being changed or rearranged. However, if all the elements of the sequence are getting shifted due to the rearrangement, then it will be better to write the full sequence in each step. 
{{% /alert %}}


## Types of Input-Output Questions

There are various possible cases based on the manner in which the rearrangement is done. 

Let’s see…

### Case I: Rearrangement based on Sliding Process

* Words are arranged alphabetically (forward or reverse), while numbers are arranged in ascending/descending order, without changing the order of the remaining words/numbers. The rest of the elements are ***slided*** to the right or left. 

* Both words and numbers could be arranged individually or simultaneously in each step. 

* The rearrangement can start from the leftmost side or the rightmost side of the sentence and sometimes even simultaneously from both the ends. In some rare cases, the rearrangement process may start from the middle, i.e. inside-out. 

Let's consider an example:

<img src="../../../media/coding-decoding/coding-decoding-11.png" alt="Coding Decoding" style="width:99%;height:99%;">

Here, the rearrangement is done simultaneously from both front and back ends.

By Step 2 all the numbers are already in ascending order. So, in Step 3 we just rearranged words. 

Step 3 is the final step of this process, i.e. the Output. 

**Logic of arrangement of numbers**: The numbers are arranged in ascending order one by one towards the left end, i.e. the next bigger number is added to the right of the previous number (i.e. numbers are arranged relative to each other). 

**Logic of arrangement of words**: The words are arranged in forward order one by one. The last word in the dictionary is placed at the rightmost end, and earlier entries in the dictionary are added to the left of that word in each subsequent step (i.e. words are arranged relative to each other).


### Case II: Rearrangement based on Interchange Process

* Positions of only two elements (words/numbers) are ***interchanged*** in each step, i.e. elements are placed at the required position, one position at a time. Positions of all other elements remain unchanged.

* We can start either from the leftmost or the rightmost position. In some rare cases, the rearrangement process may start from the middle, i.e. inside-out. 

In the sliding based ordering (i.e. Case I), once the appropriate element(s) are placed at their correct position(s), the rest of the elements are ***slided*** to the left or right.

However, in interchange based ordering (i.e. Case II), positions of only two elements are ***interchanged***. Positions of all the rest of the elements remain the same. 

Let's consider an example:

<img src="../../../media/coding-decoding/coding-decoding-12.png" alt="Coding Decoding" style="width:99%;height:99%;">

Here, we started arranging the elements from the leftmost position. In Step 1 we placed the appropriate element in the first position, in Step 2 we placed the appropriate element in the second position, and so on. 

Numbers are placed at odd positions (in ascending order), and words at even positions (in forward order). 

In case a position is already having the appropriate element, then we skip it and move on to the next position. For example, in Step 3 both '81' and 'gold' are placed at their appropriate positions (position 3 and 4). So, in Step 4 we move on work on the position 5. 

Step 4 is the final step of the process, i.e. it's the output. 


### Case III: Rearrangement based on Mathematical operations 

Sometimes the elements (generally numbers) are not only rearranged, but also changed based on some logic (i.e. based on some mathematical operations). 

Mathematical operations that may be used are: some common number added/subtracted/multiplied/divided to each number, squaring a number, adding the digits of a number, etc. 

{{% alert note %}}
It's easy to recognize such Input-Output logic. The elements in the input will vary from the elements in the output and the intermediate steps. 
{{% /alert %}}

Let's see an example. 

<img src="../../../media/coding-decoding/coding-decoding-13.png" alt="Coding Decoding" style="width:99%;height:99%;">

Here, we are subtracting the unit digit from a given number. We start simultaneously from the leftmost and rightmost number, and then move inwards. Step 3 is the final step, and hence the output. 

As you may have noticed, here none of the elements are being rearranged. They are only being changed based on the mathematical operation mentioned above. But in some cases, elements may not only be changed, but also rearranged. 

