---
title: Replacement of a part of solution
linktitle: Replacement of a part of solution
toc: true
type: docs
date: "2021-01-31T00:00:00+01:00"
draft: false
menu:
  avarage-mixtures-alligation:
    parent: 2. Mixtures & Alligation
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---

If we have a solution of alcohol and water and we remove x% of it, then we are essentially removing x% of the amount of alcohol present and also x% of the amount of water present. 

E.g. We remove 32 litres from 80 litres of 3:5 alcohol and water solution. <br>
The ratio of alcohol and water will remain 3:5, both in the 32 litres solution removed and the remaining solution because we are not changing its composition.  

<img src="../../../media/mixtures/replacement-solution.png" alt="Replacement of a part of solution" style="width:99%;height:99%;">

In most of the questions we encounter, we will not only be taking out a part of the solution, but also replacing part of the mixture with a pure component. E.g. we can replace the removed solution with water. 

## Guidelines to solve Solution Replacement Questions

These are a few of the guidelines that we can follow to ease out our work:

* We will focus on the solute which is not replaced, alcohol in our case (as it is easier to work on that salute which is only being removed and not added back).
* We will prefer to work in fractions rather than percentages, to ease out our calculation. 

***Let’s consider an example:***

We remove 20 litres from 100 litres of 2:3 alcohol and water solution. After it we replace the 20 litres of solution we took out with water. 

We will just focus on the solute that is not being replaced, i.e. alcohol in our case.  
<img src="../../../media/mixtures/replacement-solution1.png" alt="Replacement of a part of solution" style="width:99%;height:99%;">

Now, let us remove 20 litres again from 100 litres of solution. After it we replace the 20 litres of solution we took out with water. 
<img src="../../../media/mixtures/replacement-solution2.png" alt="Replacement of a part of solution" style="width:99%;height:99%;">

Alcohol left after $3^{rd}$ operation = 40 × (4/5) × (4/5) × (4/5) litres <br>
Alcohol left after $4^{th}$ operation = 40 × (4/5) × (4/5) × (4/5) × (4/5) litres

Let us generalize it in the form of a formula. <br>
Alcohol left after $n^{th}$ operation = 40 × (4/5) × (4/5) × (4/5) ..... n times = 40 × ($\frac{4}{5})^n$ 

## Formulae for Final Amount of Solute

So, as you can see, there are two steps involved in solving such questions:

* Step 1: If instead of a pure liquid, a solution is there, then find out the amount of the solute (that is not getting replaced) in the solution. <br><br>
Suppose we have a x litres of a solution of alcohol and water in the ratio m:n. <br>
So, initial volume of alcohol = [$\frac{m}{(m + n)}$] × x  <br>
In our case, initial volume of alcohol = 40 litres <br>

* Step 2: If out of the x litres, y litres are taken out and replaced by pure liquid (water in our example), then after n operations, the amount of the solute (that is not getting replaced, alcohol in our case) is:<br><br>
Initial volume of alcohol × (1 - $\frac{y}{x})^n$ <br>
In our case, it is 40 × (1 – $\frac{1}{5})^n$ = 40 × ($\frac{4}{5})^n$

<div class="toc-mak"> <br>
So, these are our formulae for the Final Amount of solute: <br><br>

### For final Absolute Amount of solute

After n operations, the amount of the solute (that is not getting replaced) = Initial volume of solute × (1 - $\frac{y}{x})^n$ <br><br>
= Initial volume of solute × ($\frac{Volume \hspace{1ex} of \hspace{1ex} solution \hspace{1ex} after \hspace{1ex} removal}{Volume \hspace{1ex} of \hspace{1ex} solution \hspace{1ex} after \hspace{1ex} replacing})^n$

### For final Ratio of solute

Above formula is not only true for absolute amounts, but for ratios as well. <br><br>
Final ratio of solute = Initial Ratio × (1 - $\frac{y}{x})^n$ <br><br>
= Initial Ratio × ($\frac{Volume \hspace{1ex} of \hspace{1ex} solution \hspace{1ex} after \hspace{1ex} removal}{Volume \hspace{1ex} of \hspace{1ex} solution \hspace{1ex} after \hspace{1ex} replacing})^n$ 
</div>

{{% alert note %}}
If you observe the formula, you will notice that replacement of a part of solution with a pure component when done repetitively is exactly similar to compound interest with the rate of interest being negative. 

Rate of interest depends on the fraction of the solution being replaced, i.e. the value of y/x. 
{{% /alert %}}

## Formulae for Final Concentration of Solute

We know that, after n operations, the amount of the solute (that is not getting replaced, alcohol in our case) is: <br>
Initial volume of alcohol × (1 - $\frac{y}{x})^n$ 

So after n operations, concentration of the solute = $\frac{Amount \hspace{1ex} of \hspace{1ex} solute}{Initial \hspace{1ex} volume \hspace{1ex} of \hspace{1ex} solution}$ = $\frac{Initial \hspace{1ex} volume \hspace{1ex} of \hspace{1ex} alcohol × (1 - \frac{y}{x})^n}{Initial \hspace{1ex} volume \hspace{1ex} of \hspace{1ex} alcohol}$ = (1 - $\frac{y}{x})^n$  

If the concentration has to be expressed as a percentage, then it will be equal to 100 (1 - $\frac{y}{x})^n$.
