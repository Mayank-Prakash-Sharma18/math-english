---
title: Pipe and Cisterns
linktitle: Pipe & Cisterns 
toc: true
type: docs
date: "2021-02-10T00:00:00+01:00"
draft: false
menu:
  time-and-work:
    parent: Work
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

Pipes/Taps are used for filling (and emptying) cisterns/tanks with liquid. 

* Inlet - A pipe that fills a tank or a cistern or a reservoir. It does 'plus/positive’ type of work.

* Outlet - A pipe that empties a tank or a cistern or a reservoir. It does 'minus/negative' type of work.

Net Work Done = Sum of work done by inlets - Sum of work done by outlets

## Work done by a pipe

If a pipe can fill or empty a tank is x hours, then 

Part of the tank filled or emptied in 1 hour = 1/x   (it’s the work done by the pipe)

## Combined work done by two pipes

Here many cases may arise, depending on whether the given pipes are inlet or outlet pipes. 

Let us consider two broad cases.

### Case 1: Two inlet pipes

If a pipe can fill a tank in x hours & another pipe can fill the tank in y hours (where y > x), then 

Work done by pipes per hour (i.e. their efficiency) will be 1/x and 1/y

Their combined efficiency = 1/x + 1/y = (x + y)/xy

This is the part of the tank filled in 1 hour, if both the pipes are opened together.

So, time taken to fill the tank when both pipes are filling it = xy/(x + y)

### Case 2: One inlet and One outlet pipe

If a pipe can fill a tank in x hours & another pipe can empty the tank in y hours, then on opening both the pipes, 

the net part filled in 1 hour = 1/x – 1/y = (y - x)/xy <br>
(where y > x) <br>
So, time taken to fill the tank when both pipes are working = xy/(y - x)

the net part emptied in 1 hour = 1/y – 1/x = (x - y)/xy <br>
(where x > y) <br>
So, time taken to fill the tank when both pipes are working = xy/(x - y)

##### Q. Pipes A and B can fill a tank in 12 and 18 minutes respectively. How long will it take for the tank to be filled, if both the pipes are opened together?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Traditional or Formula Method <br><br>

Time required for the tank to be filled if both the pipes are opened = xy/(x + y) <br>
= (12 × 18)/(12 + 18) = (12 × 18)/30 = 36/5 = 7.2 minutes <br>
(i.e. 7 minutes and 12 seconds)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: LCM Method<br><br>

Let capacity of the tank be LCM (12, 18) = 36 units

So, efficiency of pipe A (i.e. quantity filled by pipe A in 1 minute) = 36/12 = 3 units/minute <br>
And efficiency of pipe B (i.e. quantity filled by pipe B in 1 minute) = 36/18 = 2 units/minute

Their combined efficiency (i.e. quantity filled in 1 minute) = 3 + 2 = 5 units/minute

So, time needed by them when working together = Total Work/Combined Efficiency <br>
= 36/5 = 7.2 minutes <br>
(i.e. 7 minutes and 12 seconds)
</div><br>