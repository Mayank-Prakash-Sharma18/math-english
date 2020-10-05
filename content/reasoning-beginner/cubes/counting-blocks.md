---
title: Counting Blocks
linktitle: Counting Blocks
toc: true
type: docs
date: "2020-09-025T00:00:00+01:00"
draft: false
menu:
  cubes:
    parent: Cubes
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

A number of cubes (or cuboids) are shown in a figure and they need to be counted.

Let’s see some examples. 

## Finding all the cubes

##### Q. Count the number of cubes in the given figure.
<img src="../../../media/cubes/cube-blocks.png" alt="blocks of cubes" style="width:36%;height:36%;">
<pre>(a) 3   (b) 4   (c) 5   (d) 6 </pre>

Explanation:<br>
<div class="Exp">
There are 2 cubes in one column and 1 cube in two columns. <br>
So, total cubes = (2 × 1) + (1 × 2) = 4 <br>
Answer: (b)
</div>

##### Q. How many cubes are there in the group?
<img src="../../../media/cubes/cube-blocks1.png" alt="blocks of cubes" style="width:49%;height:49%;">
<pre>(a) 10   (b) 16   (c) 18   (d) 20 </pre>

Explanation:<br>
<div class="Exp">
There are 4 cubes in one column; 3 cubes in two columns; 2 cubes in three columns and 1 cube in four columns. <br>
Total number of cubes = 4 × 1 + 3 × 2 + 2 × 3 + 1 × 4 = 20 <br>
Answer: (a)
</div>

## Finding unseen cubes

Cubes that cannot be seen = Total cubes - Cubes that are visible

##### Q. Few cubes are arranged as shown in the figure. How many cubes are unseen ?
<img src="../../../media/cubes/cube-blocks2.png" alt="blocks of cubes" style="width:49%;height:49%;">
<pre>(a) 10   (b) 16   (c) 18   (d) 20 </pre>

Explanation:<br>
<div class="Exp">
There are 4 cubes in four columns; 3 cubes in four columns and 2 cubes in two columns. <br>
Total number of cubes = (4 × 4) + (3 × 4) + (2 × 2) = 32 <br>
Total number of visible cubes = 16 + 6 = 22 <br>
So, Total number of unseen cubes = Total cubes - Cubes that are visible = 32 – 22 = 10 <br>
Answer: (d)
</div>