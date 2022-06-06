---
title: Miscellaneous Counting Puzzles
linktitle: Miscellaneous Counting Puzzles
toc: true
type: docs
date: "2021-10-19T00:00:00+01:00"
draft: false
menu:
  puzzles:
    parent: 2. Counting Puzzles
    weight: 11

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 11
---

In this article, we will have a look at some of the counting puzzles where we just need to apply our common sense, and count. 


## Type 1 

##### Read the information given below and answer the two items that follow.

Five cities are connected by 6 roads as shown in the figure below. 
<img src="../../../media/puzzles/counting-puzzles-1.png" alt="Counting Puzzles" style="width:54%;height:54%;">
Ram wants to traverse all the six roads once and only once, such that he does not end up in the same city from where he started his journey. 

Q1. Which of the following statements is/are definitely true?
1. There is no such route possible.
2.  C can be the starting as well as the ending city for Ram.

(a) 1 only <br>
(b) 2 only <br>
(c) Both 1 and 2 <br>
(d) Neither 1 nor 2

Q2. If Ram starts his journey from city E, then how many such route(s) is/are possible that satisfy all the given conditions? <br>
(a) 0 <br>
(b) 1 <br>
(c) 2 <br>
(d) 3

Explanation:<br>
<div class="Exp">

**Statement 1**: First of all let us find whether such a path is possible or not. Starting from city C, we can see that every road in the route CABCDEB is traversed only once.  Also, the end city is B, which is different from the starting city A. Though, Ram visits the city he started his journey from, i.e. C, once again, but it’s not his end point. So, it satisfies all the given conditions and such a route is possible. Thus, statement 1 is false.

**Statement 2**: As mentioned in the question, Ram cannot finish his journey in the same city from where he started his journey. So, statement 2 is false.

Answer: (d)
</div> <br>


## Type 2

##### Q. A box contains 31 red and 25 blue balls. If balls are drawn one by one, what is the minimum number of balls that have to be drawn to ensure that at least one blue and one red ball are obtained? 
<pre>(a) 26   (b) 40    (c) 32   (d) 31</pre>

Explanation:<br>
<div class="Exp">

As there are 25 blue balls, it might be a possibility that the first 25 balls are all blue. Hence, to get at least one red ball, at least 26 balls need to be drawn. 

Similarly, as there are 31 red balls, it might be a possibility that the first 31 balls are red. Hence, to get at least one blue ball, at least 32 balls need to be drawn.

Hence, the minimum number of balls that have to be drawn to ensure that at least one blue and one red ball are obtained = 32.

Answer: (c)
</div> <br>


## Type 3

##### Q. Consider the following figure and answer the item that follows :
<img src="../../../media/puzzles/counting-puzzles-2.png" alt="Counting Puzzles" style="width:45%;height:45%;">
In the given figure, the balls can occupy the positions numbered 1, 2, 3, 4, 5 and 6. Suppose at every stage the white ball moves by jumping over one position in the clockwise direction and the black ball moves by jumping over three positions in the counter-clockwise direction. After how many stages, will the two balls lie at the same position?
<pre>(a) 2   (b) 3    (c) 4   (d) Never</pre>

Explanation:<br>
<div class="Exp">

The white ball moves by jumping over one position in the clockwise direction. Thus it will occupy the following positions: <br>
1, 3, 5, 1, 3, 5……… and so on.

The black ball moves by jumping over 3 positions in the counter-clockwise direction. Thus, it will occupy following positions: <br>
5, 1, 3, 5, 1, 3……… and so on.

We can represent the scenario in the form of a table as given below:
<img src="../../../media/puzzles/counting-puzzles-3.png" alt="Counting Puzzles" style="width:72%;height:72%;">

Thus, there will be no overlap between the positions of the two balls and they will never lie at the same position simultaneously.

Answer: (d)
</div> <br>


## Type 4

##### Q. The digits 1 to 9 are arranged in three rows in such a way that each row contains three digits, and the number formed in the second row is twice the number formed in the first row; and the number formed in the third row is thrice the number formed in the first row. Repetition of digits is not allowed. If only three of the four digits 2, 3, 7 and 9 are allowed to be used in the first row, how many such combinations are possible to be arranged in the three rows? 
<pre>(a) 4   (b) 3    (c) 2   (d) 1</pre>

Explanation:<br>
<div class="Exp">

We can only use three of the four digits – 2, 3, 7, and 9, in the first row. <br>
The first digit in the first row cannot be 7 or 9, as otherwise thrice the number will not be a three-digit number. <br>
So, the first digit in the first row can either be 2, or 3. <br>
The possible cases are: 237, 273, 239, 293, 279, 297, 327, 372, 329, 392, 379, or 397. <br>

On eliminating the numbers whose 3x is not a three-digit number, we are left with: 237, 273, 239, 293, 279, 297, 327, and 329.

We will check these numbers: <br>
237 × 2 =474 (digit repetition, and so eliminated) <br>
273 × 2 = 546; 273 × 3 = 819 <br>
239 × 2 = 478; 239 × 3 = 717 (digit repetition, and so eliminated) <br>
293 × 2 = 586; 293 × 3 = 879 (digit repetition, and so eliminated) <br>
279 × 2 = 558 (digit repetition, and so eliminated) <br>
297 × 2 = 594 (digit repetition, and so eliminated) <br>
327 × 2 = 654; 327 × 3 = 981 <br>
329× 2 = 658; 329× 3 = 987 (digit repetition, and so eliminated) <br>
So, only two cases are possible. 

Answer: (c)
</div> <br>


## Type 5

##### Q. In a tournament of Tennis, having 150 players, a player is eliminated whenever he loses a match. It is given that no match results in a tie/draw. How many matches are played in the entire tournament?
<pre>(a) 151   (b) 150    (c) 149   (d) 148</pre>

Explanation:<br>
<div class="Exp">

The tournament starts with 150 players. 

After first round (in which 75 matches are held): 75 players are eliminated, and 75 remain. <br>
After second round (in which 37 matches are held): 37 players are eliminated, and 38 remain. <br>
After third round (in which 19 matches are held): 19 players are eliminated, and 19 remain. <br>
After fourth round (in which 9 matches are held): 9 players are eliminated, and 10 remain. <br>
After fifth round (in which 5 matches are held): 5 players are eliminated, and 5 remain. <br>
After sixth round (in which 2 matches are held): 2 players are eliminated, and 3 remain. <br>
After seventh round (in which 1 match is held): 1 player is eliminated, and 2 remain. <br>
After eighth round (in which 1 match is held): 1 player is eliminated, and 1 remain.

So, total number of matches = 75 + 37 + 19 + 9 + 5 + 2 + 1 + 1 = 149

Answer: (c)
</div> <br>


## Type 6

##### Q. On one side of a 1.01 km long road, 101 plants are planted at equal distance from each other. What is the total distance between 5 consecutive plants?
<pre>(a) 40 m   (b) 40.4 m    (c) 50 m   (d) 50.5 m</pre>

Explanation:<br>
<div class="Exp">

Length of the road = 1.01 km = 1010 m

101 plants are planted at equal distance from each other. So, there will be 100 gaps between those plants. <br>
Length of each gap = 1010/100 = 10.1 m

Now, there must be 4 gaps between 5 consecutive plants. <br>
So, required distance = 4 × 10.1 = 40.4 m

Answer: (b)
</div> <br>


## Type 7

##### Q. A has some coins. He gives half of the coins and 2 more to B. B gives half of the coins and 2 more to C. C gives half of the coins and 2 more to D. The number of coins D has now, is the smallest two-digit number. How many coins does A have in the beginning?
<pre>(a) 76   (b) 68    (c) 60   (d) 52</pre>

Explanation:<br>
<div class="Exp">

The number of coins with D = 10 <br>
Let’s work backwards now. 

D = (C/2) + 2 <br>
Or C/2 = 10 – 2 = 8 <br>
Or C = 16

Similarly, <br>
C = (B/2) + 2 <br>
Or B/2 = 16 – 2 = 14 <br>
Or B = 28

And finally, <br>
B = (A/2) + 2 <br>
Or A/2 = 28 – 2 = 26 <br>
Or A = 52

So, A initially had 52 coins. 

Answer: (d)
</div> <br>


## Type 8

##### Q. In the series AABABCABCDABCDE..., which letter appears at the 100th place?
<pre>(a) G   (b) H    (c) I   (d) J</pre>

Explanation:<br>
<div class="Exp">

The given series is: AABABCABCDABCDE… <br>
The pattern being followed here is: A, AB, ABC, ABCD, ABCDE, … <br>

It’s kind of an arithmetic series wherein the first term has 1 letter, second term has 2 letters, and so on. We have to estimate the length of the letter-series near the 100th letter. 

If we have an arithmetic series, 1, 2, 3 …, then: <br>
Sum of first n terms = (n/2) (a + l), where ‘n’ is the number of terms in the series, ‘a’ the first term, and ‘l’ the last term.

So, sum of first 14 terms = (14/2) (1 + 14) = 7 × 15 = 105 <br>

So, the term having 14 letters will have the 100th letter of the series. <br>
It will start at the 92nd letter and end at 105th letter. Hence, the 100th letter must be I. 

Answer: (c)
</div> <br>


## Type 9

##### Q. Five friends P, Q, X, Y and Z purchased some notebooks. The relevant information is given below :
1. Z purchased 8 notebooks more than X did.
2. P and Q together purchased 21 notebooks.
3. Q purchased 5 notebooks less than P did.
4. X and Y together purchased 28 notebooks.
5. P purchased 5 notebooks more than X did.

If each notebook is priced Rs. 40, then what is the total cost of all the notebooks?
<pre>(a) Rs. 2600   (b) Rs. 2400    (c) Rs. 2360   (d) Rs. 2320</pre>

Explanation:<br>
<div class="Exp">

As per the information provided in the question: <br>
Z = X + 8   ….(i) <br>
P + Q = 21   ….(ii) <br>
Q = P – 5    ….(iii) <br>
X + Y = 28    ….(iv) <br>
P = X + 5    ….(v)

We need to find the value of P + Q + X + Y + Z

Using ii and iii, we get: <br>
P + Q = 21 <br>
Or P + (P - 5) = 21 <br>
Or P = 13 <br>
So, Q = P – 5 = 13 – 5 = 8

Using v, we get: <br>
P = X + 5 <br>
Or X = P – 5 = 13 – 5 = 8

Using i, we get: <br>
Z = X + 8 <br>
Or Z = 8 + 8 = 16

Using iv, we get: <br>
X + Y = 28 <br>
Or Y = 28 – 8 = 20

So, P + Q + X + Y + Z = 13 + 8 + 8 + 20 + 16 = 65 <br>
So, total cost of all the notebooks = 65 × 40 = Rs. 2600

Answer: (a)
</div> <br>

##### Q. The average weight of A, B, C is 40 kg, the average weight of B, D, E is 42 kg and the weight of F is equal to that of B. What is the average weight of A, B, C, D, E and F?
<pre>(a) 40.5 kg   (b) 40.8 kg    (c) 41 kg   (d) Cannot be determined</pre>

Explanation:<br>
<div class="Exp">

According to the question, <br>
(A + B + C)/3 = 40 <br>
Or (A + B + C) = 120  ……(i)

(B + D + E)/3 = 42 <br>
Or (B + D + E) = 126    ……(ii)

F = B   .....(iii)

From equations (i) and (ii), we get: <br>
A + B + C + B + D + E = 120 + 126 <br>
Or A + B + C + D + E + B = 246 <br>
Or A + B + C + D + E + F = 246 (as F = B)

So, average weight of A + B + C + D + E + F = 246/6 = 41

Answer: (c)
</div> <br>


## Type 10

##### Q. Let A, B and C represent distinct non-zero digits. Suppose x is thc sum of all possible 3-digit numbers formed by A, B and C without repetition. <br>
Consider the following statements : <br>
1. The 4-digit least value of x is 1332. <br>
2. The 3-digit greatest value of x is 888.

Which of the above statements is/are correct?
<pre>(a) 1 only   (b) 2 only    (c) Both 1 and 2   (d) Neither 1 nor 2</pre>

Explanation:<br>
<div class="Exp">

The three-digit numbers have been represented by ABC, wherein A, B, and C are non-zero digits. 

Using 3 distinct digits we can make 3 × 2 × 1 = 6 three-digit numbers. <br>
So, x will be the sum of these 6 three-digit numbers. 

We need to find the two values of x closest to 1000, one just below it (which will be the greatest 3-digit value of x), and the other just above it (which will be the lowest 4-digit value of x).

Now, we have to do a bit of hit and try, so that the value of x reaches close to 1000.

Let the three digits be the minimum possible ones, i.e. 1, 2, and 3. <br>
So, we get x = 123 + 132 + 213 + 231 + 312 + 321 = 1332 

This is the least possible value of x. So, statement 1 is correct, but statement 2 is incorrect. 

Answer: (a)
</div> <br>


## Type 11

##### Q. Consider the following statements in respect of rectangular sheet of length 20 cm and breadth 8 cm :
1. It is possible to cut the sheet exactly into 4 square sheets.
2. It is possible to cut the sheet into 10 triangular sheets of equal area.

Which of the above statements is/are correct?
<pre>(a) 1 only   (b) 2 only    (c) Both 1 and 2   (d) Neither 1 nor 2</pre>

Explanation:<br>
<div class="Exp">

The rectangle is of dimensions 20 cm × 8 cm. 

Statement I: You may think that as the area of rectangle is not a perfect square, it is not possible to cut it into exactly 4 square sheets. But there’s a catch. The statement never says that the 4 squares have to be equal in area. We can do so as follows:
<img src="../../../media/puzzles/counting-puzzles-4.png" alt="Counting Puzzles" style="width:90%;height:90%;">

Statement II: You may think that we can cut the rectangle into 8 triangles of equal area, but not in 10. But again, this can be done. It has been shown below:
<img src="../../../media/puzzles/counting-puzzles-5.png" alt="Counting Puzzles" style="width:90%;height:90%;">

Hence, both statements 1 and 2 are correct.

Answer: (c)
</div> <br>

