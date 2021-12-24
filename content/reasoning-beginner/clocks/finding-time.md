---
title: Finding Time
linktitle: Finding Time
toc: true
type: docs
date: "2020-09-25T00:00:00+01:00"
draft: false
menu:
  clocks:
    parent: Clocks
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

In this article we will study how to ***find the time at which two hands make a particular angle with each other***.

So, angle will be given and we will be supposed to find the time. 

To do so we need to have a firm grasp on the ***Concept of Relative Speed***.

{{% alert note %}}
Concept of relative speed forms the base of the chapter of clocks. 
{{% /alert %}}

## Concept of Relative Speed 

### Motion in Straight line

In the figure given below, two runners, Mr. Red and Mr. Blue, start from the same start point, with speeds of 3 km/hr and 6 km/hr, respectively, in the same direction towards the end point.

<img src="../../../media/clocks/relative-speed.png" alt="clocks" style="width:99%;height:99%;">

We can see that every hour the faster runner covers 3 km more distance than the distance traveled by the slower runner. Therefore, every hour the distance between the slower runner and the faster runner increases by 3 km. 

So, the gap between the runners is:

* 3 km in one hour.
<img src="../../../media/clocks/relative-speed1.png" alt="clocks" style="width:99%;height:99%;">

* 6 km in two hours. 
<img src="../../../media/clocks/relative-speed2.png" alt="clocks" style="width:99%;height:99%;">

* 9 km in three hours, and so on. 

Note that the gap between the runners does not depend on their absolute speeds but the difference between their speeds. The gap would still be increasing by 3 km every hour if the speeds of the runners were 5 km/hr and 2 km/hr. 

Thus, relative speed is nothing but the distance reduced/increased between the two per unit time, which in this case is the difference in their speeds, i.e. 6 – 3 = 3 km/hr.

{{% alert note %}}
So, Relative speed of two runners A and B, moving in the same direction = Speed of A - Speed of B

Similarly, Relative speed of two runners A and B, moving in opposite directions = Speed of A + Speed of B
{{% /alert %}}

### Relative Speed Formula

Basic TSD formula is:
Distance = Speed × Time

Similarly, Relative speed formula is:
Relative Distance = Relative Speed × Time

### Circular Motion

Motion on a circular track is very similar to motion in straight line. We can use the same formula of relative speed here too. We will study circular motion in much more detail in time, speed & distance chapter. Here let us just focus on the part which we need know to solve questions based on clocks. 

Suppose our two runners, Mr. Red and Mr. Blue start running on a circular track, in the same direction and from the same point, with speeds of 3 m/sec and 6 m/sec, respectively. 

<img src="../../../media/clocks/relative-speed3.png" alt="clocks" style="width:99%;height:99%;">

The moment Mr. Blue and Mr. Red start from the starting point, Mr. Blue starts getting ahead of Mr. Red. Every second, Mr. Blue increases the gap between Mr. Red and him by 3 m. 

Therefore, the gap between Mr. Blue and Mr. Red is 3 m after 1 second, 6 m after 2 seconds, 9 m after 3 seconds, and so on. (similar to what was the case when they were running in a straight line)

You may realize that the two hands of a clock are nothing but two runners running around a circular track in the same direction.

* Both hands move in the same direction i.e., (clockwise direction). 
* The minute hand moves around the whole circumference of the clock once in 1 hour. While, the hour hand moves around the whole circumference of the clock once in 12 hours. Thus, the minute hands is twelve times faster than the hour hand.

<b>In angular terms: </b>

The speed of the minute hand = $6^o$ per minute

And, speed of the hour hand = $0.5^o$ per minute.

Hence, the relative speed of the minute hand with respect to the hour hand = $6^o$ – $0.5^o$ = $5.5^o$ per minute. 

<b>In minute terms: </b>

The distance between two consecutive numbers in the clock is equal to 5 min.

In an hour, the hour hand crosses 5 min spaces while the minute hand crosses 60 min spaces.

So, in 60 min, the minute hand gains (60 – 5) = 55 min over hour hand. 

Hence, in 1 minute, the minute hand gains 55/60 = 11/12 minutes

{{% alert note %}}
Mostly, we use the relative speed in angular terms. You just need to remember that relative speed of the minute hand with respect to the hour hand is $5.5^o$ per minute, i.e. if the two hands start from the same point, then the minute hand will gain $5.5^o$ per minute over the hour hand. 

This number is the holy grail of Clocks chapter.
{{% /alert %}}

##### Q. The two hands of a clock overlap at 12 o’clock. What will be the distance between hour and minute hands of the clock 10 minutes past 12 o’clock?

Explanation:<br>
<div class="Exp">
Relative Speed = $5.5^o$/min
In 10 min, relative distance = relative speed × time = $5.5^o$/min × 10 min = $55^o$
</div> <br>

<br><hr><br>

## Finding Time

In some type of questions, we are asked to find out the time when the hands of the clock:
* overlap (i.e. $0^o$ angle between them). 
* are opposite to each other (i.e. $180^o$ angle between them), or
* make some other angle between them.

Here again there are multiple methods that you can use. Let's understand them via some examples.

##### Q. At what time between 3:00 pm and 4:00 pm, will the minute hand and the hour hand overlap? 
(a) 16 $\frac{4}{11}$ minutes past 3 pm    (b) 15 $\frac{4}{11}$ minutes past 3 pm   <br>
(c) 16 $\frac{2}{7}$ minutes past 3 pm     (d) 15 $\frac{3}{5}$ minutes past 3 pm

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Relative Speed Method <br><br>

At 3:00 pm, the distance between the minute hand and the hour hand is 90°, as shown below:
<img src="../../../media/clocks/relative-speed4.png" alt="clocks" style="width:45%;height:45%;">
Therefore, the minute hand is 90° behind at 3:00 pm and then it starts closing the gap by 5.5° every minute. <br><br>

Therefore, the time taken by the minute hand to catch up with the hour hand = $\frac{Relative Distance}{Relative Speed}$ = $\frac{90^o}{5.5^o}$ = $\frac{180^o}{11^o}$ = 16 $\frac{4}{11}$ minutes. 

So, the two hands will overlap at 16 $\frac{4}{11}$ minutes past 3 pm. 

Answer: (a)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using Formula Method<br><br>

Between x and (x + 1) O'clock, the two hands will be t min apart at (5x ± t)$\frac{12}{11}$ min past x O’clock.

Here x = 3 and t = 0 (because overlapping)
                                         
Hence, required time = 5x × $\frac{12}{11}$ = 5 × 3 × $\frac{12}{11}$ = $\frac{180}{11}$ = 16 $\frac{4}{11}$ minutes past 3 O’clock

Answer: (a)

Note: If t is not zero then: <br>
If t = 30 minutes, i.e. if the hands are opposite to each other: use (+) sign, when x < 6 and (–) sign, when x > 6 <br>
If t is not 0 or 30 minutes: If minute hand is ahead, then '+' sign is used and if hour hand is ahead, then '–' sign is used.) <br>
But here t = 0, so it doesn't matter.
</div><br>

<br><hr><br>

## Some more properties of clocks

1. In every hour, the two hands are in the same straight line two times:

* When both hands are coincident (i.e. in the same direction), i.e. angle between the two hands = 0° <br>
The two hands are 0 min apart.<br><br>
So, in every 12 hr both hands coincide 11 times. <br>
(between 11 and 1 O'clock there is a common position at 12 O'clock). <br><br>
And in 24 hrs, both hands coincide 22 times. 

* When both hands are opposite to each other, i.e. angle between the two hands = 180° <br>
The two hands are 30 min spaces apart. <br><br>
In every 12 hr, both hands are in opposite direction 11 times. <br> 
(between 5 and 7 O'clock there is a common position at 6 O'clock). <br><br>
In 24 hr, both hands are in opposite direction 22 times. <br>

2. Hence, in every 12 hr, the two hands are in the same straight line 22 times. <br>
In 24 hr, the two hands are in the same straight line 44 times.

3. In every hour, both the hands are at right angles two times, i.e. angle between the two hands = 90° <br>
In other words, the two hands are 15 min spaces apart. <br><br>
In every 12 hr, the two hands are at right angles 22 times. <br>
(between 2 and 4 O'clock there is a common position at 3 O'clock and also between 8 and 10 O'clock there is a common position at 9 O'clock). <br><br>
Hence, in 24 hr, both the hands are at right angles 44 times. <br>

<br><hr><br>

## Concept of Successive Meets

Let us again consider our example of two runners.

Suppose our two runners, Mr. Red and Mr. Blue start running on a circular track, in the same direction and from the same point, with speeds of 3 m/s and 6 m/s, respectively. 
<img src="../../../media/clocks/relative-speed3.png" alt="clocks" style="width:99%;height:99%;">

The moment Mr. Blue and Mr. Red start from the starting point, Mr. Blue starts getting ahead of Mr. Red. If they keep on running then a time will come when Mr. Blue will overtake Mr. Red again. The extra distance that Mr. Blue covered will be equal to the circumference of the circle. 

{{% alert note %}}
Note: It doesn’t matter what their actual absolute speeds are. Only thing that we need to know is their relative distance. <br><br>
Similarly, it doesn’t matter what actual distances they covered. Only thing we need to know is the difference in the distances covered. 
{{% /alert %}}

If circumference of the circle is 600 m, then time taken by Mr. Blue to catch up with Mr. Red again = $\frac{Circumference \hspace{1ex} of \hspace{1ex} the \hspace{1ex} circle}{Relative \hspace{1ex} speed}$ <br>
= $\frac{600}{(6 - 3)}$ = $\frac{600}{3}$ = 200 s.

{{% alert note %}}
The same concept can be applied to minute and hour hands of a clock. In case of clock:
* The faster runner is the minute hand and the slower runner is the hour hand. 
* Relative speed of hour and minute hands = 5.5° per minute
* Circumference of the circle in angular terms = 360°
{{% /alert %}}

Let's see an example.

##### Q. What is the time interval between two successive meets of the minute hand and the hour hand?
(a) 64 $\frac{5}{11}$ minutes     (b) 65 $\frac{5}{11}$ minutes   <br>
(c) 66 $\frac{3}{11}$ minutes     (d) 65 $\frac{4}{9}$ minutes

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-3', this, 'tablink-group2', 'tabcontent-group2')">3</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Relative Speed Method <br><br>

Once the minute hand and the hour hand are together, the minute hand starts increasing the gap between the hour hand and itself by 5.5° every minute. Therefore, when it has increased the gap by 360°, it again meets the hour hand. So, here essentially the relative distance is 360°. <br>

So, time taken for them to meet again = $\frac{Relative \hspace{1ex} Distance}{Relative \hspace{1ex} Speed}$ = $\frac{360°}{5.5°}$ = $\frac{720}{11}$ = 65 $\frac{5}{11}$ minutes. <br>

Answer: (b)
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Formula Method  <br><br>

Between x and (x + 1) O'clock, the two hands will be t min apart at (5x ± t) $\frac{12}{11}$ min past x O’clock.

The two hands were coincident at 12 O’clock. They will coincide again somewhere between 1 and 2. Hence, x = 1

For the hands to be coincident, t = 0.

Required time = 5x × $\frac{12}{11}$ = $\frac{60}{11}$ = 5 $\frac{5}{11}$ minutes. <br>
Hence, the total time taken by the two hands to meet = 60 + 5 $\frac{5}{11}$ = 65 $\frac{5}{11}$ min


Note: If t is not zero then: <br>
If t = 30 minutes, i.e. if the hands are opposite to each other: use (+) sign, when x < 6 and (–) sign, when x > 6 <br>
If t is not 0 or 30 minutes: If minute hand is ahead, then '+' sign is used and if hour hand is ahead, then '–' sign is used.) <br>
But here t = 0, so it doesn't matter.

Answer: (b)
</div>

<div id="2Exp-3" class="Exp-3 mak-tabcontent tabcontent-group2">
Explanation 3:  <br> <br>

It’s a fact that the minute and hour hand of a clock meet 22 times in 24 hours or 11 times in 12 hours.

Thus time interval between two meetings = $\frac{12}{11}$ hours = $\frac{12}{11}$ × 60 minutes = $\frac{720}{11}$ = 65 $\frac{5}{11}$ minutes.

Answer: (b)
</div><br>

{{% alert note %}}
If both the hands of a correct clock start moving together from the same position, then both the hands will coincide after every 65 $\frac{5}{11}$ minutes. <br>
In case of faulty clocks this time will vary. 
{{% /alert %}}
