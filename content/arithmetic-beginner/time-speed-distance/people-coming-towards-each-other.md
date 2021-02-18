---
title: Two people coming towards each other
linktitle: Two people coming towards each other 
toc: true
type: docs
date: "2021-02-13T00:00:00+01:00"
draft: false
menu:
  time-speed-distance:
    parent: Time, Speed and Distance
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

Many times you will encounter questions wherein two people or objects will be coming towards each other. In this sub-module, we will discuss how to tackle such questions. 

{{% alert note %}}
Many of such questions involve the concept of relative speed. Such questions have been covered separately in Relative Speed sub-module. 
{{% /alert %}}

Such questions may be framed in various forms. Let us see all such possible cases/concepts and the corresponding formulae.

## Case 1: People/Objects start at the same time

If two persons/objects A and B start at the same time from two points x and y towards each other and after crossing they take $T_1$ and $T_2$ hours in reaching y and x respectively, then:

$\frac{S_A}{S_B}$ = $√\frac{T_2}{T_1}$

##### Q. Car A starts on a journey from Bristol to London and at the same time another car B starts from London to go to Bristol. After they meet, they reach their destinations after 16 and 25 hours respectively. What is the ratio of the speeds of cars A and B?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method <br><br>

If two persons/objects A and B start at the same time from two points x and y towards each other and after crossing they take $T_1$ and $T_2$ hours in reaching y and x respectively, then:

$\frac{S_A}{S_B}$ = $√\frac{T_2}{T_1}$ = √(25/16) = 5/4
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Traditional Method<br><br>

Let the distance from Bristol to London be d km and they meet x km from Bristol. 

So, $S_A/S_B$  = Distance travelled by car A/Distance travelled by car B = x/(d - x)    (as the time for which the cars moved is the same)   ..... (1) <br>
$S_A$ = Distance travelled by car A after meeting/Time = (d - x)/16   ..... (2) <br>
$S_B$ = Distance travelled by car B after meeting/Time = x/25   ..... (3) <br>

Using (1) and (2), we get: <br>
$S_A/S_B$  = 25 (d - x)/16 x  <br>
Or $S_A/S_B$  = (25/16) ($S_B/S_A$)    (using equation 1) <br>
Or ($S_A/S_B)^2$  = 25/16 <br>
Or $S_A/S_B$ = 5/4
</div><br>

## Case 2: People/Objects end at the same time

Two persons A and B travel for $T_1$ and $T_2$ time towards each other from opposite ends on a linear track and then they meet. After this meeting both of them reach at their respective destinations at the same time, then:

Time taken by each of them to reach their respective destination after meeting each other, T = $√T_1 T_2$

##### Q. Car A starts on a journey from Bristol to London and another car B starts from London to go to Bristol. They meet after car A and car B have travelled for 16 and 25 hours respectively. What is the time taken by each of them to reach their respective destination after meeting each other, if they reach their destination at the same time?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Formula Method <br><br>

Two persons A and B travel for $T_1$ and $T_2$ time towards each other from opposite ends on a linear track and then they meet. After this meeting both of them reach at their respective destinations at the same time, then:

Time taken by each of them to reach their respective destination after meeting each other, T = $√T_1 T_2$ = √(16 × 25) = 4 × 5 = 20 hours
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Traditional Method  <br><br>

Let the distance from Bristol to London be d km and they meet x km from Bristol. 

$S_A$ = Distance travelled by car A before meeting/Time = x/16   ..... (1) <br>
Distance travelled by car A after meeting = (d – x) = $S_A$ × T     <br>
Or d – x = (x/16) × T   ..... from equation (1)  <br>
Or (d - x)/x = T/16   ..... (2) 

$S_B$ = Distance travelled by car B before meeting/Time = (d - x)/25   ..... (3)  <br>
Distance travelled by car B after meeting = x = $S_B$ × T     <br>
Or x = [(d - x)/25] × T   ..... from equation (3)  <br>
Or 25/T = (d - x)/x   <br>
Or 25/T = T/16   ..... from equation (2) <br>
Or $T^2$ = 25 × 16 <br>
Or T = 5 × 4 = 20 hours
</div><br>

## Case 3

A person/object leaves a point A at $t_1$ and reaches the point B at $t_2$. 
Time taken by A, $T_A$ = $t_2$ – $t_1$

Another person/object leaves the point B at $t_3$ and reaches the point A at $t_4$
Time taken by B, $T_B$ = $t_4$ – $t_3$

Then the time when they met = $t_1$ + $\frac{T_A  (t_4 – t_1)}{T_A + T_B}$

##### Q. Car A starts on a journey from Bristol to London at 10 AM and reaches London at 2 PM. Similarly, car B starts on a journey from  London to Bristol at 11 AM and reaches Bristol at 5 PM. What is the time when they must have met?

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Formula Method <br><br>

$t_1$ = 10 AM; $t_2$ = 2 PM; $t_3$ = 11 AM; $t_4$ = 5 PM <br>
Time taken by A, $T_A$ = $t_2$ – $t_1$ = 2 PM – 10 AM = 4 hours <br>
Time taken by B, $T_B$ = $t_4$ – $t_3$ = 5 PM – 11 AM = 6 hours

Then the time when they met = $t_1$ + $\frac{T_A  (t_4 – t_1)}{T_A + T_B}$ = 10 AM + $\frac{(4 × 7)}{(4 + 6)}$ <br>
= 10 AM + (28/10) = 10 AM + 2.8 hours = 12 noon + 0.8 hours = 12 noon + (0.8 × 60) minutes = 12 noon + 48 minutes, i.e. 12:48 PM
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Relative Speed Method  <br><br>

Time taken by A in the whole journey, $T_A$ = 2 PM – 10 AM = 4 hours <br>
Time taken by B in the whole journey, $T_B$ = 5 PM – 11 AM = 6 hours <br>
As the distance travelled is the same, speed will be inversely proportional to the time taken. 
So, $S_A/S_B$ = 6/4 = 3/2 

Let $S_A$ = 3 km/hr and $S_B$ = 2 km/hr <br>
So, the distance from Bristol to London = $S_A$ × 4 = 3 × 4 = 12 km

The distance between them at 11 AM = Total distance – Distance travelled by car A from 10 AM to 11 AM = 12 – 3 = 9 km

Time after which the cars will meet = 11 AM + [Relative distance/Relative speed] = 11 AM + [9/(3 + 2)] <br>
= 11 AM + (9/5) = 11 AM + 1.8 hours = 12 noon + 0.8 hours = 12 noon + (0.8 × 60) minutes = 12 noon + 48 minutes, i.e. 12:48 PM
</div><br>