---
title: Balls
linktitle: Balls 
toc: true
type: docs
date: "2021-10-23T00:00:00+01:00"
draft: false
menu:
  probability:
    parent: Probability
    weight: 7

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 7
---

Let us have a look at some probability questions based on <strong>Balls</strong>. 

## Type 1: Balls drawn without Replacement

##### Q. A bag contains 4 red, 4 green and 4 blue balls. Two balls are drawn at random without replacement. What is the probability that none of the balls drawn is green?
<pre>(a) 7/18        (b) 14/33          (c) 7/36          (d) 2/3</pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Method I:  <br><br>

Total non-green balls = 8 <br>
Hence chance of getting one in first draw = 8/12 

After first successful draw, non-green balls = 7. Also, total number of balls is now 11. <br>
Hence, probability of getting non-green ball = 7/11

Final probability = 8/12 × 7/11 = 14/33

Answer: (b)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Method II: Using concept of Combinations <br><br>

Number of ways to choose two non-green balls = $C^{8}_2$ = 28 <br>
Total number of ways to choose 2 balls = $C^{12}_2$ = 66

Probability = 28/66 = 14/33

Answer: (b)
</div><br>

##### Q. A bag contains 4 red, 4 green and 4 blue balls. Two balls are drawn at random without replacement. What is the probability that one ball is blue and other green? 
<pre>(a) 1/9   (b) 4/33    (c) 14/33   (d) 8/33</pre>

Explanation:<br>
<div class="Exp">

Blue balls = 4, Green balls = 4

Probability = 2 × 4/12 × 4/11 = 8/33 

We multiplied by 2 as there are two possibilities – green ball drawn 1st and blue ball drawn 1st. 

Answer: (d)
</div> <br>

