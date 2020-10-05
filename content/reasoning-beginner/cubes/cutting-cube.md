---
title: Cutting a Cube/Cuboid
linktitle: Cutting a Cube/Cuboid
toc: true
type: docs
date: "2020-09-025T00:00:00+01:00"
draft: false
menu:
  cubes:
    parent: Cubes
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## Number of smaller cubes
(Finding the number of smaller cubes when a bigger cube or cuboid is cut)

When we cut a rod once, then it divides into how many parts? <br>
When we cut a rod once, then it gets divided into two equal parts.
<img src="../../../media/cubes/rod-cut-in-two.png" alt="dices" style="width:36%;height:36%;">

Similarly, if we cut a rod twice, then it divides into three equal parts. 
<img src="../../../media/cubes/rod-cut-in-three.png" alt="dices" style="width:36%;height:36%;">
And so on...

Can we generalize?<br>
If number of cuts = (n -1), then number of parts in which a rod or a line gets divided into = n

A cube can also be cut as a rod/stick/line. <br>
If a cube of X cm long sides is cut into equal smaller cubes of sides Y cm, then n = X/Y <br>
(n is the number of smaller cubes on each edge.)

If these cuts are made along all the three dimensions, i.e. along the length, breadth and height, then we will get smaller cubes of same size. 

Total number of such smaller cubes = $n^3$

##### Q. If the edge of a cube is 10 cm and it has to be cut into smaller cubes each having edge of 2 cm, then:
1. Each edge of the cube has to be cut how many times?
2. Whole cube will has to be cut how many times?
3. What is the number of smaller cubes thus obtained?

Explanation:<br>
<div class="Exp">
Number of smaller cubes on each edge, i.e. n = X/Y = 10/2 = 5, i.e. each edge has to be divided into 5 parts. (here X = 10 and Y = 2). <br>
And to divide into five parts, each edge will have to be cut 5-1 = 4 times
<img src="../../../media/cubes/125-small-cubes.png" alt="125 cubes" style="width:54%;height:54%;">
Hence, the number of times the cube has to be cut = 4×3 = 12 <br>
Number of smaller cubes = $n^3$ = $5^3$ = 125
(Basically, it’s length × breadth × height)
</div><br>

What if it’s a cuboid? <br>
Can we still count the number of smaller cubes? <br>
When a cuboid is cut into smaller cubes of equal volume, then:<br>
Total number of Cubes = $ \frac{Vol. \hspace{1ex} of \hspace{1ex} Cuboid}{Vol. \hspace{1ex} of \hspace{1ex} smaller \hspace{1ex} cube} $ 
= $ \frac{Length × Breadth × Height \hspace{1ex} of \hspace{1ex} cuboid}{(Side \hspace{1ex} of \hspace{1ex} smaller \hspace{1ex} cubes)^3} $ 

Let’s consider an example.

##### Q. If a cuboid with length = 10 cm, breadth = 8 cm and height = 6 cm is cut into smaller cubes of edge 2 cm each, then find the number of smaller cubes.
<pre> (a) 72  (b) 42  (c) 48  (d) 60 </pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: <br>
Total number of Cubes = $ \frac{Length × Breadth × Height \hspace{1ex} of \hspace{1ex} cuboid}{(Side \hspace{1ex} of \hspace{1ex} smaller \hspace{1ex} cubes)^3} $ = $ \frac{10 × 8 × 6}{2^3} $ = 60
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br>
Total number of Cubes = No. of cubes along length × No. of cubes along breadth × No. of cubes along height = (10/2) × (8/2) × (6/2) = 5 × 4 × 3 = 60 
</div>

##### Q. How many cubes are there in this cuboid?
<img src="../../../media/cubes/cuboid.png" alt="cuboid" style="width:45%;height:45%;">

Explanation:<br>
<div class="Exp">
Number of cubes = Number of cubes along the Height × Number of cubes along the Length × Number of cubes along the Width = 5 × 3 × 3 = 45
</div> <br><br>


## Types of smaller cubes

After cutting a cube, following four types of smaller cubes are obtained:<br>
(we are taking an example of a cube where there are 3 cubes on each of its edges, i.e. n = 3)

### Corner cubes 
<img src="../../../media/cubes/corner-cubes.png" alt="types of small cubes" style="width:45%;height:45%;">
Number of corner cubes = 8 (always)

{{% alert note %}}
If a cube is painted on all faces/sides and the cuts are made, then these smaller corner cubes will have three faces/sides painted (as they have three exposed faces). <br>
No smaller cube can have more than three painted faces under normal circumstances. 
{{% /alert %}}

### Cubes at the middle of each edge

Number of middle cubes = 12 (n - 2) <br>
OR<br>
Number of middle cubes = Number of middle cubes on each edge × 12   (as there are 12 edges in a cube)
<img src="../../../media/cubes/edge-cubes.png" alt="types of small cubes" style="width:45%;height:45%;">
In this case, Number of middle cubes = 12 (n - 2) = 12 (3 - 2) = 12

{{% alert note %}}
If a cube is painted on all faces/sides and the cuts are made, then these middle smaller cubes will have two faces/sides painted (as they have two exposed faces).
{{% /alert %}}

### Cubes at the centre of each face

Number of such cubes = 6 $(n – 2)^2$ <br>
OR <br>
Number of such cubes = Number of middle cubes in each face × 6  (as there are 6 faces in a cube)
<img src="../../../media/cubes/face-cubes.png" alt="types of small cubes" style="width:45%;height:45%;">
In this case, such cubes = 6 $(3 - 2)^2$ = 6

{{% alert note %}}
If a cube is painted on all faces/sides and the cuts are made, then these smaller cubes will have one face/side painted (as they have one exposed face).
{{% /alert %}}

### Inner cubes that are hidden

Number of inner cubes = $(n - 2)^3$
In this case, such cubes = $(n - 2)^3$ = $(3 - 2)^3$ = 1

{{% alert note %}}
If a cube is painted on all faces/sides and the cuts are made, then these inner smaller cubes will have no face/side painted (as they do not have any face exposed).
{{% /alert %}}

{{% alert note %}}
Total number of smaller cubes = Corner cubes + Middle of edge cubes + Centre of face cubes + Inner cubes <br>
or $n^3$ = 8 + 12 (n - 2) + 6 $(n – 2)^2$ + $(n - 2)^3$ <br><br>
In our example:<br>
$3^3$ = 8 + 12 + 6 + 1 <br>
or 27 = 27 <br>
Hence, we have accounted for all kinds of smaller cubes.
{{% /alert %}}

##### Q. If a larger cube of 8 cm edge is cut into smaller cubes of equal volumes, each having edge of 2 cm, then:
Number of smaller cubes = ?<br>
Number of corner cubes = ?<br>
Number of cubes at the centre of edges = ?<br>
Number of cubes at the centre of faces = ?<br>
Number of inner cubes (N) = ? 

Explanation:<br>
<div class="Exp">
n = 8/2 = 4<br>
Number of smaller cubes = $n^3$ = $4^3$ = 64<br>
Number of corner cubes = 8 (always)<br>
Number of cubes at the centre of edges = 12 (n - 2) = 12 (4 - 2) = 24<br>
Number of cubes at the centre of faces = 6 $(n – 2)^2$ = 6 $(4 – 2)^2$ = 24<br>
Number of inner cubes = $(n - 2)^3$ = $(4 - 2)^3$ = 8<br>
Note: If we check, total number of cubes = 8 + 24 + 24 + 8 = 64
</div> <br><br>

##### Q. A cube of side 4 cm is painted blue on all of its surfaces and then divided into various smaller cubes of side 1 cm each. Find the number of cubes having none, one, two and three faces painted.

Explanation:<br>
<div class="Exp">
n = 4/1 = 4<br>
Smaller cubes with three faces painted = Number of corner cubes = 8 (always)<br>
Smaller cubes with two faces painted = Number of cubes at the centre of edges = 12 (n - 2) = 12 (4 - 2) = 24<br>
Smaller cubes with one face painted = Number of cubes at the centre of faces = 6 $(n – 2)^2$ = 6 $(4 – 2)^2$ = 24<br>
Smaller cubes with no face painted = Number of inner cubes = $(n - 2)^3$ = $(4 - 2)^3$ = 8<br>
</div> <br><br>

For those who are more into mugging up the numbers, here's a list of the number of four types of smallers cubes/blocks (got after cutting bigger cubes of various sizes):

<img src="../../../media/cubes/small-cubes-list.png" alt="list of small cubes" style="width:49%;height:49%; float:left;">
<img src="../../../media/cubes/small-cubes-list2.png" alt="list of small cubes" style="width:49%;height:49%; float:right;"> 

Note: We will solve questions wherein the larger cube is painted with more than one colours and then cut, in a separate module. Here we covered the basics of cutting and painting a cube. 
