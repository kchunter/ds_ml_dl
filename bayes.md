
BAYESIAN INFERENCE
---------------------------------

Event - Set of outcomes (favourable outcomes)


```python

```

If the sets A and B do not touch at all, their union would simply be their sum

∩ - intersect ∪ - union

A ∩ B = Ø -> A ∪ B = A + B

No elements are in both sets simultaneously

No double-counting

If the events intersect, the area of the union is represented by the sum of the two sets minus their intersection

A ∪ B = A + B - (A ∩ B)

Mutually Exclusive Sets - Sets, which are not allowed to have any overlapping elements (have the empty set as their intersection)

A ∪ B = A + B - (A ∩ B) = A + B - Ø = A + B

Complement Set: All values that are part of the sample space, but not part of the set

Independent Events - The theoretical probability remains unaffected by other events

Dependent Events - Probability of dependent events vary as conditions change

P(A|B) - "P of A given B" - The probability of getting A, if we are given that B has occured - We call this probability the conditional probability and we use it to distinguish dependent from independent events


```python

```

Conditional Probability - The likelihood of an event occuring, assuming
a different one has already happened

A represents getting heads
B represents getting heads on the previous flip

P(A|B) = .5
P(A) = P(A|B)

Two events (A and B) are independent

If any two events are independent P(A ∩ B) = P(A) * P(B)

P(A|B) = P(A ∩ B) / P(B) if P(B) > 0 - Conditional probability formula
P(A) = favourable / all - Favourable over all formula

Intuition behind formula:     P(A|B) = P(A ∩ B) / P(B)
-----------------------------------
 * P(A ∩ B) - Both events B and A need to occur simultaneously
 * P(B) - The conditional probability requires that event B occurs
P(A|B) and P(B|A) are not equal.

Law of Total Probability
---------------------------------

A = B1 ∪ B2 ∪ ... ∪ Bn

P(A) = P(A|B1) * P(B1) + P(A|B2) * P(B2) + ...



Additive Law
------------------

P(A ∪ B) = P(A) + P(B) - P(A ∩ B)



Multiplication Rule
---------------------------

P(A|B) = P(A ∩ B) / P(B)

       |
       ˇ
       
P(A|B) * P(B) = P(A ∩ B) * P(B) / P(B)       

       |
       ˇ
       
P(A|B) * P(B) = P(A ∩ B)


```python

```

BAYES' RULE = BAYES' LAW = BAYES' THEOREM - One of the most important formulas in probability

P(A|B) = P(A ∩ B) / P(B) - Conditional probability formula

P(A ∩ B) = P(B|A) * P(A) - Multiplication rule

P(A|B) = P(B|A) * P(A) / P(B) - Bayes' Theorem - It allows us to find a relationship between the different conditional probabilities of two events

