---
title: Question Type 1
linktitle: Question Type 1
toc: true
type: docs
date: "2020-09-09T00:00:00+01:00"
draft: false
menu:
  dices:
    parent: Opposite Faces
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

#### When Three/Four positions of a single dice are given and we are supposed to find out opposite face(s)

* Step 1: Select two positions of the same dice.

* Step 2: Now solve by applying the rules that we learnt to find out opposite faces when two positions of the dice are given.

The key is to select the two relevant positions of the dice.

## Three positions given

###### Q. In the following question, three positions of the same dice are given. What will be the digit on the opposite to the face having digit 5?
<img src="../../../media/dices/three-dices.png" alt="dices" style="width:81%;height:81%;">
<pre>(a) 6         (b) 3          (c) 4          (d) 2 </pre>
Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Choosing dices having 2 common faces <br><br>
Taking dices I and III, 2 and 3 are common. So, 4 will be opposite to 1. <br>
Taking dices I and II, 2 and 4 are common. So, 6 will be opposite to 3. <br>
Hence, 5 must be opposite to 2. <br>
Note: As you can see, one drawback of this method is that we sometimes have to apply it twice.
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Choosing dices having 1 common face<br><br>
Taking dices II and III, only one digit 2 is common. <br>
Now, we can see that 5 is opposite to 2 (as the common face is opposite to the invisible face). <br>
</div>

## Four positions given

###### Q. Four positions of a dice are given below. Identify the number at the bottom when the number at the top is 1.
<img src="../../../media/dices/four-dices.png" alt="dices" style="width:99%;height:99%;">
<pre>(a) 6         (b) 3          (c) 2          (d) 5 </pre>
Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-3', this, 'tablink-group2', 'tabcontent-group2')">3</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Choosing dices having 2 common faces <br><br>
Taking dices II and III, 1 and 4 are common. So, 5 will be opposite to 6. <br>
Taking dices II and IV, 1 and 6 are common. So, 3 will be opposite to 4. <br>
Hence, 1 must be opposite to 2. If 1 is at the top, then obviously 2 will be at the bottom.<br>
Note: As you can see, one drawback of this method is that we sometimes have to apply it twice.
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Choosing dices having 1 common face<br><br>
Taking dices I and III, only one digit 5 is common. <br>
Now, on moving clockwise from 5 in both the dices, we encounter 2 and 1 respectively. Hence, 1 and 2 are opposite to one another. If 1 is at the top, then obviously 2 will be at the bottom. <br>
</div>

<div id="2Exp-3" class="Exp-3 mak-tabcontent tabcontent-group2">
Explanation 3: Using the knowledge that adjacent faces cannot be opposite<br><br>
Digit 1 is visible in positions II, III and IV. <br>
In dice II, 4 and 6 are adjacent to 1. So, obviously they cannot be opposite to 1.<br>
In dice III, 4 and 5 are adjacent to 1. So, obviously they cannot be opposite to 1.<br>
In dice IV, 3 and 6 are adjacent to 1. So, obviously they cannot be opposite to 1.<br>
So, digits 3, 4, 5 and 6 cannot be opposite to 1. Naturally, 1 cannot be opposite to itself either. The only digit left is 2. <br>
Hence, the digit at the bottom must be 2, as it is opposite to 1. 
</div>



 