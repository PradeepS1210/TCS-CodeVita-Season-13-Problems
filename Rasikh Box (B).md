# Rasikh Box

## Problem Description

Rasikh wishes to engage with a box represented as an m × n matrix, which contains several stones marked by '*' at specified initial positions. Seeking guidance on how to rotate the box and determine the resulting arrangement of the stones, he approaches his uncle for instructions regarding the direction of rotation. His uncle, somewhat irritated by the interruption, provides Rasikh with random rotation instructions. The task is to determine the final configuration of the box, taking into account that after initial stage or after each rotation, gravity causes the stones to shift accordingly.

The box is rotated in 90° angle in the direction as provided in the input.
Consider the following example:

---

## **Constraints**
 
- 3 <= M, N <= 200
 
## **Input**
 
- First line consists of M and N, representing rows and columns of the box, respectively.
- Next M line consists of N space-separated characters, either '.' or '*'. '.' - represents blank - space while '*' represents stone in the box.
- Next line consists of K - number of instructions given by uncle.
- Next K lines represent instructions, either 'right' or 'left'.
 
## **Output**
 
Final position of the box after processing the instructions.
 
## **Time Limit (secs)**
1

---

## **Examples**

**Example 1**

**Input**
 
4 4
 
* * . .
 
. * . .
 
* * * .
 
. * . .
 
1
 
right
 
**Output**
 
. . . .
 
* . . .
 
* * . .
 
* * * *

---

**Example 2**

**Input**
 
3 4
 
. . . .
 
. * . *
 
* * * *
 
1
 
left
 
**Output**
 
. . *
 
. . *
 
. * *
 
. * *
 
**Explanation**
 
The initial position of the box is given. When the left rotation is applied to the box, the stone on the right side goes up and then the gravity plays its role.

---
