---
title: Boats and Streams 
linktitle: Boats and Streams
toc: true
type: docs
date: "2021-02-17T00:00:00+01:00"
draft: false
menu:
  time-speed-distance:
    parent: Time, Speed and Distance
    weight: 21

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 21
---

In questions of boats and stream, there are generally two variables involved - the speed of the boat(s) and the speed of the stream.  

You will only seldom get a question in which the water is still, i.e. speed of the stream is nil. In most cases the stream will be flowing with a certain speed in some direction. 

So, obviously if you will row a boat in a running stream, two cases may arise. Either the boat will row with the stream or against it. 

Now, the questions in this chapter are framed in various ways. Let us study them.

## Individual speeds of boat and stream given

This is the easiest question type, wherein you will be given the individual speeds of both boat and stream. 

Let the speed of a boat in still water be B km/hr and the speed of the stream be S km/hr.

### Finding Downstream speed 

Downstream - it means boat is moving with the current

When a boat is moving in the same direction as the water current, the speed of the water aids and so adds to the speed of the boat. 

Downstream speed = (B + S) km/hr

### Finding Upstream speed  

Upstream - it means boat is moving against the current

When a boat is moving in a direction opposite to that of the water current, the speed of the water opposes and so reduces the speed of the boat. 

Upstream speed = (B – S) km/hr

{{% alert note %}}
If the water is not moving (i.e. S = 0), then the speed of the boat is called the speed of the boat in still water.
{{% /alert %}}

{{% alert note %}}
Note: If objects move in opposite direction, then their relative speed is the addition of their speeds and if objects move in the same direction, their relative speed is their difference. 

But in case of boats and streams, when boat moves downstream (i.e. both boat and stream are moving in the same direction), we add their speeds and when boat moves upstream (i.e. in opposite direction of the stream) we subtract their speeds. 
{{% /alert %}}

##### Q. The speed of boat in still water is 8 m/sec and the speed of the stream is 5 m/sec. What is the ratio of the time taken to cover a particular stretch of distance in upstream and downstream direction?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: <br><br>

Distance travelled in both direction is the same. 

Ratio of upstream and downstream speeds are (8 - 5) : (8 + 5) = 3 : 13

So, time taken in travelling upstream and downstream will be in the ratio 13 : 3
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Distance travelled in both direction is the same. Let it be d.

Time taken to travel upstream = distance / upstream speed = d / (8 - 5) = d/3 sec

Time taken to travel downstream = distance / downstream speed = d / (8 + 5) = d/13 sec

So, time taken in travelling upstream and downstream will be in the ratio (d/3) : (d/13) = 13 : 3
</div><br>

### Finding Average speed

If a man rows the same distance up and down, then

Average speed throughout the journey =  $\frac{Downstream \hspace{1ex} Speed × Upstream \hspace{1ex} Speed}{Speed \hspace{1ex} in \hspace{1ex} still \hspace{1ex} water}$

So, Average Speed = $\frac{(B + S)(B − S)}{B}$ km/hr 

##### Q. A man can row at a speed of 15 km/hr in still water and the speed of the stream is 5 km/hr. If he goes upstream to a point and then comes back to the starting point, then what must be his average speed for the whole journey?  

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Formula Method <br><br>

Upstream speed = 15 – 5 = 10 km/hr <br>
Downstream speed = 15 + 5 = 20 km/hr

Average Speed = $\frac{Downstream \hspace{1ex} Speed × Upstream \hspace{1ex} Speed}{Speed \hspace{1ex} in \hspace{1ex} still \hspace{1ex} water}$ = (10 × 20)/15 = 40/3 km/hr
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Traditional Method  <br><br>

Let the distance travelled from starting to end point be d km <br>
Upstream speed = 15 – 5 = 10 km/hr <br>
Downstream speed = 15 + 5 = 20 km/hr

Total time = d/10 + d/20 = 3d/20

Average Speed = Total distance/Total time = $\frac{2d}{(\frac{3d}{20})}$ = 40/3 km/hr
</div><br>

<br><hr><br>

## Upstream and Downstream times given

Here, we come across two types of questions. 

### Absolute values of times given

A man rows a certain distance downstream in ‘$t_1$’ hours and returns the <strong><span class="mak-text-color">same distance</span></strong> upstream in ‘$t_2$’ hours, then 

Speed of the boat in still water, B = S $(\frac{t_2 + t_1}{t_2 − t_1})$ km/hr

##### Q. A boatman can row a certain distance upstream in 8 hours and the same distance downstream in 6 hours. If the speed of the stream is 2 km/hr, then what must be the speed of the boat in still water?

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Formula Method <br><br>

A man rows a certain distance downstream in ‘$t_1$’ hours and returns the <strong><span class="mak-text-color">same distance</span></strong> upstream in ‘$t_2$’ hours, then 

Speed of the boat in still water, B = S $(\frac{t_2 + t_1}{t_2 − t_1})$ km/hr = 2 (8 + 6) / (8 - 6) = 14 km/hr
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: LCM + Unitary Method  <br><br>

Let distance from starting point to end point be LCM (8, 6) = 24 km.

So, upstream speed, B – S = 24/8 = 3 km/hr    ……(1) <br>
And downstream speed, B + S = 24/6 = 4 km/hr   ……(2)

Using 1 and 2, we get: <br>
B = 3.5 km/hr and S = 0.5 km/hr

So, if S is 0.5 km/hr, then B is 3.5 km/hr <br>
But we know that S = 2 km/hr, so B = (3.5/0.5) × 2 = 14 km/hr
</div><br>

### Ratio of times given

A man takes n times as long to row upstream then to row downstream in the river (the <strong><span class="mak-text-color">same distance</span></strong>), then $t_2$ = n$t_1$

Speed of the boat in still water, B = S $(\frac{t_2 + t_1}{t_2 − t_1})$ km/hr = S $(\frac{n + 1}{n - 1})$ km/hr 

### Difference of times given

A man can row a boat in still water at B km/hr and a stream is flowing at S km/hr. 

If he takes ‘t’ hours more in upstream than to go downstream for the <strong><span class="mak-text-color">same distance</span></strong> (difference in time given), then

Distance between the two places = $\frac{(B^2 − S^2) t}{2S}$ km

### Sum of times given

If it takes him ‘t’ hours to row to a place and come back (total time given), then

Distance between the two places = $\frac{(B^2 − S^2) t}{2B}$ km 

##### Q. A boat can be rowed at a speed of 8 km/hr in still water. It travels 27 km upstream and then returns back to the starting point in a river flowing at a speed of 4 km/hr. What must be the total journey time?

Explanations :<br>
<button class="mak-tablink tablink-group5 default-tab" onclick="openTab('5Exp-1', this, 'tablink-group5', 'tabcontent-group5')">1</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-2', this, 'tablink-group5', 'tabcontent-group5')">2</button>

<div id="5Exp-1" class="Exp-1 mak-tabcontent tabcontent-group5">
Explanation 1: Formula Method <br><br>

If it takes him ‘t’ hours to row to a place and come back (total time given), then

Distance between the two places = $\frac{(B^2 − S^2) t}{2B}$ <br>
Or 27 = $\frac{(8^2 − 4^2) t}{(2 × 8)}$<br>
Or 27 = $\frac{t (64 - 16)}{(2 × 8)}$<br>
Or 27 = $\frac{48 t}{(2 × 8)}$ <br>
Or 27 = 3t <br>
Or t = 27/3 = 9 hours
</div>

<div id="5Exp-2" class="Exp-2 mak-tabcontent tabcontent-group5">
Explanation 2: Traditional Method <br><br>

Downstream speed = 8 + 4 = 12 km/hr <br>
Upstream speed = 8 - 4 = 4 km/hr

Total time = Time taken upstream + Time taken downstream = 27/4 + 27/12 = (27/4) (1 + 1/3) = (27/4) (4/3) = 27/3 = 9 hours
</div><br>


<br><hr><br>


## Upstream and Downstream speeds given

Let the down stream speed be x km/hr and the upstream speed be y km/hr, then

Speed in still water = $\frac{1}{2}$ (x + y) km/hr

Speed of stream = $\frac{1}{2}$ (x – y) km/hr

##### Q. Upstream speed and downstream speed of a boat are 4 km/hr and 6 km/her respectively. Find the speed of the boat in still water. 

Explanations :<br>
<button class="mak-tablink tablink-group4 default-tab" onclick="openTab('4Exp-1', this, 'tablink-group4', 'tabcontent-group4')">1</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-2', this, 'tablink-group4', 'tabcontent-group4')">2</button>

<div id="4Exp-1" class="Exp-1 mak-tabcontent tabcontent-group4">
Explanation 1: Formula Method <br><br>

Let the down stream speed be x km/hr and the upstream speed be y km/hr, then

Speed in still water = $\frac{1}{2}$ (x + y) = (6 + 4)/2 = 10/2 = 5 km/hr
</div>

<div id="4Exp-2" class="Exp-2 mak-tabcontent tabcontent-group4">
Explanation 2: Traditional Method <br><br>

Let the speed of boat in still water be B km/hr and speed of stream be S km/hr, then

B + S = 6    ..... (1) <br>
B – S = 4    ..... (2)

On adding (1) and (2), we get: <br>
2B = 10  <br>
Or B = 5 km/hr
</div><br>
