---
title: Trains
linktitle: Trains
toc: true
type: docs
date: "2021-02-17T00:00:00+01:00"
draft: false
menu:
  time-speed-distance:
    parent: Time, Speed and Distance
    weight: 18

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 18
---

In this article, we will cover the various kinds of Time, Speed, Distance (TSD) questions that are based on the theme of Trains. 

## Type 1: Time taken by the train to cross a stationary object

### Stationary object of negligible length

Time taken by a train of length ‘L’ meters to pass a stationary object of negligible length (e.g. a telegraph post or standing man) is equal to the time taken by the train to cover ‘L’ meters.

Time = $\frac{Length \hspace{1ex} of \hspace{1ex} train (L)}{Speed \hspace{1ex} of \hspace{1ex} train (S)}$

##### Q. In what time will a 720 metre train travelling at a speed of 36 km per hour cross a pole?

Explanation:<br>
<div class="Exp">

36 km/hr = 36 × (5/18) = 10 m/sec

Time needed by the train to cross the pole = $\frac{Length \hspace{1ex} of \hspace{1ex} train (L)}{Speed \hspace{1ex} of \hspace{1ex} train (S)}$ =  720 / 10 = 72 seconds
</div> <br>


### Stationary object of some length

Time taken by a train of length ‘L’ meters to pass a stationary object of length ‘b’ meters is –

T = $\frac{Length \hspace{1ex} of \hspace{1ex} train (L) + Length \hspace{1ex} of \hspace{1ex} object (b)}{Speed \hspace{1ex} of \hspace{1ex} train (S)}$

##### Q. In what time will a 720 metre train travelling at a speed of 36 km per hour cross a 180 metre long platform?

Explanation:<br>
<div class="Exp">

36 km/hr = 36 × (5/18) = 10 m/sec

Time needed by the train to cross the platform = $\frac{Length \hspace{1ex} of \hspace{1ex} train (L) + Length \hspace{1ex} of \hspace{1ex} platform (b)}{Speed \hspace{1ex} of \hspace{1ex} train (S)}$ <br>
=  (720 + 180) / 10 = 900/10 = 90 seconds
</div> <br>

<br><hr><br>


## Type 2: Time taken by the train to cross a moving object 

### Moving object of negligible length

Now let us consider the cases wherein a train crosses a moving object of negligible length. 

Here, two cases may arise:

#### Case 1

When object and train move in the same direction, T = $\frac{L}{|S_1 − S_2|}$

Where, L = length of train; $S_1$ = Speed of train; $S_2$ = Speed of object

#### Case 2

When object and train move in the same direction, T = $\frac{L}{S_1 + S_2}$

Where, L = length of train; $S_1$ = Speed of train; $S_2$ = Speed of object

##### Q. In what time will a 450 metre train travelling at a speed of 72 km per hour cross a man moving at a speed of 18 km/hr: 
A. in the same direction as that of the train? <br>
B. in opposite direction to that of the train?

Explanation:<br>
<div class="Exp">

Speed of train = 72 km/hr = 72 × (5/18) = 20 m/sec <br>
Speed of man = 18 km/hr = 18 × (5/18) = 5 m/sec

* A. Time needed by the train to cross the man = $\frac{Length \hspace{1ex} of \hspace{1ex} Train}{(Speed \hspace{1ex} of \hspace{1ex} Train – Speed \hspace{1ex} of \hspace{1ex} Man)}$ =  450 / (20 - 5) = 30 seconds

* B. Time needed by the train to cross the man = $\frac{Length \hspace{1ex} of \hspace{1ex} Train}{(Speed \hspace{1ex} of \hspace{1ex} Train + Speed \hspace{1ex} of \hspace{1ex} Man)}$ =  450 / (20 + 5) = 18 seconds
</div> <br>


### Moving object of some length 

We often encounter such a scenario when two trains are involved. 

Here, two cases may arise:

#### Case 1

If two trains are of length $L_1$ m and $L_2$ m are moving in opposite directions at $S_1$ m/s and $S_2$ m/s, then:

Relative speed = $(S_1 + S_2)$ km/h

The time taken by the trains to cross each other, $t_1$ = $\frac{L_1 + L_2}{S_1 + S_2}$ sec

#### Case 2

If two trains of length $L_1$ m and $L_2$ m are moving in the same direction at $S_1$ m/s and $S_2$ m/s, then:

Relative speed = |$S_1 – S_2$| km/h

The time taken by the faster train to cross the slower train, $t_2$ = $\frac{L_1 + L_2}{|S_1 - S_2|}$ sec

##### Q. Two trains of lengths 300 m and 400 m have speeds of 54 km/hr and 72 km/hr respectively. In how much time will the trains completely pass each other, given that they are moving in: 
A. the opposite direction? <br>
B. the same direction with the faster train just on the tail of the slower train?

Explanation:<br>
<div class="Exp">

Combined length of two trains = 300 + 400 = 700 m 

Speed of faster train = 72 km/hr = 20 m/sec <br>
Speed of slower train = 54 km/hr = 15 m/sec

A. The time taken by the trains to cross each other = Combined length of two trains / Relative Speed = 700 / (20 + 15) =  700/35 = 20 seconds

B. The time taken by the trains to cross each other = Combined length of two trains / Relative Speed = 700 / (20 - 15) =  700/5 = 140 seconds
</div> <br>

##### Another Concept 

Now, if the two times are given (i.e. time taken to cross while travelling in the same and opposite direction), then we can find out the speeds of the trains too. 

If $S_1$ is the speed of the faster train and $S_2$ is the speed of the slower train, then

Speed of faster train, $S_1$ = $(\frac{L_1 + L_2}{2})(\frac{1}{t_1} + \frac{1}{t_2})$

Speed of slower train, $S_2$ = $(\frac{L_1 + L_2}{2})(\frac{1}{t_1} - \frac{1}{t_2})$

$t_1$ – time taken by trains to cross each other if they travel in opposite directions and <br>
$t_2$ - time taken by the faster train to cross slower train if they travel in the same direction.

##### Q. Two trains of lengths 300 m and 400 m take 20 seconds to cross each other when moving in opposite directions. The same trains take 140 seconds to cross each other when they are moving in the same direction. Find the speeds of the two trains. 

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Traditional Method <br><br>

Let speeds of faster and slower trains be $S_1$ and $S_2$.
 
So, Combined speed of two trains, $S_1$ + $S_2$ = Combined length of two trains/Time taken to cross in opposite direction = 700/20 = 35 m/sec 

Difference in the speeds of two trains, $S_1$ - $S_2$ = Combined length of two trains/Time taken to cross in the same direction = 700/140 = 5 m/sec

So, Speed of faster train, $S_1$ = $\frac{(S_1 + S_2) + (S_1 - S_2)}{2}$ = (35 + 5) / 2 = 20 m/sec 

Speed of slower train, $S_2$ = $\frac{(S_1 + S_2) - (S_1 - S_2)}{2}$ = (35 - 5) / 2 = 15 m/sec 
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Formula Method<br><br>

Speed of faster train, $S_1$ = $(\frac{L_1 + L_2}{2})(\frac{1}{t_1} + \frac{1}{t_2})$ 
= $(\frac{700}{2}) (\frac{1}{20} + \frac{1}{140})$ = 350 × (8/140) = 20 m/sec

Speed of slower train, $S_2$ = $(\frac{L_1 + L_2}{2})(\frac{1}{t_1} - \frac{1}{t_2})$ 
= $(\frac{700}{2}) (\frac{1}{20} - \frac{1}{140})$ = 350 × (6/140) = 15 m/sec
</div><br>


## Type 3: Stoppages

##### Q. Excluding stoppages, the speed of a train is 60 kmph and including stoppages, it is 54 kmph. For how many minutes does the train stop per hour?
<pre>(a) 10 minutes   (b) 8 minutes    (c) 15 minutes   (d) 6 minutes</pre>

Explanation:<br>
<div class="Exp">

Speed of the train excluding stoppages = 60 km/hr. <br>
Speed of the train including stoppages = 54 km/hr. <br>
So, Loss in speed of the train due to stoppages = 60 - 54 = 6 km/hr. <br>
That is, due to stoppages, the train covers 6 km less in 1 hour.

Time taken to cover 6 km = 6/60 = 1/10 hours = (1/10) × 60 minutes = 6 minutes <br>
So, the train stops for 6 minutes per hour.

Answer: (d)
</div> <br>

