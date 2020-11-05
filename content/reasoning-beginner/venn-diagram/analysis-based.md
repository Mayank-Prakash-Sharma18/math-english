---
title: Analysis based Venn diagrams
linktitle: Analysis based Venn diagrams
toc: true
type: docs
date: "2020-10-31T00:00:00+01:00"
draft: false
menu:
  venn-diagram:
    parent: Venn Diagrams
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

In these types of questions, generally a Venn diagram comprising of different geometrical figures is given. Each geometrical figure in the diagram represents a certain class. The candidate is required to study and analyze the figure carefully and then answer the given questions based on it.

To solve such questions, a student should have solid grasp on these six conceptual terms:
1. AND – It’s intersection (A Ո B)
2. OR – It’s union (A U B)
3. Only
4. Not
5. At least
6. At most

Let's understand them using a couple of examples.

##### Let us consider a scenario where we have people speaking one or more of the given three languages - English, Sanskrit and German. 
<img src="../../../media/venn-diagram/venn-diagram12.png" alt="Venn diagrams" style="width:54%;height:54%;">

<div class="Exp">
Let us analyse the given Venn diagram.<br><br>

Number of people who speak: <br>

* only English = 35
* English = 35 + 13 + 9 + 12

* German AND English = 12 + 9 
* German AND English only = 12

* German OR English = 35 + 24 + 12 + 13 + 19 + 9
* German OR English only = 35 + 12 + 24
* German only OR English only = 24 + 35

* not German OR English = (German OR English)' = 27

* at least 2 languages = 12 + 13 + 19 + 9 (i.e. those who speak 2 or 3 languages)
* at most 2 languages = 35 + 24 + 27 + 12 + 19 + 13 or Total – 9 (i.e. those who speak 2 or 1 languages)
</div> <br>

##### Q. The following figure shows the viewership of two leading news channels, as found in a sample survey. Find out the number of people who do not watch any news channel.
<img src="../../../media/venn-diagram/venn-diagram13.png" alt="Venn diagrams" style="width:63%;height:63%;">
<pre>(a) 175   (b) 75   (c) 195   (d) 135 </pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1:  <br><br>
People who watch Republic OR ZEE News (i.e. atleast one channel) = 85 + 200 - 60 = 225 <br>
(we subtracted 60 as otherwise it would have been counted twice)<br><br>
So, people who do not watch any news channel = (Republic OR ZEE News)' = Total number of people - 225 = 420 - 225 = 195 <br><br>

Answer: (c)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>
People who watch only Republic = 85 - 60 = 25 <br>
People who watch only ZEE News = 200 - 60 = 140 <br><br>
So, people who watch Republic OR ZEE News (i.e. atleast one channel) = 25 + 140 + 60 = 225 <br><br>
And people who do not watch any news channel = (Republic OR ZEE News)'= Total number of people - 225 = 420 - 225 = 195 <br><br>

Answer: (c)
</div><br>