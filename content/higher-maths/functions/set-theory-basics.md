---
title: Basics of Set Theory
linktitle: Basics of Set Theory 
toc: true
type: docs
date: "2021-08-08T00:00:00+01:00"
draft: false
menu:
  functions:
    parent: 1. Set Theory
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

Developed by German mathematician and logician Georg Cantor, ***Set Theory*** has massive applications in various branches of mathematics, such as functions, relations, probability etc. 

In this article, we will try to cover all the basics of Set Theory. 

## What is a Set?

A set is a well-defined collection of numbers, perople or objects, which are called its members or elements. 

We generally use a capital letter to denote a set, e.g. A, B, S etc. While to denote an element of a set, we use small letters, e.g. a, b, s etc. 

If an element, say a, belongs to a certain set, say A, then we denote this as: a ∈ A <br>
If an element, say a, does not belong to a certain set, say A, then we denote this as: a ∉ A

{{% alert note %}}
There are some well known sets and letters that are used to denote them: <br>
* N : the set of all natural numbers, i.e. 1, 2, 3 ...
* W : the set of all whole numbers, i.e. 0, 1, 2, 3 ...
* Z : the set of all integers
* $Z^+$ : the set of positive integers 
* Q : the set of all rational numbers
* $Q^+$ : the set of positive rational numbers
* R : the set of real numbers 
* $R^+$ : the set of positive real numbers.
{{% /alert %}}


## Ways of representation of a Set

There a couple of ways via which we can represent a set. 

### Roster or Tabular form

In this form of representation, we just write down all the elements of a set (separated by a comma) within curly brackets { }.

For example:
* {2, 4, 6, ....} - set of even numbers. This set has infinite number of elements. 
* {a, e, i, o, u} - set of vowels in English alphabet. This set has finite number of elements, i.e. 5. 

{{% alert note %}}
The elements are generally not repeated, i.e. all the distinct elements are taken. For example, set of letters forming the word 'JAVA' is {J, A, V}

Also, the order of elements is not relevant. So, we can write {J, A, V} as {A, J, V}, or {J, V, A} etc. They are all representing the same set. 
{{% /alert %}}


### Set-builder form 

We cannot use Roster form for very large sets. Hence, mathematicians came up with another method of representing a set. 

In set-builder form, we represnt a ***single common property*** which is possessed by:
* all the elements of that set, and
* only by the elements of that set (and no other element outside the set). 

A(x) = {x: x has xyz property} <br>
We read this as: A is a set of all x, such that they all fulfil xyz property. 

For example:
* A(x) = {x: x is an even number} - It means A is a set of all even numbers. 
* A(x) = {x: x is a vowel in English alphabet} - It means A is a set of a, e, i, o, u. 


## Types of Sets

There are various types of sets that you must be aware of. 

### Finite and Infinite Sets

A finite set contains a definite number of elements. For example, {2, 4, 5}

On the other hand, an infinite set contains indefinite number of elements. For example, set of points within a circle. 

### Empty Set

An empty set (or null set, or void set) is a set that does not have any element. It is denoted by the symbol ∅, or just by empty curly brackets { }. 

For example, A = {x: x is a prime number greater than 13 but smaller than 17}. As there is no prime number between 13 and 17, so A is an empty set. 

### Subsets and Power Set

A set is a subset of another set, if all of its elements are also present in the other set. That is, if if a ∈ A ⇒ a ∈ B, then it means A ⊂ B. 

For example, if A = {1, 2, 3} and B = {1, 2, 3, 4}, then A is the subset of B. We can see here, that all the elements of set A are also present in set B. 

Power set of a set is the collection of all of its subsets (including the empty set). It is denoted by P. 

For example, if we have a set A = {H, T}, then its power set P(A) = {∅, {H}, {T}, {H, T}}

### Universal Set

A universal set contains all the elements in a given context (that may be part of other sets or not). It is denoted by U. 

For example, when we roll a dice, we can get any number from 1 to 6. So, the set {1, 2, 3, 4, 5, 6} is the universal set in this context. 

All other sets will be its subsets. For example, A = {x: x is an odd number on the dice}, i.e. {1, 3, 5} is a subset of the universal set {1, 2, 3, 4, 5, 6}. 


## Relationship between Sets

We use Venn diagrams to show relationship between two or more sets. 

### Disjoint Sets

Two sets can be called disjoint sets, if they have no common element. We can represent them using Venn diagram as follows:
<img src="../../../media/functions/set-theory-1.png" alt="Set Theory" style="width:54%;height:54%;">


### Overlapping Sets

If there are some common elements in set A and B, then their Venn diagrams will overlap and we can represent their relation as follows:
<img src="../../../media/functions/set-theory-2.png" alt="Set Theory" style="width:45%;height:45%;">


### Equal Sets

Two sets are said to be equal to each other, if they have exactly the same elements. That is, when two sets are identical. 

They are denoted by = sign. For example, if set A is identical to set B, then we can write A = B. 

In terms of Venn diagram, we can say that their Venn diagrams will completely overlap. 
<img src="../../../media/functions/set-theory-3.png" alt="Set Theory" style="width:27%;height:27%;">


## Operations on Sets

Now, we can perform some operations on set(s). Let's see some of them here. 

### Union of Sets

Union of two sets contains the elements of both the sets. That is, A ∪ B = {x | x ∈ A ***or*** x ∈ B} 

{{% alert note %}}
The word 'or' is closely related to the concept of Union. 
{{% /alert %}}

It is denoted by the symbol ∪. So, A ∪ B means A union B. 

The shaded portion in the following Venn diagram represents the union of two sets, A and B. 
<img src="../../../media/functions/set-theory-4.png" alt="Set Theory" style="width:54%;height:54%;">

#### Properties of Union operation

##### Property 1: Commutative Law

The order of sets doesn't matter, i.e. A ∪ B = B ∪ A 

##### Property 2

(A ∪ B) ∪ C = A ∪ (B ∪ C) 

##### Property 3: Distributive Law 

A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)

##### Property 4

* Union of a set with empty set is that set itself, i.e. A ∪ φ = A 
* Union of a set with itself is that set itself, i.e. A ∪ A = A 
* Union of a set with universal set is that universal set, i.e. A ∪ U = U


### Intersection of Sets

Intersection of two sets contains the elements that are common in both the sets. That is, A ∩ B = {x | x ∈ A ***and*** x ∈ B} 

{{% alert note %}}
The word 'and' is closely related to the concept of Intersection. 
{{% /alert %}}

It is denoted by the symbol ∩. So, A ∩ B means A intersection B. 

The shaded portion in the following Venn diagram represents the intersection of two sets, A and B. 
<img src="../../../media/functions/set-theory-5.png" alt="Set Theory" style="width:54%;height:54%;">


#### Properties of Intersection operation

##### Property 1: Commutative Law

The order of sets doesn't matter, i.e. A ∩ B = B ∩ A 

##### Property 2

(A ∩ B) ∩ C = A ∩ (B ∩ C) 

##### Property 3: Distributive Law 

A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)

##### Property 4

* Intersection of a set with empty set is empty set, i.e. A ∩ φ = φ 
* Intersection of a set with itself is that set itself, i.e. A ∩ A = A 
* Intersection of a set with universal set is that set itself, i.e. A ∩ U = A


### Difference of Sets

Difference of two sets is denoted by - sign. So, difference of sets A and B, will be represented as A - B. 

A- B will have all the elements of set A, that are not in set B. That is, A - B = {x | x ∈ A and x ∉ B} 

The shaded portion in the following Venn diagram represents A - B. 
<img src="../../../media/functions/set-theory-6.png" alt="Set Theory" style="width:54%;height:54%;">

{{% alert note %}}
A - B ≠ B - A
{{% /alert %}}

### Complement of a Set

To represent complement of a set, we add ' infront of the name of the set. For example, complement of set A will be A'. 

Let A be a set within the universal set U. Then A' will have all the elements of the universal set, except those that are in set A. That is, A' = {x | x ∈ U and x ∉ A}, or A′ = U – A

The shaded portion in the following Venn diagram represents the complement of set A, i.e. A'. 
<img src="../../../media/functions/set-theory-7.png" alt="Set Theory" style="width:54%;height:54%;">

#### Properties of Complement of Sets

##### Property 1

Complement of universal set is empty set, and vice-versa. That is, U′ = φ	and φ′ = U

##### Property 2

* A ∪ A′ = U 
* A ∩ A′ = φ

##### Property 3: De Morgan’s law

The complement of the union of two sets = Intersection of their complements, i.e. (A ∪ B)′ = A′ ∩ B′

The complement of the intersection of two sets = Union of their complements, i.e. (A ∩ B)′ = A′ ∪ B′

##### Property 4: Law of Double Complementation

(A′)′ = A 


