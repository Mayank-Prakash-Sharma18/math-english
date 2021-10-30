---
title: Types of Permutation Questions
linktitle: Permutation Question Types
toc: true
type: docs
date: "2021-10-24T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 10

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 10
---

In this article, we will have a look at the various types of questions that we encounter based on the topic of Permutation. 

But you must be aware of the basic concepts of Permutation before we do so. If you aren't, then have a look at the previous articles. 

## Type 1: Arranging all n distinct items

##### Q. The letters of the word LUCKNOW are rearranged to generate all possible words (meaningful or meaningless). In the list of all the words generated, how many words have the word ‘NOW’ embedded in them?
<pre>(a) 7!   (b) 24    (c) 720   (d) 120</pre>

Explanation:<br>
<div class="Exp">

The word ‘NOW’ has to appear in the word. So, we can assume that ‘NOW’ is a single alphabet and the remaining alphabets ‘L’, ‘U’, ‘C’ and ‘K’ are re-arranged along with ‘NOW’ to generate all possible words. 

Total number of alphabets available = 5 (‘L’, ‘U’, ‘C’, ‘K’ and ‘NOW’) <br>
Total number of permutations possible = 5! = 120.

Answer: (d)
</div> <br>

<!-- ### Type 2c: Words in a Dictionary -->


## Type 2: Arranging some distinct and some identical items

##### Q. In how many ways can the letters of the word ALPHA be arranged such that both As are never together?
<pre>(a) 60   (b) 24    (c) 36   (d) 120</pre>

Explanation:<br>
<div class="Exp">

Number of permutations of n objects out of which  p, q and r are of different types = $\frac{n!}{(p! q! r!)}$ 

ALPHA has 5 alphabets of which 2 are of the same type, i.e. two A’s. <br>
Total number of possible arrangements in the word ALPHA = 5!/2! = 60.

When both As come together, the two A can be treated as single and in that case, it can be considered a case of 4 alphabets, where all are distinct. <br>
Total number of possible arrangements when both As are together = 4! = 24

Total number of permutations when A’s are apart = Total number of permutations possible – Total number of permutations when A’s are together = 60 - 24 = 36

Answer: (c)
</div> <br>

