---
title: Average Speed
linktitle: Average Speed
toc: true
type: docs
date: "2021-02-15T00:00:00+01:00"
draft: false
menu:
  time-speed-distance:
    parent: Time, Speed and Distance
    weight: 12

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 12
---

## Average speed Formula

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$

Let us consider some scenarios with respect to average speed, and variations of the above formula:

### Scenario 1

If a man travels different distances $D_1$, $D_2$, $D_3$, ....... and so on in different times $T_1$, $T_2$, $T_3$, .......... and so on respectively, then

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$
= $\frac{D_1 + D_2 + D_3 + …}{T_1 + T_2 + T_3 + …}$

### Scenario 2

If one part of the distance is covered at a speed of $v_1$ in time $t_1$ and the other part of the distance is covered at a speed of $v_2$ in time $t_2$, then 

the average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$
= $\frac{v_1 t_1 + v_2 t_2}{t_1 + t_2}$

### Scenario 3

If a man travels different distances $D_1$, $D_2$, $D_3$, ...... and so on with different speeds $S_1$, $S_2$, $S_3$, ........ and so on respectively, then 

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$ 
= $\frac{D_1 + D_2 + D_3 + …}{(\frac{D_1}{S_1} + \frac{D_2}{S_2} + \frac{D_3}{S_3} + …)}$

{{% alert note %}}
Special case: If a distance is divided into n equal parts each travelled with different speeds, then $D_1$ = $D_2$ = $D_3$ = … = $D_n$

Average speed = $\frac{nD}{(\frac{D}{S_1} + \frac{D}{S_2} + \frac{D}{S_3} + … + \frac{D}{S_n})}$ = $\frac{n}{(\frac{1}{S_1} + \frac{1}{S_2} + \frac{1}{S_3} + … + \frac{1}{S_n})}$ 

where n = number of equal parts and $S_1$, $S_2$, $S_3$, ............. $S_n$ are speeds.
{{% /alert %}}

## Finding Average Speed when distance or time are same

We often encounter following scenarios in questions on average speed:
* The distances travelled at two different speeds are the same. E.g. A person travels from X to Y with speed A and then comes back with speed B.
* The time for which a person travels at the two speeds is the same. E.g. A person travels with speed A for t minutes and then at speed B for t minutes again. 

Let us consider both of these scenarios. 

### Distance travelled is same 

If there are two equal parts of journey, it means n = 2 in the following formula: 

Average speed = $\frac{n}{(\frac{1}{S_1} + \frac{1}{S_2} + \frac{1}{S_3} + … + \frac{1}{S_n})}$

In other words, if a person goes from x to y at $S_1$ km/hr and comes back from y to x at $S_2$ km/hr, then the average speed during the whole journey will be:

Average speed = $\frac{2}{(\frac{1}{S_1} + \frac{1}{S_2})}$ = $\frac{2 S_1 S_2}{S_1 + S_2}$

##### Q. A person travels from A to B at a speed of 20 km/hr and then comes back to A at a speed of 30 km/hr. What is his average speed over the entire journey?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Traditional Method <br><br>

Let the one side distance be d km. 

Time taken to travel from A to B = Distance / Speed = d/20 hrs

Time taken to travel from B to A = Distance / Speed = d/30 hrs

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$ 
= $\frac{2d}{(\frac{d}{20} + \frac{d}{30})}$ = $\frac{2 (20 × 30)}{(20 + 30)}$ = 24 km/hr 
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Formula Method<br><br>

Average speed = $\frac{2 S_1 S_2}{S_1 + S_2}$ = $\frac{2 (20 × 30)}{(20 + 30)}$ = 24 km/hr
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Allegation Method<br><br>

The average speed is the weighted average with the time travelled at the different speeds being the weight.

The two speeds are 20 km/hr and 30 km/hr. As the distance is constant, so the time must be in inverse proportion, i.e. 3:2.

So, Average speed = $\frac{(3 × 20) + (2 × 30)}{(3 + 2)}$ = 120/5 = 24 km/hr
</div><br>


##### Q. . A local bus completed a round trip at an average speed of 48 km per hour. The bus covered the first half of the distance at an average speed of 36 km per hour. What would have been its average speed during the second half of the journey?
<pre>(a) 48 km/hour   (b) 60 km/hour    (c) 72 km/hour   (d) 84 km/hour</pre>

Explanations :<br>
<button class="mak-tablink tablink-group7 default-tab" onclick="openTab('7Exp-1', this, 'tablink-group7', 'tabcontent-group7')">1</button>
<button class="mak-tablink tablink-group7" onclick="openTab('7Exp-2', this, 'tablink-group7', 'tabcontent-group7')">2</button>
<button class="mak-tablink tablink-group7" onclick="openTab('7Exp-3', this, 'tablink-group7', 'tabcontent-group7')">3</button>

<div id="7Exp-1" class="Exp-1 mak-tabcontent tabcontent-group7">
Explanation 1: Traditional Method <br><br>

Let the total distance covered by bus in the round trip be x km. Let y be the average speed during the second half of the journey.

Hence, the total time taken in complete journey = Total distance/average speed = x/48 hour

Now, total time = time taken during 1st half of the trip + time taken during 2nd half of the trip <br>
Hence, x/48 = 0.5x/36 + 0.5x/y <br>
or x/48 - 0.5x/36 = 0.5x/y <br>
or x/144 = 0.5x/y <br>
or y = 72 km/hour
</div>

<div id="7Exp-2" class="Exp-2 mak-tabcontent tabcontent-group7">
Explanation 2: Formula Method <br><br>

Average speed = $\frac{2 S_1 S_2}{S_1 + S_2}$ <br><br>
or 48 = $\frac{2 × 36 × S_2}{36 + S_2}$ <br><br>
or 2 = $\frac{3 × S_2}{36 + S_2}$ <br><br>
or $S_2$ = 72 km/hour
</div>

<div id="7Exp-3" class="Exp-3 mak-tabcontent tabcontent-group7">
Explanation 3: Allegation Method <br><br>

The average speed is the weighted average with the time travelled at the different speeds being the weight.

<img src="../../../media/tsd/average-speed-1.png" alt="Average Speed" style="width:45%;height:45%;">
As the distance is constant, so the time must be in inverse proportion. <br>
So, $\frac{36}{x}$ = $\frac{12}{(x – 48)}$ <br>
or $\frac{3}{x}$ = $\frac{1}{(x – 48)}$ <br>
or 3x - 3 × 48 = x <br>
or x = 72 km/hour
</div><br>


### Time taken is same 

When time taken is constant:  The average speed of travelling at two different speeds for the same time span is just the simple average of two speeds.

Average speed = $\frac{S_1 + S_2}{2}$

(Where, $S_1$ and $S_2$ are the two speeds at which we traveled for the same time.)

{{% alert warning %}}
Note: The average speed is the weighted average with the time travelled at the different speeds being the weight and not the distance travelled at the different speeds.
{{% /alert %}}

##### Q. A person travels from A to B. For half the time he travelled at a speed of 20 km/hr and then at a speed of 30 km/hr for the other half. What is his average speed over the entire journey?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-3', this, 'tablink-group2', 'tabcontent-group2')">3</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Traditional Method <br><br>

Let the distance travelled be d meters and the total time be 2 hours.

So, d = $d_1$ + $d_2$ = (20 × 1) + (30 × 1) = 50 kms

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$ = 50/2 = 25 km/hr 
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Formula Method  <br><br>

Time spent in the two parts of the journey is the same. 

So, Average speed = $\frac{S_1 + S_2}{2}$ = (20 + 30)/2 = 25 km/hr
</div>

<div id="2Exp-3" class="Exp-3 mak-tabcontent tabcontent-group2">
Explanation 3: Allegation Method  <br><br>

The average speed is the weighted average with the time travelled at the different speeds being the weight.

So, Average speed = $\frac{(1 × 20) + (1 × 30)}{(1 + 1)}$ = 50/2 = 25 km/hr
</div><br>

<br><hr><br>

## Special Cases of Average Speed

### Case 1

A person goes a certain distance at a speed of $S_1$ km/hr and returns back to the same place at a speed of $S_2$ km/hr. If he takes ‘T’ hours in all (i.e. addition of times taken is given), then the distance between first place and the second place is –

Distance = $\frac{Average \hspace{1ex} speed × Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} two \hspace{1ex} side \hspace{1ex} journey}{2}$
= $\frac{(\frac{2 S_1 S_2}{S_1 + S_2}) × T}{2}$ <br>
= $\frac{S_1 S_2}{S_1 + S_2}$ × T km

##### Q. A person travels from A to B at a speed of 20 km/hr and then comes back to A at a speed of 30 km/hr. What is the distance between A and B if the total time taken in the two way journey is 5 hours?

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-3', this, 'tablink-group3', 'tabcontent-group3')">3</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Traditional Method <br><br>

Let the one side distance be d km. 

Time taken to travel from A to B = Distance / Speed = d/20 hrs

Time taken to travel from B to A = Distance / Speed = d/30 hrs

Total time taken = (d/20) + (d/30) = 5 <br>
Or (5d/60) = 5  <br>
Or d = 60 km
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Formula Method <br><br>

Distance = $\frac{S_1 S_2}{S_1 + S_2}$ × T km = $\frac{(20 × 30)}{(20 + 30)}$ × 5 = 60 km   
</div>

<div id="3Exp-3" class="Exp-3 mak-tabcontent tabcontent-group3">
Explanation 3:  <br><br>

The two speeds are 20 km/hr and 30 km/hr. As the distance is constant, so the time must be in inverse proportion, i.e. 3:2.

Total time taken = 5 hours <br>
So, the time taken at 20 km/hr and 30 km/hr will be 3 hours and 2 hours respectively. 

So, one side distance = 20 × 3 = 60 km <br>
Or 30 × 2 = 60 km
</div><br>

### Case 2

If an object travels a distance 'd' with speed $S_1$ in time $t_1$ and travels back the same distance with $\frac{m}{n}$ of the usual speed $S_1$, then:

Change in time taken to cover the same distance = $[(\frac{m}{n}) – 1] t_1$     ... (if n>m)

Or Change in time taken to cover the same distance = $[1 - (\frac{n}{m})] t_1$     ... (if m>n)

##### Q. A person travels from A to B at a speed of 20 km/hr in 3 hours and then comes back to A at 3/2 times the previous speed. What is the difference in time taken in the two journeys?

Explanations :<br>
<button class="mak-tablink tablink-group4 default-tab" onclick="openTab('4Exp-1', this, 'tablink-group4', 'tabcontent-group4')">1</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-2', this, 'tablink-group4', 'tabcontent-group4')">2</button>

<div id="4Exp-1" class="Exp-1 mak-tabcontent tabcontent-group4">
Explanation 1: Traditional Method <br><br>

Let the one side distance be d km. 

d = Speed × Time = 20 × 3 = 60 km

Speed while going from B to A = (3/2) × 20 = 30 km/hr

Time taken to travel from B to A = Distance / Speed = 60/30 = 2 hours

So, the difference in time taken in the two journeys = 3 – 2 = 1 hour
</div>

<div id="4Exp-2" class="Exp-2 mak-tabcontent tabcontent-group4">
Explanation 2: Formula Method <br><br>

m/n = 3/2

So, m = 3 and n = 2

Change in time taken to cover the same distance = $[1 - (\frac{n}{m})] t_1$ = [1 – ($\frac{2}{3}$
)] × 3 = (1/3) × 3 =  1 hour
</div><br>

### Case 3

If a body covers part of the journey at speed $S_1$ and the remaining part of the journey at speed $S_2$ and the distances of the two parts of the journey are in the ratio m : n, then: 

Average speed for the entire journey = $\frac{(m + n) S_1 S_2}{(m S_2 + n S_1)}$

##### Q. A person travels one part of the journey at a speed of 20 km/hr and the other part at a speed of 30 km/hr. If the distance travelled in two parts is in the ratio 1:3, then what is his average speed in the entire journey? 

Explanations :<br>
<button class="mak-tablink tablink-group5 default-tab" onclick="openTab('5Exp-1', this, 'tablink-group5', 'tabcontent-group5')">1</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-2', this, 'tablink-group5', 'tabcontent-group5')">2</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-3', this, 'tablink-group5', 'tabcontent-group5')">3</button>

<div id="5Exp-1" class="Exp-1 mak-tabcontent tabcontent-group5">
Explanation 1: Traditional Method <br><br>

Let first part of the journey be x km and the second part be 3x km. 

Time taken to travel the first part of the journey = Distance / Speed = x/20 hrs

Time taken to travel the second part of the journey = Distance / Speed = 3x/30 hrs

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$ 
= $\frac{4x}{(\frac{x}{20}) + (\frac{3x}{30})}$
= $\frac{(4 × 60)}{(3 + 6)}$ = 80/3 km/hr 
</div>

<div id="5Exp-2" class="Exp-2 mak-tabcontent tabcontent-group5">
Explanation 2:   <br><br>

Let first part of the journey be 20 km and the second part be 60 km. 

Time taken to travel the first part of the journey = Distance / Speed = 20/20 = 1 hr

Time taken to travel the second part of the journey = Distance / Speed = 60/30 = 2 hrs

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$ 
= $\frac{(20 + 60)}{(1 + 2)}$ = 80/3 km/hr
</div>

<div id="5Exp-3" class="Exp-3 mak-tabcontent tabcontent-group5">
Explanation 3: Formula Method <br><br>

Average speed for the entire journey = $\frac{(m + n) S_1 S_2}{(m S_2 + n S_1)}$ 
= $\frac{(1 + 3) (20 × 30)}{(1 × 30 + 3 × 20)}$ = $\frac{(4 × 20 × 30)}{(30 + 60)}$ = 80/3 km/hr
</div><br>

### Case 4

Suppose a person takes T hours in covering a distance of x km. If he covers some of the distance at a speed of $S_1$ km/hr on foot and rest of the distance on cycle at a speed of $S_2$ km/hr, then:

Time taken to cover the distance on foot = $\frac{(S_2 T - x)}{(S_2 – S_1)}$ hours

##### Q. A person travels one part of the journey on foot at a speed of 10 km/hr and the other part on cycle at a speed of 20 km/hr. If the person travels 80 km in 5 hours, then what is the time taken to cover the distance on foot ?

Explanations :<br>
<button class="mak-tablink tablink-group6 default-tab" onclick="openTab('6Exp-1', this, 'tablink-group6', 'tabcontent-group6')">1</button>
<button class="mak-tablink tablink-group6" onclick="openTab('6Exp-2', this, 'tablink-group6', 'tabcontent-group6')">2</button>
<button class="mak-tablink tablink-group6" onclick="openTab('6Exp-3', this, 'tablink-group6', 'tabcontent-group6')">3</button>

<div id="6Exp-1" class="Exp-1 mak-tabcontent tabcontent-group6">
Explanation 1: Traditional Method <br><br>

Let the distance travelled on foot be x km.

The person travels 80 km in 5 hours, i.e. a speed of 80/5 = 16 km/hr

Time taken to travel the first part of the journey = Distance / Speed = x/10 hrs

Time taken to travel the second part of the journey = Distance / Speed = (80 - x)/20 hrs

Average speed = $\frac{Total \hspace{1ex} distance \hspace{1ex} travelled}{Total \hspace{1ex} time \hspace{1ex} taken \hspace{1ex} in \hspace{1ex} travelling \hspace{1ex} that \hspace{1ex} distance}$ <br>
Or 16 = $\frac{80}{(\frac{x}{10}) + (\frac{80 − 𝑥}{20})}$ <br>
Or x + 80 =  100 <br>
Or x = 20 km  <br>
So, the time taken to cover the distance on foot = Distance/Speed = 20/10 = 2 hours
</div>

<div id="6Exp-2" class="Exp-2 mak-tabcontent tabcontent-group6">
Explanation 2: Formula Method <br><br>

Time taken to cover the distance on foot = $\frac{(S_2 T - x)}{(S_2 – S_1)}$ hours <br>
= $\frac{(20 × 5 - 80)}{(20 - 10)}$ = 20/10 = 2 hours
</div>

<div id="6Exp-3" class="Exp-3 mak-tabcontent tabcontent-group6">
Explanation 3: Allegation Method <br><br>

The average speed is the weighted average with the time travelled at the different speeds being the weight.

The person travels 80 km in 5 hours, i.e. an average speed of 80/5 = 16 km/hr
<img src="../../../media/tsd/average-speed.png" alt="average speed" style="width:45%;height:45%;">

So, the ratio of time travelled on foot and cycle is 4:6 = 2:3 <br>
So, the time travelled on foot = (2/5) × 5 = 2 hours
</div><br>