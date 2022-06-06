---
title: Relation between Time, Speed and Distance
linktitle: Relation between TSD 
toc: true
type: docs
date: "2021-02-12T00:00:00+01:00"
draft: false
menu:
  time-speed-distance:
    parent: Time, Speed and Distance
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

Now, let us dive deeper in the Time, Speed and Distance (TSD) formula. We will study motion in straight line, and try to analyze the relationships between these three variables (i.e. Time, Speed and Distance). 

The best way to do so, is to keep one of them constant and then analysing how the other two vary with respect to each other. This is how many questions are structured too. 

Here are the three cases that may arise:

* Case I: When distance (D) is constant <br>
S α 1/T

* Case II: When Time (T) is constant: <br>
S α D

* Case III: When speed (S) is constant: <br>
D α T


## Distance is constant 

When distance (D) is constant, then the speed is inversely proportional to the time taken. 
 
S α 1/T

So, if the ratio of the speeds of A and B is a : b, then ratio of the time taken by A and B (in covering the same distance) = 1/a : 1/b = b : a

Or we can say that, if the ratio of the time taken by A and B (in covering the same distance) is b : a, then the ratio of the speeds of A and B is a : b. 

##### Q. A, B and C participate in a race and take 12, 8 and 16 minutes to complete it. What is the ratio of speeds of A, B and C?

Explanation:<br>
<div class="Exp">
When distance is the same, then the speed is inversely proportional to the time taken.

So, the ratio of speeds of A, B and C = (1/12) : (1/8) : (1/16) = (4/48) : (6/48) : (3/48) = 4 : 6 : 3

[LCM (12, 8, 16) = 48]
</div> <br>

Now, let us see some special concepts and question types that arise based on this relationship.

### Concept 1

A person covers a certain distance at a speed of S kmph. 

If he would have moved $S_1$  kmph faster, he would have taken $t_1$ hours less. <br>
If he would have moved $S_2$  kmph slower, he would have taken $t_2$ hours more. 

Then, the original speed, S = $\frac{S_1 S_2 (t_1 + t_2)}{S_1 t_2 − S_2 t_1}$ kmph

And the distance = S $t_1$ (1 + $\frac{S}{S_1}$) km 

{{% alert note %}}
Special Case: If $t_1$ = $t_2$,  then <br>
S = $\frac{2 S_1 S_2}{S_1 - S_2}$ kmph <br>
(if $S_1$ > $S_2$, otherwise we will  use $S_2 - S_2$ in the above formula)
{{% /alert %}}

##### Q. A person goes to his office moving at a particular speed, so as to reach at the exact time. One day he travelled 12 km/hr faster and reached his office 20 minutes earlier. Then another day he travelled 6 km/hr slower and was 15 minutes late. What is the original speed and distance to his office?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Formula Method <br><br>

$t_1$ = 20/60 = 1/3 and $t_2$ = 15/60 = 1/4 

Original speed, S = $\frac{S_1 S_2 (t_1 + t_2)}{S_1 t_2 − S_2 t_1}$ = $\frac{12 × 6 (1/3 + 1/4)}{12 × (1/4) – 6 × (1/3)}$ <br>
= 42 (3 – 2) = 42 km/hr

And the distance = S $t_1$ (1 + $\frac{S}{S_1}$) <br>
= 42 × (1/3) (1 + $\frac{42}{12}$) <br>
= 14 (9/2) = 63 km
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Traditional Method  <br><br>

Let the original speed and distance be S km/hr and d km respectively.<br>
Difference in time taken when moving at original speed and 12 km/hr faster = 20/60<br>
Or $\frac{d}{S}$ - $\frac{d}{S + 12}$ = 1/3 <br> 
Or d [$\frac{12}{S(S + 12)}$] = 1/3 <br>
Or 36d = S (S + 12)      ..... (1)

Difference in time taken when moving at original speed and 6 km/hr slower = 15/60 <br>
Or $\frac{d}{S - 6}$ - $\frac{d}{S}$ = 1/4 <br> 
Or d [$\frac{6}{S(S - 6)}$] = 1/4 <br>
Or 24d = S (S - 6)     ..... (2)

Using (1) and (2), we get: <br>
$\frac{S (S + 12)}{S (S - 6)}$ = 3/2 <br>
Or 2 (S + 12) = 3 (S - 6) <br>
Or S = 42 km/hr

Substituting this value of S in equation (2), we get: <br>
24d = S (S - 6) = 42 × 36 <br>
Or d = $\frac{42 × 36}{24}$ = 63 km
</div><br>

### Concept 2

A person travels some distance at a certain speed.

If the same distance is travelled at $\frac{a}{b}^{th}$ of the original speed and time taken is t mins more or less, then:

Original time taken = $\frac{a}{|a - b|}$ t times and <br>
New time taken = $\frac{b}{|a - b|}$ t

##### Q. A person travels some distance at a certain speed. If he increases his speed by 25%, then he takes 20 minutes less to cover the same distance. Find the time taken by him to cover the distance at original speed.

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-4', this, 'tablink-group1', 'tabcontent-group1')">4</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-5', this, 'tablink-group1', 'tabcontent-group1')">5</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Traditional Method <br><br>

Let the original speed be S km/hr and the original time taken be T hrs.

New speed = S + 25% of S = 1.25 S <br>
New time taken = T – 20/60 = T – 1/3 = (3T - 1)/3

Distance = ST = 1.25 S × (3T - 1)/3  <br>
Or T = 1.25 (3T - 1)/3  <br>
Or 12T = 15T – 5 <br>
Or 3T = 5  <br>
Or T = 5/3 hours = (5/3) × 60 = 100 minutes
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Formula Method<br><br>

Let the original speed be S km/hr and the original time taken be T hrs.
New speed = S + 25% of S = 1.25 S = (5/4) S

If the same distance is travelled at a/b th of the original speed and time taken is t mins more or less, then:

Original time taken = $\frac{a}{|a - b|}$ t times = $\frac{5}{|5 - 4|}$ × 20 = 100 minutes
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Percentage Method<br><br>

The distance travelled is constant. So, time taken will be inversely proportional to the speed.

If speed is increased by 25%, then time taken decreases by 20%. 

So, if the original time taken is T, then the new time taken = 0.8 T

Difference in the times taken = 20 <br>
Or T – 0.8 T = 20 <br>
Or 0.2 T = 20 <br>
Or T = 100 minutes
</div>

<div id="1Exp-4" class="Exp-4 mak-tabcontent tabcontent-group1">
Explanation 4: Percentage Method<br><br>

The distance travelled is constant. So, time taken will be inversely proportional to the speed.

If speed is increased by 25%, then time taken decreases by 20%. 

So, 20% ≡ 20 minutes <br>
Hence, 100% ≡ 20 × 5 = 100 minutes
</div>

<div id="1Exp-5" class="Exp-5 mak-tabcontent tabcontent-group1">
Explanation 5: Fraction Method<br><br>

The distance travelled is constant. So, time taken will be inversely proportional to the speed.

If speed is increased by 25%, then new speed is (5/4) times the original speed.

So, new time taken will be (4/5) times the original time. 

Difference in the times taken = 20 <br>
Or T – (4/5) T = 20 <br>
Or T/5 = 20 <br>
Or T = 100 minutes
</div><br>

### Concept 3

A person needs to cover a certain distance.  

If traveling at a speed of $S_1$ km/hr he gets $t_1$ hours late. <br>
And traveling at a speed of $S_2$ km/hr he reaches $t_2$ hours early.

Then, Distance = $\frac{S_1 S_2 (t_1 + t_2)}{(S_2 – S_1)}$

##### Q. A student going to summer camp will get late by 1 hour if travelling at a speed of 20 km/hr, while he will reach 2 hours early if he travels at a speed of 50 km/hr. How far is the summer camp ? 

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-3', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Formula Method <br><br>

Traveling at a speed of $S_1$ km/hr he gets $t_1$ hours late. <br>
And traveling at a speed of $S_2$ km/hr he reaches $t_2$ hours early.

So, Distance = $\frac{S_1 S_2 (t_1 + t_2)}{(S_2 – S_1)}$ = $\frac{20 × 50 (1 + 2)}{(50 - 20)}$ = 100 km
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Traditional Method  <br><br>

Let normal time = T hours

Distance, d = Speed × Time 

So, d = 20 × (T + 1)   ... (1) <br>
Also, d = 50 × (T - 2)  ... (2)

Using (1) and (2), we get: <br>
20 × (T + 1) = 50 × (T - 2)  <br>
Or 2T + 2 = 5T – 10 <br>
Or 3T = 12 <br>
Or T = 4 hours

So, d = 20 × (T + 1) = 20 × (4 + 1) = 100 km 
</div>

<div id="3Exp-3" class="Exp-3 mak-tabcontent tabcontent-group3">
Explanation 3: Percentage Method  <br><br>

Let normal time taken = T hours

Increase in speed from 20 km/hr to 50 km/hr is 150%. <br>
As distance is constant, so time taken will be inversely proportional to the speed. <br>
So, corresponding percentage reduction in time taken = (150/250) × 100 = 60%

He was initially 1 hour late and then got 2 hours early. <br>
So, reduction in time = 2 – (-1) = 2 + 1 = 3 hours 

So, 60% ≡ 3 hours <br>
And 100% ≡ 3 × (100/60) = 5 hours

So, at a speed of 20 km/hr, he will take 5 hours. <br>
Hence, distance = Speed × Time = 20 × 5 = 100 km
</div><br>


### Concept 4

When two persons cover the same distance with different speeds $S_1$ and $S_2$ km/hr and difference in time taken to cover this distance by them (i.e. |$T_1 - T_2$|) is given, then:

Distance = $|T_1 - T_2| \frac{(S_1 × S_2)}{|S_1 - S_2|}$

When two persons cover the same distance with different speeds $S_1$ and $S_2$ km/hr and addition of times taken to cover this distance by them (i.e. $T_1 + T_2$) is given, then:

Distance = $(T_1 + T_2) \frac{(S_1 × S_2)}{(S_1 + S_2)}$

##### Q. Two persons cover the same distance at a speed of 20 km/hr and 30 km/hr. If the difference in time taken by them to cover the distance is 5 hours, then find out the distance.

Explanations :<br>
<button class="mak-tablink tablink-group4 default-tab" onclick="openTab('4Exp-1', this, 'tablink-group4', 'tabcontent-group4')">1</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-2', this, 'tablink-group4', 'tabcontent-group4')">2</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-3', this, 'tablink-group4', 'tabcontent-group4')">3</button>

<div id="4Exp-1" class="Exp-1 mak-tabcontent tabcontent-group4">
Explanation 1: Formula Method <br><br>

When two persons cover the same distance with different speeds $S_1$ and $S_2$ km/hr and difference in time taken to cover this distance is given, then:

Distance = $|T_1 - T_2| \frac{(S_1 × S_2)}{|S_1 - S_2|}$ = $\frac{5 (20 × 30)}{(30 - 20)}$ = 300 km
</div>

<div id="4Exp-2" class="Exp-2 mak-tabcontent tabcontent-group4">
Explanation 2: Traditional Method  <br><br>

The distance travelled by the two persons is the same. 

20 × T = 30 × (T – 5) <br>
Or 2T = 3T – 15 <br>
Or T = 15 hours

So, distance = 20 × T  = 20 × 15 = 300 km
</div>

<div id="4Exp-3" class="Exp-3 mak-tabcontent tabcontent-group4">
Explanation 3: Percentage Method  <br><br>

Percentage increase in speed from 20 to 30 km/hr = 50%

As distance is constant, the percentage decrease in time taken will be proportional, i.e. (50/150) × 100 = 100/3 %

So, 100/3 % ≡ 5 hours <br>
And so, 100% ≡ 5 × 3 = 15 hours

So, distance = Speed × Time = 20 × 15 = 300 km
</div><br>

##### Q. Two persons cover the same distance at a speed of 20 km/hr and 30 km/hr. If the addition of the times taken by them to cover the distance is 25 hours, then find out the distance.

Explanations :<br>
<button class="mak-tablink tablink-group5 default-tab" onclick="openTab('5Exp-1', this, 'tablink-group5', 'tabcontent-group5')">1</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-2', this, 'tablink-group5', 'tabcontent-group5')">2</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-3', this, 'tablink-group5', 'tabcontent-group5')">3</button>

<div id="5Exp-1" class="Exp-1 mak-tabcontent tabcontent-group5">
Explanation 1: Formula Method <br><br>

When two persons cover the same distance with different speeds $S_1$ and $S_2$ km/hr and difference in time taken to cover this distance is given, then:

Distance = $(T_1 + T_2) \frac{(S_1 × S_2)}{(S_1 + S_2)}$ = $\frac{25 (20 × 30)}{(20 + 30)}$ = 300 km
</div>

<div id="5Exp-2" class="Exp-2 mak-tabcontent tabcontent-group5">
Explanation 2: Traditional Method  <br><br>

The distance travelled by the two persons is the same. Let times taken by them be  a and b.
So, 20a = 30b <br>
Or a = 3b/2    ..... (1) <br>
And a + b = 25    <br>
Or 3b/2 + b = 25 <br>
Or 5b/2 = 25 <br>
Or b = 10 hours

So, distance = Speed × Time  = 30 × 10 = 300 km
</div>

<div id="5Exp-3" class="Exp-3 mak-tabcontent tabcontent-group5">
Explanation 3: Percentage Method  <br><br>

Percentage increase in speed from 20 to 30 km/hr = 50%

As distance is constant, the percentage decrease in time taken will be proportional, i.e. (50/150) × 100 = 100/3 %

Now, Addition of two times taken = 100 + (100 - 100/3) = 500/3%

So, 500/3% ≡ 25 hours <br>
And so, 100% ≡ (25 × 3)/5 = 15 hours

So, distance = Speed × Time = 20 × 15 = 300 km
</div><br>


## Miscellaneous Questions

##### Q. A man started from home at 14:30 hours and drove to a village, arriving there when the village clock indicated 15:15 hours. After staying, for 25 minutes, he drove back by a different route of length 1.25 times the first route at a rate twice as fast reaching home at 16:00 hours. As compared to the clock at home, the village clock is <br>
(a) 10 minutes slow <br>
(b) 5 minutes slow <br>
(c) 10 minutes fast <br>
(d) 5 minutes fast

Explanation:<br>
<div class="Exp">

Total time taken by the man to come back home = 16 – 14.5 = 1.5 hours = 90 minutes <br>
Out of which he stayed in the village for 25 minutes. <br>
So, his total travelling time = 90 – 25 = 65 minutes

The return route was 1.25 times the initial route. So, time taken must have increased by 25% too. So, if initial time was 100 units, now it must be 125 units. <br>

But it is also given that while returning he drove twice as fast. So, time taken must have been halved. <br>So, time taken while returning back = 125/2 = 62.5 units

So, 100 + 62.5 = 65 minutes <br>
Or 162.5 units = 65 minutes <br>
So, 100 units = (65/162.5) × 100 = 40 minutes

So, the man took 40 minutes to reach to the village. <br>
So, the actual time at that moment = 14:30 + 40 minutes = 15:10 hours <br>
It’s pretty evident that the village clock is 15:15 – 15:10 = 5 minutes fast

Answer: (d)
</div> <br>

