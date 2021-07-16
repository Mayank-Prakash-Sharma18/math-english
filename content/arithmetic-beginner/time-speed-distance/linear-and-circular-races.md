---
title: Linear and Circular Races 
linktitle: Linear and Circular Races
toc: true
type: docs
date: "2021-02-18T00:00:00+01:00"
draft: false
menu:
  time-speed-distance:
    parent: Time, Speed and Distance
    weight: 24

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 24
---

There are two types of races:

* Linear race: when participants in the race move in a linear fashion.

* Circular Race: when participants in the race move in a circular manner.

Before we dive deeper into the concepts involved in the topic of races, we need to know a few jargons.

## Basic Terminologies on Races

Some common terminologies used in races related questions are given below.
 
#### Head Start 

* Distance-wise: When a runner A is allowed to start the race ‘x’ meters ahead of another runner B, then we can say that the runner A got a head start of x meters.

* Time-wise: If the runner A starts the race ‘t’ seconds earlier than the other runner B, then it means that the runner A got a head start of t seconds.

#### Beat by ‘x’ meters or ‘t’ seconds:

* Runner A beats B by ‘x’ meters means, when A finishes the race then B is ‘x’ meters behind the finishing point. 

* Runner A beats B by ‘t’ seconds means that after A finishes the race B will take ‘t’ seconds more to finish the race.

##### Q. In a race of 1000 meters, Anand can beat Bhaskar by 100 meters or by 10 seconds. What must be the speed of Anand?

Explanation:<br>
<div class="Exp">

Anand can beat Bhaskar by 100 meters – it means that when Anand runs 1000 m, Bhaskar runs only 900 m. It means that the ratio of the speeds of Anand and Bhaskar is 10:9. 

Also, Anand can beat Bhaskar by 10 seconds. It means that Bhaskar can travel 100 m in 10 seconds.

So, Speed of Bhaskar = 100/10 = 10 m/sec <br>
And Speed of Anand = 10 × (10/9) = 100/9 = 11.11 m/sec
</div> <br>

<br><hr><br>

## Races on circular track

Objects (cars etc.) or people generally move around a circular track at different speeds, and they begin from a particular point either in the same direction or in the opposite direction.

A student is generally asked to calculate:

* The time of meeting of people (running around the track) at the starting point again after they started.

* Meeting for the first time anywhere on the track.

* The number of different points where people meet while running on the circular track.

Let us try to acclimatize ourselves with the scenario wherein two runners, A and B, run around a circular track.

#### When they run in opposite directions 

* Relative speed: Their relative speed is equal to the sum of their speeds, i.e. A + B.  

* Distance covered: From one meeting point to the next meeting point, the two of them together cover a distance equal to the length of the track.

#### When they run in the same direction

* Relative speed: Their relative speed is equal to the difference of their speeds, i.e. A – B. 

* Distance covered: From one meeting point to the next meeting point, the faster person covers one complete round more than the slower person (i.e. a distance equal to the circumference of the circular track).

### Time to meet at the Starting point

To find out when the runners will all meet again at the starting point, we need to follow the following steps:

* Step 1: Calculate the time taken by each of the runners to run one complete round.

* Step 2: L.C.M of these times is the time of their meeting again at the starting point.

{{% alert note %}}
It doesn’t matter whether they are running in the same direction or in opposite directions.
{{% /alert %}}

### Time to meet for the 1st time anywhere on the track

To find out when 2 runners will meet for the first time, we need to consider two possible cases: 

* if both runners are running in the same direction: the faster runner will have to complete one full extra round over the slower runner,. 

* if both runners are running in opposite directions: the two runners will together have to complete one full round in total. 

The time taken to meet for the first time = $\frac{Circular \hspace{1ex} track \hspace{1ex} length}{Relative \hspace{1ex} speed}$

Let us summarize. 

Let A and B are two runners participating in a circular race around a circular track of length ‘L’ meters with respective speeds of ‘a’ m/s and ‘b’ m/s (starting at the same point and at the same time). 

Assume A is faster than B, then a > b.

<img src="../../../media/tsd/circular-track-race.png" alt="Races on circular track" style="width:81%;height:81%;">

##### Q. Two cyclists are participating in a race on a circular rack of 400 m circumference. Mr. White cycles at a speed of 5 m/sec, while Mr. Pink cycles at a speed of 3 m/sec. They start at the same point, at the same time and in the <strong><span class="mak-text-color">same direction</span></strong>. When will they:
A. meet for the first time?<br>
B. meet for the first time at the starting point?

Explanation:<br>
<div class="Exp">

There relative speed = 5 – 3 = 2 m/sec (as they are moving in the same direction)

A. Mr. White will take lead as soon as the race starts. To meet Mr. Pink again, he will have to cover an extra distance equal to the circumference of the track. <br><br>
Time taken by them to meet for the first time = Relative distance/Relative Speed = 400/2 = 200 seconds

B. Mr. White will be at the starting point every 400/5 = 80 seconds <br>
Mr. Pink will be at the starting point every 400/3 seconds <br><br>
Time taken by them to meet for the first time at the starting point = LCM of (80, 400/3) = LCM (80, 400)/HCF (1, 3) = 400/1 = 400 seconds.
</div> <br>

##### Q. Two cyclists are participating in a race on a circular rack of 400 m circumference. Mr. White cycles at a speed of 5 m/sec, while Mr. Pink cycles at a speed of 3 m/sec. They start at the same point, at the same time and in <strong><span class="mak-text-color">opposite directions</span></strong>. When will they:
A. meet for the first time? <br>
B. meet for the first time at the starting point?

Explanation:<br>
<div class="Exp">

There relative speed = 5 + 3 = 8 m/sec (as they are moving in opposite directions)

A. As they are moving in opposite directions, they will meet when they together cover the whole circumference of the track. <br><br>
Time taken by them to meet for the first time = Relative distance/Relative Speed = 400/8 = 50 seconds

B. Mr. White will be at the starting point every 400/5 = 80 seconds <br>
Mr. Pink will be at the starting point every 400/3 seconds <br><br>
Time taken by them to meet for the first time at the starting point = LCM of (80, 400/3) = LCM (80, 400)/HCF (1, 3) = 400/1 = 400 seconds.

{{% alert note %}}
Note: The time taken to meet for the first time at the starting point remains the same whether the runners are moving in the same direction or in opposite directions. 
{{% /alert %}}
</div> <br>

### To calculate the number of points of meeting

Let the number of points at which two runners meet be n (including the starting point). 

Then n = $\frac{time \hspace{1ex} of \hspace{1ex} their \hspace{1ex} first \hspace{1ex} meeting \hspace{1ex} at \hspace{1ex} the \hspace{1ex} starting \hspace{1ex} point}{time \hspace{1ex} of \hspace{1ex} their \hspace{1ex} first \hspace{1ex} meeting \hspace{1ex} anywhere \hspace{1ex} on \hspace{1ex} the \hspace{1ex} track}$

Let us consider two runners that started running simultaneously from the same point on a circular track .

If they cover x and y rounds in the same time, then:

* they will meet x + y times if running in opposite direction and 

* they will meet x - y times if running in the same direction. 

##### Q. Two runners run on a circular track of 600 m, with a speed of 6 m/sec and 2 m/sec. They start at the same time and from the same point. How many times will they meet before meeting again at the starting point (including the last meeting), if: 
A. they run in the same direction? <br>
B. they run in opposite directions?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: <br><br>

A. Time taken for them to meet for the first time = Relative Distance/Relative Speed = 600 / (6 – 2) = 150 seconds <br>
Time taken by them to meet for the first time at the starting point = LCM (600/6, 600/2) = LCM (100, 300) = 300 seconds <br><br>
The number of points at which two runners meet (including the starting point) = time of their first meeting at the starting point / time of their first meeting anywhere on the track = 300/150 = 2 times

B. Time taken for them to meet for the first time = Relative Distance/Relative Speed = 600 / (6 + 2) = 75 seconds <br>
Time taken by them to meet for the first time at the starting point = LCM (600/6, 600/2) = LCM (100, 300) = 300 seconds <br><br>
The number of points at which two runners meet (including the starting point) = time of their first meeting at the starting point / time of their first meeting anywhere on the track = 300/75 = 4 times
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Time taken by them to meet for the first time at the starting point = LCM (600/6, 600/2) = LCM (100, 300) = 300 seconds

Rounds covered by faster runner in 300 seconds, x = (6 × 300)/600 = 3 rounds <br>
Rounds covered by slower runner in 300 seconds, y = (2 × 300)/600 = 1 round

A. Number of times they will meet while running in the same direction = x - y = 3 - 1 = 2 times

B. Number of times they will meet while running in opposite directions = x + y = 3 + 1 = 4 times
</div><br>

### More than two people involved

Now, let us see how to solve questions on circular track races, when more than two runners are involved. 

#### To calculate the time at which they meet at the starting point for the 1st time:

Let A, B and C are three runners participating in a circular race around a circular track of length ‘L’ meters with respective speeds of ‘a’ m/s, ‘b’ m/s and ‘c’ m/s (starting at the same point and at the same time).

Time taken by A to complete the entire circular round = L/a <br>
Time taken by B to complete the entire circular round = L/b <br>
Time taken by C to complete the entire circular round = L/c

The time at which they all meet at the starting point for the 1st time = L.C.M of (L/a, L/b, L/c)

{{% alert note %}}
It doesn’t matter whether they are running in the same direction or in opposite directions.
{{% /alert %}}

##### Q. A, B and C start cycling simultaneously from the same point and in the same direction, along a circular track. A completes a round in 25 seconds, B in 30 seconds and C in 18 seconds. How many times will they meet again at the starting point if they cycle for 15 minutes?
<pre>(a) 1         (b) 2          (c) 4          (d) 3</pre>

Explanation:<br>
<div class="Exp">

L.C.M. of 25, 30 and 18 = 450 seconds.

It means that, A, B and C will again meet at the starting point in 450 seconds, or 7 minutes and 30 seconds.

Hence, in 15 minutes, they will meet twice.

Answer: (b)
</div> <br>



